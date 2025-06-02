# 🧠 CapTableGuru Agile Sprint Plan

## 🎯 Goal
Build a functional MVP for CapTableGuru — a cap table simulation + AI assistant tool — in 5 hours.

---

## 👥 Team & Stack

- **Team**: Solo (AI-assisted)
- **Stack**: 
  - Backend: Supabase
  - Frontend: Streamlit or Flask
  - AI: OpenAI / Claude via API
  - Deployment: Streamlit Sharing / Render / Vercel

---

## 🕐 Sprint Breakdown (5 Hours)

### 🔹 Hour 1: Setup & Scaffolding

**Goal**: Base structure, Supabase schema, user auth

- [ ] Clone Streamlit/Flask starter repo
- [ ] Connect Supabase project
- [ ] Add tables: `users`, `cap_tables`, `rounds`
- [ ] Create login/signup UI
- [ ] Test RLS policies

**Checkpoint**: Can login and create a blank cap table.

---

### 🔹 Hour 2: Cap Table Logic

**Goal**: Manual entry of stakeholders and equity math

- [ ] Add stakeholder creation (founders only)
- [ ] Input: shares or %
- [ ] View: ownership breakdown
- [ ] Simulate one funding round (Seed)

**Checkpoint**: Basic cap table math and visuals.

---

### 🔹 Hour 3: AI Assistant

**Goal**: Ask equity questions, get GPT-powered answers

- [ ] Add AI chat interface
- [ ] Feed user cap table data into prompt
- [ ] Handle queries like:
  - “What’s my dilution at $5M pre?”
  - “What if I raise $2M post-money?”

**Checkpoint**: Chat returns dynamic cap table analysis.

---

### 🔹 Hour 4: Multi-Round + Exit Simulations

**Goal**: Model Series A and exit scenarios

- [ ] Add multi-round flow
- [ ] Store in `scenarios` table
- [ ] Compute cap table after each round
- [ ] Add exit simulation (valuation input, payout split)

**Checkpoint**: Can model Seed → Exit journey.

---

### 🔹 Hour 5: Polish & Deploy

**Goal**: Clean UI + deploy working MVP

- [ ] Add styling (Streamlit theme or Tailwind)
- [ ] Add export to CSV
- [ ] Deploy to chosen host
- [ ] Record walkthrough

**Checkpoint**: MVP live and shareable.

---

## 🧪 Optional Bonuses (Time Permitting)

- [ ] Sample cap table for demo
- [ ] Invite flow (collaborators)
- [ ] Save AI chat history

---

## 📦 Final Deliverables

- 🔗 Live MVP URL  
- 📽️ Demo walkthrough (Loom or GIF)  
- 📄 PRD + Sprint Plan + Data Model in GitHub

