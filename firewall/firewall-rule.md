# Firewall Configuration using iptables

## Objective

To configure a Linux firewall using iptables to control network traffic.

## Firewall Rules

The following services were configured:

| Service | Port | Status |
|---|---:|---|
| HTTP | 80 | Allowed |
| HTTPS | 443 | Allowed |
| SSH | 22 | Allowed |
| FTP | 21 | Blocked |
| Telnet | 23 | Blocked |

## Configuration

The existing firewall rules were checked before configuring new rules.

```bash
sudo iptables -L 
