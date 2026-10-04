# SAHMK Gemini CLI extension

SAHMK is a read-only data source for companies listed on the Saudi Exchange (Tadawul). This extension connects Gemini CLI to the hosted SAHMK MCP server. It does not place trades or move financial assets.

## Tools

| Tool | What it returns |
|---|---|
| `companies_list` | Company directory and symbol discovery |
| `get_quote` | A single stock quote |
| `get_quotes` | Quotes for several symbols |
| `get_market_summary` | TASI or NOMU market summary |
| `get_market_movers` | Top gainers, losers, volume leaders, or value leaders |
| `get_sectors` | Sector performance |
| `get_company` | Company profile for an exact symbol |
| `get_financials` | Financial statements |
| `get_ratios` | Financial ratios |
| `compare_symbols` | Side-by-side company comparison |
| `get_dividends` | Dividend history |
| `get_depth` | Order-book depth (Market Depth entitlement) |
| `get_trades` | Recent trade prints (Pro and above) |
| `get_events` | Stock event summaries (Pro and above) |
| `get_historical` | Historical prices |

## Endpoint

The extension uses the hosted MCP server at `https://mcp.sahmk.sa/mcp`.

## Install

```bash
gemini extensions install https://github.com/sahmk-sa/sahmk-gemini-extension
```

Restart Gemini CLI after installing.

## Authenticate

```text
/mcp auth sahmk
```

Sign in with a SAHMK developer account and approve the API key you want Gemini to use. No extra configuration is required in this repository.

## Documentation

https://www.sahmk.sa/en/developers/tutorials/sahmk-mcp-ai-agents

## Support

developer@sahmk.sa

## Privacy

https://www.sahmk.sa/en/legal/privacy
