# Kubernetes
deploying a sample python code on eks cluster, creating deployment, service, ingress and install ingress controller ALB.

# Steps
1. Create a VPC with private and public subnets.
2. Attach IG and NAT Gateway to the subnets.
3. Install and configure AWS CLI V2.
4. Install Kubectl and eksctl
5. Create a cluster config yaml file and create the cluster using it.
6. Create deployment, service and ingress for the python app.
7. Create AWS ALB ingress controller.
8. Create and attach roles.
9. Open port of node group for all traffic and direct towards the Security Group.
10. Open the DNS in the browser.
