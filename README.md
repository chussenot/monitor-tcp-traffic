
Monitor TCP Traffic on specific port
====================================

TCP Listener
```
 sudo ncat -lp 80
```

Monitoring
```
sudo tcpdump -i any port 80
```

HTTP request on TCP 80
```
curl 0.0.0.0
```

Scan the open port
```
sudo nmap -sS -O -p 0-80 127.0.0.1
```


