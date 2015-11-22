# IP List Status Check #

Test IP addresses online/offline status for example from /etc/hosts.

## Usage ##

```
[OPTIONS] testHostsLocalIP
```
## Usage examples ##

1. Set the IPs list source file 

```
IP_SOURCE='/etc/hosts' ip-list-status-check
```

2. Use RegExp to find target set of IPs

```
LOCAL_IP_PREFIX='^10\.10\.10\.' ip-list-status-check
```

3. Print help

```
ip-list-status-check --help|help
```
