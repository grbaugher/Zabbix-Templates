# Zabbix
Zabbix templates and tools

This is an assortment of tools and templates I have created to manage various devices within the company network that I work for.  These tools and templates were created with help from many various websites, templates, and MIB documentation that were researched while seeking ways to poll information from our hardware.  My original inspirations were from jjmartres' collection of Zabbix templates, and I have borrowed from his styling as I modified then adapted to newer devices.  I appreciate his help in creating the original templates that I used to get started, and I am contributing my own modifications onward in the hopes it helps others.

These templates should not cause any issues, but be aware that my testing is limited to only my own environement.  I make no specific claims that they won't damage your own equipment and you use these at your own risk.  I assume no liability as these are intended for educational and research purposes only.

Templates use macros, which you may need to research how to do these from Zabbix's documentation.  

{$SNMP_COMMUNITY} = your snmp community name

{$INTF_REGEXP} = your interface strings you wish to search on

These templates were created and exported from Zabbix 2.2.9, unless otherwise specified
