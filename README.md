
# CI/CD Final Project

## Project Name
CI/CD Final Project - JavaScript Calculator

## Project Description
This is the final project for the IBM Continuous Integration and Continuous Delivery course.

The project implements a JavaScript calculator and demonstrates automated linting, unit testing, container image building, and deployment using GitHub Actions, Tekton Pipelines, and Red Hat OpenShift.

## Project Files
- calculator.js - Calculator application
- calculator.test.js - Jest unit tests
- package.json - Node.js dependencies and scripts
- eslint.config.mjs - ESLint configuration
- .github/workflows/workflow.yml - GitHub Actions CI workflow
- .tekton/tasks.yml - Tekton pipeline task definitions

## CI/CD Pipeline Stages
1. Cleanup
2. Git Clone
3. ESLint
4. Jest Unit Tests
5. Buildah
6. Deploy using OpenShift Client

## Technologies
JavaScript, Node.js, Jest, ESLint, GitHub Actions, Tekton, Buildah, Red Hat OpenShift

## Author
Dhruti Mahadik
