+++
title = "5. Internet Gateway - DC - IGW"
+++


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2dc2ede2-912f-4c54-983f-33230a1e25f6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=5e82255857c960f30b0dd77192d87620994933b6d0ce81ced5f7ef83251f5b44&X-Amz-SignedHeaders=host&x-id=GetObject)


Attach it to **VPC - DC**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/bc9962b3-3b6b-4146-95ec-fa20b3e0417e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=808ee6fd063f9dc30c3fed4ed1281f0cf9fedfe68b71f6e1b0695e64508d7acf&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9d52f744-bcd0-419e-aef7-9cf1383ae06d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=eb984e6f8eb6a0f41ddf38b20ef3054b30cf30323ddf3d8aae3e06fc3f6024b9&X-Amz-SignedHeaders=host&x-id=GetObject)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/df0364d1-faff-4346-a66f-bd7c3f361296/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=e413f796ffb864d88737c17f9f216264d6e556f2ba114260c1b094670595198d&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/8d516c8e-c307-4d41-8060-10080477035f/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=2c03fabf16442f3c8d0f5d424c5c7f3e6962c0275b1e5aa6048c5fc31e15330b&X-Amz-SignedHeaders=host&x-id=GetObject)


The route should look like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/950790c5-069b-4222-9591-a8819bd38aa7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=331b1e9dfd44b3be7cc7d6e24ead6946bc43f77069655b7e8e29dce46d2de8ea&X-Amz-SignedHeaders=host&x-id=GetObject)


