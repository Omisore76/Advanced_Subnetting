# Advanced_Subnetting

Tasks

Dotun, the network engineer, was given the subnet 192.168.0/24 and asked to subnet it into four subnets. He was also asked to assign each subnet to a different site. 
He must assign them as follow:

Subnet 1 for site 1

Subnet 2 for the link between site 1 router and the internet router

Subnet 3 for site 2

Subnet 4 for the link between site 2 router and the internet router.

Next, he must configure the DHCP servers with the third last IP address in each subnet. Plus, the DHCP servers must allocate IP addresses to the clients in each site.
He must then proceed to configure the switches with the second last IP address in each subnet. 

As for the routers, they must be configured as per the instructions in the diagram. Finally, he must verify that the PCs can access cisco.com and facebook.com using their browsers.

Solution

Dotun was excited to begin work on the project. He calculated the four subnets needed, which are:

192.168.1.0/26

192.168.1.64/26

192.168.1.128/26

192.168.1.192/26

He then continued to calculate the first, third to the last, second to the last, and the last IP addresses for each of the subnet.

Subnet 1 – 192.168.1.0/26

First host = 192.168.1.1

Third to the last host = 192.168.1.60

Second to the last host = 192.168.1.61

Last host = 192.168.1.62      


Subnet 2 - 192.168.1.64/26

First host = 192.168.1.65

Third to the last host = 192.168.1.124

Second to the last host = 192.168.1.125

Last host = 192.168.1.126 


Subnet 3 - 192.168.1.128/26

First host = 192.168.1.129

Third to the last host = 192.168.1.188

Second to the last host = 192.168.1.189

Last host = 192.168.1.190    


Subnet 4 - 192.168.1.192/26

First host =   192.168.1.193

Third to the last host = 192.168.1.252

Second to the last host = 192.168.1.253

Last host =   192.168.1.254         

The calculated subnets and IP addresses were assigned as instructed.
Finally, he verified that the PCs in each subnet could reach both cisco.com and facebook.com





