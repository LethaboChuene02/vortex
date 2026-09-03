# Deploying virtual machine clients on VirtualBox
To get started, we need to run client machines, that will be used in the organisation. Here's the full rundown:

## Client machine specifications

PC1
---
```
OS: Windows 10
RAM: 2GB
CPU core(s): 1
Storage: 20GB

Network: NAT
MAC Address: 08:00:27:EF:A8:2B
```

PC2
---
```
OS: Windows 10
RAM: 2GB
CPU core(s): 1
Storage: 20GB

Network: NAT
MAC Addres: 08:00:27:03:1A:6C
```

DC1
---
```
OS: Windows Server 2019 x64
RAM: 4GB
CPU core(s): 4
Storage: 40GB

Network: NAT
MAC Addres: 08:00:27:83:B7:68
```

pfSense (Router)
---
```
OS: freeBSD x64
RAM: 1GB
CPU core(s): 1
Storage: 10GB

Network: NAT
MAC Addres: 08:00:27:65:95:45
```
