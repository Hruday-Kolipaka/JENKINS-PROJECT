###CI/CD Pipeline for Web Application Deployment###

This project sets up a complete CI/CD pipeline to automate the deployment of a web application. It integrates various tools to streamline the development, testing, and deployment processes, ensuring high code quality and efficient artifact management.

## Tools Used

- **Git**: Source code management.
- **Maven**: Build automation.
- **SonarQube**: Code quality analysis.
- **Nexus**: Artifact repository.
- **Tomcat**: Application server for deployment.
- **Jenkins**: Orchestration of the CI/CD pipeline.

## Overview

The pipeline encompasses the following stages:

1. **Code Retrieval**: Fetches the latest code from a Git repository.
2. **Build**: Compiles the source code and packages it into a deployable artifact.
3. **Quality Check**: Analyzes the code for quality and security issues using SonarQube.
4. **Artifact Management**: Uploads the built artifact (WAR file) to Nexus for versioned storage.
5. **Deployment**: Deploys the artifact to a Tomcat server using Jenkins.

### Key Steps

1. **Setup**: Launch instances for Jenkins, Tomcat, SonarQube, and Nexus.
2. **Configure Jenkins**: Install necessary plugins and create a pipeline job.
3. **Pipeline Execution**: Automate the process from code retrieval to deployment.
4. **Monitoring**: Review build and deployment statuses to ensure smooth operation.

## Outputs

Screenshots and logs of the following components will provide insights into the successful execution of the pipeline:

- **Jenkins**: Build and deployment status.
- **Tomcat**: Deployed application and server status.
- **Nexus**: Uploaded artifacts and repository details.
- **SonarQube**: Code quality reports.

*Please see the screenshots below for detailed output examples.*

![Sonarqube png](https://github.com/user-attachments/assets/a0c4069a-febc-4128-84cd-b3e64f4b9773)
![Nexus_Artifactory png](https://github.com/user-attachments/assets/1d2caf38-2922-4c2c-bba6-6bdb78028da8)
![jenkins_build_status png](https://github.com/user-attachments/assets/367b7aa4-80b0-4d51-94ea-a5ba768b43a2)
![website png](https://github.com/user-attachments/assets/1da73602-0db9-4e15-89f7-1d6b8f6324ed)
![tomcat_deployment png](https://github.com/user-attachments/assets/2fdc38ba-290a-4f8d-8494-8d601fa214f1)
![TIC-TAC-TOE-GAME png](https://github.com/user-attachments/assets/c3e66680-4cb0-486a-b200-b49aca97dcc5)


