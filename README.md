# Homework-1 for BLM5117 Implementation of Database Management Systems Course at YTU

## Project Details
> **Description:** # Homework-1 & More Details: BLM5117_VTSG_HW-1.pdf  
> **Course Name:** BLM5117 - Implementation of Database Management Systems

## Install Postgres & pgAdmin 

### Rename and customize .env_example to .env
    - POSTGRES_USER
    - POSTGRES_PW
    - POSTGRES_DB
    - PGADMIN_MAIL
    - PGADMIN_PW

### PostgreSQL DB  
    - Create Postgres Database
    $ docker-compose up -d

    - List of running docker containers
    $ docker-compose ps

    - Run command inside the container
    $ docker-compose run db bash

    - Connect to Container
    $ docker exec -it postgres bash    

    - Connect postgres inside the host
    $ psql --host=localhost --dbname=postgres --username={POSTGRES_USER}

    - Stop container
    $ docker-compose down

### pgAdmin
    Web UI: localhost:5050  
    UserName: {PGADMIN_MAIL}  
    Password: {PGADMIN_PW}  

#### Add Server
    Hostname Address: postgres
    User: {POSTGRES_USER}
    Pass: {POSTGRES_PW}

## Contact
    - Metin Uslu - 235B7014