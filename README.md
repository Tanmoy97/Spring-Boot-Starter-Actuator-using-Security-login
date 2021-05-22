# Spring-Boot-Starter-Actuator-using-Security-login

I have created a login security using Spring Boot Starter Actuator and Spring Boot starter Security.

And I got the output below for security login:

![Screenshot (819)](https://user-images.githubusercontent.com/53449205/119233092-ef2ff580-bb44-11eb-8a7d-0f135ccdf29d.png)

I also get the all Spring Boot Starter Actuator endpoints. Below is it's output:

![Screenshot (823)](https://user-images.githubusercontent.com/53449205/119233390-75007080-bb46-11eb-96a1-8719133b4690.png)
 
 I also got the my app information and health status.
 
 ![Screenshot (824)](https://user-images.githubusercontent.com/53449205/119233470-db858e80-bb46-11eb-8b6e-64a499b28650.png)
 
 ![Screenshot (825)](https://user-images.githubusercontent.com/53449205/119233511-2901fb80-bb47-11eb-93ca-c214ba4c3747.png)
 
 If I commit(remove) the "management.endpoints.web.exposure.exclude=health,info" from the application.properties file. I can't see the output of the health, info .
 It's showing error. It's useful for real time apps.
