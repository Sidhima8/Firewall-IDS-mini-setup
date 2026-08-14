# Suricata IDS

## Objective

To install, configure, and use Suricata to monitor network traffic and detect suspicious activity.

## Installation

Suricata was installed in the Kali Linux environment.

## Rule Update

The latest Suricata detection rules were downloaded and updated.

## Configuration Validation

The Suricata configuration was tested before starting the IDS.

The configuration test completed successfully without errors.

## Network Interface

The active network interface identified for monitoring was:

`eth1`

## Monitoring

Suricata was started on the selected network interface using:

```bash
sudo suricata -c /etc/suricata/suricata.yaml -i eth1
