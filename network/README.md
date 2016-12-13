# Euclid network #

## Internet uplink ##

Comcast Business 

Bandwidth limit is 150 Mb/s up and 20 Mb/s down.

## Modem ##
    Models: ARRIS SURFboard SB6183 DOCSIS 3.0 Cable Modem
    Location: 3rd floor network closet

## Main router ##

    External IP:       DHCP
    Internal IP:       10.20.36.1
    Netmask:           255.255.255.252 (/22)
    DHCP client range: 10.20.36.100 - 10.20.39.190 (859 addresses)
    Location: 3rd floor network closet

Our current router is TP-Link TL-WR1043ND v2.1 running OpenWRT

## Servers ##

### server1 (Segate 5TB NAS Running NAS OS it contains two 2.5TB hard drives in RAID 0) ###
    
    Internal IP: 10.20.56.10
    Location: Network closet

## Printers ##

### printer1 (Brother MFC-9330CDW) ###

    Internal IP: 10.20.36.90
    Location:    Living-room
    Ethernet MAC: 30:05:5c:a8:c0:81
    Wi-Fi MAC: 44:1c:a8:52:40:03
    Location: Living room

## APs (Ubiquity UniFi UAP-AC-PRO) ##

* 1st floor Living Room, IP:, MAC:
* 1st floor Dining Hall, IP:, MAC:
* 2nd floor Room 4, IP:, MAC:
* 3rd floor Network closet, IP:, MAC:
* 3rd floor Room 16, IP:, MAC:

You can find exact locations on one of the versions of the floor plan in the eucnm google drive.

## Switches (If they have an IP then they are managed) ##

 * [] - Network Closet, IP:10.20.56.9, MAC:08:bd:43:71:24:50 (Netgear GS748T)
 * [] - Kitchen, MAC: (Netgear GS108E)
 * [] - Living room media center, IP:, MAC: (TP-Link TL-SG108E)
 * [] - Living room computer center, MAC: (Netgear GS105Ev2)
