# 🗂️ AI Integration Registry

<p align="center">
  <img src="https://raw.githubusercontent.com/gijs-hulsebos/gijs-hulsebos/main/GijsHulsebos.banner.png" alt="Gijs Hulsebos AI Automation" width="100%" />
</p>

<p align="center">
  <a href="https://gijshulsebos.com">
    <img src="https://img.shields.io/badge/gijshulsebos.com-121212?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/gijs-hulsebos">
    <img src="https://img.shields.io/badge/LinkedIn-121212?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

---

### The "Single Source of Truth" for AI Providers & Services

This repository serves as the central engine for **gijshulsebos.com/AI-Tools**. It is a structured database of AI integrations, engineered for **n8n data extraction**, **Next.js frontend rendering**, and **AI Agent context injection**.

---

## 🏗️ Architecture
This registry follows a strict **Service-First** hierarchy. Each provider is segmented into specific technical services to ensure maximum precision in automation workflows.

**Structure:** `Providers/ [ProviderName] / [ServiceName] /`

### The 4 Core Components per Service:
Every service folder contains four essential Markdown files, each serving a distinct architectural purpose:

* **`Capabilities.md`**: *What can it do?* – Technical specs, model limits, unique selling points, and commercial tiers.
* **`Integration.md`**: *How do you build it?* – API endpoints, authentication headers, JSON payloads, and n8n node configurations.
* **`Prompts.md`**: *How do you talk to it?* – Optimized System Prompts, few-shot examples, and fine-tuned parameter settings.
* **`Notes.md`**: *What is the experience?* – Personal "Initial Architect Notes," latent "gotchas," real-world latency benchmarks, and use-case advice. - Human in the loop creation

---

## 🚀 Automation & Scalability
This repository is built to be machine-readable:

1.  **n8n Pipeline:** A specialized workflow monitors this repo for commits. Upon update, data is extracted and pushed to the frontend database.
2.  **Next.js Frontend:** The site at `gijshulsebos.com` dynamically generates service pages based on this folder structure.
3.  **Standardization:** All new additions must utilize the `.Template.md` files in the root to maintain data integrity across the stack.

---

## 🛠️ Templates
Need to add a new service? Use the official blueprints to maintain consistency:
* [Integration Template](./Templates/Integration.Template.md)
* [Capabilities Template](./Templates/Capabilities.Template.md)
* [Prompts Template](./Templates/Prompts.Template.md)
* [Notes Template](./Templates/Notes.Template.md)

---

## 🌐 Let's Connect
Are you building complex AI systems and looking for a scalable integration architecture?

* **Website:** [gijshulsebos.com](https://gijshulsebos.com)
* **Email:** gijs@gijshulsebos.com

---

<p align="center">
  <img src="https://raw.githubusercontent.com/gijs-hulsebos/gijs-hulsebos/main/readme.md.banner.png" alt="Gijs Hulsebos AI Automation Footer" width="100%" />
</p>
