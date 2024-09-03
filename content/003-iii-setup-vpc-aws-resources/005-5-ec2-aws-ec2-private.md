+++
title = "5. EC2 - AWS - EC2 Private"
weight = 5
+++


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b5018226-36ec-4e95-a65c-6cf2a10e77aa/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=0b70b5bb0650f9348c00f89838004eeac1f648de03b699ae2b3e2277814095e0&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into **AWS - EC2 - Private** if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b91c40ad-eb69-4175-8a44-2980d709c864/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=8843748f856be2520b2d954ae3068e08da67f37d8cd5ab4073bef625cf9d7396&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d8a694e6-9e80-4143-bf2f-de202544e9d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=814a8171002a49a939ac9fdd80a9ed334aeb94e70207eff95842a4a0b9bc176e&X-Amz-SignedHeaders=host&x-id=GetObject)


After creating the key pair, you can select it now.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/f0770b20-a220-4560-8b7a-5ac33d96de85/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=9f871ac6350c0dd63c2fd52baba40852806094672a097b234494bc4d70bf0da6&X-Amz-SignedHeaders=host&x-id=GetObject)


For network settings, we will edit them as follows:


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c595234b-dbdc-4f83-b684-4c350daca38e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=94f9dea4f13ef3d8756d3e8a1a74f1358441cb5e996b01bab8951dba3452ac0b&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/79b9cff1-0e52-4a72-87af-dae0b5516d0d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171243Z&X-Amz-Expires=3600&X-Amz-Signature=1e0f944c366883f9d653d6233f7308c37502270c41863d8a1461d7041ebf8b61&X-Amz-SignedHeaders=host&x-id=GetObject)


Now, we’re done setting up the VPC AWS resources!


