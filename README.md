# Wireshark Packet Capture Assignment

## Steps Performed

1. Installed Wireshark and Npcap on Windows.
2. Started packet capture on the active network interface.
3. Generated network traffic by browsing websites and using the `ping` command (produced ICMPv6 traffic).
4. Stopped the capture after approximately one minute.
5. Applied filters to view DNS, TCP, and ICMPv6 packets.
6. Identified three protocols and analyzed sample packet details.
7. Saved the capture in `.pcap` format.
8. Summarized the findings.

## Protocols Observed

- **DNS**: Domain name resolution
- **TCP**: Reliable data transport (e.g., HTTPS)
- **ICMPv6**: Diagnostic and network discovery protocol for IPv6

## Conclusion

The capture demonstrated how DNS, TCP, and ICMPv6 work together in typical network communication. ICMPv6 traffic confirmed an IPv6-enabled environment. Filters and protocol analysis in Wireshark provided insight into each protocol's role.
