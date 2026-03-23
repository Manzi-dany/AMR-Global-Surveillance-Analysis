📊 Project Ecosystem

🔗 Live Tableau Dashboard
🚀 Personal Portfolio Website
💼 Professional LinkedIn Profile


🔬 Project Overview
As a Biotechnology graduate (University of Rwanda) and Certified Data Analyst (ALX Africa), I developed this end-to-end data pipeline to analyze Antimicrobial Resistance (AMR) trends across all 6 WHO global regions from 2017 to 2020.
This project addresses a critical public health challenge — normalizing fragmented global health surveillance data to identify where the "silent pandemic" of AMR is most under-reported, and what that means for policy decisions in low-resource settings like Rwanda and Sub-Saharan Africa.

🛠️ Technical Stack
ToolPurposePython (Pandas)Automated ETL — combining 10 WHO CSV files into one clean datasetMySQLRelational database queries for deep AMR trend analysisExcelPivot tables, charts, and data cleaning dashboardTableauGeospatial risk-assessment dashboard for public health decision-makingPower BIInteractive executive summary dashboardGit/GitHubProfessional version control for reproducible research

💡 Key Clinical Insight: The "Surveillance Gap"
The core finding of this analysis is the disparity between Resistance Levels and Reporting Density:
1. 📈 Mature Infrastructure (Americas & Europe)
These regions show significantly higher average resistance values (Avg.NumericValue≈700–870Avg. Numeric Value \approx 700\text{--}870
Avg.NumericValue≈700–870). This reflects
mature surveillance infrastructure (GLASS) capturing a high volume of laboratory isolates — not necessarily higher resistance rates.
2. ⚠️ The African Context (Low-Detection Artifact)
While Africa shows a lower reported average (<100< 100
<100), this analysis identifies this as a
"Reporting Gap" — not a safety advantage. This reflects:

Lack of integrated digital health systems
Limited diagnostic laboratory infrastructure
Under-investment in AMR surveillance programs


Public Health Implication: Africa's low AMR scores are a data quality problem, not a clinical reassurance. This distinction is critical for organizations like WHO, RBC Rwanda, Partners in Health, and Minisanté making resource allocation decisions.


🔍 Key Findings
RegionAvg ScoreTrendInterpretationEurope734.97📈 Rapidly improvingStrong GLASS participationAmericas874.09📈 High reportingMature surveillance systemE. Mediterranean41.04📊 ModerateGrowing infrastructureAfrica25.34⚠️ Low reportingCritical surveillance gapSE Asia25.06⚠️ Low reportingNeeds urgent investmentW. Pacific134.58📊 ModerateMixed infrastructure

📂 Repository Structure
AMR-Global-Surveillance-Analysis/
│
├── 📁 data/
│   ├── amr_combined_dataset.csv        # Cleaned & combined dataset (666 rows)
│   ├── AMRGLASS_COORD02.csv            # Raw WHO files (10 files)
│   ├── AMRGLASS_SURVL01.csv
│   └── ...
│
├── 📁 notebooks/
│   └── AMR-Global-Surveillance-Analysis.ipynb   # Python analysis engine
│
├── 📁 sql/
│   └── amr_analysis.sql                # All SQL queries used
│
├── 📁 excel/
│   └── AMR_Analysis_Project.xlsx       # Excel dashboard with pivot tables
│
├── 📁 images/
│   └── Image for AMR Dashboard tableau.png
│
└── README.md

🚀 How to Run
bash# Clone the repository
git clone https://github.com/yourusername/AMR-Global-Surveillance-Analysis

# Install Python dependencies
pip install pandas matplotlib seaborn mysql-connector-python jupyter

# Run the analysis notebook
jupyter notebook notebooks/AMR-Global-Surveillance-Analysis.ipynb
MySQL Setup:
sqlCREATE DATABASE amr_surveillance;
USE amr_surveillance;
-- Then import amr_combined_dataset.csv using Table Data Import Wizard

📦 Data Source
WHO Global Health Observatory — GLASS Dataset

🔗 https://www.who.int/data/gho
Years covered: 2017 — 2020
Regions: 6 WHO Regions (AFR, AMR, EMR, EUR, SEAR, WPR)
Total records: 666 rows across 10 indicator files
Indicators tracked:

AMR Coordination (National action plans)
Laboratory Quality Assurance
Surveillance enrollment and reporting




🌱 Why This Project Matters for Rwanda
Rwanda is one of the African countries working hardest to build AMR surveillance capacity through institutions like:

RBC (Rwanda Biomedical Centre)
Minisanté (Ministry of Health)
University of Rwanda

This analysis provides a data-driven baseline showing exactly where Rwanda and the broader AFR region stand in global AMR surveillance — and what investments are needed to close the gap with Europe and the Americas.

📩 Contact & Collaboration
I am a Biotechnology professional making a strategic transition into Healthcare Data Science, passionate about using data to solve Africa's most pressing public health challenges.
I am actively seeking opportunities in:

🏥 Public health data analysis
🧬 Biotech data science
🌍 Digital health systems
📊 Healthcare analytics

Open to: Internships | Volunteering | Graduate positions | Research collaborations

📧 Email: manzidany72@gmail.com
📍 Location: Kigali, Rwanda
🔗 LinkedIn: manzi-dany-b2842030b

🌐 Portfolio: portifolio-git-main-manzi-danys-projects.vercel.app



Built with ❤️ in Kigali, Rwanda | Dedicated to closing the AMR surveillance gap in Africa
