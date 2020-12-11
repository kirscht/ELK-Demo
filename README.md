# ELK-Demo
ELK Stack Demonstration

# Background & Purpose #

Describe the bckground and purpose for the ELK Demo.

# Scope #

This was deployed in an Axure Cloud environment.  This ELK stack monitored Filebeats and Metricbeats for a DVWA application.

# Implementation #

## VNet Creation ##

1. Create the VNet with network IP range 10.0.0.0/16
2. Create defatul subnet with IP range 10.0.0.0/24

## Establish Network Security Group ##

Immediately created a network security group that by default blocked all traffic to protect the environement as it was built.  The NSG is subquently modified to allow specific traffic as the infrastructure is built.

![Cloud Diagram](images/13-Elk-Stack-Project_Images_Finished-Cloud-Diagram.png)



