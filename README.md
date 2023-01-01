
# Face Authentication System

This is a modern Face Authentication System which includes state-of-art algorithms to detect face and generate face embedding. This system contains endpoints which can be integrated to any device depending on the requirements. 

## Project Archietecture
<img width="844" alt="image" src="https://user-images.githubusercontent.com/57321948/195135349-9888d9ea-af5d-4ee2-8aa4-1e57342add05.png">

## Run the Application
Before we run the project, make sure that you are having MongoDB in your local system, with Compass since we are using MongoDB for data storage. You also need Azure account to access the service like ACS and App services.


## Deployment to Azure

### Services used
- Azure container Registry (ACR) for Docker image of project is stored
- Azure App Services for deploying the application
- GitHub Actions for CI/CD
