# Grafana GraphQL Schema

Grafana is the open-source analytics and monitoring platform that connects to a wide range of data sources. While Grafana's primary management interface is a REST HTTP API, Grafana can query GraphQL-based data sources, and its plugin ecosystem and alerting infrastructure expose structured data models that map cleanly to a GraphQL schema.

This schema covers the core Grafana resource model including dashboards, panels, data sources, alert rules, alert instances, alert groups, contact points, annotations, users, teams, organizations, service accounts, tokens, RBAC roles, playlists, library panels, snapshots, correlations, and observability query types for Tempo, Loki, Prometheus, InfluxDB, Elasticsearch, CloudWatch, and Azure Monitor.

## Schema Source

Derived from the Grafana HTTP API reference documentation and the Grafana OSS data model:

- https://grafana.com/docs/grafana/latest/developers/http_api/
- https://github.com/grafana/grafana

## Types

| Type | Description |
|------|-------------|
| Dashboard | A Grafana dashboard containing panels and variables |
| Panel | A visualization panel within a dashboard |
| Query | A data query executed against a data source |
| DataSource | A configured data source connection |
| Folder | A folder that organizes dashboards |
| AlertRule | A Grafana Unified Alerting rule |
| AlertInstance | A firing or resolved alert instance |
| AlertGroup | A group of alert rules sharing an evaluation interval |
| AlertContact | A notification contact point |
| Notification | A notification policy configuration |
| Annotation | A time-range annotation attached to a dashboard |
| User | A Grafana user account |
| Team | A team grouping users within an organization |
| Organization | A Grafana organization (tenant) |
| ServiceAccount | A non-human service account for API access |
| Token | An API token or service account token |
| Role | An RBAC role definition |
| RoleAssignment | An assignment of a role to a user, team, or service account |
| Playlist | A rotating sequence of dashboards |
| Report | A scheduled PDF/PNG dashboard report |
| PublicDashboard | A publicly shareable dashboard with access controls |
| Snapshot | A point-in-time snapshot of a dashboard |
| PluginSettings | Configuration settings for a Grafana plugin |
| LibraryPanel | A reusable panel shared across dashboards |
| CorrelationConfig | A correlation linking data across two data sources |
| TempoQuery | A Tempo distributed tracing query |
| LokiQuery | A Loki log query using LogQL |
| PromQuery | A Prometheus/Mimir metrics query using PromQL |
| InfluxQuery | An InfluxDB Flux or InfluxQL query |
| ElasticsearchQuery | An Elasticsearch/OpenSearch query |
| CloudWatchQuery | An AWS CloudWatch metrics or logs query |
| AzureMonitorQuery | An Azure Monitor metrics or logs query |
| SLO | A Service Level Objective definition |
| Incident | A Grafana Incident record |
| OnCall | An on-call schedule configuration |
| EscalationChain | An escalation chain for alert routing |
| Integration | An alerting integration with an external system |
| TimeRange | A relative or absolute time range |
| Variable | A dashboard template variable |
| PanelTarget | A query target bound to a panel |
| DataSourcePlugin | Metadata for an installed data source plugin |
| UserPreferences | Personal preferences for a Grafana user |
| TeamPermission | A permission level granted to a team |
| FolderPermission | An access control entry on a folder |
| DashboardPermission | An access control entry on a dashboard |
| OrgUser | A user within an organization with a role |
| TeamMember | A user member of a team |
| SearchResult | A dashboard or folder search result |
| HealthStatus | Grafana server health and version info |
| Stats | Server-wide usage statistics |
| DatasourceHealth | Health check result for a data source |
