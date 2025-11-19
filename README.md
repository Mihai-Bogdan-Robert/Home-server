# Home Server Setup Suite

A comprehensive automation toolkit for simplifying the creation and management of a personal home server. This project provides an interactive shell interface to deploy and configure containerized services on Proxmox Virtual Environment.

## Overview

This project is designed for users who want to:
- Build a personal home server for media, storage, or hosting various services
- Simplify the deployment of complex applications with automated installation
- Manage multiple services with recommended configurations out of the box
- Learn about containerization and server management

## Quick Start

```bash
bash <(curl -s https://raw.githubusercontent.com/Mihai-Bogdan-Robert/Home-server/main/install.sh)
```

This will launch an interactive menu where you can select which services you want to deploy.

## License

See LICENSE file for details.

## Contributing

Contributions welcome! Please ensure scripts are well-documented and tested.

## Acknowledgments

This project uses the installation scripts created by the amazing **[Proxmox Community Scripts](https://github.com/community-scripts/ProxmoxVE)** project. A big shoutout to the community developers who maintain these scripts and make home server deployment accessible to everyone!

Our role is simply to provide an interactive menu layer that makes it easy to select and deploy these scripts sequentially. All credit for the actual service installation goes to the Proxmox Community Scripts maintainers.

---

**Note**: This project builds upon [Proxmox Community Scripts](https://community-scripts.github.io/ProxmoxVE/)
