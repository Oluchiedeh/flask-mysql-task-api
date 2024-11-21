# Building Your First Multi-Container Application with Docker: A Step-by-Step Guide

In modern application development, microservices and containerization have become crucial for creating modular, scalable, and maintainable applications. 
Multi-container applications are the backbone of modern web applications, allowing developers to separate different services into individual containers that work together seamlessly. 
In this blog post, we'll walk through creating a simple multi-container application with Docker using Flask (for the web server) and MySQL (for the database). 
This setup is perfect for learning how to build and connect different services within Docker, a skill essential for any DevOps engineer or developer.

# Prerequisites:
- Basic knowledge of Docker.
- Docker installed on your machine.
- Docker Compose installed on your machine.

# Step 1: Setting Up Your Flask Application
Let's start by creating a basic Flask application that connects to a MySQL database to store and retrieve data.

**File Structure: Create the following file structure for the project:**

multi-container-app/
├── app/

│   ├── app.py

│   ├── requirements.txt

├── db/

│   └── init.sql

└── docker-compose.yml

**Writing the Flask Application.**
In the app/app.py file, write a simple Flask API that connects to a MySQL database:


