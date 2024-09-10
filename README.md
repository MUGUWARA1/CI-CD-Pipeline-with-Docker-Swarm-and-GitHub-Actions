# CI/CD Pipeline with Docker Swarm and GitHub Actions

## Overview: 

This repository demonstrates a CI/CD pipeline using Docker Swarm and GitHub Actions. The pipeline automates the process of building an HTML file with Docker, pushing it to Docker Hub, and deploying it in a Docker Swarm cluster using "Play with Docker."

### Task 1: CI/CD on a Docker Swarm Cluster 

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/ci-cd-pipeline-docker-swarm.git
    cd ci-cd-pipeline-docker-swarm
    ```

2. **Configure Variables and Secrets:**
    - Update Docker token and username.
    - Set the SSH link of the manager node.

3. **Push to Your GitHub Account:**
    - Push the repository to your GitHub account.

4. **Verify Deployment:**
    - After each commit, you should see the changes reflected on the worker node address at port 80.
      
## The pipeline CI/CD :

![setting of the pipeline](https://github.com/user-attachments/assets/3a9423c8-c497-402d-be83-4d868602fafb)

## Lifecycle
![Diagramme sans nom-Page-2](https://github.com/user-attachments/assets/cd9e94c5-e7b8-4531-a3ee-7c4003ce356e)

## conclusion

This pipeline automates the entire software development lifecycle, from the moment code is pushed to the repository, through integration with other components, and finally to deployment in production.
