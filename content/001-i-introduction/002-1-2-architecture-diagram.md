# 2. Architecture Diagram


Take a first look at what we’ll build:


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/57a35495-f431-43ff-a13b-c130f4476d5e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=47830d257844032b276ccf5f9c9d3bd9b4df94ed8cd51e4d782ebea26a41a81f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

