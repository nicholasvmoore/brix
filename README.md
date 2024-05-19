# Build & Maintain the primary host at the Pensacola house

## Networking

### Internet Connection

| Provider | WAN Technology | Download (mbps) | Upload (mbps) |
| --- | --- | ---| ---- |
| AT&T | VDSL2 | 100 | 20 |

### Core Networking

Router: TP-Link ER605 Router
Switch: TP-Link TL-SG2008P
APs: [EAP245, EAP235-Wall]

### Subnet overview

| CIDR | Subnet | VLAN | DHCP Pool | Purpose |
| --- | --- | --- | --- | --- |
| 192.168.16.0 | /21 | | | Pensacola Supernet |
| 192.168.16.0 | /23 | 1 | 192.168.16.11 - 192.168.17.254 | Management & Routing DHCP |
| 192.168.18.0 | /23 | 10 | 192.168.18.10 - 192.168.19.254 | Clients DHCP |

## 