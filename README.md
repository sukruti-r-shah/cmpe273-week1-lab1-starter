# CMPE 273 – Week 1 Lab 1: Your First Distributed System (Starter)

## 1) Running both the services locally
- **Service A** running on (port 8080): 

  ![My photo](images/service_a.png)

- **Service B** running on (port 8081): 

   ![My photo](images/service_b.png)


## 2) Running **curl** commands for both the services

   ![My photo](images/curl_success.png)

   - ## **Service A** logs: 

      ![My photo](images/service_a_success.png)

   - ## **Service B** logs: 

      ![My photo](images/service_b_success.png)


## 3) **Service A** stopped

   ![My photo](images/a_stopped.png)

   - ## Running **curl** commands after service A is stopped

      ![My photo](images/curl_fail.png)

   - ## **Service B** logs:
 
      ![My photo](images/b_fails.png)


## 4) What makes this distributed?

   - Both the services A and B are running independently and communicating through network, even when they are physically on the same machine. So, if we were to run these services on different machines, given that both the services can communicate through the network, the services would run the same way. This separation is what makes the services distributed.