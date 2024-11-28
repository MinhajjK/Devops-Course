# Devops-Course

**Terraform Through EKS:**

In this blog i explored setting up an EKS cluster using Terraform to automate cloud infrastructure without relying on the AWS Console. Here's what I did and learned:

Configured AWS Credentials: I set up my local machine to interact with AWS using aws configure.
Wrote the Terraform Script: I created a configuration to provision a VPC, subnets, IAM roles, and an EKS cluster. This made the process streamlined and repeatable.
Initialized and Applied Terraform: Using terraform init and terraform apply, I watched Terraform spin up the entire infrastructure in minutes.
Connected to the EKS Cluster: I connected the cluster to my local machine with AWS CLI and verified it using kubectl get nodes.
What I Learned:
Automation is a Game Changer: Terraform eliminates the need for manual setups, making deployments faster and error-free.
EKS Simplifies Kubernetes Management: Combining Terraform with EKS lets me focus on applications while AWS handles the Kubernetes backend.
This experience reinforced how powerful infrastructure as code can be for modern DevOps workflows!