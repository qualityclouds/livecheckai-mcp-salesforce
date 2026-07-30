# livecheckai-mcp-salesforce

Real-time validation of AI-generated Apex, LWC, and metadata in VS Code, checked against your org's governance, security, and platform-limit rules as the code is written.

## Install

1. Install [Visual Studio Code](https://code.visualstudio.com/download).
2. In the Extensions panel, search for **Livecheck Quality for Salesforce** and install it.

## Authentication

**Quality Clouds customers:** ask your Success Manager to enable the LivecheckAI add-on, then enable auto-update in the extension. It activates automatically.

**New to Quality Clouds:** requires a Quality Clouds license. [Sign up](https://id.qualityclouds.com/sign-up?utm_source=github&utm_medium=readme&utm_campaign=livecheckai-mcp-salesforce), then authenticate in the extension's Quality Clouds settings panel.

## What it does

| Check | What it catches |
|---|---|
| SOQL and DML | Unsafe queries, missing bulkification, governor-limit risks |
| Naming and metadata | Org naming conventions, metadata consistency |
| Security | Hardcoded IDs, credential leaks, insecure patterns |
| Architecture | Org-specific and platform-limit rule violations |

Feedback and autofixes appear inline in VS Code as the AI assistant generates code, before a pull request exists.

## Links

- Product: [qualityclouds.ai](https://qualityclouds.ai)
- Documentation: [qualityclouds.com/documentation](https://qualityclouds.com/documentation/)
- Questions and bugs: [community](https://github.com/qualityclouds/community/discussions)

## License

Proprietary. Requires a Quality Clouds license.

---

Built by [Quality Clouds](https://qualityclouds.ai), governing enterprise platforms since 2017.
