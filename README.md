# Network Security Research
## Objectives
This activity was done with the intent to learn about nmap and other definition like Log4Shell, Netgear R6700v3 and other model. 

### Different Tasks and Definition 

| Codes                                         | Definitions                                                    |
|-----------------------------------------------|----------------------------------------------------------------|
|nmap -sV -O 192.168.18.1                       | -sV (for Service detection) and nmap -O (for OS detection)
|nmap -p [Port number] [target IP]              | Scanning using Sepcific Port Number and IP                     |
|nmap -p ‘*’ [target]                           | Scan all the ports avaliable                                   |

| Services    | Different Attacks Applicable                                                                |
|-------------|---------------------------------------------------------------------------------------------|
| http        | SQL injection, cross-site scripting broken authentications, Log4Shell HTTP Header Injection.|
| ssl/http    | MITM (Man-In-The-Middle) attacks, phishing scams.                                           |
| UPnP        | Alarming Eternal Silence UPnPkali, Netgear R6700v3 Unauthenticated LAN Admin Password Reset |

| Modules                                 | Definition                                                                |
|-----------------------------------------|---------------------------------------------------------------------------|
| Log4Shell HTTP Header Injection Module  | allows the usage of configuration, log messages and parameters, it does not protect against the attacker who is in control of the LDAP and other JNDI related endpoints. This module exploits an HTTP end point and inject a formal message with Log4Shell, which will trigger an LDAP connection to Metasploit and load a payload. |
| Netgear R6700v3 Unauthenticated LAN Admin Password Reset Module | a buffer overflow vulnerability in the UPNP daemon. The attack can log in to telnet server using the new password (after rest) and enter as root user. |

Sample: 
![Screenshot 2024-04-17 132712](https://github.com/JolynNgSC/Network_Security/assets/164031233/b9b80985-b84f-4ed5-abc6-ed78f6d1e77a)

