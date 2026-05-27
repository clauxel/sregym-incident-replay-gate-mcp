# Evaluation Guide

Use this page to evaluate whether SREGym Incident Replay Gate fits a real workflow.

## What To Test

- SREGym
- SREGym Incident Replay Gate
- SREGym Incident Replay Gate documentation
- SREGym Incident Replay Gate remote MCP
- sregymgate server card

## Expected Evidence

- Open SREGym Incident Replay Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://sregymgate.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call run_incident_replay with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://sregymgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=evaluation_checkout
