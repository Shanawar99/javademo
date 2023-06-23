# javademo
java demo

This is a sample interactive Java website that prints hello world

## Prerequisites

Before running the application, make sure you have the following prerequisites:

- EC2 running and SSH access 

## Set Secrets

In your GitHub repository, go to Settings > Secrets > New Repository Secret.

Add the following secrets:

Name: EC2_HOST
Value: The Public IP address or hostname of your EC2 machine.

Name: EC2_USERNAME
Value: The username to use for SSH connection to the EC2 machine e.g ubuntu/ec2-user

Name: EC2_PRIVATE_KEY
Value: The contents of the encrypted .pem file.
