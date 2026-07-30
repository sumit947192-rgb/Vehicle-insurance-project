This project is an end-to-end Machine Learning Operations (MLOps) pipeline built to process, model, and serve vehicle insurance data. Designed with production-readiness in mind, it demonstrates how to integrate machine learning models with robust software engineering practices, cloud infrastructure, and automated deployment workflows.

Pipeline Architecture
Data Management: Connects to a MongoDB Atlas cluster for dynamic data ingestion, followed by strict schema validation and feature transformation.

Model Lifecycle: Automates model training, evaluates performance against baseline metrics, and pushes versioned models to an AWS S3 registry.

Web Interface & API: Serves real-time predictions via a web application utilizing custom static and template directories.

CI/CD Automation: Utilizes GitHub Actions and Docker to automatically build images, push them to AWS ECR, and deploy the application to a self-hosted AWS EC2 instance.

Observability: Features modular, custom-built exception handling and logging systems for easy pipeline monitoring and debugging.

Tech Stack
Language & Environment: Python 3.10, custom virtual environments, and local package management (setup.py, pyproject.toml)

Database: MongoDB Atlas

Cloud & Deployment: AWS (IAM, S3, ECR, EC2), Docker

Automation: GitHub Actions
