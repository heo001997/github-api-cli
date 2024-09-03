
Double-check if it’s truly connected to **AWS - EC2 Private’s** Private IPv4.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/bc63c416-3600-4e66-8053-75229d7f0d4b/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T084459Z&X-Amz-Expires=3600&X-Amz-Signature=65545450a51871d8de5a724ba9cb9c1f7c11718317a6799fa806b588d94e56fd&X-Amz-SignedHeaders=host&x-id=GetObject)


```bash
ping 10.10.1.141 -c5
```


It’s ok now


```bash
[root@ip-192-168-1-206 ec2-user]# ping 10.10.1.141 -c5
PING 10.10.1.141 (10.10.1.141) 56(84) bytes of data.
64 bytes from 10.10.1.141: icmp_seq=1 ttl=254 time=1.86 ms
64 bytes from 10.10.1.141: icmp_seq=2 ttl=254 time=1.83 ms
64 bytes from 10.10.1.141: icmp_seq=3 ttl=254 time=1.53 ms
64 bytes from 10.10.1.141: icmp_seq=4 ttl=254 time=2.07 ms
64 bytes from 10.10.1.141: icmp_seq=5 ttl=254 time=1.67 ms

--- 10.10.1.141 ping statistics ---
5 packets transmitted, 5 received, 0% packet loss, time 4007ms
rtt min/avg/max/mdev = 1.532/1.796/2.079/0.193 ms
```


If we can ping, then Tunnel 1 in the VPN connection details must be Up. If the status is still Down for both tunnels, it’s likely because it takes some time to re-check the connection.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/7368c218-edee-4463-86ec-37f1251732cb/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240903%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240903T084459Z&X-Amz-Expires=3600&X-Amz-Signature=7e7c10238ef497c094350e2ee4442f594643b1bf702a01bd17d5e102b84a13d1&X-Amz-SignedHeaders=host&x-id=GetObject)


In this workshop, I’ll only use one tunnel, because with my current Static IP VPN connection strategy, it would cause **random asymmetric routing** if I use 2 tunnels in my VPN. You can still use 2 tunnels and avoid this issue by using a Dynamic IP (try it if you’re a curious cat).

