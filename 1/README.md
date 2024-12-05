# Challenge 1 :: Cloud Native Applications

Welcome to Challenge 1 of our Cloud Native Developer Journey series!

This challenge serves as a foundational step toward understanding and implementing cloud-native principles in application development. 

In this challenge, you will create a simple web application using any programming language of your choice.

## Prerequisites
Before starting this challenge, ensure you have the following:

- **Basic Programming Knowledge:** Familiarity with at least one programming language (e.g., JavaScript, Python, Go, etc.) and an understanding of coding principles.
- **Web Development Fundamentals:** Basic understanding of web technologies like HTML and CSS to create simple user interfaces.
- **Familiarity with HTTP:** An understanding of [how HTTP works](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview), including requests and responses, and the ability to interact with endpoints.
- **Tools & Setup:** You should have a development environment set up (e.g., VS Code, WebStorm) and be familiar with using version control tools like - [Git](https://git-scm.com/) and [GitHub](https://github.com/) for collaboration and version management.
- **Understanding of Architectural Models:** A conceptual understanding of how frontend and backend components interact within a web application.

## Objectives

1. **Application Setup:**
Develop a web page with a text area and a button. When the button is clicked, it should interact with the backend endpoint described in 2.

2. **Backend Development:**
- Implement a backend with an HTTP endpoint ('/save') that receives data from the frontend (text area input) and stores it in an in-memory collection (like a slice or array).
- Create another HTTP endpoint ('/all`) that retrieves and returns all elements stored in the collection.

3. **Integration:**
Display the retrieved data on the web page to demonstrate full-stack communication.

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

## Frequently Asked Questions
Check the [FAQ](./FAQ/challenge1.md) to find answers to common questions about this challenge.

## References

- [Julia's Challenge 1 experience](https://www.juliafmorgado.com/posts/challenge-1-create-a-simple-app-with-http-endpoints-and-host-in-github/)
