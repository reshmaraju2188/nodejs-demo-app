# Task 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

## Objective
Set up a Continuous Integration and Continuous Deployment (CI/CD) pipeline to build and deploy a sample Node.js web application using GitHub Actions.

---

## Tools & Technologies Used

- **GitHub** – Version control and CI/CD trigger source.
- **GitHub Actions** – For automating the build and deployment process.
- **Node.js** – Sample application stack.
- **Docker** – Containerization of the application.
- **Docker Hub** – For pushing Docker images.

---

---

## Pipeline Workflow Overview

1. **Trigger**  
   The pipeline is triggered on `push` to the `main` branch.

2. **Build**  
   The Node.js app is built and a Docker image is created.

3. **Test (Optional)**  
   Application-level tests can be run (optional step).

4. **Push to Docker Hub**  
   The built image is tagged and pushed to your Docker Hub repository.

5. **Deploy**  
   Deployment step handled via Docker pull and run (customized per environment).

---

## Deliverables

- GitHub Repository with:
  - A working `.github/workflows/main.yml` CI/CD pipeline file.
  - Dockerfile for the sample Node.js application.

---

## Outcome

Successfully implemented a CI/CD pipeline to:
- Build a Docker image for the Node.js app
- Push the image to Docker Hub
- Automate the entire process using GitHub Actions


