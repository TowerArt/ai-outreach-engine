# AI Outreach Engine
AI-powered B2B outreach research engine that turns a company name into a fully personalized, executive-ready message in seconds. Built for growth and GTM teams who are tired of generic cold outreach — drop in a target, get back ICP analysis, contact intel, and multi-touch sequences tailored to their actual growth signals. Powered by Claude AI, Hunter.io, and GitHub.
## What it does
- **Researches target companies** using Claude AI with web search — finds leadership teams, funding signals, job postings, and growth indicators
- **Generates personalized outreach** — email subject + body, LinkedIn connection request, and follow-up for each executive contact
- **Tracks your pipeline** — tier companies, log interactions, track reply status
- **Syncs to GitHub** — your company list and outreach data persist in a private GitHub repo, so nothing lives on a server
- **Exports to CSV** — full pipeline export at any time
## How it works
Everything runs in a single HTML file in your browser. No backend, no server, no data sent anywhere except the APIs you configure. Credentials are stored in your browser's localStorage only.
## Setup
1. Download `ai-outreach-engine.html` and open it in your browser
2. On first launch, configure:
   - **Anthropic API Key** — get one at [console.anthropic.com](https://console.anthropic.com)
   - **GitHub Personal Access Token** — [create one](https://github.com/settings/tokens/new?scopes=repo) with `repo` scope
   - **GitHub Repo** — a private repo where your company list (`master_company_list.csv`) and outreach data live
   - **Your Name** — used to personalize AI-generated messages
   - **Your Background** — paste your role, experience, credentials, and what you're targeting. The AI uses this to write outreach that sounds like you, not a template
   - **Hunter.io API Key** *(optional)* — for email lookup, free tier at [hunter.io](https://hunter.io)
## Company list format
Import a CSV with your target companies. Expected columns:
| Column | Description |
|---|---|
| `Company Name` | Company name |
| `Website` | Company website |
| `Industry` | Industry or sector |
| `# Employees` | Headcount |
| `Latest Funding` | Funding stage (Series A, B, PE-backed, etc.) |
| `Last Raised At` | Date of last raise |
| `Total Funding` | Total funding raised |
| `Short Description` | One-line company description |
| `Bucket` | Your custom category |
| `Total_Score` | Your fit score (optional) |
## Skills
The `skills/` folder contains the LinkedIn connection request skill file — a detailed prompt engineering document that instructs Claude on how to write LinkedIn notes that get accepted. It covers character limits, anti-patterns, role-specific guidance, and quality evaluation criteria. You can extend or modify it to match your outreach style.
## Stack
- Vanilla HTML/CSS/JavaScript — no framework, no build step
- [Anthropic API](https://docs.anthropic.com) (Claude) — company research + message generation
- [GitHub API](https://docs.github.com/en/rest) — data persistence
- [Hunter.io API](https://hunter.io/api-documentation) — email lookup
## Privacy
- No data is sent to any server other than the APIs you configure
- Your API keys are stored in your browser's localStorage
- Your company list and outreach data live in your own private GitHub repo
