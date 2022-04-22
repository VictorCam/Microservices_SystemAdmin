# System Administration Final
Docker Container Microservices Application with MariaDB and Nodejs with HAproxy as a Load Balancer


## Video Demonstration
https://media.oregonstate.edu/media/t/1_ci95rpo0

## Description

Throughout this class we have learned on how to extensively use Docker and it is useful for system administrators to deliver quickly. This is important to many jobs where system administrators are asked to scale their application by distributing load between many servers in a efficient manner. The main drive for this approach is to make it everything easy by using docker files in order to spin up and spin down containers for the servers. The reason being is that it will be easy for system administrators to scale the microservice horizontally by adding or removing service instances to the haproxy configuration file and the docker-compose yaml file with little downtime. Why is this important to a system administration? The reason being is that microservices can be overwhelmed in certain server endpoints which can strain the entire system. This can easily be solved by distributing the workload by spinning up new instances on another server. Lets say an endpoint isn’t getting much work done we can balance out a server by giving it a different microservice so that it takes the load off of another server. So pretty much the best part of this approach is that you can distribute the load between the services and apply updates from the official images when vulnerabilities occur in them for ease of maintainability. Unlike a monolithic approach if your once server service goes down the entire system goes down.
