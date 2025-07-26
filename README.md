# 🕸️ Agentic Web Scraper AI

An autonomous, agentic AI-powered web scraping framework that intelligently plans, scrapes, filters, and delivers structured information from the web based on the request made by users.

## 🚀 Project Overview

This project transforms a basic web scraper into a **multi-agent AI system** that:

- Understands natural language prompts like:
  > "Find the latest remote Python developer jobs on LinkedIn and Indeed, summarize the key requirements, and email me every Monday."
- Plans and executes multi-step tasks across websites
- Dynamically adapts to changes in website structure
- Delivers cleaned, filtered, and enriched data (e.g., email, Google Sheets, Notion)



## 🧠 Key Features

- 🗣️ **Natural Language Interface** – Give goals, not instructions.
- 🕵️ **Autonomous Agents** – Each task is handled by intelligent sub-agents.
- 🔄 **Adaptive Scraping** – Recovers from broken selectors using an LLM to re-parse pages.
- 📬 **Automated Delivery** – Email reports, push to Notion or upload to Sheets.
- 🧹 **Data Cleaning & Summarization** – Extract and summarize core information.
- 📅 **Scheduled or On-Demand Execution** – Run manually or via cron/Cloud scheduler.



## 🛠️ Tech Stack

| Component      | Tool/Library                         |
|----------------|--------------------------------------|
| Scraping       | Playwright / Puppeteer / BeautifulSoup |
| Agentic AI     | LangChain / CrewAI / OpenAgents       |
| LLM            | OpenAI GPT-4 (via API)                |
| Scheduling     | Python `schedule`, Airflow or `cron`  |
| Output         | SMTP (email), Google Sheets API, Notion API |

---

## 📦 Example Use Case: Job Scraper Agent

### Input Prompt

> "Get me the latest **remote** Python developer jobs from LinkedIn and Indeed, **posted in the last 5 days**. Summarize the requirements, group them by skills, and email the report every Monday at 9am."

### Agent Workflow
