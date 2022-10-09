# whichSystem.py

Tool that automates system recognition implemented on Python3 using ICMP packets' TTL to determine a system's OS (Windows or Linux).

## Usage
This script works as following:

```python
python3 whichSystem.py <destination>
```
For example:
```python
python3 whichSystem.py 192.168.1.1
>192.168.1.1 (ttl -> 127): Windows
```

## Credits

[s4vitar](https://github.com/s4vitar)
