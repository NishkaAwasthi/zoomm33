# 🏎️ F1 Weekly Agent

An agentic AI workflow that tracks Formula 1 standings, race odds, and predictions — fully automated through **n8n**.

---

## 🧠 Overview

This project automates F1 insights using real-time data and AI summarization. Each week, it pulls data from APIs (like **Live Pulse** and **The Odds API**), analyzes upcoming race probabilities, and generates an email-ready summary with insights, predictions, and event highlights.

I built this as a fun side experiment to combine my two favorite things: **agentic AI workflows** and **Formula 1**.

---

## ⚙️ Tech Stack

- **n8n** — orchestration and automation  
- **RapidAPI (F1 Live Pulse)** — real-time race and driver data  
- **The Odds API** — prediction and betting insights  
- **OpenAI API** — summarization and HTML email generation  
- **Gmail / Google Sheets** integrations for output delivery  

---

## 🔁 Workflow Highlights

- Fetches latest race and driver data  
- Computes prediction probabilities  
- Generates an AI-written weekly email summary  
- Automatically sends updates via Gmail  

---

## 🚀 How to Use

1. Import the included `.json` file into your n8n workspace.  
2. Add your API credentials in the **HTTP Request** nodes.  
3. Configure your email/GSheet nodes.  
4. Run the workflow — or schedule it weekly.  

---

## 🧯 Issues to Fix

- [ ] Occasionally hits API rate limits from F1 Live Pulse  
- [ ] Parsing sometimes breaks if JSON response format changes  
- [ ] Email output styling could use better mobile formatting  
- [ ] Needs a retry node for failed API calls  
- [ ] Would be fun to auto-generate race memes from AI summaries 😎  

---

### Built by **Nishka Awasthi**  
*Just another side project I made because I got curious about what it would take for Max Verstappen to win the 2025 World Championship.*
