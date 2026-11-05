# FORGE — AI-Powered Workforce Intelligence Platform

**Transforming Workforce Data into Skills, Career Intelligence & Future-Ready Decisions.**

FORGE is an AI-powered workforce intelligence platform designed to connect workforce data, occupational skills, career pathways, and organizational intelligence through an integrated ecosystem.

It brings together four interconnected modules — WORKTRACE, SKILL SHADOW, WORKFOLD, and LATTICE — to help understand workforce capabilities, analyze skill requirements, explore career scenarios, and support data-driven workforce planning.

---

## 🚀 Core Modules

### 1. WORKTRACE — Workforce Intelligence
- Analyzes workforce and occupational information.
- Connects occupations with tasks and capabilities.
- Provides workforce insights using structured datasets.
- Helps understand evolving workforce requirements.

### 2. SKILL SHADOW — Skills Intelligence
- Maps occupational skills and capabilities.
- Connects skills with workforce requirements.
- Helps identify skill relationships and capability patterns.
- Supports skill-based workforce analysis.

### 3. WORKFOLD — Career Intelligence
- Explores career pathways and occupational transitions.
- Supports career scenario analysis.
- Connects tasks, occupations, and capabilities.
- Helps users understand potential career directions.

### 4. LATTICE — Workforce Capability Intelligence
- Organizes occupational and capability relationships.
- Connects tasks, skills, and occupational structures.
- Supports capability-gap analysis.
- Provides structured workforce intelligence.

---

## 🧠 Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js, Vite, JavaScript |
| Backend | Python, FastAPI |
| Data Processing | Python, Pandas |
| API Communication | REST APIs |
| Database / Data Sources | Structured datasets and CSV files |
| Visualization | Interactive frontend dashboards |
| Version Control | Git & GitHub |

---

## 📊 Data Sources

FORGE uses structured occupational and workforce datasets, including:

- ESCO — European Skills, Competences, Qualifications and Occupations
- O*NET — Occupational Information Network
- U.S. Bureau of Labor Statistics (BLS)
- Greenhouse Job Postings
- Occupational and capability mapping datasets

These datasets support occupational analysis, skill relationships, workforce intelligence, and career exploration.

---

## 🏗️ Project Architecture

```text
FORGE/
│
├── frontend/
│   └── React + Vite Application
│
├── backend/
│   └── FastAPI Application
│
├── datasets/
│   ├── ESCO
│   ├── O*NET
│   ├── BLS
│   ├── Greenhouse
│   └── Workforce Mapping Data
│
├── README.md
└── Other project resources
```

---

## ⚙️ Installation & Setup

### Prerequisites

- Python 3.10+
- Node.js and npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Baljinder-22/FORGE.git
cd FORGE
```

### 2. Backend Setup

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install backend dependencies:

```bash
pip install -r requirements.txt
```

Start the backend:

```bash
uvicorn backend.api.main:app --reload
```

Backend API:

```text
http://127.0.0.1:8000
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

The frontend development server will display its local URL in the terminal.

### 4. Production Build

```bash
npm run build
```

---

## 🎯 Project Objectives

- Build an integrated workforce intelligence ecosystem.
- Connect occupations, skills, tasks, and capabilities.
- Enable data-driven workforce analysis.
- Explore career transitions and occupational scenarios.
- Identify capability gaps and workforce transformation signals.
- Support future-ready workforce planning.

---

## 🌟 Vision

FORGE aims to bridge the gap between workforce data, skills intelligence, and career decision-making.

By bringing occupational intelligence and capability mapping into one connected ecosystem, FORGE seeks to make workforce insights more accessible, structured, and actionable.

---

## 👩‍💻 Project

**Project Name:** FORGE  
**GitHub Repository:** [Baljinder-22/FORGE](https://github.com/Baljinder-22/FORGE)

*Building intelligence. Connecting capabilities. Shaping the future of work.*

