+++
title = "1. Virtual Private Gateway - AWS - PGW"
weight = 1
+++


Create a new Virtual Private Gateway - **AWS - PGW**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/330d9412-b5e2-41c2-86ba-66c9f4fa82d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=5e530661254e6955085b6743410b213fdec8a4490783eac5458b02c8d98ccfe2&X-Amz-SignedHeaders=host&x-id=GetObject)


Refresh the page if it says "Success" but shows nothing.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d3b02044-81aa-4990-af24-c7140f784c21/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=b1fe718befb5895a31f7fffa943a89071f5ec953d257cad7a3b03661591b1acd&X-Amz-SignedHeaders=host&x-id=GetObject)


Select and attach it to **VPC - AWS**


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c4bb2bf1-9956-42f9-8d1a-6319b893192e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=10d03c4ea7c2992d89dc22de0fab60d7983946dde135e4b1676dadb0e396feb2&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit the Route Table - **AWS - Private** so it can route traffic from this VGW.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e4acad0-4c0e-4f11-86b1-bd63fb30145d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=4585222f699f9a69f0be4e6323b12869e07adde2c6b1514121c57da6341a113f&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/424b778e-2ce9-487e-99e5-b179a35f49d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=3d7ed22031874610fb0216447823fcb42efbf82f6120fd611914bd1e8d9a60e5&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/5c412718-7ea4-47b9-b63b-6b0c0f33ebc7/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=149c8cacf9675890e7c73c5a613598fb328757a3f16a46663be1285c7a9115d5&X-Amz-SignedHeaders=host&x-id=GetObject)


