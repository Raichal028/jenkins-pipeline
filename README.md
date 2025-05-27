# Jenkins Pipeline Project

This repository contains the code and Jenkins pipeline configuration for automating the build, test, and deployment of the application using Jenkins and Docker.

## Project Overview

- The Jenkins pipeline is defined in the `Jenkinsfile` at the root of this repository.
- The pipeline includes stages for building, testing, and deploying the app.
- Jenkins polls this repository every 5 minutes to detect code changes and trigger builds automatically.

## How to Use

1. Make changes to the code or Jenkinsfile.
2. Commit and push the changes to the `main` branch.
3. Jenkins will detect the changes and trigger the pipeline build.

## Technologies Used

- Jenkins
- Docker
- GitHub

---

*Last updated on May 27, 2025.*
