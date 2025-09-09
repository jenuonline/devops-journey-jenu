# Azure DevOps CI/CD Pipeline for .NET Web Application

This project demonstrates a complete CI/CD pipeline setup using Azure DevOps for a .NET web application. It includes build, test, SonarQube code analysis, and deployment to Azure App Service with staging and production slots.

## Features

- Automatic trigger on `main` branch commits
- Build and restore using NuGet
- Static code analysis with SonarQube
- Unit testing with VSTest
- Deployment to Azure App Service staging slot
- Slot swap to production after successful deployment

## Prerequisites

- Azure DevOps project
- Azure App Service with staging slot
- SonarQube service connection configured in Azure DevOps
- Azure Resource Group and Subscription

## Setup Instructions

1. Update `azure-pipelines.yml` with your:
   - Azure subscription name
   - App service name
   - Resource group name
   - SonarQube service connection name

2. Commit the pipeline file to your repository.

3. Configure pipeline in Azure DevOps and run it.

## File Structure

- `azure-pipelines.yml`: Defines the CI/CD pipeline
- `README.md`: Documentation for pipeline setup

## Author

Jenu Varughese  
DevOps Engineer | CI/CD Specialist | Cloud Native Advocate  
[LinkedIn](https://linkedin.com/in/jenu)
