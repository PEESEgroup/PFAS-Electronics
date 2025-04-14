# **PFAS-Electronics**

This repository contains tools and datasets for analyzing PFAS removal from electronics and semiconductor manufacturing wastewater, incorporating spatiotemporal characteristics and future scenario modeling.

---

## **1. Overview and Instructions**

This repository supports scenario-based Life Cycle Assessment (LCA) and economic analysis of PFAS treatment technologies under various industrial development pathways.

### 🔮 **Future Scenarios**

- The **IMAGE 3.2** model is used as the primary Integrated Assessment Model (IAM) scenario source. Additional IAM models are referenced where appropriate.
- The **Premise** tool is applied to integrate IAM scenario outputs into the LCA database.

### ♻️ **LCA Database**

- **Baseline data source**: [Ecoinvent 3.8](https://www.ecoinvent.org/).
- LCA analyses are performed using IAM-informed LCA databases generated via **Premise**, **Brightway**, and **Python**.
- **Database features**:
  - Temporal (year-specific) and regional customizations.
  - Tailored for wastewater treatment analysis in electronics and semiconductor sectors.

### 💰 **Economic Model**

- An economic model estimates the treatment cost of three PFAS removal technologies:
  - **Granular Activated Carbon (GAC)**
  - **Ion Exchange Resin (IER)**
  - **Reverse Osmosis (RO) membranes)**
- Cost assessments are scenario-dependent and regionally resolved.

---

## **2. Repository Structure**

### 📁 **Code**

Includes Python scripts for:

- **Integrating IAM & LCA data** using Premise and Brightway.
- **Modeling electronics and semiconductor growth**:
  - PFAS emission projections based on market development.
  - CAGR-based scaling and regional factor adjustments (labor, energy, etc.).
  - Compressed data files (Excel) provide supporting variables and assumptions.

🔗 Reference: [Premise GitHub Documentation](https://github.com/polca/premise)

### 📊 **Data**

Contains all supporting datasets used in the study:

- Regional market development and emission projections.
- Scenario-based LCA results.
- Economic assessments for PFAS removal technologies.
- Analysis of regional treatment standard impacts.

---

## **3. Tool Dependencies**

To run the full pipeline, the following tools and versions are recommended:

| Tool          | Minimum Version | Notes                                    |
|---------------|------------------|------------------------------------------|
| Python        | 3.9              | Required for Premise and Brightway       |
| IMAGE         | 3.2              | IAM scenario source                      |
| Premise       | 2.3              | Compatible with Python 3.9+              |
| Brightway     | 2.5              | LCA modeling environment                 |
| Ecoinvent     | 3.8              | Baseline LCA database                    |

---

