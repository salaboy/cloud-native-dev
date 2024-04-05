# Challenge 3 :: Cloud Native Applications Distributed Interactions (Basics) 

In this challenge we will use the SQL version of the application that you built in challenge 2. 
This challenge consist in adding a new application called `dashboard` that will poll the database every 2 seconds and keep a counter of how many texts are stored in the database. 
The `dashboard` backend should send using via websockets the information about how many texts are stored to the client side (HTML/JS). 
In other words, the client side SHOULD NOT send a reqeust to the backend to get the number of texts stored in the database.

As part of this challange, the Database selected should be running as a Docker Container. Both applications should connect to that container. 

## Deliverables

A new directory called `challenge-3` should be created, containing both applications (app and dashboad). 
A README.md showing how to run the database using a Docker container, and how to start up both applications should be provided. 
