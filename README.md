# DPF Allocations

Tracking lab resource allocations for the DPF team — machines, DPU workers, HBN
subnets, and cluster domains.

## Files

- **lab-machines.yaml** — Hypervisors, DPU-equipped servers, and cluster domain
  records. Each entry includes addressing, BMC info, assigned users, cluster
  membership, and hardware features.
- **hbn-subnets.yaml** — Host-Based Networking subnet pool and per-slot
  assignments.

## Conventions

- Users are identified by GitHub username.
- Machine features are tagged as a list (e.g. `[x86, BF3, MTU9000, OOB]`).
- Broken machines are marked with `broken: true` and a `notes` field.

# Why

To be consumed by tooling
