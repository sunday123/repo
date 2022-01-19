$ netstat -u -n
Proto Recv-Q Send-Q Local Address           Foreign Address         State
udp        0      0 10.184.42.84:1701      123.45.6.78:1701        ESTABLISHED

$ ss -u -n
Recv-Q   Send-Q         Local Address:Port        Peer Address:Port   Process
0        0               10.184.42.84:1701         123.45.6.78:1701
