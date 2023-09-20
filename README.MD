### VPC

This module is going to create 
* VPC
* IGW
* 2-public subnets
* 2-private subnets
* 2-database subnets


### INPUTs

* CIDR_block(required)  - user has to provide cidr block
* enable_dns_hostnames(optional) -user can provide enable_dns_hostnames, ***default is
true***
* enable_dns_support(optional) -user can provide enable_dns_support, ***default is true*** 
* commom_tags(optional) - user can provide commom_tags for all resources, default is empty
* vpc_tags(optional) - user can provide vpc_tags for vpc resources, default is empty
* igw_tags(optional) - user can provide internet_gateway_tags for all resources, default is empty
* public_subnet_cidr(required) - User must provide a list of 2-public subnet CIDR
* public_subnet_names(required) - User must provide a list of 2-public subnet names
* azs(required) -user must provide 2 az.
* private_subnet_cidr(required) - User must provide a list of 2-private subnet CIDR
* private_subnet_names(required) - User must provide a list of 2-private subnet names
* database_subnet_cidr(required) - User must provide a list of 2-database subnet CIDR
* database_subnet_names(required) - User must provide a list of 2-database subnet names
