# Infra

just my infra configuration.

## How it works

- use traefik as a reverse proxy to map service by hostname.
- use tailscale for internal resource e.g. `komodo`
- use komodo behind tailscale vpn to manage resource.

### Services

- `tailscale` -> as a client for internal app.
- `komodo` -> manage resource
- `zitadel` -> Auth Service
- `stalwart` -> Mail + CalDAV
