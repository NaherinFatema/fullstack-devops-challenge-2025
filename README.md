FSA DevOps Challenge – React Todo App Deployment

● Project Description
This project is part of the FSA DevOps Challenge and involves the end-to-end deployment of a React Todo application using various DevOps tools and services. The process covers EC2 setup, user management, Node.js deployment, Jenkins CI/CD configuration, Docker containerization, Nginx reverse proxy setup, and automation via shell scripting.



--Manual Implementation Note
This project was implemented manually from the ground up as part of the FSA DevOps Challenge.
All AWS configurations, CI/CD pipelines, shell scripts, and deployment steps were set up individually to demonstrate a hands-on understanding of each component.



Project Breakdown

● Part 1: EC2 and User Management

* Created an EC2 Ubuntu instance on AWS
* Created a new user and added SSH access
* Provided sudo privileges without password prompt
* Configured SSH hardening and disabled root login

● Part 2: React App Setup and Node Deployment

* Cloned the React Todo app repository
* Installed Node.js and dependencies
* Built the React app for production
* Used PM2 to serve the app on port 3000

● Part 3: Jenkins Installation and CI/CD Pipeline

* Installed Jenkins on EC2
* Installed required plugins and set up admin credentials
* Created a Jenkins pipeline job with GitHub integration
* Configured build steps to pull code, build app, and deploy with PM2
* Enabled webhook-based automatic deployment on push

● Part 4: Docker and Nginx Deployment

* Installed Docker and Docker Compose
* Created a Dockerfile and docker-compose.yml for the React app
* Built and ran the container
* Configured Nginx as a reverse proxy to serve the app on port 80

● Part 5: Shell Script Automation

* Wrote automation scripts for installation, deployment, and setup
* Scripts covered Node.js install, PM2 install, app deployment, Docker setup, and Nginx configuration
* Added executable permissions and verified outputs

Technologies Used
● AWS EC2
● Ubuntu
● Node.js
● React
● PM2
● Jenkins
● Docker
● Nginx
● Shell Scripting
● GitHub Webhooks



Screenshots and Proof of Work
Refer to the `fsa devops challenge` folder containing 25 screenshots demonstrating each step of the implementation.



