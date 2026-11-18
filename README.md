# SRE on FileForge
SLI/SLO/SLA, error budget, alerting, incident drill, Golden Signals dashboard, and logging (Loki + Alloy) on my own app.

- monitoring/: Prometheus, Blackbox, Alertmanager (example), SLO rules
- loki/: Loki log store
- alloy/: Alloy log shipper (runs on the app server)
- grafana/: Golden Signals dashboard JSON
- docs/: study notes

SLO 99.2% | SLA 99% | Error budget 0.8% | Alert detected in ~2 min during a failure drill.
