# godashrepo

Step 1:
Install mininet-wifi

Step 2:
Install GoDash
Step 3:
Install TcpDump

Step 4:
You need to define number of hosts, bandwidth, delay on link and packet loss in test.py. For example 
#delays used on link
delay = [10, 50, 100]
#bandwidth combinations
ban = [5,10,15]
#packetloss combinations
ploss = [0.0]
#number of hosts (Nodes) to run
host = [20,30,50]

Step 5:
Open Terminal and run command
sudo python3 test.py

It will take all combinations that defined for hosts, delays, bandwidth and packetloss.
