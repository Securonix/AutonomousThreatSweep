
## IOCs

__spotterqueries__:

```text
rg_functionality="Next Generation Firewall" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="Firewall" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="Next Generation Firewall" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
rg_functionality="Web Application Firewall" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
rg_functionality="DNS / DHCP" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
rg_functionality="Firewall" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
rg_functionality="Web Proxy" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
rg_functionality="IDS / IPS / UTM / Threat Detection" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="Web Application Firewall" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="Web Proxy" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="DNS / DHCP" AND destinationhostname NOT NULL AND (destinationhostname CONTAINS "gmtagency.online" OR destinationhostname CONTAINS "aurorafoss.xyz" OR destinationhostname CONTAINS "d0cumentview.info" OR destinationhostname CONTAINS "cheapen.top")
rg_functionality="IDS / IPS / UTM / Threat Detection" AND ipaddress NOT NULL AND ipaddress IN ("118.89.135.58", "154.37.215.146", "91.245.255.99", "154.205.156.20", "27.124.42.235", "162.251.122.76")
```