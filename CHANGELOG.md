# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [0.0.1]

### Added

- Initial App-as-Code service definition for Portainer Server (`portainer/portainer-ce:2.43.0`).
- Web UI, edge tunnel and legacy API ports, with Traefik routing and automatic DNS for the legacy API.
- Persistent data volume and bind mount of the host Docker socket.
- README with configuration reference and project icon.
