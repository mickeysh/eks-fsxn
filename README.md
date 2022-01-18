# EKS and FSxN - The most efficient way to run your and clone your containerized databases

This repo comes as an appendix to the this (link here) blog post. It will help you build the demo enviroment and run the code samples that are mendioned throughout the blog. 

## Prerequisites
- Install [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) on your workstation/server
- Install [aws cli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) on your workstation/server
- Install [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) on your workstation/server

## Content
- [terraform](/terraform) - terraform code to start a demo environment in AWS with 
- [samples](/samples) - kubernetes yaml samples that are used throughout the blog
- [trident-installer](/trident-installer) - this is a sample trident installer directory we used to install trident while writing the blog. You should download the most updated version using the instructions in the blog
