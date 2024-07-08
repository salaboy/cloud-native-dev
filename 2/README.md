# Challenge 2 :: Cloud Native Applications Persistence
Welcome to Challenge 2 of our Cloud Native Applications series! 

In this challenge, we will extend the application from [Challenge 1](https://github.com/salaboy/cloud-native-dev/tree/main/1) to store its data using two different approaches: file system storage and SQL database storage.

## Objectives

1. File System Storage (Branch: fs):

- Create a branch (called `fs` or `filesystem`) from the `main` branch and store the list of texts saved into a file (using the file system APIs provided by your programming language of choice). Ensure the application can read from this file to retrieve previously saved texts.

2. SQL Database Storage (Branch: sql):

- Create a branch (called `sql`), set up a SQL database of your choice, and store the list of texts in a table inside the database. Recommended PostgreSQL, but you can choose any SQL database that you want.
- Modify the application to save texts into this database table.
- Implement functionality to retrieve texts from the database.


## Deliverables 

- **Repository Setup:**
Create a new directory named `challenge-2`. Copy the application code from Challenge 1 into this directory and push it to your GitHub repository.

- **Branch Management:**
Create two branches from your main repository:
    - Branch fs (File System): Implement file system storage.
    - Branch sql: Implement SQL database storage.
 
Please ensure that both branches have fully functional applications and that everything is pushed to your GitHub repository. 

- **README.md:**
Create a README.md to explain how to run both application versions locally by switching branches. Include setup instructions for the file system storage (reading/writing files) and SQL database setup (creating tables, configuring connection).

Ensure all branches contain fully functional applications and that all code and instructions are pushed to your GitHub repository.

## Important Lessons Learned
By completing Challenge 2, you will gain practical experience and insights into key aspects of cloud-native application persistence:

- **Persistence Strategies:** Understand different approaches to data persistence, including file system and database storage, and their respective advantages and use cases.

- **Database Management:** Learn basic SQL skills, such as creating tables, inserting data, and querying data, essential for managing data in relational databases.

- **Version Control:** Practice using Git branches to manage different versions of your application, facilitating parallel development and experimentation with different storage mechanisms.

- **Dependency Management:** Handle dependencies specific to your programming language and database system, ensuring compatibility and seamless integration.

## References
- [Julia's Challenge 2 experience](https://www.juliafmorgado.com/posts/challenge-2-application-persistence-with-fs-sql-db/)