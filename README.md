﻿# AWS-Three-Tier-Web-Architecture
 
![image](https://github.com/Muzamilraheman/AWS-Three-Tier-Web-Architecture/assets/98537723/cbbf64cc-942f-4095-bc75-f68a46e6ab4a)

## Step 1: Networking and Security
In this step I have built VPC networking components as well as security groups that will add a layer of protection around our EC2 instances, Aurora databases, and Elastic Load Balancers.

### components:
VPC,
Subnets,
Route Tables,
Internet Gateway,
NAT gateway,
Security Groups

## Step 2: Database Deployment
In this step I have deployed the database layer of the three tier architecture.

### components:
Deploy Database Layer,
Subnet Groups,
Multi-AZ Database

## Step 3: App Tier Instance Deployment
In this step I have created  an EC2 instance for our app layer and make all necessary software configurations so that the app can run. The app layer consists of a Node.js application that will run on port 4000. We will also configure our database with some data and tables.

### components:
Create App Tier Instance,
Configure Software Stack,
Configure Database Schema,
Test DB connectivity

## Step 4: Internal Load Balancing and Auto Scaling
In this step I have created an Amazon Machine Image (AMI) of the app tier instance, and use that to set up autoscaling with a load balancer in order to make this tier highly available.

### components:
Create an AMI of our App Tier,
Create a Launch Template,
Configure Autoscaling,
Deploy Internal Load Balancer

## Step 5: Web Tier Instance Deployment
In this step I have  deployed  an EC2 instance for the web tier and make all necessary software configurations for the NGINX web server and React.js website.

### components:
Update NGINX Configuration Files,
Create Web Tier Instance,
Configure Software Stack

## Step 6: External Load Balancer and Auto Scaling
In this step  I have created a Amazon Machine Image (AMI) of the web tier instance , and use that to set up autoscaling with an external facing load balancer in order to make this tier highly available.

### components:
Create an AMI of our Web Tier,
Create a Launch Template,
Configure Auto Scaling,
Deploy External Load Balancer



