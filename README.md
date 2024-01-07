# Eureka Service Registry for Cloud-Based Microservices with DevOps and Automation

## Description
A part of the cloud-based microservices with DevOps and automation project that include:
* Set up this server for port 8761
* Configure this server to not register to itself
* This server allows microservices and servers to register, discover, and communicate with other services in a distributed system without hard-coding their locations or dependencies (Examples: API Gateway utilizes this server to discover and use functions of other microservices; the length conversion service uses this server to detect length exchange microservice without requiring port number)
* Enable load balancing to the length exchange service's instances from the length conversion service's instance that uses FeignClient
