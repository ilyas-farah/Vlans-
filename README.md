# Vlans-
CREATING VLAN
-------------

hostname SW-1
vlan 10
name HR
vlan 20
name IT
vlan 30
name Finance
exit
------

int range fa0/1-3
switchport mode access 
SW-1(config-if-range)#w
switchport access vlan 10
exit
int range fa0/4-6
switchport mode access 
switchport access vlan 20
exit
int range fa0/7-9
switchport mode access 
switchport access vlan 30
exit
![Uploading Screenshot 2022-06-19 084915.jpg…]()
