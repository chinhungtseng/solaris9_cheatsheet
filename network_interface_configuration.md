# Network interface configuration

## Use ifconfig command (not permanent)

Find network card name
```
# kstat -c net | grep net
```

Add ip-address and net-mask on bge0
```
# ifconfig bge0 plumb up
# ifconfig bge0 192.168.1.200 netmask 255.255.255.0
```

Add default router
```
# route add default 192.168.1.2
```

List network status and routing table
```
# ifconfig -a
# netstat -nr
```
