# Container Runtime

## Runtime Choice
- containerd is used as the container runtime.
- Docker is not installed.

## Configuration
- cgroups version: v2
- cgroup driver: systemd
- containerd configured with SystemdCgroup = true

## Rationale
containerd is the recommended runtime for kubeadm-based Kubernetes clusters.
Systemd cgroup driver is required for compatibility with cgroups v2.
