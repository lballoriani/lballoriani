# Hi, I'm Luca 👋

Sysadmin / developer working across infrastructure, time-series data, IoT/edge
and automation. I like small, well-tested tools that make operations boring — in
a good way.

Below are open-source projects distilled and generalized from real work
(client-specific code and data removed): each is standalone, documented, tested,
and runnable with one command.

## 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| [**timescaledb-rollups**](https://github.com/lballoriani/timescaledb-rollups) | Hierarchical time-series roll-up pipeline: continuous aggregates (minute→month), time-weighted LOCF averaging, tiered retention. One-command Docker demo. | PostgreSQL · TimescaleDB · SQL |
| [**energy-dispatch-engine**](https://github.com/lballoriani/energy-dispatch-engine) | Self-adapting solar-plus-storage dispatch engine + simulator: recovers curtailed solar and minimises the bill from tariff, forecast and battery state. | Python · matplotlib · pytest |
| [**grafana-dashboards-as-code**](https://github.com/lballoriani/grafana-dashboards-as-code) | GitOps for Grafana: version dashboards in git, dry-run diff (terraform-style), idempotent apply over the API, round-trip pull. | Python · Grafana API · Docker |
| [**claude-code-toolkit**](https://github.com/lballoriani/claude-code-toolkit) | A tested PreToolUse safety hook for Claude Code (blocks `rm -rf /`, `curl\|sh`, secret exfiltration, force-push…), plus reusable sub-agents and slash commands. | Python · Claude Code |
| [**edge-provision**](https://github.com/lballoriani/edge-provision) | Idempotent bash bootstrap for edge/fleet Linux hosts: `ensure_*` primitives, dry-run, per-host config, container-tested idempotency. | Bash · Docker |

## 🧰 Tech

`Linux` · `Python` · `Bash` · `PostgreSQL/TimescaleDB` · `Grafana` · `Docker` ·
`Proxmox` · `Node-RED` · `IoT/edge` · `monitoring & observability`

📫 Reach me on [LinkedIn](https://www.linkedin.com/in/lballoriani/)
