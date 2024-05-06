# My First Load Balancer with Docker Containers 📌
### Nginx Load Balancer with Three Flask Servers.
In our exciting journey of containerization and orchestration, we embarked on a mission to deploy a Flask website using Docker Compose. Our goal was to achieve high availability, efficient resource utilization, and seamless traffic distribution. Here’s how we did it:
### 1- The Flask Website
  * Our Flask-based website was the heart of our application. It provided dynamic content, handled user requests, and interacted with databases or other services.
### 2- Docker Containers
  * We encapsulated our Flask application within three Docker containers. Each container represented an instance of our website.
  * These containers were isolated, portable, and easy to manage. Docker allowed us to package our application along with its dependencies, ensuring consistency across different environments.
### 3- Docker Compose
  * Enter Docker Compose! This powerful tool allowed us to define our multi-container application in a single docker-compose.yml file.
  * We specified our Flask service, database service (if any), environment variables, and networking details.
  * With a simple docker-compose up, our entire stack came to life.
### 4- Nginx Load Balancer
  * To distribute incoming traffic across our three Flask servers, we introduced Nginx as our load balancer.
  * Nginx acted as the gateway, receiving requests from clients and intelligently forwarding them to the available Flask containers.
  * Load balancing ensured that no single server was overwhelmed, improving performance and fault tolerance.

#

![Copy of server](https://github.com/MazenMoneim/Nginx-Loadbalancer/assets/135109542/6785165b-f076-40ef-9db9-b5dbeb1327c5)

