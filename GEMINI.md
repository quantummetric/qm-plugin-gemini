# Quantum Metric

Use the `quantum-metric` MCP server to analyze funnels, errors, friction and session replays.

- Call `get_context` first and tell the user the subscription, workspace and timezone in use.
- To use another workspace, call `list_workspaces` and pass the workspace ID as `workspace` on each call.
- Before building a query, call `search_skills` and follow the guidance it returns.
- Report only numbers returned by a tool.
