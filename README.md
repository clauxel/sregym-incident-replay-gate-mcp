# SREGym Incident Replay Gate

Prove your SRE agent can resolve incidents before production.

SREGym Incident Replay Gate is a paid hosted remote MCP for SREGym. It exposes Streamable HTTP tool calls, bearer-token access, public server-card metadata, usage logs, and receipt-oriented JSON for AI agent workflows.

## Public Endpoints

- Website: https://sregymgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- MCP endpoint: https://sregymgate.clauxel.com/mcp
- Server card: https://sregymgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.sregymgate/sregymgate-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `run_incident_replay`
- `score_sre_agent`
- `export_incident_verdict`
- `compare_runbook_versions`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://sregymgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- Pricing: https://sregymgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27#pricing
- Server card: https://sregymgate.clauxel.com/server-card.json
- MCP endpoint: https://sregymgate.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
