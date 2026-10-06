# Lab2 INSTRUCTIONS

# Using terminal, got to the folder where the project files are stored.

    # Run the script below to create a Docker Image
    docker build -t etv-terraform-image:lab2 .


    # Run the script below to create a Docker Container
    docker run -dit --name etv-lab2 etv-terraform-image:lab2 /bin/bash


    # Check Terraform an AWS CLI version, using the script
    terraform version
    aws --version
