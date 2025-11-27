# Images Directory

This folder contains architecture and pipeline diagrams for the CICD_Pipeline project.

## Images to Add

1. **pipeline-flow.png** — CI/CD Pipeline workflow diagram
   - Shows stages from Git Checkout → Kubernetes Deployment
   - Includes: Maven, SonarQube, Trivy, Nexus, Docker, Kubernetes

2. **azure-architecture.png** — Azure infrastructure architecture diagram
   - Shows: Resource Group, VNet, Subnets, VMs (Jenkins, SonarQube, Nexus)
   - Includes: Network Security Group, Public IPs, NICs, AKS Cluster

## How to Add Images

1. Save the PNG files to this directory:
   ```bash
   cp /path/to/pipeline-flow.png ./
   cp /path/to/azure-architecture.png ./
   ```

2. Commit and push:
   ```bash
   git add Images/
   git commit -m "Add architecture and pipeline diagrams"
   git push -u origin main
   ```

3. Images will then display in README.md
