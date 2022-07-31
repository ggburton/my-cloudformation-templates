# A collection of Cloudformation templates 

These AWS Cloudformation templates are things I've been building to better understand AWS and Cloudformation. I'll probably also start converting them to Terraform deployments in another repo once I'm more comfortable with what I'm doing.

## 1. basicWebServer.yaml

A Minimal deployment that creates a web server.... no HTTPS at this stage.


## 2. basicRDSsetup.yaml

This will eventually setup a 2 tier database lab for testing

At the moment it only create a VPC, a private subnet and a public subnet.

It then creates an internet gateway and connects it to the VPC.