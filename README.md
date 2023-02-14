# Deployment to EC2 using Ansible

## Description
This project is to create EC2 instances with all other resources it needs to run including, a VPC, Subnets, Internet Gateway, Routes, Security groups, Key pair, etc. 

The ansible script is triggerred by a Github action against an AWS account. 

This was an experiment. The actual usage is for a much larger project, where after creating the resources, another playbook does the deployment to the EC2 instance. 


