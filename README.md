# Grafana

Grafana is the open-source analytics and monitoring platform that connects to a wide range of data sources including Prometheus, Loki, Elasticsearch, InfluxDB, MySQL, PostgreSQL, and cloud providers. It provides a comprehensive HTTP API for managing dashboards, data sources, alert rules, users, organizations, folders, annotations, and teams.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/apis.yml)

## APIs

- **Grafana HTTP API** — RESTful API for managing Grafana resources including dashboards, data sources, alert rules, users, organizations, folders, annotations, and teams. Supports authentication via API keys, basic auth, and OAuth tokens.
  - [OpenAPI](openapi/grafana-api.yml)
  - [Full OpenAPI](openapi/grafana-openapi.yml)
  - [Documentation](https://grafana.com/docs/grafana/latest/developers/http_api/)
  - [JSONSchema — Dashboard](json-schema/dashboard.json)
  - [JSONSchema — Data Source](json-schema/datasource.json)
  - [JSONSchema — Panel](json-schema/panel.json)
  - [JSON-LD Context](json-ld/grafana-context.jsonld)

## Tags

Alerting, Analytics, Dashboards, Logs, Metrics, Monitoring, Observability, Traces, Visualization

## Properties

- [Portal](https://grafana.com)
- [Getting Started](https://grafana.com/docs/grafana/latest/getting-started/)
- [Documentation](https://grafana.com/docs/grafana/latest/)
- [Authentication](https://grafana.com/docs/grafana/latest/administration/service-accounts/)
- [Pricing](https://grafana.com/pricing/)
- [Terms of Service](https://grafana.com/legal/terms/)
- [Privacy Policy](https://grafana.com/legal/privacy-policy/)
- [Status](https://status.grafana.com/)
- [Support](https://grafana.com/support/)
- [Blog](https://grafana.com/blog/)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
