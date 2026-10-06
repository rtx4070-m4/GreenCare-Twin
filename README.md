# GreenCare Twin 🏥🌱

> **AI Digital Twin for Sustainable Hospitals**  
> *Balancing Patient Care & Planetary Health*

**GreenCare Twin** is a multi-disciplinary capstone project combining AI in healthcare, sustainability development management, predictive analytics, operations research, and strategic management. It serves as a privacy-preserving AI-powered digital twin for hospitals, helping decision-makers simultaneously improve patient care quality, control costs, and reduce environmental impact.

---

## 🚀 Core Idea & Pillars

The project addresses the dual challenge of delivering excellent patient care while reducing healthcare's heavy environmental footprint (greenhouse gas emissions, energy consumption, water use, and medical waste). 

* **🧠 Clinical Intelligence:** Predicts patient demand, length of stay (LOS), readmission risks, and staffing requirements using tools like PyHealth and Prophet.
* **🍃 Sustainability Intelligence:** Calculates real carbon, energy, and waste footprints via Life Cycle Assessment (LCA) using openLCA.
* **⚖️ Smart Optimization:** Utilizes operations research models (PuLP and CVXPY) to generate Pareto fronts and balance multi-objective trade-offs between care quality, cost, and carbon emissions.

---

## 🔄 End-to-End Workflow

```text
Synthea (Synthetic Patients)
        ↓
   MySQL / PostgreSQL Database
        ↓
┌───────────────────┬────────────────────────────┐
│   Member 1 (You)  │        Member 2            │
│  Clinical AI      │  openLCA + Optimization    │
│  PyHealth+Prophet │  PuLP + CVXPY              │
└───────────────────┴────────────────────────────┘
        ↓
   Database (Results + Predictions)
        ↓
   Member 3 → Tableau Dashboard + Docker + Strategy
        ↓
   Hospital Decision Maker
```

1. **Data Generation:** Synthea generates synthetic Electronic Health Record (EHR) data combined with energy/supply chain data and openLCA impact factors.
2. **Clinical Intelligence (Member 1):** PyHealth and Prophet models forecast patient demand, length of stay, and clinical risks while incorporating fairness constraints.
3. **Sustainability & Operations Research (Member 2):** openLCA impact models and optimization scripts (PuLP + CVXPY) determine carbon/waste metrics and generate trade-off Pareto frontiers.
4. **Dashboard & Strategy (Member 3):** Tableau views, Docker containerization, and data security layers feed into an interactive web prototype for hospital leadership.

---

## 👥 Team Division & Responsibilities

| Team Member | Focus Area | Key Contributions |
| :--- | :--- | :--- |
| **Member 1 – You** | Healthcare & Clinical AI | • Synthea & PyHealth models<br>• Demand & LOS forecasting<br>• Clinical risk & fairness models |
| **Member 2** | Sustainability & Operations Research | • openLCA impact modeling<br>• Multi-objective optimization (PuLP + CVXPY)<br>• Pareto front analysis |
| **Member 3** | System, Security & Strategy | • MySQL & Docker deployment<br>• Tableau dashboards<br>• Privacy/security layer & financial roadmap |

---

## 💻 Tech Stack

* **Frontend/Dashboard:** HTML5, Tailwind CSS, Chart.js, Font Awesome
* **Clinical AI:** PyHealth, Prophet, Synthea
* **Sustainability & OR:** openLCA, PuLP, CVXPY
* **Infrastructure & Visualization:** Tableau, MySQL/PostgreSQL, Docker, GitHub Pages

---

## 🌐 Live Demo

You can view the live project dashboard hosted on GitHub Pages:  
🔗 **[https://rtx4070-m4.github.io/GreenCare-Twin/](https://rtx4070-m4.github.io/GreenCare-Twin/)**
