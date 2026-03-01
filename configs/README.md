# Configuration Files

This directory stores important server configuration files.

Examples:
- netplan configuration
- sshd_config (hardened)
- ufw rules

These files represent the final production-ready configuration of the server.


# Server Configuration Files

This directory stores important server configuration files used for the Education Project 1 server.

### Contents

- **netplan.yaml** — Network configuration (bridge + internal network)
- **sshd_config** — Hardened SSH configuration (ED25519 keys only, password login disabled, restricted access)
- **ufw.rules** — Full firewall rules, can be imported to another machine (`iptables-restore`)
- **ufw-summary.txt** — Human-readable summary of firewall rules for documentation and review

These files represent the **final, production-ready configuration** of the server.
