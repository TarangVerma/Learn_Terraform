# Learn_Terraform

First run terraform init then copy this code to main.tf and you are good to go. 

1. created a VPC
2. Created a internet gateway
3. Created a custom route table
4. create a subnet
5. associate subnet with route table
6. created a security group to allow port 22, 80, 443
7. create a network interface with an ip in the subnet that was created in step 4
8. assign an elastic ip to the network interface created in step 7
9. create ubuntu server and install/enable apache2
