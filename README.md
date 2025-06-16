# Dockerized Nagios Server
This repository contains a Dockerized Nagios server setup. It is designed to be used with Docker Compose for easy deployment and management.

## Usage
Using docker compose to boot up the instance:
```bash
docker compose up -d
```

## Accessing the Nagios Web Interface
After starting the Docker container, you can access the Nagios web interface by navigating to:

```
http://localhost:8080/
```
You can log in with the following credentials:
- **Username:** nagiosadmin
- **Password:** secretpassword

## Stopping the Nagios Server
To stop the Nagios server, you can run the following command:

```bash
docker compose down
```