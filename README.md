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

# Network
## Switch
Main-Switch:
  24 Port Base1000 non-PoE unmanaged rack-mounted Switch

Second PoE-Swtich:
  8 Port Base1000 PoE+ managed not rack-mounted Switch
# Server
## Raspberry Pi 5
Architecture: ARM

CPU: Broadcom BCM2712 quad-core Cortex A76 @ 2.4GHz

microSD-Storage: 64GB

RAM: 4GB

OS: Raspberry Pi OS 64-bit


### Docker Container running on my Pi
1. Homarr Dashboard
2. Bitwarden / Vaultwarden
3. Uptime Kuma
4. Portainer
5. Pihole
6. heimdall
7. Homeassistant Supervise
8. Speedtesttracker
9. Cloudflared-container for most applications

All of my services are published to the internet via the above mentioned Cloudflared Tunnels.
Those are able to expose services without opening any ports nor having to deal with ddos-protection or firewalling because Cloudflare is the firewall in that case.
Also the Cloudfared Tunnels are secured with ther own OAuth-Authentication using a integrated service.

## Dell Mini-Computer (pve)
Most of the time, this is my playground for any hosting project I want to do.
It's running Proxmox 8.x.x
### Tests I already did
1. wazuh Endpoint Protection
2. Windows 11 VM for remote access over the web console
3. Ubuntu server 24.04 LTS for remote shell over the web console

## Synology DS218+ (NAS)
My NAS is a Synology DS218+ running in RAID 1 with 2x2TB HDDs
To reach the NAS I can either use the DDNS entry domain directly configured on the NAS or use a dedicated cloudlfared tunnel.
Using the cloudflared tunnel my Raspberry Pi is communicating over the HTTPS-Port (5001) with the NAS.
It's secured with username:password aswell as 2FA.



<!---
HuckleberryLovesYou/HuckleberryLovesYou is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
