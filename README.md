# UdoCluster

A Big Data-project as part of the class "Big Data Analytics" in the winter semester 2023 of the course TINF21AI2 at DHBW Mannheim.

# Quickstart

## Run the application

You need to have Docker and docker compose installed on your device.

Before starting the application, copy the files 

- [db.json](https://drive.google.com/file/d/1HnB43OQrPZAuC4CG9U0hzCnN3fV7t2_3/view?usp=drive_link) and [nyt.json](https://drive.google.com/file/d/1oodDslsXbQEkNT_JPbDOQHqu1_OPnhV8/view?usp=drive_link) into the folders **airflow/project_secrets** and 

- [db.json](https://drive.google.com/file/d/1HnB43OQrPZAuC4CG9U0hzCnN3fV7t2_3/view?usp=drive_link) into **Visualization/udoCloud/static**

To start the application, run on you windows machine 

```sh
docker compose up --build
```

or

```sh
docker-compose up --build
```

Keep in mind that Docker Desktop must be running.

The visualization will be running on [localhost:80](http://localhost) and airflow on [localhost:8080](http://localhost:8080) (you will find the password to airflow in the file **airflow/standalone_admin_password.txt**, the username should be "airflow" or "root")
