# 🚀 Legacy AI Modernizer

> **Autonomous AI Software Modernization Agent** — Analyze. Recommend. Migrate.

An end-to-end AI-powered platform that analyzes legacy enterprise software, 
builds code graphs, recommends modernization strategies, estimates migration 
effort, and auto-generates phased migration plans using **Static Analysis**, 
**Code Graphs**, and **Google Gemini LLM**.

![Status](https://img.shields.io/badge/status-active-success)
![Python](https://img.shields.io/badge/python-3.10+-blue)
![React](https://img.shields.io/badge/react-18-61dafb)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📌 Overview

Modernizing legacy software is one of the biggest challenges enterprises face. 
**Legacy AI Modernizer** automates this entire workflow:

1. 🔍 **Analyze** — Deep static analysis of legacy source code (Python, Java, JS)
2. 🕸️ **Graph** — Build dependency & call graphs using NetworkX
3. 🧠 **Recommend** — AI-driven modernization strategy using the **6R Framework**
4. 📊 **Estimate** — Effort, cost, and timeline estimation
5. 📋 **Plan** — Auto-generated phased migration roadmap

---

## ✨ Features

- 📤 **Upload legacy code** (ZIP / folder / individual files)
- 🔬 **Static Analysis** — Complexity, code smells, metrics (LOC, classes, functions)
- 🕸️ **Code Graph Visualization** — Interactive dependency graph (ReactFlow)
- 🧠 **Gemini LLM Integration** — Smart modernization recommendations
- 🎯 **6R Framework** — Rehost, Replatform, Refactor, Rearchitect, Rebuild, Replace
- ⏱️ **Effort Estimation** — Person-days, cost, team size
- 📋 **Migration Plan Generator** — Phase-wise tasks & timeline
- 📚 **Project History** — All past analyses stored in DB
- 🎨 **Modern UI** — Tailwind CSS + Framer Motion + Dark theme

---

## 🏗️ Architecture



---

## 🛠️ Tech Stack

### Backend
- **Python 3.10+**
- **FastAPI** — REST API framework
- **SQLAlchemy** — ORM
- **SQLite** — Database
- **NetworkX** — Code graph building
- **Tree-sitter / AST** — Static analysis
- **Google Gemini API** — LLM reasoning
- **Pydantic** — Data validation
- **Uvicorn** — ASGI server

### Frontend
- **React 18** + **Vite**
- **Tailwind CSS** — Styling
- **React Router** — Routing
- **Axios** — API calls
- **Recharts** — Charts
- **ReactFlow** — Graph visualization
- **Framer Motion** — Animations
- **Lucide React** — Icons

---

## 📁 Project Structure



---

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Node.js 18+
- Google Gemini API Key → [Get it here](https://aistudio.google.com/app/apikey)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/legacy-ai-modernizer.git
cd legacy-ai-modernizer

cd backend
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Mac/Linux
pip install -r requirements.txt

cd frontend
npm install
npm run dev