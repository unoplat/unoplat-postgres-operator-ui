# unoplat-postgres-operator-ui

## Local Dev Env Install
helm install postgres-operator-ui . -n unoplat-db-sql -f environments/dev/values.yaml

## Scope
- Integration with Linkerd
- Alerting on CPU/MEM
- Alerting on any error Logs through Loki/Signoz
- High Availability
- Enforcing Access Control For Users who should be granted permission to create/view dbs.
- DevSecOps:
  - Helm Chart Vulnerability Analysis
  - Container Vulnerability Analysis and Automatic Fix.
  - Automatic Release changelog.
  - Helm Chart release using gh pages
  - Upstream Sync for automatic PRS with versions.
  - Webhook for Installation through Http.
  - Cpu/Mem changes as per qal/e2e/perf/prod.


## Current Feature Set
- Integration with Linkerd
- Optimised Cpu/mem.
- DevSecOps:
  - Helm Chart Vulnerability Analysis
  - Automatic Release changelog.
  - Helm Chart release using gh pages
