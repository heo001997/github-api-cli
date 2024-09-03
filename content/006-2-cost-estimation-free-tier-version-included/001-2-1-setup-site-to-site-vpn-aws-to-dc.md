# 1. Setup Site-to-Site VPN - AWS to DC


Fill out the form as follows, with explanations:

1. **Static IP Prefixes:** You will need to fill in two CIDRs. The first is our **VPC - DC (192.168.0.0/16)**, and the second is **VPC - AWS (10.10.0.0/16)**.
2. **Local IPv4 Network CIDR:** Fill in our **VPC - DC** CIDR **(192.168.0.0/16)**.
3. **Remote IPv4 Network CIDR:** Fill in our **VPC - AWS** CIDR **(10.10.0.0/16)**.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9d504ed3-e661-48c3-bdad-49e63cd32849/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=14995172c48439f6d87579d6d212c68599de2603801a462e0545b77a333b6bcd&X-Amz-SignedHeaders=host&x-id=GetObject)


That’s everything, click "Create" You should see the new VPN connection from **AWS to DC**. We will move on to the next step while waiting for this VPN to be ready.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/a1e2e5d9-c7f5-4910-9e33-66561c005baf/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=6b3a465a3b02832641f79bdc0f3d0a6868c532188dfe851da9ae4c4543d3bb20&X-Amz-SignedHeaders=host&x-id=GetObject)

