# Basic-Dockerfile

## Project URL  
[project URL](https://roadmap.sh/projects/basic-dockerfile)

 
## Overview 
This project demonstrates how to create a basic Dockerfile to build a Docker image that prints a custom greeting to the console. The Docker image can print "Hello, Captain!" by default or use a custom name from a file (`imageName.txt`), making it a simple example for understanding Dockerfile creation and building Docker images with custom arguments.

## Files in this project:
- **Dockerfile**: Contains the instructions to create a Docker image that prints "Hello, [NAME]!" to the console.
- **name.txt**: A text file that contains the custom name to be passed as a build argument.
- **.github/workflows/docker-build.yml**: A GitHub Actions workflow file that builds and runs the Docker image, both with the default and custom names.

## Features
- **Basic Docker Image**: Prints "Hello, Captain!" when run.
- **Advanced Docker Image**: Accepts a custom name from `imageName.txt` and prints "Hello, [your name]!".
- **GitHub Actions Integration**: Automates the process of building and running the Docker image in the CI/CD pipeline.
