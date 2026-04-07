# Kubernetes Homelab - Multi-Node Cluster

## Overview
A 3-node Kubernetes cluster built on Proxmox for learning cloud & cybersecurity concepts.

## Quick Stats
- **Nodes:** 3 (1 control + 2 workers)
- **Hardware:** Dell OptiPlex 7050, i7-7700, 24GB RAM
- **OS:** Ubuntu 22.04 LTS
- **Kubernetes Version:** v1.28
- **Runtime:** containerd
- **CNI:** Flannel

## Architecture
[Insert diagram showing: Proxmox Host → 3 VMs → Kubernetes cluster]

## Features Implemented
- ✅ Multi-node cluster with kubeadm
- ✅ Container networking (Flannel CNI)
- ✅ Pod deployments & services
- ✅ Network policies (security)
- ✅ RBAC setup
- ✅ Persistent volumes
- ✅ Audit logging

## Quick Start
```bash
# Clone repo
git clone https://github.com/yourname/kubernetes-homelab
cd kubernetes-homelab

# Run setup (see docs/setup-guide.md for details)
bash config/kubeadm-init.sh
bash config/worker-setup.sh
```

## Learning Goals
- Understand Kubernetes architecture
- Practice container orchestration
- Implement security best practices
- Troubleshoot distributed systems

## Documentation
- [Setup Guide](docs/setup-guide.md) - Step-by-step instructions
- [Architecture](docs/architecture.md) - System design
- [Security](docs/security.md) - RBAC, network policies, hardening
- [Troubleshooting](docs/troubleshooting.md) - Common issues

## Results
- Deployed 3-node cluster from scratch
- Implemented pod security policies
- Created network policies restricting traffic
- Set up RBAC with custom roles

## Key Learnings
1. Kubernetes node initialization & bootstrapping
2. Container networking fundamentals
3. Security hardening (what NOT to do in production)
4. Debugging cluster issues with kubectl
5. Infrastructure automation

