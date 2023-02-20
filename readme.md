# Wirekube

In ur cluster, runnin' ur wireguardz

## Summary

This project is aimed at providing a High-Availability[1] Wireguard service in a cloud-native way.

## Development

Todo items for development work

### Minimum Viable Product

- [ ] GitHub Actions Container Builds
- [ ] Security Scanning
- [ ] Startup Docs

### Longer Term Goals

- [ ] Nightly Builds
- [ ] Container minimization
- [ ] Ephemeral Testing Environments (?)

## Wirekube Service

Todo items for the service itself

### Minimum Viable Product

- [ ] Multi-Architecture Container Images
  - [ ] Wireguard
  - [ ] Controller Sidecar
    - [ ] Provides Liveness/Readiness Probe endpoints
    - [ ] Watches for configMap and secret changes
    - [ ] 
  - [ ] Host `ip route` update service
  - [ ] Init-Container
    - [ ] necessary host dependencies
    - [ ] wait for verification
- [ ] Helm Chart
  - [ ] RBAC manifests
  - [ ] Deployment/DaemonSet manifests
  - [ ] Wireguard Service manifest
  - [ ] Wireguard configMap manifests
    - [ ] Formatting for configuration
  - [ ] Wireguard secrets manifests
    - [ ] Formatting for configuration
  - [ ] Targeted manifests
    - [ ] Target Service Manifets
      - [ ] Formatting for configuration
    - [ ] Target Endpoint manifests
      - [ ] Formatting for configuration
- [ ] Requirements Documentation
- [ ] Service Documentation
- [ ] Architecture Diagrams (Mesh Topology)

### Longer Term Goals

- [ ] Prometheus Metrics
- [ ] Dashboard?
