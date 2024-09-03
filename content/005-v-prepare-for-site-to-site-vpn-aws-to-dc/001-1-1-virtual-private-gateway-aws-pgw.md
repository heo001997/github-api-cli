# 1. Virtual Private Gateway - AWS - PGW


Create a new Virtual Private Gateway - **AWS - PGW**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/330d9412-b5e2-41c2-86ba-66c9f4fa82d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=3ddd11c766b9631e645de8cd3fba790ea90f61a97c59031704bda5df2a948d08&X-Amz-SignedHeaders=host&x-id=GetObject)


Refresh the page if it says "Success" but shows nothing.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d3b02044-81aa-4990-af24-c7140f784c21/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=8f66c5c114d1b8076d37cc5b8c3f84ea1260d3d2291ea625b21ecdd7bea6de3c&X-Amz-SignedHeaders=host&x-id=GetObject)


Select and attach it to **VPC - AWS**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c4bb2bf1-9956-42f9-8d1a-6319b893192e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=74df1cf58e6e55f8de13bb0667d643a02a589c9b5f9cccb50e76e4daccbd6a33&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit the Route Table - **AWS - Private** so it can route traffic from this VGW.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e4acad0-4c0e-4f11-86b1-bd63fb30145d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=f1c514f14e4f0d08aefe0f549de8ed0c2468496c9bc08718a90504e6b6f0c983&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/424b778e-2ce9-487e-99e5-b179a35f49d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=88a98e67001114a9e4c5e164b59a8ab8d2ba32e02d46a4b8bd1a64fe3511e1a9&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/5c412718-7ea4-47b9-b63b-6b0c0f33ebc7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123814Z&X-Amz-Expires=3600&X-Amz-Signature=f17cbfc7a00781951f044bc00738f8a042f63b9b37db5b55a3582b6836f51529&X-Amz-SignedHeaders=host&x-id=GetObject)

