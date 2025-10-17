AWS EKS Kubernetes Setup Demo

Step 1 - Create EKS Cluster

eksctl create cluster \
--name my-first-eks-cluster \
--region us-east-1 \
--nodes 2 \
--nodes-min 1 \
--nodes-max 3 \
--managed


 This command provisions an Amazon EKS cluster with 2 managed EC2 worker nodes.


Step 2 - Verify Cluster
kubectl get nodes
kubectl get svc


Confirms that my Kubernetes nodes and services are running properly.


Step 3 - Create a Sample Deployment
kubectl create deployment nginx-demo --image=nginx

This deploys a sample NGINX web server container on my EKS cluster.


Step 4 - Expose the Deployment
kubectl expose deployment nginx-demo --type=LoadBalancer --port=80

This creates a service that exposes NGINX to the internet using an AWS Elastic Load Balancer (ELB).

Step 5 - Verify Deployment and Service
kubectl get pods
kubectl get svc

This lists all running pods and shows the EXTERNAL-IP of my service.
Once the EXTERNAL-IP appears, I open it in my browser, then, I should see the NGINX welcome page.

Step 6 - Clean Up Resources
eksctl delete cluster --name my-first-eks-cluster --region us-east-1

This deletes my EKS cluster and all related AWS resources to avoid costs.

Notes
This project was executed on an EC2 Linux instance.
Tools used: eksctl, kubectl, AWS CLI.
AWS Service used: EKS (Elastic Kubernetes Service), EC2, IAM, and VPC.
Purpose: Learn how to deploy and manage Kubernetes clusters on AWS.
