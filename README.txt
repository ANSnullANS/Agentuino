An updated version of the Agentuino (http://code.google.com/p/agentuino/; Copyright (C) 2010 Eric C. Gionet) SNMP library.

Based on the version by Petr Domorazek (https://github.com/1sw/Agentuino) and updated by Paco "ANSnullANS" Lechner to run on WiFiNINA based Arduinos.


Supported SNMP-Version: 1

Library supports WiFiUDP and EthernetUDP. To set which library to use, put one of the following #define-Blocks into your code:

WiFiNINA: "#define WIFI_ENABLED true"
Ethernet: "#define ETH_ENABLED true"
