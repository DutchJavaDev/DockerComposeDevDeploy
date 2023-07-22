# DockerComposeDevDeploy
Basic configuration for a new server that will have programs running via docker

### Access via web with nginx.
## Urls
Uptime Kuma = /  

Adminer = /dbadmin  


# Dashboard
Uptime Kuma will be the dashboard to monitor all programs via pings etc.
	Will run in docker locally, redirect with nginx to local port

# Programs

### Access
To have access to the databeses, create a db_password.txt file and store the password in there

### Adminer 
Easy connect to the Mysql and Postgres databases
Adminer does not support SQL server, MongoDb and Redis 

Use other tools to connecto to those like MongoDb Compas etc... google :)

### Mysql database
Normal access 

User: root

### Posgres database
Normal access 

User: postgres

### SQL database
Normal access 

User: sa

### MongoDB
Normal access 

User: root

### redis DB
Normal access

### VS code server
Test and see how it works :)
