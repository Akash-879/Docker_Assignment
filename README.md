**Dockerized Node.js REST API Assignment**

---

**Objective:**  
The objective of this assignment is to demonstrate basic proficiency in working with Docker features by containerizing a simple Node.js Express REST API that returns a "Hello, World!" response.

---

**Assignment Files:**  
The assignment includes two files:
1. `main.js`: This file contains a simple Node.js Express server setup to respond with "Hello, World!" on port 3000.
2. `package.json`: Dependency management file for the Node.js project.

---

**Instructions:**

**Step 1:** Download the Assignment Files  
Download the files `main.js` and `package.json` from the provided Google Drive link.

**Step 2:** Install Node.js  
Ensure that Node.js is installed on your computer. If not, download and install it from the official Node.js website (https://nodejs.org/).

**Step 3:** Install Dependencies  
Open a terminal or command prompt, navigate to the directory where you downloaded the files, and run `npm install` to install the project dependencies.

**Step 4:** Run the Node.js Server  
Execute `node main.js` in the terminal to start the Node.js server. The API will be accessible at http://localhost:3000, and you should see the response "Hello, World!".

**Step 5:** Dockerize the Application  
Create a Dockerfile in the project directory with instructions to build an image of the Node.js application. Use the provided Dockerfile template.

**Step 6:** Build Docker Image and Run Container  
Use Docker to build an image from the Dockerfile (`docker build -t my-node-app .`) and run a container based on that image (`docker run -d -p 3000:3000 my-node-app`).

**Step 7:** Access the API  
Access the API at http://localhost:3000 to verify that the Dockerized application is responding with "Hello, World!".

**Bonus:** Docker Compose  
Write a docker-compose.yml file to define and run multi-container Docker applications. Use the provided docker-compose.yml template.

**Step 8:** Use Docker Compose  
Run `docker-compose up -d` to start the container using Docker Compose.

**Step 9:** Access the API  
Once again, access the API at http://localhost:3000 to verify that the application is responding as expected.

**Step 10:** Push Assignment to GitHub  
Initialize a Git repository, add the files, commit the changes, and push the repository to GitHub. Share the repository link with your instructor.

---

**Note:**  
- Make sure Docker is installed on your system before proceeding with Docker-related steps.
- If you encounter any issues during the assignment, feel free to reach out for assistance.

---

**Author:** Aakash Rathod
**Date:** 29-03-2024

**Repository Link:** github.com/Akash-879/Docker_Assignment

---
