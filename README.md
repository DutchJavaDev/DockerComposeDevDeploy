# DockerComposeDevDeploy
Basic configuration for a new server that will have programs running via docker 

[Live example (link)](http://bamdevserver.nl:3001/status/dockercomposedevdeploy)
![image](https://github.com/DutchJavaDev/DockerComposeDevDeploy/assets/19773367/e780aa5a-8366-4c1f-9c8c-0f67e9a7987f)



### Access via web with nginx. (nginx setup not included)
## Urls
Uptime Kuma = host:3001  

Adminer = host/dbm  


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
Normal access Or remove...
