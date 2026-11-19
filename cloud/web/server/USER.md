# Metrics API — user guide

This is the API the SDK talks to. After you create a server and API key at [https://mcp-monitor.vercel.app/](https://mcp-monitor.vercel.app/), `mcp-monitor-sdk` POSTs tool-call events to `/v1/metrics` with `X-API-Key`. The dashboard reads the same store. Default production ingest: `https://mcp-metrics-server.just-a-dev.workers.dev/v1/metrics`.
