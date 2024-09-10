# CI/CD Pipeline with Docker Swarm and GitHub Actions

## overview: 

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
      
#### The pipeline CI/CD :
![alt text](<setting of the pipeline.png>)

#### The first push :
![alt text](<the first push of the pipeline.png>)

#### After changing the title  :
![alt text](<the second push.png>)

#### Lifecycle
![alt text](<Diagramme sans nom-Page-2.jpg>)
### conclusion

This pipeline automates the entire software development lifecycle, from the moment code is pushed to the repository, through integration with other components, and finally to deployment in production.
