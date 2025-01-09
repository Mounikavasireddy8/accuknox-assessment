Accuknox QA Trainee Practical Assessment

Problem Statement 1: Containerisation and Deployment of Wisecow Application on Kubernetes
Overview
This repository contains the solution for the first problem statement, which involves containerizing and deploying the Wisecow application on a Kubernetes environment with secure TLS communication.

Requirements
- Dockerization of the Wisecow application
- Kubernetes deployment of the Wisecow application
- Continuous Integration and Deployment (CI/CD) using GitHub Actions
- Secure TLS communication

Artifacts
- Dockerfile for the Wisecow application
- Kubernetes manifest files for deployment
- CI/CD pipeline configuration using GitHub Actions
- GitHub Actions workflow file for facilitating Continuous Build and Deployment (CI/CD)

Setup
1. Clone this repository to your local machine.
2. Create a Kubernetes cluster and configure it to use the Wisecow application.
3. Set up a container registry (e.g., Docker Hub) to store the Wisecow application image.
4. Configure the CI/CD pipeline using GitHub Actions.

Usage
1. Make changes to the Wisecow application code.
2. Commit the changes to the repository.
3. The CI/CD pipeline will automatically build and push the updated image to the container registry.
4. The updated application will be deployed to the Kubernetes environment.

Security
- TLS communication is enabled for the Wisecow application.
- The Kubernetes cluster is configured to use secure communication protocols.

Problem Statement 2: System Health Monitoring Script and Log File Analyzer
Overview
This repository also contains solutions for the second problem statement, which involves developing a system health monitoring script and a log file analyzer.

System Health Monitoring Script
- The script monitors the health of a Linux system by checking CPU usage, memory usage, disk space, and running processes.
- If any of these metrics exceed predefined thresholds, the script sends an alert.

Log File Analyzer
- The script analyzes web server logs (e.g., Apache, Nginx) for common patterns such as the number of 404 errors, the most requested pages, or IP addresses with the most requests.
- The script outputs a summarized report.

Artifacts
- System health monitoring script (Bash or Python)
- Log file analyzer script (Bash or Python)

Setup
1. Clone this repository to your local machine.
2. Configure the system health monitoring script to run at regular intervals.
3. Configure the log file analyzer script to run on the web server logs.

Usage
1. Run the system health monitoring script to check the health of the Linux system.
2. Run the log file analyzer script to analyze the web server logs.

Security
- The scripts are designed to be secure and do not store any sensitive information.
