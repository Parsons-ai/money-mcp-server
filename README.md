# Money MCP Server

Personal finance MCP server by [Parsons.AI](https://parsons.ai) — connect AI assistants to your financial data.

## Server URL

```
https://money.parsons.ai/api/mcp
```

**Transport:** Streamable HTTP
**Auth:** OAuth 2.1 (Dynamic Client Registration)

## Tools

| Tool | Description | Type |
|------|-------------|------|
| `whoami` | Get authenticated user info | Read |
| `schema` | Get database table/column details | Read |
| `query` | Execute read-only SQL queries on your financial data | Read |
| `mutate` | Create, update, or delete budgets, goals, reminders, and other entities | Write |
| `sync` | Refresh latest data from connected bank accounts via Plaid | Write |

## What You Can Do

- **"What's my net worth?"** — Query all accounts and get total assets, liabilities, and net worth
- **"Show my top spending categories this month"** — Analyze transactions by category
- **"Create a grocery budget for $500/month"** — Create budgets, goals, and reminders
- **"Sync my latest transactions"** — Pull fresh data from your connected banks
- **"Compare dining spending: January vs December"** — Comparative analysis across time periods

## How to Connect

### Claude.ai / Claude Desktop
Add as a connector using the server URL above. OAuth will guide you through sign-in.

### Any MCP Client
Point your client to `https://money.parsons.ai/api/mcp` using Streamable HTTP transport.

## Links

- **Website:** https://money.parsons.ai
- **Privacy Policy:** https://money.parsons.ai/privacy
- **Terms of Service:** https://money.parsons.ai/terms
- **Support:** support@parsons.ai

## About

Money connects to your bank accounts via [Plaid](https://plaid.com) to provide real-time financial tracking. All data is secured with row-level security — you can only access your own financial data.

Built by [Parsons.AI](https://parsons.ai).
