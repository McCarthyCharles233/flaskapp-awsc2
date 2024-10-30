# Flask App Deployment with GitHub Actions to AWS EC2

This project demonstrates how to continuously deploy a Flask application to an AWS EC2 instance using GitHub Actions. By leveraging CI/CD, each push to the repository automatically triggers deployment to ensure the latest version of the application is live.

The application is a simple Flask app that serves a welcome message on the root endpoint (`/`). This deployment pipeline uses GitHub Actions to build and deploy the app to an AWS EC2 instance upon each push to the main branch.

