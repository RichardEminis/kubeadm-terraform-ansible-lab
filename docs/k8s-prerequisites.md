# Kubernetes Prerequisites

## Swap
- Swap was disabled as required by kubelet.
- Swap entry was commented out in /etc/fstab.

## Kernel Modules
- overlay
- br_netfilter

## sysctl Parameters
- net.ipv4.ip_forward = 1
- net.bridge.bridge-nf-call-iptables = 1
- net.bridge.bridge-nf-call-ip6tables = 1
