# Which pings succeeded and which failed?
The pings on the same network for host1 succeeded
The pings from host1 to host2 failed because they are not on the same network

# The ARP table entries you observed
On host1 the ARP table entries are shown below:
(10.1.1.1) at 1a:2f:02:ff:00:01 [ether]  on eth1
(172.20.20.1) at 96:3a:2c:5d:7e:70 [ether]  on eth0

On srl1 the ARP table entries are shown below:
ethernet-1/1 | 0 |    10.1.1.2
ethernet-1/2 | 0 |    10.1.2.2
mgmt0        | 0 | 172.20.20.1

# Your explanation of why cross-subnet ping fails
A router is needed 
