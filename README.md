# inventory-api

Tracks stock levels and reservations.

| | |
|---|---|
| **CI/CD** | GitHub Actions builds + pushes `ghcr.io/<owner>/inventory-api` on every push to `main` |
| **Deploy** | ArgoCD auto-discovers this repo (topic `idp-service`) and syncs `k8s/` |
| **Observability** | `/metrics` scraped via ServiceMonitor; dashboard auto-appears in Grafana |
| **Docs** | `docs/` renders in the portal via TechDocs |
