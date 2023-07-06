# Deploy a 3-Tier Network VPC Architecture on AWS

## A manually configured and fully functional EXAMPLE 3-Tier cloud project deployed on AWS  implementing VPC networking resources and a Wordpress website


This project is an example that was built along with a tutorial series from AOSNOTE (www.aosnote.com) that teaches you how to build a classic 3-Tier application which includes the Web Tier, Application Tier, and Data Tier. The project also includes deploying these resources in a custom built VPC, from scratch, and deploying a Wordpress website as the final product.

This is a great project to solidify core AWS networking principles and getting some hands on experience with building n-tier applications which are used in the everyday world. In particular, this project shows how to do the following:


- Create a custom VPC from scratch, with public and private subnets in 2 availability zones
- Enchancing the architecture by adding NAT Gateways, Application Load Balances and Auto Scaling Groups
- Creating a MYSQL RDS database for the data tier
- Using Amazon EFS for the webservers to have access to shared files
- Using ECS Instances to host the website
- Using ALBs and ASGs to distribute the traffic as well as making the website highly scalable, fault tolerant and elastic
- Use Route 53 and AWS Certificate Manager to customize DNS route and secure the website

## Architectural Diagram:
![Alt text](reference-architecture.jpeg)