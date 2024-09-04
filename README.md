## Cloud-Native DevOps Project (Part 3 of 5)

## Background
 
Our University Library is a cornerstone of academic resources, aims to enhance accessibility to educational materials through an advanced online platform. 
You has been asked to develop a cloud-native microservices architecture to support the library’s diverse user base and streamline deployment processes.

By end of this project, you will gain a comprehensive understanding of essential DevOps practices and cloud-native application deployment techniques. 
More specifically, you will be able to do following:

1. Create Dockerfiles to containerize application and define the runtime
environment.
2. Develop Kubernetes YAML files (deployment.yaml and service.yaml) to deploy
and manage their microservice on Azure managed Kubernetes cluster.
3. Write Terraform scripts (main.tf, variables.tf, outputs.tf, provider.tf) to
provision Azure infrastructure.
4. Deploy Azure Kubernetes Service (AKS) and integrate PostgreSQL for data
storage.
5. Configure GitHub Actions workflows to automate the CI/CD pipeline.
6. Apply theoretical knowledge to real-world scenarios, enhancing their
understanding of cloud computing and DevOps principles.

## Tasks

In this task, you are continuing work from the previous project, focusing on
Dockerizing the book_catalog and inventory_management microservices and
deploying it to Azure Managed Kubernetes. By the end of this project, you will gain
hands-on experience in setting up and managing containerized applications to
Azure Container Registry and host them on Azure Kubernetes Service.

## Steps

1. Downlaod code from the Task Resources and unzip.
2. Create a github repository named : <your-name-sit722-part3> .
3. Add given code to a github repository (local first then push to the remote
repo).
4. Write Dockerfiles for both Microservices ( book_catalog and
inventory_management ).
5. Write a Docker Compose file to orchestrate the microservices and PostgreSQL
database (Use Azure PostgreSQL or Render PostgreSQL).
6. Upload docker images to the remote repository.
7. Create deployment.yaml .
8. Deploy Microservice to Azure Managed Kubernetes.
