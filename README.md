- 👋 Hi, I’m Tim Matheis
- 👀 I’m currently working in the Networking Segment
- 🌱 I’m currently learning Debian
- 📫 How to reach me: mail@timmatheis.de


# My Homelab
## Router
Nothing crazy just a normal Speedport Smart 3

It is being DHCP-Server, DNS-Server, Access Point and Switch on my Network

avg. Upstream-Bandwith: 257.69Mbit/s

Network: 192.168.2.0/24

DHCP-Range: 192.168.2.101 - 192.168.2.230

DHCP-Leasetime: 1 day

DNS-Upstreamserver: 8.8.8.8


## Switch
It's a 24 RJ-45 1G non-PoE unmanaged Switch.

That means there are no VLANs in my Network, but there surely will be in further future.

## Raspberry Pi 5
Architecture: ARM

CPU: Broadcom BCM2712 quad-core Cortex A76 @ 2.4GHz

microSD-Storage: 64GB

RAM: 4GB

OS: Raspberry Pi OS 64-bit


### Services running on my Pi
1. Docker-ce
2. Docker-compose
3. Portainer
4. Pihole
5. heimdall
6. Homeassistant Supervised
7. Open vpn #not final
8. many many Cloudflared-container
9. Speedtesttracker

All of my services are published to the internet via the above mentioned Cloudflared Tunnels.
Those are able to expose services without opening any ports nor having to deal with ddos-protection or firewalling because Cloudflare is the firewall in that case.
Also the Cloudfared Tunnels are secured with ther own OAuth-Authentication using the integrated service.

## Synology DS218+ (NAS)
My NAS is a Synology DS218+ running in RAID 1 with 2x2TB HDDs
To reach the NAS I can either use the DDNS entry domain or use a dedicated cloudlfared tunnel.
Using the cloudflared tunnel my Raspberry Pi is communicating over the HTTPS-Port (5001).
It's secured with username:password aswell as 2FA.



<!---
HuckleberryLovesYou/HuckleberryLovesYou is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
