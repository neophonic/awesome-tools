# awesome-marcom-tools
List of tools and resources (both opensource and proprietary) I love to use or do recommend.

## Research Tools


## Content Management Systems

### [Directus](https://github.com/directus)
I love Directus because of its flexibility & ability to help us generate massive amounts of semi-customized landing pages and content elements across the website.

## Information Management

### [Obsidian](https://obsidian.md)

### [Syncthing](https://github.com/syncthing/syncthing)
Peer-to-peer file sync with no cloud in the middle. Keeps notes and files in step across machines.

### [Readwise](https://readwise.io)
Hub for reading and highlights. Also usable from the terminal through its [CLI](https://github.com/readwiseio/readwise-cli) and from agents through its MCP server.

## AI Agents and Claude Code

### [Claude Code](https://github.com/anthropics/claude-code)
Agentic coding CLI from Anthropic. The main engineering layer on every machine I work from.

### [herdr](https://github.com/herdrdev/herdr)
Terminal multiplexer built for coding agents: panes, workspaces, and agents controlling other agents. See [herdr.dev](https://herdr.dev).

### [Hermes Agent](https://github.com/NousResearch/hermes-agent)
Open-source, self-hostable personal agent from Nous Research.

### [Superpowers](https://github.com/obra/superpowers)
Skill library for Claude Code: brainstorming, writing plans, TDD, systematic debugging and subagent-driven development.

### [Context7](https://github.com/upstash/context7)
MCP server that gives agents up-to-date library documentation instead of whatever they remember from training.

## Agent Memory and Knowledge

### [beads](https://github.com/gastownhall/beads)
Git-backed issue tracker and memory store designed for coding agents. Tasks and durable facts survive between sessions. See [beads.gascity.com](https://beads.gascity.com).

### [Dolt](https://github.com/dolthub/dolt)
SQL database with Git-style versioning (branch, diff, merge). The storage engine under beads.

### [Cognee](https://github.com/topoteretes/cognee)
Knowledge-graph memory for AI agents, with its own MCP server.

### [FalkorDB](https://github.com/FalkorDB/falkordb)
Low-latency graph database, a good fit for agent knowledge graphs.

### [pgvector](https://github.com/pgvector/pgvector)
Vector similarity search inside Postgres, so embeddings live next to the rest of the data.

### [Ollama](https://github.com/ollama/ollama)
Runs local models (embeddings, small LLMs) behind a simple API.

## JavaScript, TypeScript and Python

### [pnpm](https://github.com/pnpm/pnpm)
Fast, disk-efficient package manager. The default for every JS project.

### [Bun](https://github.com/oven-sh/bun)
JavaScript runtime and toolkit. Good for small servers and single-file compiled CLIs.

### [tsx](https://github.com/privatenumber/tsx)
Runs TypeScript directly with Node, no build step.

### [Vitest](https://github.com/vitest-dev/vitest)
Vite-native test runner.

### [Playwright](https://github.com/microsoft/playwright)
Browser automation and end-to-end testing.

### [uv](https://github.com/astral-sh/uv)
Extremely fast Python package and project manager.

### [pytest](https://github.com/pytest-dev/pytest)
The Python testing framework.

## Infrastructure and Ops

### [Tailscale](https://github.com/tailscale/tailscale)
WireGuard-based mesh VPN; machines reach each other without opening ports.

### [Docker Compose](https://github.com/docker/compose)
Multi-container deployments on a single host.

### [Ansible](https://github.com/ansible/ansible)
Agentless configuration management and deployment automation.

### [Traefik](https://github.com/traefik/traefik)
Reverse proxy with automatic TLS and Docker service discovery.

### [Keycloak](https://github.com/keycloak/keycloak)
Open-source identity and access management with single sign-on.

### [systemd](https://github.com/systemd/systemd)
Services and timers for long-running jobs; `OnFailure=` hooks make failures loud.

### [restic](https://github.com/restic/restic)
Fast, encrypted, deduplicated backups.

### [Wrangler](https://github.com/cloudflare/workers-sdk)
CLI for developing and deploying Cloudflare Workers.

## Observability

### [Prometheus](https://github.com/prometheus/prometheus)
Metrics collection and alerting.

### [Grafana](https://github.com/grafana/grafana)
Dashboards on top of Prometheus and other data sources.

### [htop](https://github.com/htop-dev/htop)
Interactive process viewer.

### [smartmontools](https://github.com/smartmontools/smartmontools)
Disk health monitoring through S.M.A.R.T.

## Real-time and Messaging

### [LiveKit](https://github.com/livekit/livekit)
Open-source WebRTC server for real-time voice and video agents. Comes with [livekit-cli](https://github.com/livekit/livekit-cli).

### [Synapse](https://github.com/element-hq/synapse)
Self-hosted Matrix homeserver.

## Security and Secrets

### [SOPS](https://github.com/getsops/sops)
Encrypted secrets files that stay diffable in git.

### [age](https://github.com/FiloSottile/age)
Simple, modern file encryption. The key backend for SOPS.

### [gitleaks](https://github.com/gitleaks/gitleaks)
Scans git repos and commits for leaked secrets.

### [fail2ban](https://github.com/fail2ban/fail2ban)
Bans IPs that show brute-force patterns in service logs.

## CLI Workhorses

### [jq](https://github.com/jqlang/jq)
Command-line JSON processor. Glue for every API response and log.

### [ripgrep](https://github.com/BurntSushi/ripgrep)
Recursive search that respects `.gitignore`.

### [poppler-utils](https://poppler.freedesktop.org)
`pdftotext` and friends. Turns PDFs into text that agents can read.

### [FFmpeg](https://github.com/FFmpeg/FFmpeg)
Audio and video conversion for anything media-shaped.

### [superfile](https://github.com/yorukot/superfile)
Modern terminal file manager.
