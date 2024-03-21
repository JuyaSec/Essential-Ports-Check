# List-of-important-ports
List of important ports that should be tested on each target

# LIST PORT

```bash
22 - SSH 
23 - Telnet
25 - SMTP
21 - FTP
53 - DNS 
80 - HTTP 
110 - POP3 
143 - IMAP 
443 - HTTPS 
445 - SMB
139 - NetBIOS 
389 - LDAP
587 - SMTP 
993 - IMAP over SSL
995 - POP3 over SSL
1433 - MS SQL Server
3306 - MySQL
3389 - RDP
1194 - OpenVPN
1723 - PPTP
4500 - IPsec NAT Traversal
5432 - PostgreSQL
5900 - VNC 
53 - DNS 
123 - NTP 
161,162 - SNMP 
1521 - Oracle database 
27017,27019 - MongoDB 
5601 - Kibana
9200,9300 - Elastic Search
8000,8089,9997 - Splunk
10050,10051 - Zabbix
3000 - grafana
23560 - PRTG Monitoring

# Nmap PortScan
With the NAMP tool, we can test the following command to scan important protocols on a target

#Nmap Command
nmap -vv -sV -p 22,23,25,21,53,80,110,143,443,445,139,389,587,993,995,1433,3306,3389,1194,1723,4500,5432,5900,53,123,161,162,1521,27017,27019,5601,9200,9300,8000,8089,9997,10050,10051,3000,23560 targetip
