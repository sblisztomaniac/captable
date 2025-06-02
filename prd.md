# CapTableGuru – PRD

## 📌 Project Overview

**CapTableGuru** is a lightweight, AI-assisted cap table intelligence module for OpenCapStack. It helps founders, early employees, and angel investors understand, simulate, and optimize cap table structures — without needing a background in venture finance.

This module allows users to visualize dilution, model SAFEs and convertible notes, understand pro-rata rights, and project funding scenarios — all through a clean UI and conversational agent.

---

## 🧭 Goal

> Empower early-stage builders and startup teams to **simulate equity outcomes** and **avoid costly mistakes** when fundraising.

- Reduce dependency on spreadsheets or expensive advisors.
- Provide venture-grade clarity with no financial jargon.
- Seamlessly plug into OpenCapStack for full-stack equity management.

---

## 🧑‍🎯 Target Users

| Persona         | Pain Point                                       | How We Solve It                          |
|-----------------|--------------------------------------------------|------------------------------------------|
| First-time founder | Struggles to model dilution across rounds      | Visual and AI-assisted dilution models   |
| Angel investor  | Doesn’t know how much equity they actually hold | Position-clarity and round simulators    |
| Employee #3     | Doesn’t know exit value of their ESOP            | Scenario planner and exit simulation     |
| University hacker | Wants to learn cap tables without finance talk | Interactive, gamified agent assistant    |

---

## ⚙️ Core Features

1. **Cap Table Visualization**
   - Live, editable table for equity ownership
   - Pie chart + stacked timeline of dilution events

2. **SAFE & Convertible Note Modeling**
   - Input terms like discount, valuation cap, MFN
   - Auto-calculate post-money outcomes

3. **Dilution Simulator**
   - Add new rounds (Pre-Seed to Series C+)
   - Visualize % change per stakeholder
   - Show pre vs post round cap table

4. **AI Copilot**
   - Chat-style interface
   - Ask: “What happens if I raise $500k at $5M cap?”
   - Translate complex terms into simple language

5. **Exit Scenario Planning**
   - Simulate exits (acquisition, IPO)
   - Show final payouts for each stakeholder
   - Calculate ROI for investors

6. **Education Layer (Mini Academy)**
   - Embedded tutorials: “What’s a SAFE?”, “What is dilution?”
   - Every field explains itself

7. **Export Options**
   - Download PDF summary
   - Export to Google Sheets or .csv
   - Shareable cap table link for teams/investors

---

## 🔌 Integrations

- OpenCapStack backend
- Stripe for checkout & licensing (if paid)
- Notion or Google Docs export (optional)

---

## 🔐 Access Control

- Tiered: Free for learners, Premium for export/simulation
- Admin access to manage cap tables
- Invite teammates or investors (view-only)

---

## ⛳ Success Criteria

| KPI                          | Target                         |
|-----------------------------|--------------------------------|
| First-Time User Completion  | 80% create first simulation    |
| Agent Accuracy               | >90% for equity math prompts   |
| Engagement Rate             | 2+ scenarios run per session   |
| Virality                    | 1.2x shares per user           |
| Retention (30d)             | 40%                            |

---

## 🛠 Tech Stack

- Frontend: Streamlit or Next.js (React) + Tailwind
- Backend: Supabase or Firebase
- AI: GPT-4 or Claude Sonnet via OpenRouter
- Visualization: Plotly / D3.js (TBD)

---

## 🧭 Roadmap

| Phase       | Milestone                                  | ETA         |
|-------------|---------------------------------------------|-------------|
| Phase 1     | Cap table visual + round editor             | Week 1–2    |
| Phase 2     | Dilution simulator + export/share           | Week 3–4    |
| Phase 3     | AI Copilot + SAFE modeling                  | Week 5–6    |
| Phase 4     | Mini Academy + exit planner                 | Week 7–8    |
| Phase 5     | Team features + Stripe integration          | Week 9–10   |

---

## 🧪 Bonus Use Cases

- University founder bootcamps
- Incubator equity planning tool
- Investor onboarding kits
- Product Hunt-style launch simulator

---

## ✍️ Authors & Credits

- Product: [Your Name]
- Vision: Toby Morning (AI-Native Studio)
- Tech: Nova x AI Agents x OpenCapStack
