# Netherlands KvK Company Search MCP

Search Dutch companies from the KvK Handelsregister by name or KvK number and see their business activities.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/company/netherlands
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month

## Netherlands data coverage

- Company ids are `NL` + the KvK number
- Business activities and active / inactive status

## Example prompts

- *"Look up this KvK number"*
- *"Find Dutch companies with 'Logistics' in the name"*
- *"What are the business activities of this B.V.?"*

## Tools

| Tool | Description |
|---|---|
| `Netherlands_search_companies` | Search companies in the Netherlands registry by name or id |
| `Netherlands_get_company` | Full company profile by id (the `NL` prefix is optional) |

## Nederlands

KvK-gegevens voor uw AI-assistent: zoek bedrijven op naam of KvK-nummer en bekijk de bedrijfsactiviteiten en status.

**Voorbeeldvragen**

- *"Zoek dit KvK-nummer op"*
- *"Vind B.V.'s met 'Logistiek' in de naam"*
- *"Wat zijn de bedrijfsactiviteiten van dit bedrijf?"*

## Keywords

KvK, KvK nummer, Handelsregister, bedrijf zoeken, KvK uittreksel, Dutch company lookup
