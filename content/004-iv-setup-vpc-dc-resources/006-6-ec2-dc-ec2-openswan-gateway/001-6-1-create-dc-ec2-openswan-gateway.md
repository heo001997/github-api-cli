+++
title = "6.1 Create DC - EC2 Openswan Gateway"
weight = 1
+++


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/68379cf6-81c1-4bdd-b50c-97f882a75c39/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=c318205ceb6e4ec9a88143573e787049c5b7eaf21148d8f14ef54592c745e493&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into AWS - EC2 - Private if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e8f3b13-abe4-476a-9702-c922dd617d30/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=144b2bb39159b8ffbed14f4d7968e8cb7706406b4ea6af38cd5afd20c031631d&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2de80525-c893-42fc-babd-52d67f9add5b/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=ab51691e24328b0820adf0b8a9435a6b1bbaccf3c630bc43215cb7a3e51caf81&X-Amz-SignedHeaders=host&x-id=GetObject)


Select the newly created key pair.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/19e053e9-2c19-4295-9a2f-b7329afb1be8/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=547f6d89717e6ed204ba2b4a7a53bd5d82c366ba0ebe284f64c303ddc3c64967&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit Network like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3b2c7b64-dabe-43be-9af1-318c8bab86cc/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T171244Z&X-Amz-Expires=3600&X-Amz-Signature=7bd5bed624bef7e0c0ee4b8a37ee8437ad644c31fde1a29f9426740611ae277d&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


