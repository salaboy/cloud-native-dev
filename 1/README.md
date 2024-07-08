# Challenge 1 :: Cloud Native Applications

Welcome to Challenge 1 of our Cloud Native Applications series!

This challenge serves as a foundational step towards understanding and implementing cloud-native principles in application development. 

In this challenge, you will create a simple web application using any programming language of your choice.

## Objectives

1. Application Setup:
- Develop a web page with a text area and a button. When the button is clicked, it should interact with the backend endpoint described in 2.

2. Backend Development:
- Implement a backend with an HTTP endpoint ('/save') that receives data from the frontend (text area input) and stores it in an in-memory collection (like a slice or array).
- Create another HTTP endpoint ('/all`) that retrieves and returns all elements stored in the collection.

3. Integration:
- Display the retrieved data on the web page to demonstrate full-stack communication.

## Deliverables

To complete this challenge, set up a GitHub repository (`challenge-1`) with the following structure:

```
challenge-1/README.md <- Detailed instructions on how to build, run, and test the application locally. 
challenge-1/app/ <- Directory containing the source code for both the frontend and backend components of your application.
```

Ensure that your repository contains all necessary code and instructions for others to replicate and run your application seamlessly.

## Important Lessons Learned
By completing this challenge, you will gain insights into several key aspects of cloud-native development:

- **HTTP Server Basics:** Learn how to create an HTTP server and define and expose endpoints.
- **Client-Server Interaction:** Understand how web applications communicate between frontend and backend components using HTTP.
- **Data Management:** Learn basic techniques for handling and storing data within an application's memory.
- **Development Workflow:** Practice setting up a GitHub repository, organizing your code, and documenting your project for collaboration.

## References

- [Julia's Challenge 1 experience](https://www.juliafmorgado.com/posts/cloud-native-dev-challenge-1/)
