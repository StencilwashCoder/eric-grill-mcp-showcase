# Eric Grill MCP Server Collection

**Building infrastructure for AI agents that actually do things.**

Author: [Eric Grill](https://ericgrill.com) | [GitHub](https://github.com/EricGrill) | [Chainbytes LLC](https://ericgrill.com)

12 MCP servers. 280+ tools. Infrastructure, Security, Bitcoin, Finance, and AI orchestration.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-888888?style=for-the-badge&logo=vercel&logoColor=white)

**Website**: https://ericgrill.com  |  **Blog**: https://ericgrill.com/blog

---

## Quick Install (Claude Code)

```bash
# Infrastructure
/plugin install mcp-proxmox-admin@agents-skills-plugins
/plugin install mcp-multi-agent-ssh@agents-skills-plugins
/plugin install mcp-multi-agent-server-delegation@agents-skills-plugins

# Security
/plugin install mcp-kali-orchestration@agents-skills-plugins

# Bitcoin
/plugin install mcp-bitcoin-cli@agents-skills-plugins

# Markets
/plugin install mcp-predictive-market@agents-skills-plugins
/plugin install mcp-market-data@agents-skills-plugins
```

---

## MCP Servers

### Infrastructure & Virtualization

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [mcp-proxmox-admin](https://github.com/EricGrill/mcp-proxmox-admin) | Proxmox VE management (VMs, LXC, snapshots) | 16 | TypeScript |
| [mcp-multi-agent-ssh](https://github.com/EricGrill/mcp-multi-agent-ssh) | Persistent SSH with AES-256-GCM encryption | 8 | TypeScript |
| [mcp-multi-agent-server-delegation](https://github.com/EricGrill/mcp-multi-agent-server-delegation) | Task delegation to isolated Proxmox VMs | 5 | TypeScript |

### Security

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [mcp-kali-orchestration](https://github.com/EricGrill/mcp-kali-orchestration) | 50+ Kali Linux security tools (nmap, Metasploit, sqlmap) | 50+ | TypeScript |

### Bitcoin & Crypto

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [mcp-bitcoin-cli](https://github.com/EricGrill/mcp-bitcoin-cli) | Bitcoin blockchain ops, OP_RETURN, BRC-20 | 16 | Python |

### Finance & Markets

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [mcp-predictive-market](https://github.com/EricGrill/mcp-predictive-market) | 5-platform prediction market aggregation | 8 | Python |
| [mcp-market-data](https://github.com/EricGrill/mcp-market-data) | Real-time stock/crypto/forex via Yahoo Finance | 6 | Python |
| [quickbooks-online-mcp-server](https://github.com/EricGrill/quickbooks-online-mcp-server) | QuickBooks Online CRUD (55 tools) | 55 | Python |

### Data & Memory

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [mcp-civic-data](https://github.com/EricGrill/mcp-civic-data) | 7 government APIs (weather, census, NASA) | 22 | TypeScript |
| [mcp-memvid-state-service](https://github.com/EricGrill/mcp-memvid-state-service) | AI memory layer with vector search | 10 | TypeScript |
| [mcp-ipfs](https://github.com/EricGrill/mcp-ipfs) | IPFS decentralized storage, pinning, DAG | 34 | TypeScript |

### AI Orchestration

| Server | Description | Tools | Language |
|--------|-------------|:-----:|:--------:|
| [fulcrum-mcp](https://github.com/EricGrill/fulcrum-mcp) | AI orchestration - jobs, knowledge, workers | 50+ | TypeScript |

---

## Resources

- **Claude Code Plugin Marketplace**: [agents-skills-plugins](https://github.com/EricGrill/agents-skills-plugins)
- **GitHub**: [@EricGrill](https://github.com/EricGrill)
- **Website**: [ericgrill.com](https://ericgrill.com)
- **Blog**: [ericgrill.com/blog](https://ericgrill.com/blog)

---

## About Eric Grill

Navy veteran. Bitcoin infrastructure builder. IBJJF champion. Chainbytes LLC founder.

Writing about AI, Bitcoin, and infrastructure at [ericgrill.com](https://ericgrill.com).

---

*This showcase repository is SEO-optimized to improve discoverability of Eric Grill's MCP servers.*
