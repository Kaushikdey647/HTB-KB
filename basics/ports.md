# PORTS and what they mean

| Port(s)    | Protocol                  | Description                                               |
|------------|---------------------------|-----------------------------------------------------------|
| 7          | TCP, UDP                  | Echo service                                              |
| 19         | TCP, UDP                  | Character Generator Protocol, has severe vulnerabilities  |
| 20         | TCP, SCTP                 | File Transfer Protocol data transfer                      |
| 21         | TCP, UDP, SCTP            | File Transfer Protocol command control                    |
| 22         | TCP, UDP, SCTP            | Secure Shell, secure logins, file transfers, port forwarding |
| 23         | TCP                       | Telnet protocol, for unencrypted text communications      |
| 25         | TCP                       | Simple Mail Transfer Protocol, for email routing          |
| 42         | TCP, UDP                  | WINS Replication, Microsoft Windows Internet Name Service |
| 43         | TCP, UDP                  | Whois service, provides domain-level information          |
| 49         | UDP; TCP on other ports   | TACACS, provides remote authentication                    |
| 53         | TCP, UDP                  | Domain Name System name resolver                          |
| 67, 68     | UDP                       | DHCP/BOOTP Server and Client                              |
| 69         | UDP                       | Trivial File Transfer Protocol                            |
| 70         | TCP                       | Gopher protocol                                           |
| 79         | TCP                       | Finger protocol                                           |
| 80         | TCP, UDP, SCTP            | Hypertext Transfer Protocol                               |
| 88         | TCP, UDP                  | Kerberos, network authentication system                   |
| 102        | TCP                       | Microsoft Exchange ISO-TSAP                               |
| 110        | TCP                       | Post Office Protocol, version 3                           |
| 113        | TCP                       | Identification Protocol                                   |
| 119        | TCP                       | Network News Transfer Protocol                            |
| 123        | UDP                       | Network Time Protocol                                     |
| 135        | TCP, UDP                  | Microsoft RPC EPMAP                                       |
| 137-139    | TCP, UDP                  | NetBIOS services                                          |
| 143        | TCP, UDP                  | Internet Message Access Protocol                          |
| 161        | UDP                       | SNMP-agents (unencrypted)                                 |
| 162        | UDP                       | SNMP-trap (unencrypted)                                   |
| 177        | UDP                       | X Display Manager Control Protocol                        |
| 179        | TCP                       | Border Gateway Protocol                                   |
| 194        | UDP                       | Internet Relay Chat                                       |
| 201        | TCP, UDP                  | AppleTalk Routing Maintenance, also used by malware       |
| 264        | TCP, UDP                  | Border Gateway Multicast Protocol                         |
| 318        | TCP, UDP                  | Time Stamp Protocol                                       |
| 381, 383   | TCP, UDP                  | HP Openview services                                      |
| 389        | TCP, UDP                  | Lightweight Directory Access Protocol                     |
| 411, 412   | TCP, UDP                  | Direct Connect services                                   |
| 427        | TCP                       | Service Location Protocol                                 |
| 443        | TCP, UDP, SCTP            | HTTPS (HTTP over SSL)                                     |
| 445        | TCP, UDP                  | Microsoft Directory Services                              |
| 464        | TCP, UDP                  | Kerberos for password settings                            |
| 465        | TCP                       | SMTP over TLS/SSL, SSM                                    |
| 497        | TCP, UDP                  | Dantz Retrospect backup software                          |
| 500        | UDP                       | IPSec / ISAKMP / IKE                                      |
| 512-515    | TCP                       | rexec, rlogin, syslog, LPD/LPR                            |
| 520        | UDP                       | Routing Information Protocol                              |
| 521        | UDP                       | RIPng (IPv6)                                              |
| 540        | TCP                       | Unix-to-Unix Copy Protocol                                |
| 548        | TCP                       | Apple Filing Protocol                                     |
| 554        | TCP, UDP                  | Real Time Streaming Protocol                              |
| 546, 547   | TCP, UDP                  | DHCPv6 client and server                                  |
| 560        | UDP                       | Remote Monitor                                            |
| 563        | TCP, UDP                  | NNTP over TLS/SSL                                         |
| 587        | TCP                       | Email message submission via SMTP                         |
| 591        | TCP                       | FileMaker Web Companion                                   |
| 593        | TCP, UDP                  | Microsoft DCOM                                            |
| 596        | TCP, UDP                  | SMSD                                                      |
| 631        | TCP                       | Internet Printing Protocol                                |
| 636        | TCP, UDP                  | LDAP over TLS/SSL                                         |
