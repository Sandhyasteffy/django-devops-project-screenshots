# Django DevOps Project — Screenshots

## Project Overview
This repository contains screenshots documenting my Django application deployment using Docker, Jenkins, GitHub Container Registry (GHCR), Terraform, and AWS EC2.

## Project Architecture
GitHub → Jenkins → Docker Image → GHCR → AWS EC2

Terraform is used to provision the AWS infrastructure. Jenkins builds the Docker image and pushes it to GHCR. The image is then manually pulled and run on the EC2 instance.

## Screenshots

| No. | Screenshot | Description |
|---|---|---|
| 01 | GitHub Repository | Source code and project files |
| 02 | Jenkins Build Success | Successful Jenkins build |
| 03 | Jenkins GHCR Push Success | Docker image pushed to GHCR |
| 04 | GHCR Container Image | Published Docker image |
| 05 | Terraform Resources | Terraform-managed infrastructure resources |
| 06 | AWS VPC | Virtual Private Cloud in AWS |
| 07 | EC2 Docker Container | Running application container |
| 08 | Live Application | Django welcome page running on AWS EC2 |
| 09 | EC2 Instances | AWS EC2 instances |
| 10 | Dockerfile | Instructions used to build the Docker image |

## Technologies Used
- Python and Django
- Docker
- Jenkins
- GitHub
- GitHub Container Registry (GHCR)
- Terraform
- Amazon Web Services (AWS EC2 and VPC)

## Deployment Note
The CI image build and push are automated through Jenkins. Deployment to EC2 is performed manually.

## Live Application
http://13.207.200.39

## Author
Sandhya Steffy M
