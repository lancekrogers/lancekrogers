```go
package main

type EngineerProfile struct {
 Blockchain struct {
  Since int; Scale string; Specs, ChainsBuiltOn, Lang []string
  Cos map[string]struct{ Focus, Detail string }
 }
 AI, Fintech struct {
  ExpYr int; Current, Past, Specs, APIs []string; Lang, Sec, Auto, Clients []string
 }
 Leadership, Impacts, Skills []string
}

func main() {
 var p EngineerProfile

 // ── Blockchain ───────────────────────────────────────────────────────────────
 p.Blockchain.Since = 2016
 p.Blockchain.Scale = "50M+ users"
 p.Blockchain.Specs = []string{
  "Gaming Infra", "DeFi", "Protocol R&D", "dApp", "trading",
 }
 p.Blockchain.ChainsBuiltOn = []string{
  "Eth", "Polygon", "Besu", "BTC", "Iota", "Lisk", "Ark",
 }
 p.Blockchain.Lang = []string{
  "Go", "Solidity", "Python", "Vyper", "TypeScript", "Node.js", "Rust",
 }
 p.Blockchain.Cos = map[string]struct{ Focus, Detail string }{
  "🎮 Mythical Games": {
   Focus: "Blockchain Engineer",
   Detail: "Custodial wallets, chain listeners, " +
    "tx executors, smart contracts, node management",
  },
  "🐉 Dragonchain": {
   Focus:  "Senior Developer",
   Detail: "Modular cross chain dApps, den.social, smart contracts",
  },
  "🔄 Swapblocks": {
   Focus: "CTO",
   Detail: "Designed subnet chain with modular contract engines, " +
    "8000 Discord Community, SBX Token Sale",
  },
  "🗿 Blockhead": {
   Focus: "Owner",
   Detail: "Full Cycle NFT Projects, Trading Tools, Crypto SDKs, " +
    "Strategy Consultations, DeFi LP",
  },
  "🗿 CharlotteBlockheads": {
   Focus:  "Lead Organizer",
   Detail: "Most active crypto meetup group in Carolinas 2017-2020",
  },
 }

 // ── AI ───────────────────────────────────────────────────────────────────────
 p.AI.Current = []string{"Guild Agent Framework"}
 p.AI.Past = []string{"claude-code-go SDK", "yt_summarizer"}
 p.AI.Specs = []string{
  "Complex Automation", "Custom Agent Framework", "RAG", "MCP", "Domain Expert Agents",
 }
 p.AI.APIs = []string{"Claude", "OpenAI", "Ollama"}
 p.AI.Lang = []string{"Go", "Python"}

 // ── Fintech ──────────────────────────────────────────────────────────────────
 p.Fintech.ExpYr = 5
 p.Fintech.Specs = []string{"Security infra", "Algo trading", "Compliance"}
 p.Fintech.Sec = []string{"CI/CD", "Git Security"}
 p.Fintech.Auto = []string{"Compliance Gen", "Neural Net Quality"}
 p.Fintech.Clients = []string{"🏦 BoA", "🏛️ PNC", "💳 Global Payments"}
 p.Fintech.Lang = []string{"Python", "Go", "Java"}

 // ── Leadership / Impacts / Skills ───────────────────────────────────────────
 p.Leadership = []string{
  "Mentored teams boosting productivity",
  "Structured async processes",
  "Strategic refactoring cutting costs",
  "Pragmatic technical decisions",
 }
 p.Impacts = []string{
  "Blockchain infra 50M+ users",
  "Claude Code SDK <1 week post-launch",
  "Drove >$120k on-chain sales in 2 hrs",
  "Automated tasks saving $80k/mo",
  "Optimized AWS cost $40k/mo",
  "Modernized Fortune 500 security code/processes saving 6mo/yr dev time",
  "Turned $100 into $50k (personal algo trading)",
  "Generated 33%-100% annual income via algo trading (2017-2021)",
 }
 p.Skills = []string{"Go", "Python", "Eth", "Solidity", "Distributed Sys", "AI/ML"}

 _ = p
}
```

## 📞 Available for New Opportunities

I’m a builder and a doer. Since my last contract, I’ve built an overland vehicle, finished my basement, and shipped multiple software projects. I’m now looking for my next role or contract. If you’re seeking someone who gets things done rather than just grinding leetcode, reach out. Particularly interested in blockchain and AI-focused roles.

<!-- - 💼 [blockhead.consulting](https://blockhead.consulting) -->

> “I solve problems and automate systems other people don’t realize exist."
