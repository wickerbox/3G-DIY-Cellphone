cellphone3g
===========

Hardware for a 3G cellphone based on GSM/GPRS Arduino shield and damellis' DIY Cellphone.

[David A Mellis' DIY Cellphone 2G 'Cellphone Module'](http://web.media.mit.edu/~mellis/gsm/)

That project uses the 2G Quectel M10 Module which is pin compatible with the 3G Quectel UC15 Module. 

[Quectel GSM/GPRS M10](http://www.quectel.com/product/prodetail.aspx?id=14)

[Quectel UMTS/HSDPA UC15](http://www.quectel.com/product/prodetail.aspx?id=64)

[Quectel M10 and UC15 Design Compatibility](http://top-electronics.com/news/26/quectel-uc15-and-m10-design-compatibility.html)

**Differences**

1. Slightly different 3.3V-4.3V (UC15) vs 3.3V-4.6V (M10). Using a 3.7V battery is fine. MCP73831 recharges the 3.7V battery from the USB ... if the unit is powered off USB, it's at 4.2V which is on the high end. which is a little too close for comfort so I'd want to replace it with a USIM is the same. 

1. Frequency bands are slightly different but not much.

1. Pinout from controller will have to change. 

**Vocabulary**

GSM - Global System for Mobile Communications, 2G  
GPRS - General Packet Radio Services, packet data service on 2G and 3G  
UMTS - Universal Mobile Telecommunications System, 3G  
HSDPA - High-Speed Downlink Packet Access, allows higher speeds 3G speeds

**Reference**

"GSM (Global System for Mobile Communications, originally Groupe Spécial Mobile), is a standard developed by the European Telecommunications Standards Institute (ETSI) to describe protocols for second generation (2G) digital cellular networks used by mobile phones." [Wikipedia](http://en.wikipedia.org/wiki/GSM)

"General packet radio service (GPRS) is a packet oriented mobile data service on the 2G and 3G cellular communication system's global system for mobile communications (GSM)." [Wikipedia](http://en.wikipedia.org/wiki/General_Packet_Radio_Service)

"UMTS specifies a complete network system, which includes the radio access network (UMTS Terrestrial Radio Access Network, or UTRAN), the core network (Mobile Application Part, or MAP) and the authentication of users via SIM (subscriber identity module) cards." [Wikipedia](http://en.wikipedia.org/wiki/Universal_Mobile_Telecommunications_System)

"High-Speed Downlink Packet Access (HSDPA) is an enhanced 3G (third-generation) mobile-telephony communications protocol in the High-Speed Packet Access (HSPA) family, also dubbed 3.5G, 3G+, or Turbo 3G, which allows networks based on Universal Mobile Telecommunications System (UMTS) to have higher data-transfer speeds and capacity." [Wikipedia](en.wikipedia.org/wiki/High-Speed_Downlink_Packet_Access)
