# Git Commands for Updating Submodules

```sh
git clone https://github.com/edu-rpa/edurpa.git
git submodule update --init --recursive
```

To ensure all submodules in your repository are up-to-date, use the following command:

```sh
git pull --recurse-submodules
```

# Project Components

Below is a list of the various components involved in the EduRPA project. Each component plays a specific role within the system.

## Robot Binary (bin)

This component contains the binary files necessary for running the EduRPA robot.

## EduRPA Backend (edu-rpa-backend)

The backend service for EduRPA, handling the core business logic and data processing.

## EduRPA Frontend (edu-rpa-frontend)

The frontend service for EduRPA, providing the user interface for interaction with the EduRPA system.

## EduRPA Infrastructure Service (edu-rpa-serverless)

The infrastructure service for EduRPA, utilizing serverless architecture for scalability and efficiency.

## Image Preprocessing Service (edu-rpa-serverless-robot)

A specialized service within the EduRPA ecosystem, responsible for preprocessing images before they are fed into the robot's workflow.

## EduRPA Library (edurpa-librabry)

A collection of libraries and utilities used across various EduRPA services.

### EduRPA.Cloud (edurpa-cloud)

A submodule of the EduRPA Library, focusing on cloud integration and services.

### EduRPA.Document (edu-rpa-document)

Another submodule of the EduRPA Library, dealing with document processing and management within the EduRPA system.