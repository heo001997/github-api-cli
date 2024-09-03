# 5. EC2 - AWS - EC2 Private


This form is quite long, so we will fill it out step by step.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b5018226-36ec-4e95-a65c-6cf2a10e77aa/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=30533c9e8acd2620e63e6ed2ec72dd863796b6df50968a51f08b04fb8e9a8f6b&X-Amz-SignedHeaders=host&x-id=GetObject)


Create a key pair to be able to SSH into **AWS - EC2 - Private** if you don’t already have one.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/b91c40ad-eb69-4175-8a44-2980d709c864/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=bc976f42846f0403ed06181ccd265c2272f3591ffbffd22e310dfa5c4876e0de&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d8a694e6-9e80-4143-bf2f-de202544e9d6/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=58fa9933c7a3710127215358dd5c66fe56ed8ba0674ef32d677d9678be8fd35f&X-Amz-SignedHeaders=host&x-id=GetObject)


After creating the key pair, you can select it now.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/f0770b20-a220-4560-8b7a-5ac33d96de85/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=b1895f124bf30d36c2f7ec24f462d0c40aa389621590541725775d0ec9b81fe3&X-Amz-SignedHeaders=host&x-id=GetObject)


For network settings, we will edit them as follows:


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c595234b-dbdc-4f83-b684-4c350daca38e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=f365021988aacf0d2c508020f15ad021240a600cf3adf3d45582d807bfbfb665&X-Amz-SignedHeaders=host&x-id=GetObject)


We can click "Launch Instance" now, leaving the other settings at their defaults is fine.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/79b9cff1-0e52-4a72-87af-dae0b5516d0d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T123812Z&X-Amz-Expires=3600&X-Amz-Signature=61ef163c7530fd09114448252f38df817f3e16e5c6489c44ae16308096b239af&X-Amz-SignedHeaders=host&x-id=GetObject)


Now, we’re done setting up the VPC AWS resources!

