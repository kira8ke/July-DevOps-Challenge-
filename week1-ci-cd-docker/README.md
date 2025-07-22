# Week 1 – CI/CD Pipeline with Docker 🐳 

# View it on https://july-devops-challenge.onrender.com

## Goal

Build and containerize a Node.js app, and set up a CI/CD pipeline using GitHub Actions.

## Structure

- `app/`: Node.js app
- `Dockerfile`: Container definition
- `.github/workflows/ci.yml`: CI pipeline

## Run Locally

```bash
docker build -t devops-challenge-app .
docker run -p 3000:3000 devops-challenge-app
```
