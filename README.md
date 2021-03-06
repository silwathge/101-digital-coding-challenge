# API Portal: Sample API Implementation (For OpenAPI V3)

## Sample Solution is available on AWS (EC2) as docker containers


App: global-api-marketplace-app

DB: api-postgres

Network: global-api-marketplace-app-network(bride)

Volume: postgres-database-data-volume


## Server URL and Port

http://ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com:8080/


## Postman Script 

with other files used for uploadeding will be sent separately via email. 

The zip file “PostmanScriptAndFilesToUpload.zip” will also available with source code in the GitHub repo


 1. Use environment variable 
“host”  with value ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com

2. Place other files in the Postman working directory

3. Default user in db 

	 User : username
	 
	 Password: password





## Source code is available on GitHub as a public repo :

https://github.com/silwathge/101-digital-coding-challenge



## Docker image is available on DockeHub :use the one with highest tag

https://hub.docker.com/repository/docker/kapilas/global-api-marketplace-app


kapilas/global-api-marketplace-app:0.0.3-SNAPSHOT



## Docker Compose File
Is available with source code in the repo.


### To deploy from images directly:

Can be used as it is to deploy service with db to docker


### To build image:
Comment out image and uncomment all three lines which is commented out in the current file
Do  mvn clean package

Then run docker-compose up - new image will be created and services will be deployed.


## Server URL and Port
http://ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com:8080/


## Swagger API Doc :
http://ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com:8080/v2/api-docs


## Swagger UI :
http://ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com:8080/swagger-ui.html


## Actuator (with default exposed endpoints)   :

http://ec2-13-229-60-201.ap-southeast-1.compute.amazonaws.com:8080/actuator







