# 💫 About Me:
<br>    👋 Hi, I’m Tim Matheis<br>    👀 I’m currently working as a Network Engineer Trainee<br>    🌱 I’m currently learning Python<br>    📫 How to reach me: mail@timmatheis.de


# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![GithubPages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white) ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white) ![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Home Assistant](https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=HuckleberryLovesYou&theme=synthwave&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=HuckleberryLovesYou&theme=synthwave&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=HuckleberryLovesYou&theme=synthwave&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=HuckleberryLovesYou&limit=5&theme=synthwave&combine_all_yearly_contributions=true)

[![](https://visitcount.itsvg.in/api?id=HuckleberryLovesYou&icon=1&color=6)](https://visitcount.itsvg.in)



# My Homelab
## Router
Nothing crazy just a normal Speedport Smart 3

It's DHCP-Server, DNS-Server, Access Point and Switch on my Network

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
