# Notes: {{Codex}} , {{OpenAI}}

## 📌 {{Basic Info}}
* **AI Tool for:** {{Autonomous Software Engineering}}
* **Primary Use Case:** {{Delegating large coding tasks in parallel to cloud-based subagents (Creating a whole repo}}
* **Link:** [Website/Dashboard](https://openai.com/codex) 
* **Region:** {{USA}}

---

## ⚖️ {{Pros & Cons}}

** {{What is great about it?}} **
* {{1. Parallel Subagents: Can spawn multiple specialized agents to work on different files or tasks simultaneously.}}
* {{2. Codex Cloud: Runs heavy tasks (builds, tests, deployments) in sandboxed cloud environments instead of slow local machines.- good for retail use}}
* {{3. Multi-Interface: Works via a dedicated macOS app, a CLI for power users, can be used in Cursor for example}}
* ** {{What sucks / limitations?}} **
* {{1. Token Heavy: Spawning multiple subagents consumes large amounts of tokens as each subagent needs its own context + system message}}
* {{2. Management: For smaller tasks managing and approving tasks can take longer and consume more tokens than using a LLM chat model}}
* {{3. Desktop-First: Currently heavily optimised for macOS use. Optimisation for Windows is lacking}}

## 🧠 {{My Notes & Learnings}}
* **Watch out for:** {{Sub-agents might get confused when working in the same files as other sub-agents without clear boundaries}}
* **Tips:** {{Use the '/agent' command in the CLI to see what tasks agents are performing in real time}}
* **Pricing feeling:** {{For bigger projects it will need higher tier or pay-per-usage model, great for smaller projects}}

---

## 📝 {{To-Do / Testing}}
- [ ] {{Benchmark: Test the 'spawn_agents_on_csv' feature to automate a bulk audit of multiple services.}}
- [ ] {{Stress Test: Let a subagent run a full CI/CD pipeline in the Codex Cloud and see if it catches deployment errors.}}
- [ ] {{Comparison: Compare subagent efficiency against Anthropic’s 'Claude Code' in a complex multi-file refactor.}}
