# AgentReeve skills

Agent skills for [AgentReeve](https://agentreeve.com): Bitcoin market data, plus funding, basis and open interest for every crypto perpetual on Binance, Bybit, OKX and Hyperliquid, for AI agents, paid per request over x402 (USDC on Base), with a free preview and free samples of every product.

| Skill | What it does |
|---|---|
| `btc-intelligence` | The full product line: pick the right product for any Bitcoin market question |
| `hyperliquid-whale-watch` | What Hyperliquid's 40 largest accounts are doing with BTC |
| `btc-market-brief` | A short, data-backed Bitcoin market brief |
| `btc-derivatives-check` | Funding, positioning, liquidations and order-book walls before a trade |
| `btc-similar-setups` | What BTC did after past moments that looked like now |
| `crypto-funding-scanner` | Extreme funding, cross-exchange funding spreads and open-interest movers across all coins |

Each skill is instructions only: no scripts, no keys. Agents verify the payment quote (payout address, Base, USDC), keep to a per-task spending cap, try the free samples first and never invent data. Observational market data, not financial advice.

## MCP server

AgentReeve is also an MCP server (Streamable HTTP) at `https://agentreeve.com/mcp`, listed in the official MCP Registry as `io.github.shakeelamjid/agentreeve` (`server.json` here). Tools: `btc_free_preview`, `btc_list_products`, `btc_free_sample`, `btc_product` and `btc_compute_help`.
