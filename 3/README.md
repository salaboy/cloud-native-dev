# Challenge 3 :: Cloud Native Applications Distributed Interactions (Basics) 

Welcome to Challenge 3 of our Cloud Native Applications series!

In this challenge, we will build upon the SQL application developed in [challenge 2](https://github.com/salaboy/cloud-native-dev/tree/main/2) by integrating real-time interactions and Docker containerization.

## Objective

This challenge consist in adding a new application called `dashboard` that will poll a database every 2 seconds and keep a counter of how many texts are stored in the database.
The `dashboard` backend should use websockets to send real-time updates on the count of stored texts directly to the client-side (HTML/JS). In other words, the client side SHOULD NOT send a request to the backend to retrieve the number of texts stored in the database.

As part of this challenge, the Database backend should be running as a Docker Container. Both the existing application (`app`) and the new dashboard application should connect to this container.

## Deliverables
To successfully complete Challenge 3, follow these steps:

- **Directory Setup:**

Create a new directory named `challenge-3`. Include both applications (app and dashboard) within this directory.

- **README.md:**

Provide a detailed `README.md` showing how to run the database using a Docker container, and how to start up both applications. Include any necessary configurations and dependencies required for smooth operation.


## Important Lessons Learned
By completing Challenge 3, you will gain valuable experience in:

- **Containerized Database Integration:**
Understanding how to integrate Dockerized databases with multiple applications, ensuring consistency and scalability.

- **Real-Time Data Communication:**
Implementing websockets for real-time updates, enhancing user experience by delivering instant data changes to the client-side.

- **Cloud-Native Distributed Interactions:**
Orchestrating distributed interactions between components of a cloud-native application, preparing you for handling more complex architectural challenges.


## References
- [Julia's Challenge 3 experience](https://www.juliafmorgado.com/posts/challenge-3-creating-real-time-web-applications-with-docker-and-postgresql/)