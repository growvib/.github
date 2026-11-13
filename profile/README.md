<div align="center">

<img src="https://github.com/growvib.png?size=160" width="96" height="96" alt="GrowVib logo" />

# GrowVib

**Social media growth, built for people and AI agents.**

Followers, subscribers, members, views, likes and reactions across every major platform —
ordered in seconds from the web, from Telegram, or straight from your AI agent.

[![Website](https://img.shields.io/badge/growvib.com-6B2C91?style=for-the-badge&logo=googlechrome&logoColor=white)](https://growvib.com)
[![MCP server](https://img.shields.io/badge/MCP_server-111111?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)](https://growvib.com/mcp)
[![Pay with USDC](https://img.shields.io/badge/USDC_·_x402-2775CA?style=for-the-badge&logo=circle&logoColor=white)](https://growvib.com/x402)

<sub>Instagram · TikTok · YouTube · Telegram · X · Facebook · Spotify · and more</sub>

</div>

---

### 🤖 Let your agent buy growth

GrowVib runs a public [MCP](https://modelcontextprotocol.io) server. Any MCP-capable agent can search the catalog, get an exact quote and hand you a checkout link — **no account, no API key**.

```bash
claude plugin marketplace add GrowVib/agent-plugins
claude plugin install growvib@growvib
```

Then just ask:

> *Find 1,000 Instagram followers for instagram.com/yourprofile and give me a link to pay.*

You pay in USDC on **Base** or **Solana** from your own wallet. Agents with their own wallet can pay over **x402**. The model never touches a key, a signature or a card.

| Endpoint | Auth | What it's for |
|---|---|---|
| `https://api.growvib.com/mcp-public` | none | Catalog, quotes, checkout links, x402 orders |
| `https://api.growvib.com/mcp` | OAuth | Your GrowVib account: balance, funds, orders |

Listed in the official MCP registry as **`com.growvib/growvib`**.

---

### 📦 Open source

| Repository | What's inside |
|---|---|
| [**agent-plugins**](https://github.com/growvib/agent-plugins) | Claude Code plugin marketplace — the `growvib` plugin and its `buy-growth` skill |
| [**x402-mcp-lab**](https://github.com/growvib/x402-mcp-lab) | A workbench for building and testing paid MCP tools over x402 |

---

<div align="center">

[Website](https://growvib.com) · [MCP docs](https://growvib.com/mcp) · [x402 & USDC](https://growvib.com/x402) · [Server card](https://api.growvib.com/.well-known/mcp/server-card.json)

</div>
