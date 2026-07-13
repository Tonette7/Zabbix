# pfSense Zabbix Template

This is a pfSense active template for Zabbix, based on Standard Agent and a php script using pfSense functions library for monitoring specific data.

Tested with pfSense 2.7.x, Zabbix 7.0.

## What it does

**Template pfSense Active**
 
 - Network interface Discovery and Monitoring with User Assigned Names
 - Gateway Discovery and Monitoring (Gateway Status/RTT) 
 - OpenVPN Server Discovery and Monitoring (Server Status/Tunnel Status)
 - OpenVPN Clients Discovery and Monitoring (Client Status/Tunnel Status)
 - CARP Monitoring (Global CARP State)
 - Basic Service Discovery and Monitoring (Service Status)
 - pfSense Version/Update Available
 - Packages Update Available
 - Certificate Discovery and Monitoring
 
**Template pfSense Active: OpenVPN Server User Auth**

 - Discovery of OpenVPN Clients connected to OpenVPN Servers in user auth mode
 - Monitoring of Client Parameters (Bytes sent/received, Connection Time...) 

**Template pfSense Active: IPsec**

 - Discovery of IPsec Site-to-Site tunnels
 - Monitoring tunnel status (Phase 1 and Phase 2)
 
**Template pfSense Active: Speedtest**

 - Discovery of WAN Interfaces
 - Discover public IP Address/ISP Name of WAN Interfaces
 - Perform speed tests and collect metrics
