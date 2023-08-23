## Project: Multi-Instance DevOps Automation with Jenkins, Ansible, and AWS

In this project, I orchestrated a comprehensive DevOps workflow using AWS instances, Jenkins, Ansible, and Docker to streamline application deployment. The project workflow consisted of the following key steps:

1. **Infrastructure Setup:** Configured three AWS instances for distinct purposes: one hosted Jenkins, another hosted Ansible, and the third acted as a web server for application hosting.
2. **Code Integration:** Utilized Jenkins in a freestyle setup to pull code from a GitHub repository and sync it with the Jenkins server.
3. **SSH Configuration:** Established SSH connections between Jenkins, Ansible, and the web server instances, ensuring secure communication for automation tasks.
4. **GitHub Repo Synchronization:** Employed asynchronous synchronization between the Jenkins server and Ansible server to keep the GitHub repository data updated on the Ansible server.
5. **Docker Image Creation:** Automated the creation of Docker images through Jenkins pipelines and pushed them to DockerHub, incorporating commands to manage and delete old Docker images.
6. **Ansible Playbook Deployment:** Executed Ansible playbooks to deploy Docker containers on the web server instance, hosting the application website. Included cleanup code in the Ansible playbook to remove previous containers and maintain a smooth pipeline.

This project underscored my proficiency in orchestrating multi-instance environments, setting up continuous integration, automating Docker image management, and deploying applications using Ansible. It showcased my expertise in implementing robust DevOps practices for efficient and reliable software delivery.
