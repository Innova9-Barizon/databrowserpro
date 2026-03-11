# JDE DataBrowser Pro

> A zero-install, single-file HTML data browser for **JD Edwards EnterpriseOne** — powered by the AIS REST API.

Built and distributed by **[Innova9 / ChatJDE](https://chatjde.ai)** · [contact@innova9.io](mailto:contact@innova9.io)

---

## What is this?

JDE DataBrowser Pro lets you browse, search, filter, and export any JD Edwards table or business view directly from your browser — no backend, no install, no dependencies. Just open the HTML file, connect to your AIS server, and start exploring your data.

---

## Features

- **Multi-tab browsing** — open multiple tables side by side, each in its own tab
- **Server-side search** — query the entire table using AIS `query.condition` (dot-notation `TABLE.ALIAS`), not just loaded rows
- **Row filters** — multi-condition filtering with highlight or filter-rows mode
- **Field search** — search column aliases and descriptions; filter or dim non-matching columns
- **Column management** — pin, hide, reorder (drag & drop), and resize any column
- **Grid formats** — save and restore column layouts per table
- **CSV export** — download visible columns and rows as a CSV file
- **Grid zoom** — scale the grid from 60% to 105%; below 80% descriptions collapse to hover tooltips
- **Dark / light mode** — toggle with persistent preference
- **Zero dependencies** — a single `.html` file, runs entirely in the browser

---

## Getting Started

### 1. Requirements

- A running **JD Edwards EnterpriseOne AIS Server** (Application Interface Services)
- Any modern browser (Chrome, Edge, Firefox, Safari)

### 2. Open the file

Save `JDE-DataBrowser-Pro.html` anywhere on your computer and open it in your browser. No web server needed.

### 3. Connect

Click **⚙ Connection** in the top bar and fill in:

| Field | Example |
|---|---|
| AIS Server URL | `http://192.168.1.10:6083` |
| Username | `JDE1` |
| Password | `••••••••` |
| Environment | `JDV920` |
| Role | `*ALL` *(default)* |

Click **Connect**. A green badge in the header confirms a successful session.

> Your credentials are used only to obtain an AIS token and are **never stored** beyond the current browser session.

### 4. Browse a table

Type a JD Edwards table or business view name in the search box (e.g. `F4101`, `F0101`, `F4211`) and click **▶ Browse**.

---

## Searching the Entire Table (Server-Side)

Open the **Row Filters** bar, add a condition with a field alias (e.g. `EDOC`) and a value, then click **🔍 Search Table**.



---

## License

This code is released into the **public domain** and may be freely used, modified, and distributed for any purpose — commercial or non-commercial. Attribution is appreciated but not required.

---

## About Innova9

We are not a typical consulting firm.

**Innova9** is an AI-first innovation company dedicated to reimagining how enterprise organizations — especially JD Edwards customers — interact with their own systems. We don't just implement software. We build intelligent experiences that make your ERP work for you, not the other way around.

We believe that every JD Edwards customer deserves AI-powered tools that are practical, fast to deploy, and built by people who deeply understand the platform. That's exactly what we deliver.

---

### 🤖 ChatJDE Vibe

**ChatJDE** ([chatjde.ai](https://chatjde.ai)) is our flagship AI platform for JD Edwards — and **Vibe** is our most powerful offering yet.

ChatJDE Vibe is an **app builder platform** that lets you design, generate, and publish fully functional applications on top of your JD Edwards Orchestrations — without writing a single line of traditional code. Point it at an Orchestration, and Vibe generates a production-ready app that your users can run directly, no development team required.

- **Build apps from Orchestrations** — turn any JDE Orchestration into a deployable, user-facing application in minutes
- **Publish & share** — apps are hosted and accessible to your team the moment you publish them
- **AI-assisted generation** — describe what the app should do and let Vibe build the UI, logic, and API wiring for you

> Vibe turns your Orchestrator investment into a self-service app ecosystem — faster than anything else on the market.
---

### 🔌 MCP Servers for JD Edwards

We build and operate **Model Context Protocol (MCP) Servers** that give AI models — Claude, GPT-4, Gemini, and others — direct, structured access to JD Edwards data and processes.

MCP Servers are the bridge between large language models and enterprise systems. Our JDE MCP Server exposes AIS endpoints as callable tools that any AI agent can use to:

- Browse and query JDE tables in real time
- Execute Orchestrations and form service requests
- Retrieve address book records, purchase orders, work orders, and more
- Integrate JDE into any AI workflow, chatbot, or agentic pipeline

This is the infrastructure that makes **true JDE AI agents** possible — and we've already built it.

---

### What Else We Do

- **AI Dashboard & Analytics** — real-time insights on top of your JDE data
- **Orchestrator Training & Consulting** — from zero to production-grade orchestrations
- **Supplier Onboarding & Self-Service Portals** — AI-assisted supplier collaboration
- **Secure API Tunnels** — safely expose your on-premise AIS server to cloud AI services
- **Custom AI Development** — if you can imagine it for JDE, we can build it

---

### Get in Touch

| | |
|---|---|
| 🌐 Website | [https://chatjde.ai](https://chatjde.ai) |
| 📧 Contact | [contact@chatjde.ai](mailto:contact@innova9.io) |
| 💼 LinkedIn | [linkedin.com/in/barizon](https://linkedin.com/in/barizon) |

---

*Let's build the future, together!*
