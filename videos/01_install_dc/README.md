# 01 - Installing the Domain Controller

1. Use `sconfig` to:
    - Change hostname
    - Change IP address to static
    - Chnage the DNS server to our own IP address


2. Install the Active Directory Windows Feature

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```