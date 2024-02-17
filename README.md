- 👋 Hi, I’m Tim Matheis
- 👀 I’m currently wokring in the Networking Segment
- 🌱 I’m currently learning Debian
- 📫 How to reach me: mail@timmatheis.de


# My Homelab
I though I just share my Homelab here.  Right now I'm only running a Raspberry Pi 5 and a Synology DS218+ (NAS) in my Homelab, except my Router and a Switch

## Router
Nothing crazy just a normal Speedport Smart 3

It is being DHCP-Server, DNS-Server, Access Point and Switch on my Network

avg. Upstream-Bandwith: 257.69Mbit/s

Network: 192.168.2.0/24

DHCP-Range: 192.168.2.100 - 192.168.2.230

DHCP-Leasetime: 1 day

DNS-Upstreamserver: 8.8.8.8


## Switch
It's a 24 RJ-45 1G non-PoE unmanaged Switch.

That means there are no VLANs in my Network, but there surely will be in further future.

## Raspberry Pi 5
Architecture: ARM

CPU: Broadcom BCM2712 quad-core Arm Cortex A76 processor @ 2.4GHz

microSD-Storage: 64GB

RAM: 4GB

OS: Raspberry Pi OS 64-bit


### Services running on my Pi
1. Docker-ce
2. Dockge # not Portainer because I don't have multiple server where Kubernetes would be great and Homeassistant-Supervised doesn't like giving away it's privliges
3. 



<!---
HuckleberryLovesYou/HuckleberryLovesYou is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
