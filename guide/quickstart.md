# Quickstart

SREGym Incident Replay Gate is a hosted remote MCP for SREGym.

## Fast Path

1. Open SREGym Incident Replay Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://sregymgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call run_incident_replay with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://sregymgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=quickstart_home
- https://sregymgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=quickstart_pricing
- https://sregymgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=sregymgate_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://sregymgate.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
