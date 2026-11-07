<a href="https://specstream.ai">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/readme-banner-night.png">
    <img src="assets/readme-banner-day.png" alt="SpecStream" width="100%">
  </picture>
</a>

### The live web data engine.

One platform to build, search, extract, enrich, map, and monitor data across the entire web.

Ask for any dataset in plain words, and SpecStream builds it from the entire live web: every match found, extracted and enriched into structured records, then monitored for change. It runs through the API and MCP, and inside Sheets, CRMs, Slack, n8n, Zapier and the other tools teams already use.

| Product | What it does | Price |
| --- | --- | --- |
| [Search API](https://specstream.ai/search-api) | `GET /v1/web-search`. The most accurate web search API in the world ([scores and method](https://specstream.ai/benchmarks)). | $5 per 1,000 searches |
| [Extract API](https://specstream.ai/extract-api) | `POST /v1/extract`. The main text of up to 20 web pages, PDF, Word or Excel files a call. | $0.80 per 1,000 pages. A page with no text is not charged. |
| [Deep Search](https://specstream.ai/deep-search) | Ask in plain words. Get every match on the live web, in structured rows. | 5¢, 15¢ or $1 a row |

- Source URL and read time on every value.
- The most a run can cost is shown and approved before it runs. Only delivered rows are billed, and a run that finds nothing costs nothing.
- A saved request reruns hourly to yearly, and each row is labeled changed, unchanged or no longer matching.
- Your agent works on your account, inside the spending limits you set.

**Connect an agent:** `https://api.specstream.ai/mcp` (Streamable HTTP, also in the [official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=ai.specstream) as `ai.specstream/specstream`). Setup for each client: [specstream.ai/docs/mcp](https://specstream.ai/docs/mcp).

[![Add to Replit](https://replit.com/badge?caption=Add%20to%20Replit)](https://replit.com/integrations?mcp=eyJkaXNwbGF5TmFtZSI6IlNwZWNTdHJlYW0iLCJiYXNlVXJsIjoiaHR0cHM6Ly9hcGkuc3BlY3N0cmVhbS5haS9tY3AifQ==)

| Install | For |
| --- | --- |
| `pip install specstream-client` | Python, plus the `specstream` command |
| `npm i @specstream/sdk` | TypeScript and Node |
| `npm i @specstream/ai-sdk` | Vercel AI SDK tools |
| `pip install langchain-specstream` | LangChain tools and a retriever |
| `pip install llama-index-tools-specstream` | LlamaIndex |
| `pip install crewai-specstream` | CrewAI |
| `pip install specstream-haystack` | Haystack |
| `pip install specstream-mcp-stdio` | MCP clients that only start local servers |

Plugins for Claude Code, Cursor, VS Code, OpenCode, OpenClaw, Pi, Kiro and Grok Build, the n8n node and a GitHub Action live in [specstream-tools](https://github.com/specstream/specstream-tools).

New accounts start with $10 of work free for 30 days, no card. [Website](https://specstream.ai) · [Docs](https://specstream.ai/docs) · [Pricing](https://specstream.ai/pricing) · [support@specstream.ai](mailto:support@specstream.ai)
