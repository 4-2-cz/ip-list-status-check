# IP List Status Check

Test IP addresses online/offline status for example from /etc/hosts.

## Usage

```
[OPTIONS] ip-list-status-check
```
## Usage examples

### Set the IPs list source file

```
IP_SOURCE='/etc/hosts' ip-list-status-check
```

### Use RegExp to find target set of IPs

```
LOCAL_IP_PREFIX='^10\.10\.10\.' ip-list-status-check
```

### Print help

```
ip-list-status-check --help|help
```
