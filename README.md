# How to install NextCloud as VM in Proxmox with data on NFS

This document details how to install [NextCloud](https://nextcloud.com/) as a virtual machine inside a [Proxmox](https://www.proxmox.com/en/) installation, where the data shared via NextCloud resides on a [NFS](https://en.wikipedia.org/wiki/Network_File_System) share from a TrueNAS.

# Background and Rationale

Self-hosting home servers has many advantages, such as having your own cloud-based storage with very high storage quota. One way to achieve this is to host several cloud-based applications using [Proxmox](https://www.proxmox.com/en/), thereby having everything running on single computer hardware.

## Proxmox

Proxmox Virtual Environment (Proxmox VE) is an open-source server management platform for virtualization, allowing a user to host virtual machines and Linux Containers (LXC) with a web-based interface.