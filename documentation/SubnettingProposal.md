# 🧮 Subnetting Proposal

| Subnet             | Network ID     | CIDR | Devices                             |
|--------------------|----------------|------|-------------------------------------|
| Workstations       | 172.16.10.0    | /24  | 91+ desktops/laptops                |
| Executive Offices  | 172.16.11.0    | /28  | Private office machines             |
| Servers            | 172.16.20.0    | /28  | Domain Controllers, File Server     |
| Printers           | 172.16.30.0    | /28  | Networked printing devices          |
| Wireless APs       | 172.16.40.0    | /28  | Wi-Fi 6 access points               |
| VoIP Phones        | 172.16.50.0    | /25  | VoIP (optional)                     |
| Guest Wi-Fi        | 172.16.60.0    | /25  | Internet-only guest network         |
| Testing Environment| 172.16.70.0    | /24  | Isolated test VLAN                  |
| Infrastructure     | 172.16.100.0   | /28  | Routers, Switches, Firewalls        |