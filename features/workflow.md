# Workflow

SREGym Incident Replay Gate is a hosted remote MCP for SREGym.

## Repeatable Flow

1. Open SREGym Incident Replay Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://sregymgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call run_incident_replay with public-safe sample data.
5. Save the returned receipt or export for human review.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
