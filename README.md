# devops-capstone
[![CircleCI](https://circleci.com/gh/rajkumar1498/devops-capstone/tree/main.svg?style=svg)](https://circleci.com/gh/rajkumar1498/devops-capstone/tree/main)

# Udacity-capstone-project :
In this project I have applied the skills I learnt in the past months from the Udacity Cloud Devops Engineer nanodegree. This nanodegree course provided us various tools and handson lab practices that will certainly help me to work with realtime project. I have learnt many things that i will continue to explore more and more to get more deeper insight about the topics i learnt. 

# Working in AWS
In this project, i have used Circle CI to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Worked with Ansible and CloudFormation to deploy clusters
* Building Kubernetes clusters locally using minikube as well as AWS EKS Kubernetes cluster.
* Building Docker containers in pipelines and also pushed image to github repo

# Setup the Environment
* Create Dockerfile, makefile, requirements.txt
    * create python virtualenv & source it:
        * python3 -m venv ~/.capstone
        * source ~/.capstone/bin/activate 
* Install the required dependencies.        
* Then check for lint by runing make install.

# Set up project in CircleCi
* Creaye the kubernetes cluster.
* Create nginx_deployment.yml
* Running app.py
* Set up static web application
* Deploy the application in Amazon EKS
* Successfully assigned default/capstone-devpos-cluster-66966c6d8f-m6p76 to ip-192-168-23-5.*********.compute.internal
* kubectl get nodes
* kubectl get pods --all-namespaces
* kubectl apply -f nginx_deployment.yml
* kubectl get deployment
