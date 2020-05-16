---
layout: post
title: 'PiNode-XMR'
repo_name: 'PiNode-XMR'
description: 'Monero node for single board computers with web interface and pre-configured tools.'
introduction: 'Monero Node for Single Board Computers'
date: 2020-05-13 00:00:00
maintainer: 'shermand100'
maintainer_uid: '20049380'
main-class: 'utility'
tags:
- shermand100
- Raspberry Pi
- Single-Board-Computer
- Node
image: 
color: '#B31917'
---

The PiNode-XMR project is a Monero full node solution for single board computers. Compatible with Raspbian & Armbian Debian Buster [supporting many popular single board computers](https://github.com/monero-ecosystem/PiNode-XMR/wiki/Hardware). It is Open Source for self installing or alternatively some pre-configured disk images are [available for download](https://github.com/monero-ecosystem/PiNode-XMR#downloads) for use with the Raspberry Pi 3b+ & 4.

**Check out the project home repository to see the full README: [github.com/monero-ecosystem/PiNode-XMR](https://github.com/monero-ecosystem/PiNode-XMR/blob/master/README.md)**

## Purpose:
This project aims to solve two problems

* Power and hardware usage for running a 24/7 node.

  Running this project allows you to run your own Monero node on a single board computer. These devices are well known for low power consumption and cost, ideal for use 24/7. Typically this project consumes less than 15W and costs less than $100 in hardware to setup.
  
* Perceived technical barrier to entry 

  Those new to cryptocurrencies can find the new terms and concepts confusing or daunting. PiNode-XMR aims to keep things as simple as possible and is aimed at the beginner user level. All core functions are either activated by a mouse click on the web interface or selectable from the main menu in the terminal.
  Additional features from bolt on projects are also self installing so customisation couldn't be easier. When selecting a new feature from the menu, PiNode-XMR will guide you through the process step by step.

## Features:
* 6 Node modes (click to start)
  * Private Node
  * Private Node - with mining (Hardware dependant)
  * Public Node - Free access for connecting external wallets
  * Public Node - Using new RPC payment feature* - Coming soon
  * Anonymity modes -
    * tor bridging Node - routes your transactions through the tor network
    * I2P bridging Node - routes your transactions through the I2P network - Coming soon
    
* Simple control with Web-UI
  * View Monero node and hardware status
  * Control bandwidth, connection limits and RPC port access
  * Transaction pool and summary viewer
  * View connected peer info
  * Monerod log file view page
  
* Monero Block Explorer [Github - onion-monero-blockchain-explorer](https://github.com/moneroexamples/onion-monero-blockchain-explorer)
* Easy setup menu for config of passwords and Updates.

* **New** - Additional tools
  * raspi-config (Hardware and Wifi settings pre-built into PiNode-XMR menu
  * Agnostics - SD Card read/write health checker included
  * PiVPN - Tool for easy configuration of OpenVPN for Raspbian and Armbian
  * Pop blocks - Monero tool to help recover blockchain problems - UI
  * Systemd Monitor to track running node and explorer functions
  * All status boxes have improved scripts for clearer more constant feedback during high CPU loads.
  * Improved helper to setup an external USB storage device to hold the Monero blockchain. This new script allows a user to import a blockchain already held from a PC. Also on SD card failure this storage device can be identified by PiNode-XMR as configured for use, preserving the blockchain and so reducing re-startup time.
  
* All the other benefits of running a node on a Single Board computer (EG. RasPi, silent/fan-less, low power (approx 15w) for 24/7 node, low cost)
* Headless (No need for extra monitor,keyboard,etc) direct connect via Ethernet or WiFi**


## Support at
* [Redit.com/r/PiNode](https://www.reddit.com/r/pinode/)
* Telegram group PiNode-XMR [t.me/PiNodeXMR](https://t.me/PiNodeXMR)

**Screenshots and full documentation at: [github.com/monero-ecosystem/PiNode-XMR](https://github.com/monero-ecosystem/PiNode-XMR/blob/master/README.md)**
