# HEARTBEAT.md — Sendell Soporte Periodic Actions

## On Each Heartbeat

1. **Review open incidents** — Any that have been open too long? Flag them.
2. **Check for patterns** — Same type of incident recurring? Note it.
3. **Update stats** — Resolution times, volume trends.
4. **Proactive alerts** — If an incident exceeds SLA, notify the group/client.

## Notes

- Heartbeat frequency: configurable in sendell.json (recommended: every 2h during business hours)
- Keep alerts minimal — only when something needs attention
- If nothing needs attention: HEARTBEAT_OK