# IP-Ping with Python
Ping an ip or specific range of IP using loop.

### Requirements
```
pip install -r requirements.txt
```

You can set the ip range by changing the values
```
for i in range(1, 256):
    ip = '192.168.0.%s' % str(i)
```

Call the function `ping(ip)` and you will get the result.

### Sample Output
```
192.168.0.1
PING 192.168.0.1 (192.168.0.1): 56 data bytes
64 bytes from 192.168.0.1: icmp_seq=0 ttl=64 time=1.233 ms

--- 192.168.0.1 ping statistics ---
1 packets transmitted, 1 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 1.233/1.233/1.233/0.000 ms
```