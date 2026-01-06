# ⚾ MLB Offseason Roster Optimization

### Los Angeles Angels — 2026 Season

This project models a **realistic MLB offseason strategy** for the Los Angeles Angels, optimizing roster construction to **maximize projected wins (WAR)** under payroll, roster size, and front-office constraints.

Unlike simple player rankings, this tool simulates **actual decision-making used by MLB front offices**, including trade limitations, free-agent rules, and positional requirements.

---

## 📌 Project Overview

The model builds an optimal **26-man roster** using Mixed-Integer Programming, integrating Fangraphs WAR projections with real-world constraints such as:

- Competitive Balance Tax (CBT) payroll limits  
- Trade capital limitations  
- Free-agent signing rules  
- Positional roster requirements  

The output includes not just a roster, but a **full on-field deployment plan**.

---

## ⚙️ Key Features

- **26-man roster optimization** using Mixed-Integer Programming (CVXPY)
- **Fangraphs WAR projections** for hitters and pitchers
- **CBT payroll constraint** (2026 Angels budget)
- Realistic front-office constraints:
  - Limited trade capital (depth-only trades)
  - Free-agent signing caps
  - Qualifying Offer (QO) restrictions
  - Positional minimums and maximums
  - No external DH acquisitions
- Automatic generation of:
  - Starting lineup vs RHP
  - 5-man rotation
  - Bullpen with defined roles
  - Bench roles

---

## 📊 Model Outputs

The model produces:

- Optimal **26-man roster**
- **Total projected WAR**
- **Payroll summary**
- Full depth chart:
  - Starting lineup
  - Bench
  - Rotation
  - Bullpen (with roles)

This allows rapid comparison of different offseason strategies by adjusting constraints.

---

## 🧠 Why This Matters

This project demonstrates:

- Optimization under real-world constraints  
- Sports analytics + baseball operations thinking  
- Data engineering and modeling skills  
- Ability to translate analytics into **actionable roster decisions**

The framework is modular and can be adapted to:
- Other MLB teams
- Different payroll strategies
- Additional leagues (e.g., NPB free agents)

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
2. Open the Notebook:
   notebooks/angels_offseason_optimizer.ipynb
3. Run all Cells Top to Bottom


---
## Tech Stack
- Python
- Pandas / NumPy
- CVXPY (Mixed-Integer Optimization)
- Fangraphs projection data

---
## 📈 Future Extensions
- Japanese (NPB) free-agent integration
- Platoon-based lineup optimization
- Injury risk and variance modeling
- Multi-year roster planning

--- 
## 📬 Author
Jose Smith

Sports Analytics | Optimization | Baseball Operations
