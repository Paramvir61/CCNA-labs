# CCNA 200-301 Labs

Hands-on Cisco Packet Tracer labs completed while preparing for the **Cisco CCNA 200-301** exam, organized by exam domain. Each lab folder contains a README (objective, topology, addressing, configuration, verification, takeaways), a topology image, and the `.pkt` file.

**Author:** Paramvir · **Tool:** Cisco Packet Tracer · **Progress:** 16 of 49 labs documented

## 3.0 IP Connectivity

| # | Lab | Topics | Completed |
| --- | --- | --- | --- |
| 01 | [RIP Configuration](03-ip-connectivity/01-rip-configuration/) | RIPv1, hop count, 3-router chain, DHCP per LAN | 2026-06-28 |
| 02 | [EIGRP Configuration](03-ip-connectivity/02-eigrp-configuration/) | EIGRP AS 1, diamond topology, equal-cost load balancing, FD/RD | 2026-07-04 |
| 03 | [HSRP](03-ip-connectivity/03-hsrp/) | Virtual gateway, active/standby election, failover | 2026-08-06 |
| 04 | [OSPF Multi-Area](03-ip-connectivity/04-ospf-multi-area/) | Areas 0/1/2, ABRs, router IDs, neighbor states, DR/BDR | 2026-08-11 |

## 4.0 IP Services

| # | Lab | Topics | Completed |
| --- | --- | --- | --- |
| 01 | [DHCP on a Router](04-ip-services/01-dhcp-on-router/) | DHCP pool, excluded addresses | 2026-06-27 |
| 02 | [DHCP on a Server](04-ip-services/02-dhcp-on-server/) | Server-based DHCP, /28 subnetting | 2026-06-27 |
| 03 | [Static NAT](04-ip-services/03-static-nat/) | One-to-one NAT, inside/outside interfaces, default routes | 2026-07-08 |
| 04 | [Dynamic NAT](04-ip-services/04-dynamic-nat/) | NAT pool, ACL, dynamic translations, NAT statistics | 2026-07-09 |
| 05 | [PAT (NAT Overload)](04-ip-services/05-pat/) | Overload, port-based translation, NAT types compared | 2026-07-09 |
| 06 | [NTP & Syslog](04-ip-services/06-ntp-syslog/) | NTP client, central syslog, severity levels, timestamps | 2026-07-12 |

## 5.0 Security Fundamentals

| # | Lab | Topics | Completed |
| --- | --- | --- | --- |
| 01 | [Console, Enable & SSH Password Security](05-security-fundamentals/01-console-enable-ssh-passwords/) | Console/enable passwords, type 7 encryption, SSH, local users | 2026-06-27 |
| 02 | [SSH Remote Access on a Router](05-security-fundamentals/02-ssh-remote-access/) | RSA keys, local users, VTY SSH-only access | 2026-06-27 |
| 03 | [Telnet Remote Access on a Router](05-security-fundamentals/03-telnet-remote-access/) | VTY lines, login vs no login, Telnet vs SSH | 2026-06-28 |
| 04 | [Standard ACL](05-security-fundamentals/04-standard-acl/) | Numbered ACL, implicit deny, ACL placement | 2026-07-11 |
| 05 | [Extended ACL](05-security-fundamentals/05-extended-acl/) | Protocol/port filtering, DHCP blocked by implicit deny (troubleshooting) | 2026-07-12 |
| 06 | [DHCP Snooping](05-security-fundamentals/06-dhcp-snooping/) | Trusted/untrusted ports, rogue DHCP protection | 2026-08-11 |

## How to open the labs

Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) (free with a Cisco Networking Academy account), then open `lab.pkt` in any lab folder.
