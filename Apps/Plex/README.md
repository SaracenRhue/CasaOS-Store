# Portainer

## Overview
Portainer is an open-source tool for managing containerized applications in Docker, Docker Swarm, and Kubernetes. It provides a web-based user interface for managing your Docker containers, images, networks, and volumes.

## Features
- Simple management of Docker containers, images, networks, and volumes.
- User-friendly web interface.
- Supports Docker Swarm and Kubernetes.
- Comprehensive access control and user management.

## Installation
- Use the provided `docker-compose.yml` to deploy Portainer in CasaOS.
- Access Portainer at `http://<your-host-ip>:9000`.

## Configuration
- The data volume (`/DATA/AppData/portainer`) stores Portainer's data and configuration.
- Portainer exposes two ports: 8000 for the API and 9000 for the web UI.

## Usage
- After installation, open Portainer by visiting `http://<your-host-ip>:9000`.
- Set up your admin user account.
- Connect to your local Docker environment.

## Support
For support and more information, visit [Portainer's official website](https://www.portainer.io/).
