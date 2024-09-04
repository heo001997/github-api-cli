+++
title = "5. Internet Gateway - DC - IGW"
weight = 5
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-825337-image.png)


Attach it to **VPC - DC**


![image.png](/images/004-iv-setup-vpc-dc-resources/18-556965-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-930641-image.png)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](/images/004-iv-setup-vpc-dc-resources/18-713425-image.png)


![image.png](/images/004-iv-setup-vpc-dc-resources/18-610861-image.png)


The route should look like this


![image.png](/images/004-iv-setup-vpc-dc-resources/18-630895-image.png)


