# Raspberry-pi-5-PXE-Server-Setup:
This repository aims for helping with the configuration of Raspberry pi 5 as a PXE server
This tutorial assumes that the base system is a linux system regardless of the architecture (amd64,arm,etc).
For Windows based PXE server tutourial that guide will be coming soon.

**Note:** This guide can also be extended to other setups.

# Prequisites:
i.) A Raspberry pi 5 (with Raspbian OS or any other OS) or any other device having a linux operating system.  
ii.) The device should be connected to the local network, via ethernet or wi-fi. (Ethernet is preferred for better network speeds)

# PXE server setup:
### Step 1: Install `dnsmasq`:  
**bash**
  ```bash
  sudo apt update
  sudo apt install dnsmasq
