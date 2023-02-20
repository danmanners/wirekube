# WireGuard Controller

Needs to do a bunch of things for the wireguard service; [check the specs doc here](../../spec/containers/controller.md).

## Healthz endpoint

Container checks the port open/close status of the wireguard service

- TCP/80 Ingress; responds to readiness/liveness probe
  - `/healthz`

- returns a `200` response if happy
- returns a `400` response if sad
