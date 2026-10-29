# BESS Energy Optimization Engine – Numerical Proof of Concept

## Asset Overview
* **Asset Type:** Python-Based Linear Programming (LP) Optimization Core
* **Mathematical Solver:** scipy.optimize.linprog (Method: 'highs')
* **Target Application:** Data Center Infrastructure / Battery Storage (BESS)
* **Market Architecture:** European Power Exchange (EPEX Spot) Day-Ahead

---

## 1. Core Technical Configuration
* **Time Step Resolution:** 1 Hour Interval (8760 steps per annum)
* **Base BESS Configuration:** 80 MWh Storage Capacity (Configurable 1-200 MWh)
* **Operational Boundary:** Physical Grid Ingress/Egress Restriction

---

## 2. Immutable Mathematical Constraints (Hard-Coded Bounds)
* `MAX_GRID_CHARGING_POWER_MW = 15.0 MW` (Strict Upper Bound)
* The 15.0 MW threshold is enforced as an unyielding physical restriction within the matrix bounds, safeguarding local grid transformer hardware under all load-shedding and arbitrage simulation sweeps.

---

## 3. Validated Simulation Results (EPEX Spot DE-LU Benchmark)
* **Simulation Horizon:** 168 Hours (Continuous Market Sweep)
* **Baseline Energy Cost (Unoptimized):** 121,351.49 EUR
* **Optimized Energy Cost (Engine Active):** 115,992.88 EUR
* **Net Financial Cost Reduction:** 5,358.62 EUR (**4.42% Efficiency Gain**)
* **Grid Constraint Integrity:** 100% Compliance (No 15.0 MW Violations)

---

## 4. Intellectual Property & Transfer Structure
* **Transaction Model:** Asset Purchase Agreement (Full IP Rights Transfer)
* **Legal Setup:** Clean international corporate framework ready for deployment.
* **Integrity Validation:** SHA-256 Validation Enabled for source code deployment.

---

## 5. Commercial Inquiries & M&A Screening
For technical due diligence requests, extended simulation logs, or to review the full brief under a standard Non-Disclosure Agreement (NDA), please contact the asset management desk directly:

📩 **Email:** centurion.ip.asset@proton.me
