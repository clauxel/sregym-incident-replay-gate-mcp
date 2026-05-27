# SREGym Incident Replay Gate

SREGym Incident Replay Gate is a hosted remote MCP for SREGym.

This repository is a public documentation project for SREGym Incident Replay Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://sregymgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=readme_home
- Pricing: https://sregymgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=readme_pricing
- Checkout: https://sregymgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://sregymgate.clauxel.com/mcp
- Server card: https://sregymgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.sregymgate/sregymgate-mcp`
- Tools: `run_incident_replay`, `score_sre_agent`, `export_incident_verdict`, `compare_runbook_versions`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: run_incident_replay
- MCP tool: score_sre_agent
- MCP tool: export_incident_verdict
- MCP tool: compare_runbook_versions

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
