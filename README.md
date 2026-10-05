# Fuel Ledger Deploy

Deployment wrapper for `muhtegaralfikri/fuel-ledger-system`.

The application repo is not modified. GitHub Actions builds ARM64 Docker images, then the STB only pulls and runs them.

## Images

- `ghcr.io/muhtegaralfikri/fuel-ledger-api:latest`
- `ghcr.io/muhtegaralfikri/fuel-ledger-web:latest`

## Server

```bash
git clone https://github.com/muhtegaralfikri/fuel-ledger-deploy.git /mnt/hdd/.apps/fuel-ledger-deploy
cd /mnt/hdd/.apps/fuel-ledger-deploy
sudo ./server/install-or-update.sh
```

Open:

```text
http://100.84.28.55:8092
```

