# Data Management DB Setup

1. Start the docker compose by going into the DataManagement folder and running the following command:
```bash
docker-compose up -d
```

2. Visit pgAdmin at http://localhost:5050 and login with the following credentials:
```
Email: admin@localhost.com
Password: admin
```

3. Add a new server with the following credentials:
```
Host name/address: postgres
Port: 5432
Maintenance database: postgres
Username: postgres
Password: postgres
```

1. Create a new database called `db123___`