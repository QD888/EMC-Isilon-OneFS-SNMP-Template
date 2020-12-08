# EMC-Isilon-OneFS-SNMP-Template
copy from https://share.zabbix.com/storage-devices/emc/emc-isilon-onefs-snmp-template

EMC Isilon OneFS SNMP Template
This EMC Isilon OneFS template was built from scratch by myself from the latest Isilon MIB's.

!NOTE! SOME ISILONS DO NOT DO WELL WITH BULK SNMP REQUESTS!!!!

If you notice flapping supported items, make sure bulk requests is off on your hosts.

It contains several additional features beyond basics, including drive, sensor, and license discovery. 2 different templates (One for your CLUSTER VIP, The other to monitor individual NODES).

It monitors basic network, drive, IFS usage, bandwidth, cluster / node / drive status, etc.

UPDATE v4: Fixed Temp discovery syntax problem

UPDATE v3: Fixed unixtime unit in licensing expiration item.

UPDATE v2: Fixed discovery item for disk size OID incorrect.

 

This is version 1.1 so it may have some inconsistencies, but I'm pretty good at uploading any fixes as I find them. You can see this from my other templates on this site which are popular.

Type          Template
Min Zabbix version  3.2.x
Features      SNMP Agent
Created       2016-12-08
Modified      2016-12-09 01:38:00
Version 3.2   4 version, '2016-12-09 00:54' modified
Owner         Tag Wolf
