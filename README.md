This is a simplest project which shows how to create a Docker image with Postgres Server and execute SQL initialization commands on a startup. 


To run execute the following command: 
```docker-compose up```


Folder `db` contains all the scripts which will be run during the startup. Be aware, those scripts will be run in an alphabetical order.


## Known Issues:
If, when you start your Docker Compose, you're getting:
`PostgreSQL Database directory appears to contain a database; Skipping initialization` then execute a following command:

```docker-compose down --volumes```


