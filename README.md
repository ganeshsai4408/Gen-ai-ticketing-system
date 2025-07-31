<h1 align="center">🎫 Gen‑AI Ticketing System</h1>
<p align="center">AI-powered ticket management that handles your chaos, so you don't have to.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-blue" />
  <img src="https://img.shields.io/github/license/ganeshsai4408/Gen-ai-ticketing-system?style=flat-square" />
  <img src="https://img.shields.io/github/issues/ganeshsai4408/Gen-ai-ticketing-system" />
</p>

---

## 🧠 What It Does

A modern ticketing system backed by generative AI. This baby reads the ticket, understands its mood, sets its urgency, and routes it like a pro. All automatically.

---

## ⚡ Features

- 🎯 **Auto-Categorize Tickets**
- ⏱️ **AI-Powered Priority Detection**
- 🧭 **Smart Agent Routing**
- 📝 **Suggested Replies via LLM**
- 🧩 **Modular & Easily Extensible**

---

## 🛠️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/ganeshsai4408/Gen-ai-ticketing-system.git
cd Gen-ai-ticketing-system

# Install dependencies
npm install

# Add your environment variables
echo AI_API_KEY=your_ai_key >> .env
echo DB_URI=your_database_uri >> .env

# Run the dev server
npm run dev 
📂 Project Structure
pgsql
Copy
Edit
📦 src/
├── controllers/    → All route controllers
├── services/       → AI logic + integrations
├── routes/         → API endpoints
├── models/         → MongoDB (or other DB) schemas
├── utils/          → Utility functions
└── index.js        → Main app entry
🧪 API Endpoints
Method	Route	Description
POST	/tickets	Submit a new ticket
GET	/tickets	Fetch all tickets
GET	/tickets/:id	View ticket by ID
🤝 Contribution Guide
Wanna make it better? Hell yeah.

Fork it 🍴

Create a feature branch: git checkout -b feat/cool-feature

Commit like a legend: git commit -m "Add cool feature"

Push & PR

