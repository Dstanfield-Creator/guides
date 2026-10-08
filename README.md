# Guides & Processes

Operational guides, runbooks, deployment checklists, troubleshooting procedures, and best practices for IT operations, infrastructure, and security.

## Structure

```
├── operational-guides/      # Step-by-step procedures
├── deployment-checklists/   # Pre-flight and post-deployment checklists
├── runbooks/                # Incident response and recovery runbooks
├── troubleshooting-guides/  # Problem diagnosis and resolution
├── best-practices/          # Industry standards and recommendations
├── CONTRIBUTING.md          # Contribution guidelines
└── LICENSE
```

## Contents

### Operational Guides
- [Proxmox VE API Tokens with Least Privilege](./operational-guides/proxmox-api-token-least-privilege.md) - custom roles, dedicated users, path-scoped ACLs and safe secret handling for automation tokens

### Deployment Checklists
- [New Proxmox VM Checklist](./deployment-checklists/new-proxmox-vm-checklist.md) - tickable checklist from VM settings through network, access, firewall, updates, monitoring, backup and documentation

### Runbooks
- [Remote Firewall Change Without Lockout](./runbooks/remote-firewall-change.md) - enable or change UFW/nftables over SSH with a dead-man rollback timer and a fresh-session test

### Troubleshooting Guides
- [SSH Key Authentication Failures](./troubleshooting-guides/ssh-key-auth-failures.md) - classify DNS, DOWN, AUTH, HOSTKEY, HOSTKEY! and agent problems, with the command for each

### Best Practices
- [Documentation vs Live State](./best-practices/documentation-vs-live-state.md) - verify with live commands, date and status every doc, retire docs with the hardware

## Using This Repository

1. Find the guide relevant to your task
2. Follow the step-by-step procedures
3. Validate completion against checklists
4. Document any deviations for team review

For adding new guides, see [CONTRIBUTING.md](./CONTRIBUTING.md).

---

**Author:** Danny Stanfield · Perth, WA
**License:** MIT
