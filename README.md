# Uptime

Outside-in checks for the Output Apps sites, run by GitHub Actions every 10 minutes from GitHub's
network, so they still fire when a whole server is down. A failed run emails the repository owner.

| Site | Checked URL |
|---|---|
| hostaroast.co.uk | https://hostaroast.co.uk/api/health |

Add a site: add its URL to `matrix.site` in `.github/workflows/uptime.yml`.
Test the alert: Actions, Uptime, Run workflow, with a URL that does not exist.

This repository is public only because public repositories get unlimited Actions minutes. It holds
no secrets.
