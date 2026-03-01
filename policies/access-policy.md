### Server Access & Network Overview

The server is now configured with a secure and controlled network:

- **Network Interfaces**
  - `enp0s3` → Bridge interface (LAN access, static IP for management)
  - `enp0s8` → Internal network for corporate clients (isolated subnet)

- **SSH Access**
  - Authentication only via **ED25519 SSH keys**
  - **Password login disabled**
  - Access allowed **only from the management machine**
  
- **Firewall**
  - Incoming connections blocked by default
  - Only SSH from authorized host is allowed
  - Logs all connection attempts for monitoring

- **Routing**
  - Server can act as a **gateway** for internal network clients
  - Internal network fully isolated from the external LAN except via server

This setup simulates a secure mini-enterprise network: controlled access, segmented LAN, and full logging.
