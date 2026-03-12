---
name: "openclaw-skill-observability"
description: "Use this skill when the user wants OpenClaw health, cost, or recent failure reports, especially for session monitoring, recent errors, and cost summaries."
---

# Observability Skill

Tools for monitoring OpenClaw health, costs, and logs.

## Tools

### get_cost_report
Get a report of estimated API costs for sessions active in the last 24 hours.
- Returns: Markdown table of costs per model.

### get_recent_errors
Get a list of recent sessions that failed or were aborted (checks last 50 sessions).
- Returns: List of problematic sessions with IDs and status.
