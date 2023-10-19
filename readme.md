![Vut fit logo](doc/vut_fit_logo.png)
# IPK packet sniffer
Easy utility in CPP for sniffing packets.
All usefull information are in manual.pdf.

Usage: ./ipk-sniffer [-i rozhraní | --interface rozhraní] {-p ­­port} {[--tcp|-t] [--udp|-u] [--arp] [--icmp] } {-n num}

For this utility was used pcap library.

List of files:
ipk-sniffer.cpp - Main source code
ipk-sniffer.hpp - Header file with definitions
makefile        - its used for build utility
manual.pdf      - detail info about usage and implementation
readme.md       - this file


# Example of sniffing ICMP packet

![Vut fit logo](doc/Testing/any/sniffer-any-icmp.png)

![Vut fit logo](doc/Testing/any/wireshark-any-icmp.png)