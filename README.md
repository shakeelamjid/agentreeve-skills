# AgentReeve skills

Agent skills for [AgentReeve](https://agentreeve.com): Bitcoin market data for AI agents, paid per request over x402 (USDC on Base), with a free preview and free samples of every product.

| Skill | What it does |
|---|---|
| `btc-intelligence` | The full product line: pick the right product for any Bitcoin market question |
| `hyperliquid-whale-watch` | What Hyperliquid's 40 largest accounts are doing with BTC |
| `btc-market-brief` | A short, data-backed Bitcoin market brief |
| `btc-derivatives-check` | Funding, positioning, liquidations and order-book walls before a trade |
| `btc-similar-setups` | What BTC did after past moments that looked like now |

Each skill is instructions only: no scripts, no keys. Agents verify the payment quote (payout address, Base, USDC), keep to a per-task spending cap, try the free samples first and never invent data. Observational market data, not financial advice.

## MCP server

AgentReeve is also an MCP server (Streamable HTTP) at `https://agentreeve.com/mcp`, listed in the official MCP Registry as `io.github.shakeelamjid/agentreeve` (`server.json` here). Tools include `btc_free_preview`, `btc_free_sample`, `list_paid_endpoints` and `paid_endpoint`.
