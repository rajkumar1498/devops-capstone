# devops-capstone
This is to submit final nanodegree project capstone.
# Udacity-capstone-project :
In this project I applied the skills I learnt in the past couple of months from the Udacity Cloud Devops Engineer nanodegree. These include:

# Working in AWS
Using Jenkins or Circle CI to implement Continuous Integration and Continuous Deployment
Building pipelines
Working with Ansible and CloudFormation to deploy clusters
Building Kubernetes clusters
Building Docker containers in pipelines

# Setup the Environment
Create Dockerfile, makefile, requirements.txt
create python virtualenv & source it: source ~/.capstone/bin/activate python3 -m venv ~/.capstone
Then run make install

# Set up project in CircleCi
Create nginx_deployment.yml
Running app.py
Set up Hello world application
Deploy the application in Amazon EKS
eksctl create cluster --name capstone --region us-east-1 --fargate
aws eks --region us-east-1 update-kubeconfig --name capstone
kubectl config use-context arn:aws:eks:us-east-1:731488622603:cluster/capstone
kubectl get nodes
kubectl get pods --all-namespaces
kubectl apply -f eks_deployment.yml
kubectl get deployment
