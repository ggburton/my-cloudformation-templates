# A collection of Cloudformation templates 

These AWS Cloudformation templates are things I've been building to better understand AWS and Cloudformation. I'll probably also start converting them to Terraform deployments in another repo once I'm more comfortable with what I'm doing.

## 1. basicWebServer.yaml

A Minimal deployment that creates a web server.... no HTTPS at this stage.


## 2. multiAzRDSNetworkSetup.yaml

Create the network stack for a multi-AZ RDS instance.

This creates 4 subnets; 2 public, 2 private and creates an private and public RDS subnetgroup.

It also creates a NAT gateway in the private subnetgroup, so I can place an EC2 instance for testing.
