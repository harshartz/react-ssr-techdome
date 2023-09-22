# CI/CD Documentation

## Introduction

This documentation provides a step-by-step guide to the Continuous Integration/Continuous Deployment (CI/CD) pipeline set up for the React application in this repository. As the primary focus of this documentation is on the pipeline setup and deployment, it's important to note that my role in this project is as a DevOps engineer with limited expertise in React development.

## Pipeline Overview

The purpose of the CI/CD pipeline is to automate the build and deployment process of the React application whenever changes are pushed to the master branch. The pipeline consists of several stages, including code building, testing, and deployment to an AWS S3 bucket.

## Pipeline Configuration

### GitHub Actions Workflow

The pipeline is configured using GitHub Actions, and the workflow definition is specified in the [react-ssr.yml]([.github/workflows/main.yml](https://github.com/harshartz/react-ssr-techdome/blob/master/.github/workflows/react-ssr.yml)) file. This YAML file outlines the various steps and configurations for the CI/CD process.

### Environment Variables

Certain environment variables are set to securely manage sensitive information such as AWS access keys and secrets. These variables are defined within the GitHub repository's secrets settings.

## Manual Triggering

In rare cases where manual triggering of the pipeline is required, developers can do so by following these steps:

1. Navigate to the GitHub repository.
2. Click on the "Actions" tab.
3. Select the workflow named "CI/CD Pipeline" or a similar name.
4. Click the "Run workflow" button.
5. Choose the branch (typically "master") and start the workflow.

### Issue Description

The `index.html` file generation appears to be problematic. Despite multiple attempts at troubleshooting, the issue persists. It is important to note that my primary role is as a DevOps engineer, and my expertise is focused on infrastructure and automation rather than React development. My limited understanding of React may have influenced the troubleshooting process.

### Suspected Causes

While I have made observations about specific code sections that might be related to the issue, I suspect that a more in-depth analysis by a React expert is required to pinpoint the exact cause.

## Feedback Request

I welcome feedback and guidance from the recruiter or any React experts who may be reviewing this assignment. Your expertise in React development would be invaluable in diagnosing and resolving the `index.html` issue effectively.


## Additional Notes

- The application is deployed to an AWS S3 bucket, and the live version can be accessed at [React App on AWS S3](http://react-app-project1.s3-website-us-east-1.amazonaws.com).
- This documentation aims to provide clarity on the pipeline setup and the encountered issue, fostering collaboration to resolve it.

---

Your cooperation and expertise in React development are greatly appreciated in addressing the `index.html` issue. Together, we can ensure the successful deployment of this React application.

Please feel free to reach out with any feedback, suggestions, or guidance.

*Thank you,*

Harsh Hire
