## Logical Design:
![Logical Design](https://scontent.fdad1-3.fna.fbcdn.net/v/t1.15752-9/275589115_225623996417435_6035879981291989121_n.png?_nc_cat=111&ccb=1-5&_nc_sid=ae9488&_nc_ohc=S0WA6y-AVPAAX9Newnr&_nc_ht=scontent.fdad1-3.fna&oh=03_AVJ--dN4jxKIYFCwYpY9fEFpWPttdGXKtUd4UkfI6zfduw&oe=625A1915)
## Physical Design:
![Physical Design](https://scontent.fdad1-1.fna.fbcdn.net/v/t1.15752-9/275644917_1392689727835546_8608105130110296279_n.png?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_ohc=CBe3cfvd0ZsAX_wIwy_&_nc_ht=scontent.fdad1-1.fna&oh=03_AVIPv5xgTU3vG3Cl5xEsheC7HriZUZNTmwO_-8cQiIyVQQ&oe=625C61DA)

## Table design:
### Configuration server:

| Name        | IP address | Default-gateway|
| ------------- |-------------|-----|
DHCP server | 192.168.2.2 | 10.1.1.1
Web server | 192.168.2.6 | 10.1.1.1
DNS server | 192.168.2.5 | 10.1.1.1
TFTP server | 192.168.2.7 | 10.1.1.1
Mail server | 192.168.2.4 | 10.1.1.1

### Configuration Table:

Name | Device | VLAN | Interface | IP address | Subnet mask |
-----|--------|------|-----------|------------|-------------|
IT-labs1 | PC1 -> PC25 |9| |Fa0/0| 192.168.9.1| 255.255.255.0|
IB-labs2 | PC26 -> PC50 |10| Fa0/0| 192.169.10.1| 255.255.255.0|
Teacher |PC51-PC64 |2| Fa0/0| 192.168.2.1| 255.255.255.0|
Marketing| PC66 -> PC71 | 4| Fa0/0| 192.168.4.1| 255.255.255.0|
Admin |PC78 -> PC80 |7| Fa0/0| 192.168.7.1 |255.255.255.0||
Manager |PC81 -> PC83 |6| Fa0/0| 192.168.6.1 |255.255.255.0|
Academic |PC84 -> PC85 |8| Fa0/0| 192.168.8.1 |255.255.255.0|
Staff |PC72-> PC77 |5| Fa0/0| 192.168.5.1 |255.255.255.0|
