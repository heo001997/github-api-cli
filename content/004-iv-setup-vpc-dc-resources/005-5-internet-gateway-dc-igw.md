# 5. Internet Gateway - DC - IGW


Create an Internet Gateway - DC - IGW to allow the DC - VPC to connect to the internet.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2dc2ede2-912f-4c54-983f-33230a1e25f6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=503ab0b027f79862484b000055821a529e1d315ba3e9e44811efc3122165e262&X-Amz-SignedHeaders=host&x-id=GetObject)


Attach it to **VPC - DC**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/bc9962b3-3b6b-4146-95ec-fa20b3e0417e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=9792c4ce01922405d09cc35022e869ee9e42d9d88cc97e6a40d77701f90a8788&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9d52f744-bcd0-419e-aef7-9cf1383ae06d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=02dfa496d9f48d69ae28809687795b06ce0dfd1940cc34ca5a7c049eeb0be477&X-Amz-SignedHeaders=host&x-id=GetObject)


Go back to the Route Table and edit it to accept the attached Internet Gateway.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/df0364d1-faff-4346-a66f-bd7c3f361296/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=592fbc935deb9e558985efc30a70c085e68cc9368607d8fcfa0b6509d177f610&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/8d516c8e-c307-4d41-8060-10080477035f/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=f7337c38806f05cff99e49fbba2a40fb0d13ad63a2d3377c8c290ca7475d2b9d&X-Amz-SignedHeaders=host&x-id=GetObject)


The route should look like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/950790c5-069b-4222-9591-a8819bd38aa7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=1708552bd85af3f42d823cb7016a8da57b0f2154e2b6ae20a364a37c50fab7b2&X-Amz-SignedHeaders=host&x-id=GetObject)

