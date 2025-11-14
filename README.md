# Data-Validation-Automation-Wipro (Ongoing)

## Overview
This project focuses on automating large-scale data validation processes within QA workflows using **Python, SQL, and Power BI**, along with Generative-AI–assisted development. The goal is to reduce manual effort, improve accuracy, and streamline quality checks for enterprise data pipelines.

This repository contains a generalized, non-confidential version of the automation workflow to demonstrate the logic, tools, and techniques used.

## Objectives
- Automate manual data validation steps performed during QA cycles.
- Compare datasets across multiple source systems using Python + SQL scripts.
- Build reusable functions for schema checks, duplicate detection, and reconciliation.
- Create a Power BI dashboard to visualize validation results, error trends, and QA metrics.
- Implement AI-assisted code generation (ChatGPT / GitHub Copilot) to accelerate development.

## Tech Stack
- **Python:** Pandas, NumPy, Logging, OS, Regex  
- **SQL:** Joins, aggregations, validation queries  
- **Power BI:** Error trends, test coverage, automation performance  
- **Tools:** Jupyter Notebook, VS Code, Git/GitHub, Generative AI tools  
- **Automation:** Scheduled runs / reusable python modules

## Workflow & Approach
### 1. Data Extraction
- Extract raw tables from source systems using SQL queries.
- Load into Pandas dataframes for processing.

### 2. Validation Checks (Python Modules)
- Schema validation (column names, datatypes)
- Duplicate & null check modules
- Primary key & foreign key integrity checks
- Row count comparison
- Business rule validation (config-driven)

### 3. Reconciliation Logic
- Source vs Target comparison
- Outlier detection  
- Exception reporting (export to CSV/Excel or database)

### 4. Dashboard Creation (Power BI)
- Validation summary  
- Pass/Fail status  
- Error frequency & trends  
- Automation time saved  

### 5. Automation & Scheduling
- Modular scripts for repeated runs  
- Automated log generation  
- Optional scheduler / cron job / task scheduler  

## Key Results & Impact (Generalized)
- Reduced manual validation time by **~50%** through automation.
- Increased accuracy of data checks and reduced human error.
- Provided visibility into QA health through interactive Power BI dashboards.
- Enabled faster release cycles with standardized validation workflows.

## Repository Structure
Data-Validation-Automation-Wipro/
├── data/ # sample (dummy) datasets
├── scripts/ # reusable python validation scripts
├── notebooks/ # EDA / workflow demonstration
├── assets/ # screenshots / dashboard visuals
└── README.md

## How to Use
1. Clone the repo:  
   `git clone https://github.com/Shephali8/Data-Validation-Automation-Wipro.git`

2. Install dependencies (if requirements.txt is included):  
pip install -r requirements.txt

3. Run validation modules using example scripts inside `scripts/`.

4. Review results inside the `output/` folder (if created).

## Notes on Confidentiality
This repository is a **safe**, **generalized**, and **anonymized** version of the automation project.  
It does **not** include any client data, proprietary code, or restricted information.

## Author
**Shephali Samadhiya**  
_Data Analyst | Python • SQL • Power BI • Generative AI_  

🔗 LinkedIn: https://www.linkedin.com/in/shephalisamadhiya  
🔗 GitHub: https://github.com/Shephali8
