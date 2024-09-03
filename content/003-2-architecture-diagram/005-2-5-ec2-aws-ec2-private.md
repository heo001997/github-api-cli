# 5. EC2 - AWS - EC2 Private


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b5018226-36ec-4e95-a65c-6cf2a10e77aa/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=92f3e58b50679713b2957f118a4c178bc859e0613eb9403ec1f34b5f3c37c90b&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into **AWS - EC2 - Private** if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b91c40ad-eb69-4175-8a44-2980d709c864/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=d063b9de7ab4a697ef77252e2b549a0043f923d7ed2c130a71b1241189a970aa&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d8a694e6-9e80-4143-bf2f-de202544e9d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=44e42b4e172106a175f1f4133497a9093e7eed35c1e27565e38add653ab356da&X-Amz-SignedHeaders=host&x-id=GetObject)


After creating the key pair, you can select it now.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/f0770b20-a220-4560-8b7a-5ac33d96de85/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=cade6fe60a6bf6d16505cede9b21843b34c0127a789f3da470733ee1bf7edeb0&X-Amz-SignedHeaders=host&x-id=GetObject)


For network settings, we will edit them as follows:


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c595234b-dbdc-4f83-b684-4c350daca38e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=87e83c764f8ca57dc0575808d73b3b530dd8d17aa90d0dac4d71240a798d3b31&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/79b9cff1-0e52-4a72-87af-dae0b5516d0d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091835Z&X-Amz-Expires=3600&X-Amz-Signature=9eeedc3afe9a3820a0b49b2bbdb21b886791ebbf58287abe1a4560206a51f4e6&X-Amz-SignedHeaders=host&x-id=GetObject)


Now, we’re done setting up the VPC AWS resources!

