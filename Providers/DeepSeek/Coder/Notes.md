# Notes: {{Coder -> Reasoner}} , {{DeepSeek}}

## 📌 {{Basic Info}}
* **AI Tool for:** {{Advanced Coding, Debugging, Mathematical Reasoning}}
* **Primary Use Case:** {{Writing complex production ready functions}}
* **Link:** [Website/Dashboard](https://www.deepseek.com/en) 
* **Region:** {{China}}

---

## ⚖️ {{Pros & Cons}}

** {{What is great about it?}} **
* {{1. SOTA Coding Benchmarks: As of March 2026, DeepSeek V3.2 scores 84.7% on HumanEval, beating GPT-4o and rivaling the latest Claude 4.6 Sonnet for pure syntax accuracy.}}
* {{2. Unified Reasoner: The 'deepseek-reasoner' mode is a game-changer for coding; it 'thinks' (CoT) before outputting code, which caught 92% of logic errors in recent 2026 benchmarks.}}
* {{3. Massive Language Support: Native support for 300+ programming languages, including deep expertise in niche languages like Verilog and COBOL.}}
* {{4. OpenAI Compatibility: The API uses the exact same structure as OpenAI, making it a 30-second swap in your n8n or LangChain workflows.}}

* ** {{What sucks / limitations?}} **
* {{1. Rate Limits: Because it's so cheap, the official API frequently hits 'Server Overload' during peak US/EU working hours.}}
* {{2. Context Window (Native): While it handles 128K tokens, it is outclassed by Claude’s 1M+ window for analyzing truly massive, multi-repo codebases in one go.}}
* {{3. Verbosity in Reasoner: The 'Thinking' model can sometimes over-explain simple fixes, consuming more output tokens than a standard chat model.}}

---

## 🧠 {{My Notes & Learnings}}
* **Watch out for:** {{'deepseek-reasoner' vs 'deepseek-chat'. Use 'chat' for boilerplate and 'reasoner' for bugs. Reasoner is slower but significantly more reliable for complex architectural logic.}}
* **Tips:** {{Take advantage of 'Context Caching'. If you send the same 50KB of documentation/context in every prompt, your costs drop by 90% (down to $0.028/1M tokens).}}
* **Pricing feeling:** {{Disruptively cheap. You can run an entire dev-agent for a month for the price of a single Starbucks coffee.}}
---

## 📝 {{To-Do / Testing}}
- [ ] {{Benchmark 'deepseek-reasoner' against my current n8n 'Bug Fixer' agent to see if it reduces the need for manual human review.}}
- [ ] {{Check the performance of the 'FIM' (Fill-In-the-Middle) endpoint for real-time IDE completion in my local environment.}}
