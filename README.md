# Fault Tracing in MicroService Architecture using Jaegar

This is a microservice architecture consisting of two services: Admin and User. The services are built using Flask and PostgreSQL and are integrated with a distributed tracing system to enable effective monitoring and troubleshooting.
<br />
<br />

# Admin Service

The Admin service provides an API for adding products to a PostgreSQL database.The Admin service incorporates distributed tracing using Jaeger, allowing you to trace the execution flow and performance of requests.
<br />
<br />

# User Service
The User service provides an API for viewing and liking products stored in a PostgreSQL database. 
<br />
<br />

# Steps to run:
1. Zip this repo to your local machine
2. Power up your terminal and build containers with `docker-compose build`
3. Finally `docker-compose up`