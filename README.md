## Observability

This setup ingests structured NDJSON logs from:

- python-lab
- ollama_workbench
- openvpn

Key fields:
- service.name
- event.dataset
- event.action
- event.outcome
- error.message / error.type
- owb.elapsed_ms (app-level timing)

Logs are shipped via Filebeat and visualized in Kibana.
