# Cloud Native SaaS Platform

Production-like Kubernetes + GitOps lab built on VMware Workstation.

## Lab

- 3 Kubernetes control-plane nodes
- 3 Kubernetes worker nodes
- 3 PostgreSQL/Patroni nodes
- 1 storage node
- 1 bastion/admin node

## Network

- VM network: `10.50.0.0/24`
- Pod CIDR: `10.244.0.0/16`
- Service CIDR: `10.96.0.0/12`
- Kubernetes API VIP: `10.50.0.100`
- MetalLB pool: `10.50.0.200-10.50.0.220`

## Current status

Stage 2 — Ansible bootstrap
