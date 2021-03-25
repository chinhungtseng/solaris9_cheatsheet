# ALOM NET MGT Port IP Address Setting on SUN v240

SC mode:
```
sc> setsc if_networkd true
sc> setsc netsc_dhcp false
sc> setsc netsc_ipaddr 192.168.1.230
sc> setsc netsc_ipnetmask 255.255.255.0
sc> setsc netsc_ipgateway 192.168.1.2
sc> resetsc -y
```

Show SC network configuration
```
sc> shownetwork
```

System:
```
# scadm set if_network true
# scadm set netsc_dhcp flase
# scadm set netsc_ipaddr 192.168.1.230
# scadm set netsc_ipnetmask 255.255.255.0
# scadm set netsc_ipgateway 192.168.1.254
```

```
# scadm shownetwork
```
