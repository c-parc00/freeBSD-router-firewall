This repository contains a minimal yet functional configuration for setting up
a FreeBSD-based router and firewall using WireGuard VPN. It includes example files
for pf.conf, rc.conf, and wg0.conf, designed to route all LAN traffic through a secure
VPN tunnel using WireGuard on a single-board computer (SBC). The setup enforces strict
outbound rules (kill switch), supports logging and NAT, and enhances privacy and security
across local and external networks. These configurations serve as a base template and
should be adjusted to match your network environment and VPN provider details.
