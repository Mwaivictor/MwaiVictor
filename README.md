<div align="center">

<h1>Victor Mwai</h1>

<p><b>Clinical Medicine &nbsp;·&nbsp; Data Science &nbsp;·&nbsp; Healthcare Analytics &nbsp;·&nbsp; Applied AI</b></p>

<p>Clinically trained, building data and AI skills to solve healthcare problems in Africa.<br/>Nairobi, Kenya &nbsp;·&nbsp; Open to on-site, hybrid and remote roles</p>

<a href="https://www.linkedin.com/in/mwai-victor-brian-a0273b272/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://dev.to/code_with_mwai"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=flat-square&logo=devdotto&logoColor=white" alt="dev.to"/></a>
<a href="https://medium.com/@mwaivictorbrian68"><img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="mailto:mwaivictorbrian68@gmail.com"><img src="https://img.shields.io/badge/Email-0E7490?style=flat-square&logo=maildotru&logoColor=white" alt="Email"/></a>

</div>

<br/>

## About

I trained in Clinical Medicine and work in hospital settings, from outpatient clinics to inpatient wards. That experience showed me how much clinical data is collected every day and how little of it is turned into decisions.

Alongside clinical training I have built practical skills in data analysis, SQL, business intelligence and machine learning, and I use them professionally for data analysis and client reporting. I am now applying those skills to health data: readmission risk, disease surveillance, health information systems and, over time, medical imaging.

My aim is to be the person in the room who understands both the ward and the dataset, and to build tools that work in resource-limited African health systems, not only in well-funded ones.

<br/>

## Focus areas

| Demonstrated in my work and repositories | Actively learning and building |
|:---|:---|
| Python and Pandas for data cleaning and analysis | Machine learning for clinical prediction |
| SQL and PostgreSQL: schema design, cleaning pipelines, analytical queries | Disease surveillance and forecasting (malaria in Kenya) |
| Power BI and Excel dashboards for decision makers | Medical imaging AI |
| Leakage-aware, reproducible ML workflows in scikit-learn | API development and data engineering fundamentals |
| Healthcare data interpretation from a clinical perspective | Health informatics and health information systems |

<br/>

## Featured projects

### [Predicting Hospital Readmission in Diabetes](https://github.com/Mwaivictor/diabetes-readmission-prediction)
`Python` `scikit-learn` `pandas` `Jupyter` `pytest`

**Problem.** Patients with diabetes are frequently readmitted. A discharge team with limited staff needs to know which patients to prioritise for medication review, education and early follow-up.

**What I built.** A reproducible, leakage-aware ML study on the UCI Diabetes 130-US Hospitals dataset (99,343 encounters after excluding deaths and hospice discharges). It includes a column-by-column leakage review, a patient-grouped train/test split so no patient appears in both sets, a majority-class baseline, logistic regression and gradient boosting, calibration, bootstrap confidence intervals, a pre-specified decision threshold and a subgroup audit.

**Result.** ROC-AUC of 0.679 (95% CI 0.670 to 0.687) for logistic regression and 0.691 for gradient boosting on 19,870 held-out encounters. Both models are well calibrated but only moderately discriminating, and the write-up states that plainly. The project is framed as educational and not clinically validated.

<br/>

### [Pharmacy Sales Analytics: PostgreSQL to Power BI](https://github.com/Mwaivictor/pharmacy_analytics)
`PostgreSQL` `SQL` `Power BI`

**Problem.** A multi-branch Kenyan pharmacy chain (case study dataset, 6,000 order lines across 11 branches) had transaction data but no trusted view of revenue, margin, product and channel performance.

**What I built.** A layered PostgreSQL warehouse (staging, clean, 9 reporting views) with 30+ data-quality checks before cleaning and 15 reconciliation tests after, feeding a three-page Power BI dashboard and 13 standalone SQL analyses.

**Finding.** Revenue was flat while order counts rose, meaning customers bought more often but spent less per order. Margin and revenue rankings across branches did not agree.

<br/>

### [Safari Connect: Booking Analytics Pipeline](https://github.com/Mwaivictor/safari_connect)
`PostgreSQL` `SQL` `Power BI`

**Problem.** A Nairobi bus and matatu booking platform (case study) kept a year of bookings in a messy shared spreadsheet and needed answers on route profitability, cancellations and peak travel times.

**What I built.** A PostgreSQL cleaning pipeline that resolves 23 distinct data-quality problems, analysis with CTEs and window functions, reporting views and indexes, and a two-page Power BI board dashboard with written recommendations.

<br/>

### [Sunrise Supermarket: Relational Database Design](https://github.com/Mwaivictor/sunrise_supermarket_sql)
`PostgreSQL` `SQL`

**Problem.** Point-of-sale exports cannot answer questions about repeat customers, product movement or stuck orders.

**What I built.** A normalised schema for a fictional Kenyan supermarket, built from an empty PostgreSQL instance, with constraint-enforced integrity, schema migrations and 14 business queries spanning aggregation and four-table joins.

<br/>

### In progress

- **Malaria risk prediction and forecasting for Kenyan counties:** next-month transmission forecasting using county-level data. Repository coming soon.
- **Kenya maternal and child health analytics:** an end-to-end project on inequalities in MCH indicators using PostgreSQL, Python and Power BI. Repository coming soon.

<br/>

## Technical stack

| Area | Tools |
|:---|:---|
| Languages | Python, SQL |
| Data analysis | pandas, NumPy, SciPy, Jupyter |
| Machine learning | scikit-learn (pipelines, logistic regression, gradient boosting, calibration, cross-validation) |
| Databases | PostgreSQL (incl. Aiven cloud), relational modelling, CTEs, window functions, views, indexes |
| Visualisation and BI | Power BI (Power Query, DAX, data modelling), Excel (PivotTables, dashboards), Matplotlib |
| APIs and integration | REST APIs with Python `requests`, JSON processing |
| Developer tools | Git, GitHub, VS Code, pytest, Agile and Jira |

<br/>

## Research interests

- AI for healthcare in Africa and resource-limited settings
- Clinical decision support and risk prediction
- Disease surveillance and epidemiological forecasting
- Medical imaging AI
- Health information systems and healthcare data quality
- Applied, honestly evaluated machine learning: calibration, fairness audits and leakage control

<br/>

## Writing

I write about data analysis, SQL, Power BI and machine learning on [dev.to](https://dev.to/code_with_mwai) and [Medium](https://medium.com/@mwaivictorbrian68).

<br/>

## GitHub activity

<p align="left">
  <img src="https://streak-stats.demolab.com/?user=Mwaivictor&hide_border=true&theme=transparent&ring=0E7490&fire=0E7490&currStreakLabel=0E7490" alt="GitHub contribution streak" height="165"/>
</p>

<img src="https://komarev.com/ghpvc/?username=Mwaivictor&style=flat-square&color=0e7490&label=Profile+views" alt="Profile views"/>

<br/><br/>

## Get in touch

I am open to roles and collaborations in healthcare analytics, health informatics, data science and AI for health, particularly work focused on African health systems.

[LinkedIn](https://www.linkedin.com/in/mwai-victor-brian-a0273b272/) &nbsp;·&nbsp; [dev.to](https://dev.to/code_with_mwai) &nbsp;·&nbsp; [Medium](https://medium.com/@mwaivictorbrian68) &nbsp;·&nbsp; [GitHub](https://github.com/Mwaivictor)
