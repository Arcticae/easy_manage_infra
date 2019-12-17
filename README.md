# Easy manage complete package

This repo is meant for installation of webserver, and setting up other services associated with it using docker-compose 

## Running the project

You will need to build docker images:
 - `easy_manage_webserver`
 - `easy_manage_frontend`
 - `easy_manage_nginx`
 
 Instructions on how to build them, are included in corresponding repositories.
 
 In `/nginx` folder there's a dockerfile for easy_manage_nginx image. 
 
 You'll need to build it with the tag given above, and it's ready for running
 
 After all these steps, simply run `docker-compose up`.
 
 All of necessary configuration is included in `.env` files included in this project.   
 