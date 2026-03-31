# proxmox-prepare

Prepare one or more Proxmox hosts for monitoring.

This repo is intended to be run from a Proxmox host and can work for:
- a single Proxmox server
- a multi-node Proxmox cluster

Current scope:
- enable Ceph Prometheus module once
- install base packages
- install and start node exporter

Future scope:
- smartctl exporter
- ZFS textfile collector
- validation tasks