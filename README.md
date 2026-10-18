# homelab
- [Troubleshooting](#troubleshooting)

## Repository Layout
```
homelab/
├── .github/
│   ├── rulesets/          # Exported GitHub rulesets (branch protection, naming)
│   └── workflows/         # CI checks run on pull requests
├── services/              # Everything that runs as a container stack
│   ├── infrastructure/    # Services others depend on: reverse proxy, DNS, VPN
│   ├── apps/              # Services I use: Jellyfin, Kavita, Immich, ...
│   └── monitoring/        # Services that observe the homelab
```

Each service live in its own folder, `services/<category>/<name>/`, containing a `compose.yml`, an `.env.example`, and a `README.md`.


## Prerequisites
_TODO: tools and versions needed on a workstation._

## Getting started
_TODO: how to install the prerequisites and deploy the homelab._

## Secrets
_TODO: where and how secrets are stored._

## Troubleshooting
_TODO: known failure modes and how to fix them, added as they come up._