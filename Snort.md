# Snort IDS

## Objective

To install and configure Snort as a Network Intrusion Detection System and monitor network traffic.

## Installation

Snort IDS was installed using the package manager in Kali Linux.

## Network Interface

The active network interface was identified for IDS monitoring.

The selected interface was:

eth1

## Command
```bash
sudo snort -c /etc/snort/snort.lua -i eth1
