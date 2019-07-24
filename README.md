
Juniper SRX Series
------------------

This template is for the monitoring of Juniper SRX series firewall hardware via SNMP.

It requires no additional files or components - just add the template and you're done.

Monitors the following items:

* Device availability (ping check)
* Alarm status (red / yellow)
* 5 minute load average
* CPU use (RE and PFE)
* Memory use (RE and PFE)
* Flow sessions (max, current and available)
* Device temperature
* Interfaces
  * Use interface names and description in triggers and graphs
	* Inbound discarded packets
	* Inbound errors
	* Inbound traffic
	* Outbound discarded packets
	* Outbound errors
	* Outbound traffic

Discovery will detect your ports and VLANs, and this will work in virtual chassis configurations.

Tested with the following hardware:

* SRX1400
* SRX240
* SRX210

All suggestions, edits, ideas and merge request are welcome!

A documentation of the monitoring capabilities can be reviewed by this [html-documentation](http://htmlpreview.github.io/?https://github.com/zabbix-tooling/zabbix-juniper-srx-firewall-template/blob/master/documentation/Custom_-_HW_-_Juniper_SRX.html).
