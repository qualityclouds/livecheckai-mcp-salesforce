# platform-mcp

AI code governance for ServiceNow and Salesforce, exposed as an MCP server: instance and scan visibility, real-time validation of components as they're written, and rule lookups, all callable from Cursor, Claude Code, and any MCP-compatible client.

## Install

```bash
claude mcp add --scope user --transport http platform https://mcp.qualityclouds.com/mcp \
  --header "Authorization: Bearer <your-api-key>"
```

## Authentication

Requires a Quality Clouds license. Existing customers: generate an API key in the Admin Portal. New to Quality Clouds: [sign up](https://id.qualityclouds.com/sign-up?utm_source=github&utm_medium=readme&utm_campaign=platform-mcp).

## What it does

| Capability | What it does |
|---|---|
| Instances and scans | Lists your governed instances and recent scan history, and compares instances by issue count or quality score |
| Issues and quality posture | Issue distributions and KPIs by severity, impact area, application, or developer, with filtering for narrower questions |
| Configuration inventory | Configuration element counts by type, creator, and application for a given scan |
| Developer analytics | Issue and technical debt totals by developer |
| Live validation (livecheck) | Real-time analysis of a ServiceNow or Salesforce component as it's written, returning issues against your ruleset |
| Rules | Looks up the active Quality Clouds best practices for a given configuration element type |
| Write-offs | Lists write-off reasons and requests a write-off for one or more issues found during a livecheck |

ServiceNow and Salesforce are both covered; some tools take platform-specific parameters (for example, ServiceNow rule lookups take an instance URL and severity, Salesforce lookups don't).

## Links

- Product: [qualityclouds.ai](https://qualityclouds.ai)
- Documentation: [qualityclouds.com/documentation](https://qualityclouds.com/documentation/)
- Questions and bugs: [community](https://github.com/qualityclouds/community/discussions)

## License

Proprietary. Requires a Quality Clouds license.

---

Built by [Quality Clouds](https://qualityclouds.ai), governing enterprise platforms since 2017.
