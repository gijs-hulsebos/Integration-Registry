# Notes: {{Artifacts}} , {{Anthropic}}

## 📌 {{Basic Info}}
* **AI Tool for:** {{Interactive Workspace}}
* **Primary Use Case:** {{Visualising code, creating interactive dashboards}}
* **Link:** [Website/Dashboard](https://claude.ai/) 
* **Region:** {{USA}}

---

## ⚖️ {{Pros & Cons}}

** {{What is great about it?}} **
* {{1. Live Iteration: You can see your React components or websites render in real-time. If there is a bug, you just tell Claude to "fix the button," and the Artifact updates instantly.}}
* {{2. Persistence (2026 Update): For Pro/Max users, Artifacts now have 20MB of 'Persistent Storage,' meaning they can remember data across different chat sessions (like a tracker or a journal).}}
* {{3. Publishing & Customizing: You can publish an Artifact to a public URL (claude.site) for others to use, or 'Remix' someone else’s Artifact from the global catalog.}}
* {{4. MCP Integration: Artifacts can now connect to external tools. You can build a 'Dashboard' Artifact that pulls live data from your n8n workflows or Google Sheets.}}

* ** {{What sucks / limitations?}} **
* {{1. Text-Only Storage: While they have persistence, they cannot store images or binary files directly yet—only JSON/Text data.}}
* {{2. Execution Limits: Complex Python scripts rely on Pyodide (WebAssembly), which can be slow for heavy data processing compared to a native terminal.}}
* {{3. Versioning: While you can flip through previous versions, manually merging changes between two different versions of an Artifact is still clunky.}}

---

## 🧠 {{My Notes & Learnings}}
* **Watch out for:** {{Context Bloat. Large Artifacts (like a 1000-line React app) consume a lot of your message quota every time you ask for an update.}}
* **Tips:** {{Check out the 'Inspiration' tab in the sidebar. It has a curated catalog of high-quality Artifacts (games, life hacks, data tools) that you can 'Remix' for your own repo.}}
* **Pricing feeling:** {{Extremely fair. Artifacts and Projects were made **FREE** for all users in March 2026, though Free users are limited to the Sonnet 4.6 model.}}

---

## 📝 {{To-Do / Testing}}
- [ ] {{Build a 'Registry Dashboard' Artifact that visualizes my /Providers folder structure using a tree-map layout.}}
- [ ] {{Test the new 'Persistent Storage' by creating a task-manager Artifact that saves my to-do list even after I close the browser.}}
- [ ] {{Try the 'Publish' feature to share a specific AI-tool comparison tool with a teammate via a public link.}}
