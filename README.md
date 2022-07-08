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
![nasriin 1st july](https://user-images.githubusercontent.com/106605770/177987755-8f7ae004-42d8-4251-9cf2-50299f430329.jpg)
