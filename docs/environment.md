# Environment Baseline

## Operating System
- Distribution: Ubuntu
- Version: 24.04 LTS
- Installation type: Ubuntu Server
- Architecture: x86_64

## Virtualization
- Environment: Virtual Machine
- Hypervisor: VMware

## Hardware Resources
- CPU: 2 vCPU
- RAM: 8 GB
- Swap: 4 GB

## Storage
- Root filesystem: LVM
- Root volume size: 19 GB
- Available space: ~11 GB
- Boot partition: 2 GB

## Networking
- Interface: ens33
- IP address: 192.168.111.128/24 (DHCP)
- Network type: Private / NAT (depending on VM setup)
- Default gateway: Provided by DHCP

## Notes
- Swap is enabled by default and will be disabled before Kubernetes installation.
- This environment is intended for a single-node Kubernetes cluster during initial setup.
- Resource limits are sufficient for control-plane components and basic workloads.
