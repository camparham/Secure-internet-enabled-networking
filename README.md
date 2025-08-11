# Secure-internet-enabled-networking
I set up a secure networking environment that allows communication between resources and the internet.

## Concept
In this practice lab, you will:
 - Explore the components that comprise a virtual private cloud (VPC).
 - Configure a route table attached to a subnet within a VPC.
 - Configure a route table to direct internet-bound traffic to the internet gateway.
 - Configure inbound rules within a security group to control access.

## Challenge
A bank recently migrated their services to the cloud, but have noticed some connectivity issues with the Amazon EC2 instances and databases. The EC2 instances cannot connect to the internet, and the databases are unable to communicate with their instances. They need this fixed immediately without additional costs.

## Solution
Have you checked your virtual private cloud, or VPC, settings? In your route tables, you can check that an internet gateway is attached and that the VPC is set to allow outside traffic. Security group and route table modifications are applied immediately. Also, setting up an internet gateway for internet access can be done in minutes.
## Goal


Explore the components that comprise a virtual private cloud (VPC).
Configure a route table attached to a subnet within a VPC.
Configure an internet gateway inside a VPC.
Configure inbound rules within a security group to control access.
