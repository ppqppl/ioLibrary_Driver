# ioLibrary Driver
The ioLibrary means “Internet Offload Library” for WIZnet chip. It includes drivers and application protocols.
The driver (ioLibrary) can be used for the application design of WIZnet TCP/IP chips as [W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start), W5300, W5200, W5100 [W5100S](http://wizwiki.net/wiki/doku.php?id=products:w5100s:start).

## ioLibrary
This driver provides the Berkeley Socket type APIs.
- Directory Structure
<!-- ioLibrary pic -->
![ioLibrary](http://wizwiki.net/wiki/lib/exe/fetch.php?media=products:w5500:iolibrary_bsd.jpg "ioLibrary")

- Ethernet : SOCKET APIs like BSD & WIZCHIP([W5500](http://wizwiki.net/wiki/doku.php?id=products:w5500:start) / W5300 /  W5200 / W5100 / [W5100S](http://wizwiki.net/wiki/doku.php?id=products:w5100s:start)) Driver
- Internet :
  - DHCP client
  - DNS client
  - FTP client
  - FTP server
  - SNMP agent/trap
  - SNTP client
  - TFTP client
  - HTTP server
  - MQTT Client
  - Others will be added.

## How to add an ioLibrary in project through github site.
  - Example, refer to https://www.youtube.com/watch?v=mt815RBGdsA
  - [ioLibrary Doxygen doument](https://github.com/Wiznet/ioLibrary_Driver/blob/master/Ethernet/Socket_APIs_V3.0.3.chm) : Refer to **TODO** in this document
    - Define what chip is used in **wizchip_conf.h**
    - Define what Host I/F mode is used in **wizchip_conf.h**


