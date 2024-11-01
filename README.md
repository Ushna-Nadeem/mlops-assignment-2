# mlops-assignment-2


1.	Architecture Diagram

•	Frontend Service: A responsive, user-friendly UI for user interactions.
•	Backend Service: An API-driven backend for handling user requests, authentication, and communication with the database.
•	Database Service: Store user data and authentication details.



2.	User Authentication Module

•	Signup: Allow users to register.
•	Login: Enable users to log in.
•	Forgot Password: Provide password reset functionality.


3.	Technology Stack

•	Frontend: React
•	Backend: Node.js (Express)
•	Database: PostgreSQL
•	Authentication: JWT (JSON Web Tokens)


4.	Containerization (Docker)

•	Dockerfiles: Create individual Dockerfiles for each service (Frontend, Backend, Database, Authentication).
•	Docker Compose: Define and run a multi-container Docker application.


5.	Orchestration and Deployment with Kubernetes

•	Kubernetes Deployment and Service YAML files: Define YAML files for each microservice.
•	Pods: Manage individual services and ensure they communicate effectively.
•	Expose the frontend service: Allow it to be accessible through a NodePort or LoadBalancer on Minikube.
•	Replicas: Maintain 3 replicas for each pod.


6.	Implementation

•	Frontend Service (React)
Create a React application.

•	Backend Service (Node.js with Express)
Create an Express Application.
Implement API endpoints: Create routes for Signup, Login, and Forgot Password.
 
•	Database Service (MongoDB)

•	Backend Service (Node.js with Express)
Create Dockerfiles for each service: frontend/Dockerfile, backend/Dockerfile, Docker-compose.yml

•	Kubernetes Deployment
Create Kubernetes YAML files (shown in GitHub)

•	Deploy on Minikube
Start Minikube
Build and push Docker images                                     
Apply Kubernetes configurations