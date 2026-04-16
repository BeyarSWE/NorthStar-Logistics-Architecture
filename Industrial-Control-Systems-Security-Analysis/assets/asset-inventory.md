# Asset Inventory
## OT-Network
| Subnet | IP Address | Purdue Level | Function in network | Device Name | Device Description | Model | Vendor | Operating System | OS Vendor |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Unknown | 192.168.1.10 | Level 1 | PLC | Turbine-PLC1 | Controller | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.2.10 | Level 1 | PLC | Turbine-PLC2 | Controller | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.1.20 | Level 1 | Controller | Pitch-Controller1 | Controls blade angle | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.2.20 | Level 1 | Controller | Pitch-Controller2 | Controls blade angle | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.1.30 | Level 1 | Controller | Yaw 01 | Controls turbine orientation | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.2.30 | Level 1 | Controller | Yaw 02 | Controls turbine orientation | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.1.40 | Level 1 | Sensor | CMS 01 | Condition monitoring | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.2.40 | Level 1 | Sensor | CMS 02 | Condition monitoring | Unknown | Unknown | Unknown | Unknown |
| Unmanaged | 192.168.4.6/192.168.1.1 | Level 1 | Switch | FL SWITCH 1005N | Turbine switch | Unknown | Unknown | Unknown | Unknown |
| Unmanaged |	192.168.4.7/192.168.2.1 |	Level 1	| Switch	| FL SWITCH 1005N	| Turbine switch |	Unknown	| Unknown	| Unknown	| Unknown |
| Unknown	| 192.168.4.11	| Level 2 or 3	| SCADA	| Unknown	| Central SCADA	|	Unknown	| Unknown	| Unknown	| Unknown |
| Unknown	| 192.168.4.22 |	Level 2 or 3	| Historian	| WINSRV16-Historian-1	| Historian server	| Unknown	| Unknown	| Windows Server	| Microsoft
| Unknown	| 192.168.4.x	| Level 1	| Controller	| WIN7-HMI-1	| HMI	| Unknown	| Unknown	| Windows 7	| Microsoft
| N/A	| RS232	| Level 0	| Sensor | Vibration 01	| Measurement Turbine 01	| Unknown	| Unknown	| Unknown	| Unknown
| N/A	| RS232	| Level 0	| Sensor	| Temp 01	| Measurement Turbine 01	| Unknown	| Unknown	| Unknown	| Unknown
| Unknown	| 192.168.4.2 |	Level 2 or 3	| Switch	| Hirschmann-SW	| Rugged L3 Switch	| Unknown	| Hirschmann	| HiOS/HiEOS	| Hirschmann
| Unknown | 192.168.4.1	| Level 4 or 5	| Router	| CISCO RT1	| Network router	| Unknown	| Cisco	| Unknown	| Cisco
| Unknown	| 192.168.4.3	| Level 2 or 3	| Firewall	| OT Firewall	| Fortigate 60E	| Fortigate 60E |	Fortinet	| FortiOS	| Fortinet
 

## IT-Network
| Subnet | IP Address | Purdue Level | Function in network | Device Name | Device Description | Model | Vendor | Operating System | OS Vendor |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Unknown | 10.0.0.10 | Level 4 or 5 | Other Server | FileSrv 01 | Central file storage | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.0.20 | Level 4 or 5 | Other Server | ERPSrv 01 | Enterprise Resource Planning | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.0.30 | Level 4 or 5 | Other Server | DB 01 | Enterprise database | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.0.40 | Level 4 or 5 | Other Server | AD 01 | Active Directory | Unknown | Unknown | Unknown | Unknown |
| Unknown | DHCP | Level 4 or 5 | Field Laptop/Workstation | Lenovo Thinkcenter | Enterprise Workstation | Thinkcenter | Lenovo | Unknown | Unknown |
| Unknown | DHCP | Level 4 or 5 | Field Laptop/Workstation | ENG-WS-1 | Engineering Workstation (RDS access) | Unknown | Dell | Unknown | Unknown |
| Unknown | 10.0.0.50 | Level 4 or 5 | Other | HP-Print1 | Network printer | Unknown | HP | Unknown | Unknown |
| Unknown | 10.0.0.2 | Level 4 or 5 | Switch | IT Switch | Data Center Switch | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.0.1 | Level 4 or 5 | Firewall | IT Firewall | 60F LAN1 | FortiGate 60F | Fortinet | FortiOS | Fortinet |
| Unknown | 10.0.0.100 | Level 4 or 5 | Firewall | IT Firewall | 60F LAN2 | FortiGate 60F | Fortinet | FortiOS | Fortinet |


## DMZ
| Subnet | IP Address | Purdue Level | Function in network | Device Name | Device Description | Model | Vendor | Operating System | OS Vendor |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Unknown | 172.16.0.10 | Level 3.5 | Other Server | OPCBuf 01 | OPC Buffer | Unknown | Unknown | Unknown | Unknown |
| Unknown | 172.16.0.20 | Level 3.5 | Other Server | RDSSrv 01 | Remote Desktop Server | Unknown | Unknown | Unknown | Unknown |
| Unknown | 172.16.0.40 | Level 3.5 | Other Server | DNS 01 | DNS Server | Unknown | Unknown | Unknown | Unknown |
| Unknown | 172.16.0.1 | Level 3.5 | Firewall | OT-FW-1 | 60E LAN2 | Unknown | Unknown | Unknown | Unknown |

## Security and Infrastructure
| Subnet | IP Address | Purdue Level | Function in network | Device Name | Device Description | Model | Vendor | Operating System | OS Vendor |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Unknown | 10.0.0.100 | Level 4-5 | Firewall | OT-FW-1 | 60E WAN1 | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.0.12 | Level 4-5 | Other | VPN 01 | Remote access for IT | Unknown | Unknown | Unknown | Unknown |
| Unknown | 192.168.6.10 | Level 2-3 | Other | Camera 01 | Site surveillance | Unknown | Unknown | Unknown | Unknown |
| Unknown | 10.0.7.2-100 | Level 4-5 | Other | Office DHCP | Client Range | Unknown | Unknown | Unknown | Unknown |
