**DOWNLOAD AND RUN**

_NOTE: iperf3 should be installed on the machine running this netspeed test_

```bash
apt update -y && apt install iperf3 -y
```

```bash 
curl -sSL https://github.com/a1010s/as.netspeed/raw/master/as.netspeed \
    -o /${PWD}/as.netspeed && chmod +x /${PWD}/as.netspeed && /${PWD}/as.netspeed
```
