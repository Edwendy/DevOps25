# DevOps25

This repository demonstrates a complete DevOps workflow. It includes source control, continuous integration, containerization, and automated deployment. The goal is to show how software can move from code to a running service with minimal manual steps.

---

## Project Overview

The DevOps25 project simulates a production-style delivery pipeline:

1. Application code is managed in GitHub.
2. A GitHub Actions pipeline builds and tests the application on each commit.
3. The application is packaged as a Docker image for consistency across environments.
4. The Docker image is deployed to a container runtime (local or cloud).
5. The setup can be extended to Kubernetes or cloud services such as AWS, Azure, or Google Cloud.

---

## Tools and Technologies

- Git and GitHub for version control
- GitHub Actions for CI/CD
- Docker for containerization
- Bash for scripting
- Future extension: Terraform for infrastructure as code
- Future extension: Kubernetes for orchestration
- Future extension: Prometheus and Grafana for monitoring

---

## Features

- Automated build and test pipeline triggered by each push to the repository
- Docker image build and local deployment
- Optional push to Docker Hub or other registries
- Ready to extend into cloud deployments

---

## Setup and Usage

Clone the repository:

```bash
git clone https://github.com/Edwendy/DevOps25.git
cd DevOps25

CI/CD with GitHub Actions

The repository includes a workflow configuration in .github/workflows/ci.yml.
This pipeline runs automatically when code is pushed:

Install dependencies

Run tests

Build a Docker image

Push the image to Docker Hub (if configured)

Deploy the container to the target environment
Developer → GitHub → GitHub Actions → Build and Test → Docker Image → Deployment

Roadmap

Add Terraform to automate infrastructure setup

Deploy to AWS EC2 or Kubernetes

Add monitoring with Prometheus and Grafana

Configure notifications on pipeline success or failure

Add security scans for container images
Author

Edith Wendy Sosu
Aspiring DevOps Engineer focused on automation, infrastructure, and continuous delivery.
