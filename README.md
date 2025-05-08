
# Socialytics – AI-Powered Social Media Analytics Dashboard

[![Deploy](https://img.shields.io/badge/Deployed%20App-Click%20Here-blue)](https://socialytix-kappa.vercel.app/)
[![Demo Video](https://img.shields.io/badge/Watch%20Demo-YouTube-red)](https://www.youtube.com/watch?v=DUSaSaHtjDQ)
The chatbot might not work due to expiration of API Keys involved.

**Socialytics** is an AI-driven analytics platform designed to help content creators, marketers, and brands understand and optimize their social media performance. From global KPIs to real-time tracking and intelligent chatbot support, Socialytics transforms raw data into actionable insights.

---

##  Features

### Global Analytics

- Visualizes **overall engagement metrics** across all content types (posts, reels, stories, etc.).
- Includes **content-type breakdown** to pinpoint performance by format.
- Features an **AI-powered chatbot**, built with:
  - [Langflow](https://github.com/logspace-ai/langflow) for flow-based prompt design
  - [AstraDB](https://www.datastax.com/astra) for vector database
  - [Gemini 1.5 Flash API](https://deepmind.google/technologies/gemini/) for LLM-powered answering
- The chatbot can:
  - Answer questions about social media strategies
  - Query and analyze **dummy social media data** stored in AstraDB
  - Provide growth suggestions based on past data

---

### CSV-Based Analytics

- Users can upload a **CSV file** in the provided format.
- Automatically calculates:
  - Overall metrics: likes, comments, reach, impressions, etc.
  - Per-content-type metrics
- Simple interface and dynamic visualization of data

> 📎 Sample CSV included for reference!

---

### Real-Time Analytics

- Connect your social media account (mocked for demo).
- Displays **live metrics** such as:
  - Follower count
  - Likes, comments, shares per second/minute
  - Engagement trends using real-time graphs and counters
- Built for dynamic updates with smooth visual feedback

---

## Tech Stack

| Layer        | Tools / Services                               |
|--------------|------------------------------------------------|
| Frontend     | NextJs, TailwindCSS                             |
| AI / LLM     | Langflow, Gemini 1.5 Flash API                 |
| Vector DB    | AstraDB                                        |
| Analytics    | Chart.js
| Hosting      | Vercel                                         |

---

## Live Links

- **🚀 Deployed App:** [https://socialytix-kappa.vercel.app/](https://socialytix-kappa.vercel.app/)
- **📺 Demo Video:** [Watch on YouTube](https://www.youtube.com/watch?v=DUSaSaHtjDQ)

## Getting Started Locally
```bash
git clone https://github.com/yourusername/socialytics.git
cd socialytics

cd frontend
npm install
npm run dev
