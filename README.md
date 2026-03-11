# DevOps CI/CD Pipeline using GitHub Actions

## Project Overview
This project demonstrates a simple Continuous Integration (CI) pipeline using GitHub Actions. The pipeline automatically runs when code is pushed to the repository.

## Technologies Used
- Python
- Git
- GitHub
- GitHub Actions
- Linux Runner

## CI/CD Workflow
The pipeline performs the following steps:

1. Trigger workflow on code push
2. Checkout repository code
3. Setup Python environment
4. Run Python application

## Workflow File
Location:
.github/workflows/ci.yml

## Example Output
When code is pushed to GitHub, the pipeline runs automatically and executes the Python script in a Linux environment.

## Learning Outcome
- Understanding CI/CD concepts
- Automating build pipelines
- Working with GitHub Actions workflows
- Using Linux runners for automation

## Future Improvements
- Add automated testing
- Add Docker container deployment
- Deploy application to cloud
