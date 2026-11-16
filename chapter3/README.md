# Recipe Sharing Application

A full-stack recipe-sharing application built using AWS cloud services. This project was developed as part of my AWS Cloud Projects learning journey.

## Architecture

- **Frontend:** React
- **Frontend Hosting:** Amazon S3 and CloudFront
- **Backend:** Python, FastAPI
- **Compute:** Amazon EC2
- **Database:** Amazon DynamoDB
- **Infrastructure:** AWS CloudFormation

## Features

- View shared recipes
- Create new recipes through the admin interface
- Delete recipes
- Store recipe titles, ingredients, and preparation steps
- Separate user and admin interfaces

## AWS Deployment

The frontend is hosted on Amazon S3 and distributed through CloudFront. The backend API runs on an EC2 instance and communicates with DynamoDB to store and retrieve recipe data.

## Application

**Live Demo:** https://d2c3hwekal8xjq.cloudfront.net

## Future Improvements

- Migrate the backend to AWS Lambda and API Gateway
- Implement authentication using Amazon Cognito
- Add recipe likes and sorting functionality
- Improve API security with HTTPS

## Repository Structure

- `frontend/` – React application
- `backend/` – Python FastAPI backend
- `platform/` – AWS CloudFormation templates

---

**Version:** Chapter 3 – EC2-based Recipe Sharing Application
