# Packets, TCP/UDP, Ports
Frame = MAC address, local delivery (Layer 2)
Packet = IP address, internet delivery (Layer 3)
[Frame[Packet[data]]]

TCP = reliable, slow, SYN→SYN-ACK→ACK handshake
UDP = fast, unreliable, no handshake
TCP = banking/downloads | UDP = gaming/calls

Ports = which app gets the data
IP = finds laptop | Port = finds app on laptop
Common: 80=HTTP, 443=HTTPS, 22=SSH, 53=DNS
Ephemeral ports = temporary, reused after closing
Port forwarding = open hole in router for outside
                  access, every open port = risk
