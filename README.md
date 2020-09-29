# spring-microservices

Developing a microservices architecture uisng Spring-boot, Maven and Netflix-Eureka server

## Two microservices:
CustomerService : Contain endpoints of getting all customers, and also a particular customer. <br/>
OrderService : Contain endpoints of getting all orders, and also a particular order.

Both the microservices will connect and communicate with each other using Eureka server

## Steps to run the server and the microservices :
- Clone the repository
- Run Discoveryservice first and let them wait for the services to register
- Run both the services and wait for them to display on the Eureka server http://localhost:3000
- Check if the services are running by visiting the url provided

If all the things work properly, you can see the services running on Eureka server <br/>
View the final output uploaded with the image name 
## Final output.JPG

