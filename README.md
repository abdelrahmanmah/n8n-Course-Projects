<div align="center">

```
███╗   ██╗ █████╗ ███╗  ██╗    ██╗    ██╗ ██████╗ ██████╗ ██╗  ██╗███████╗██╗      ██████╗ ██╗    ██╗███████╗
████╗  ██║██╔══██╗████╗ ██║    ██║    ██║██╔═══██╗██╔══██╗██║ ██╔╝██╔════╝██║     ██╔═══██╗██║    ██║██╔════╝
██╔██╗ ██║╚█████╔╝██╔██╗██║    ██║ █╗ ██║██║   ██║██████╔╝█████╔╝ █████╗  ██║     ██║   ██║██║ █╗ ██║███████╗
██║╚██╗██║██╔══██╗██║╚████║    ██║███╗██║██║   ██║██╔══██╗██╔═██╗ ██╔══╝  ██║     ██║   ██║██║███╗██║╚════██║
██║ ╚████║╚█████╔╝██║ ╚███║    ╚███╔███╔╝╚██████╔╝██║  ██║██║  ██╗██║     ███████╗╚██████╔╝╚███╔███╔╝███████║
╚═╝  ╚═══╝ ╚════╝ ╚═╝  ╚══╝     ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚══════╝ ╚═════╝  ╚══╝╚══╝ ╚══════╝
```

# ⚡ My n8n Workflows Collection

**Automate Everything · Build Fast · Ship Faster**

[![n8n](https://img.shields.io/badge/Built%20with-n8n-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![Workflows](https://img.shields.io/badge/Workflows-Growing%20Daily-brightgreen?style=for-the-badge&logo=github-actions&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange?style=for-the-badge)]()

*A curated collection of production-ready n8n workflows — built, tested, and battle-hardened.*

</div>

---

## 🗂️ What's Inside

```
📦 n8n-workflows/
 ┣ 📂 ai-agents/          → LLM-powered automation workflows
 ┣ 📂 data-pipelines/     → ETL & data transformation flows
 ┣ 📂 Chatbots/           → Slack bots, Telegram bots..
 ┣ 📂 integrations/       → Third-party API connections
 ┣ 📂 scrapers/           → Web scraping & data collection
 ┗ 📂 utils/              → Reusable sub-workflows & helpers
```

> 📌 **Each workflow includes:** a ready-to-import `.json` file + a `README.md` explaining what it does and how to run it.

---

## 🚀 Quick Start

### 1️⃣ Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/n8n-workflows.git
cd n8n-workflows
```

### 2️⃣ Import a workflow into n8n

```
1. Open your n8n instance
2. Go to Workflows → Import from File
3. Select any .json file from the repo
4. Configure your credentials
5. 🚦 Activate and let it run!
```

### 3️⃣ Prerequisites

- **n8n** — Self-hosted or n8n Cloud
- Node.js `>=18.x` (for self-hosted)
- Some workflows require API keys — listed in each workflow's own README

---

## ⭐ Featured Workflows

| # | Workflow | Category | Integrations | Difficulty |
|---|----------|----------|--------------|------------|


> 💡 **Pro tip:** Every workflow has `// CUSTOMIZE HERE` comments inside nodes so you can adapt them in minutes.

---

## 🧠 Design Philosophy

```
✅  Modular       — Every workflow runs independently
✅  Documented    — A README ships with everything
✅  Error-handled — Nothing fails silently
✅  Version-controlled — Full Git history for every change
```

---

## 📖 Workflow Template

When adding a new workflow, follow this structure:

```markdown
## 🔄 Workflow Name

**What it does:** One sentence describing the workflow.

**Trigger:** Manual / Webhook / Schedule (e.g. every hour)

**Integrations used:**
- Service A
- Service B

**Setup:**
1. Import the .json file
2. Add your credentials
3. Edit the config nodes
4. Test and activate!

**Notes:** Anything important to know.
```

---

## 🤝 Contributing

Got a cool workflow? **Share it!** 🙏

```bash
# Fork → Branch → Add your workflow → PR
git checkout -b feat/my-awesome-workflow
# Add the .json + README
git commit -m "feat: add [workflow-name]"
git push origin feat/my-awesome-workflow
# Open a Pull Request 🚀
```

**Contribution guidelines:**
- Workflow must work on n8n v1.0+
- Include a README with every workflow
- Test before submitting
- No hardcoded secrets — use n8n Credentials or env vars

---

## 🛡️ Security

> ⚠️ **Important:** Never commit API keys or passwords inside workflow files.  
> Always use n8n's Credentials system or environment variables.

---

## 📊 Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/n8n-workflows?style=social)
![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/n8n-workflows?style=social)
![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/n8n-workflows?color=red)
![Last commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/n8n-workflows?color=green)

</div>

---

## 📬 Connect

<div align="center">

Got a question? Found a bug? Want to collab?

[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/YOUR_USERNAME)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/YOUR_HANDLE)

</div>

---

<div align="center">

**Built with ❤️ + ☕ + way too many late nights**

*If this repo helped you — drop a ⭐ Star! It takes 2 seconds and means a lot. 😄*

</div>
