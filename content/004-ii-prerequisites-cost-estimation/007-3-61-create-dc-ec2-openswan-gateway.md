# 6.1 Create DC - EC2 Openswan Gateway


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/68379cf6-81c1-4bdd-b50c-97f882a75c39/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=5290dabe126422bfd5f14ddc3158930c2818636a2bf1aac6d36e4072adcdad9f&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into AWS - EC2 - Private if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3e8f3b13-abe4-476a-9702-c922dd617d30/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=d6e76d56f064d1426312e729202f0035195df9df7f133d9b33b0ed229b209dc7&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/2de80525-c893-42fc-babd-52d67f9add5b/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=948745280a1a89754a6870c81d71584482bdf37240144b206b1da47c2fd1f852&X-Amz-SignedHeaders=host&x-id=GetObject)


Select the newly created key pair.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/19e053e9-2c19-4295-9a2f-b7329afb1be8/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=300a745e36c2a2e54db5e4ea1931f77409b50282f321b0c2a9c3702b7e3d4f48&X-Amz-SignedHeaders=host&x-id=GetObject)


Edit Network like this


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3b2c7b64-dabe-43be-9af1-318c8bab86cc/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T091836Z&X-Amz-Expires=3600&X-Amz-Signature=9593a522077a33a81e9b5323f260981ef7118b8c65adc9e3b4db320e66b8a89c&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.

