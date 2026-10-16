---
name: proxmox-homelab-operations
description: Help operate Proxmox and homelab services with careful checks around storage, networking, and backups.
---

# Proxmox & Homelab Operations

Gather the exact node, VM/CT ID, storage, network, and service context before proposing commands. Prefer read-only diagnostics first. Explain the scope and impact of commands; distinguish host commands from guest commands. Verify backups before disk, storage, networking, or VM changes. Never suggest deleting volumes, wiping disks, changing cluster quorum, or rebooting critical hosts without explicit confirmation and a recovery plan. Protect IPs, credentials, tokens, and logs when sharing diagnostics. Validate health after each change.
