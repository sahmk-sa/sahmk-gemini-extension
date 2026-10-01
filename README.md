# SAHMK Gemini CLI extension

SAHMK is a read-only data source for companies listed on the Saudi Exchange (Tadawul). This extension connects Gemini CLI to the hosted SAHMK MCP server. It does not place trades or move financial assets.

## Tools

| Tool | What it returns |
|---|---|
| `companies_list` | Company directory and symbol discovery |
| `get_quote` | A single stock quote |
| `get_quotes` | Quotes for several symbols |
| `get_market_summary` | TASI or NOMU market summary |
| `get_financials` | Financial statements |
| `get_ratios` | Financial ratios |
| `get_dividends` | Dividend history |
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
