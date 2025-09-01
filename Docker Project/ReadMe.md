# Trackit - Docker Visit Tracker Project 🐳➡📦
## A project focusing on creating a live website with a visit counter!
![ezgif-6e2eb69a239149](https://github.com/user-attachments/assets/5a47607e-7ff9-4d15-9b4d-0e3ce47d55e7)

This application runs a live website with real-time visitor tracking.

By using:
<br>
- **Flask** framework for the webserver
- **Redis** database for website visitor tracking
- **Docker** platform to containerise and run the isolated applications
<br>
The combination of these technologies allows for the production and deployment of code to run a website that performs and provides live information!
<br><br>
Some of the challenges I faced are:
<br>

- Writing and understanding code for Flask webserver and Redis database
- Understanding Docker images

Some features I REALLY want to implement in the near future are:

- Producing Volumes that persist data, so visit counter is not reset upon container restarts
- Adding great looking display through HTML/CSS to make the website vibrant
- Deploying NGINX webservers and load balancing traffic
- Additional security features like passwords to database

## Creating Flask Application
<br>
1. Set up - Network Chuck tutorial

## Creating Redis Application
1. Set up

Official Docs: https://redis.io/docs/latest/develop/clients/redis-py/
<br>
GeeksforGeeks: https://www.geeksforgeeks.org/system-design/introduction-to-redis-server/

# Creating Dockerfiles:

Creating seperate Dockerfile: https://www.divio.com/blog/guide-using-multiple-dockerfiles/

# Creating Docker-Compose file
As per Flask-SQL walkthrough
also: https://medium.com/@y.zeynab1/building-a-visitor-counter-app-with-docker-flask-and-redis-40b6bab5ec1e

