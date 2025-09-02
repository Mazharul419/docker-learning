# Trackit - Docker Visit Tracker Project 🐳➡📦
## A project focusing on creating a live website with a visit counter!
![ezgif-6e2eb69a239149](https://github.com/user-attachments/assets/5a47607e-7ff9-4d15-9b4d-0e3ce47d55e7)

This application runs a live website with real-time visitor tracking.

## Technologies 

<br>

<img src="{(https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white)}" /> framework for the webserver
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

## Credit 

Credit to [CoderCo](https://coderco.io/) for providng me with the skills and opportunity to demonstrate my knowledge in this project - it is highly appreciated!

Credit to Network Chuck for his [clear and easy-to-follow tutorial](https://www.youtube.com/watch?v=5aYpkLfkgRE) on how Flask works and the meaning behind routes

Creating Redis Application - I learnt how to perform increments via the [Official Documentation for Redis](https://redis.io/docs/latest/develop/clients/redis-py/) and the [GeekforGeeks tutorial on setting up a Redis server](https://www.geeksforgeeks.org/system-design/introduction-to-redis-server/)
<br>

Credit to Zeynab for her [excellent Medium article](https://medium.com/@y.zeynab1/building-a-visitor-counter-app-with-docker-flask-and-redis-40b6bab5ec1e) on attempting this challenge and demonstrating how to use Docker-Compose to create the containers for web and db applications.

Credit to [Joel Burch](https://www.linkedin.com/in/joel-burch/?originalSubdomain=ch) for his well-written article on [using multiple dockerfiles](https://www.divio.com/blog/guide-using-multiple-dockerfiles/)

Credit to [Othneil Drew](https://www.linkedin.com/in/othneildrew/) for providing an [awesome template](https://github.com/othneildrew/Best-README-Template?tab=readme-ov-file) for ReadMEs!
