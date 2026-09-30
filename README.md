# RDP over Tailscale

Set up a Linux machine for Remote Desktop (RDP) access over a private Tailscale network.

## What this installs

- **xrdp** — RDP server
- **XFCE** — lightweight desktop environment
- **Tailscale** — private network connectivity
- Basic service configuration

> This repository does not contain a Tailscale auth key, password, or other secret.

## Supported systems

Target: Debian/Ubuntu-based Linux systems.

## 1. Run the installer

On the Linux machine:

```bash
git clone https://github.com/ViratUp11/rdp-tailscale.git
cd rdp-tailscale
chmod +x install.sh
sudo ./install.sh
