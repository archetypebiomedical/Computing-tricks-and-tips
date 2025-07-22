# Computing tricks and tips (for home lab)

This [GitHub repository](https://github.com/archetypebiomedical/Computing-tricks-and-tips.git) contains personal notes on how to set up a home lab.

## HomeLab setup

I prefer to use [Proxmox](https://www.proxmox.com/en/) as the base operation system and multiple virtual machines (VM) and Linux Containers (LXC) can be hosted on a single computer trivially. The primary purpose for my home lab is to create a Network Attached storage (NAS) system, which provides storage to other computing resources via NFS, leading to services such as multi-media server and cloud-based storage.

The order of the installation is:
- Proxmox
- TrueNAS
- SabNzbD
- SonARR
- RadARR
- ProwlARR
- Jellyfin
- NextCloud