+++
title = "2. Architecture Diagram"
weight = 2
+++


Take a first look at what we’ll build:


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/57a35495-f431-43ff-a13b-c130f4476d5e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240904%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240904T055726Z&X-Amz-Expires=3600&X-Amz-Signature=d31238adadaa1fa929c1e20fe1ffcd69b3b3d1976ba5fcc0e35f6792ff7374cb&X-Amz-SignedHeaders=host&x-id=GetObject)


Diagram convention:


```bash
Example:
EC2 - AWS - EC2 Private
Private IP - 10.10.1.x

Explanation:
- The naming convention is always: <Service> - <Service Name>
Sample: EC2 - AWS - EC2 Private => <EC2> - <AWS - EC2 Private>

- Other lines represent properties:
Sample: Private IP - 10.10.1.x => <Properties>
```


That's everything. let's get it started.


