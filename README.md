## AWS End-To-End Project

Steps:
1) created a vpc
2) created subnets
3) created route-tables, internet-gateway
4) configured rt,igw and subnets
5) created an ec2 instance
6) installed apapche2 webserver
7) cloned my app from github and moved /var/www/html folder(delete default index.html before moving)
8) purchased a domain
9) cteate hosted-zone with the domain name
10) copied the ns records into the domain provider
11) create A record in route53 hostedzone
12) browse application with the domain name

Cammands:
1. sudo su
   
3. apt update

5. apt install apache2
   
7. systemctl enable apache2
