# AI-Technology-Job-Market-Analysis
Built a dynamic Excel dashboard to analyze AI and Technology job market data using Pivot Tables, Pivot Charts, Slicers, GETPIVOTDATA, and advanced Excel techniques. The dashboard provides insights into salary trends, hiring demand, work modes, job roles, countries, and job openings.

# Global AI Jobs Dataset

An Excel workbook containing a 90,000-row dataset of AI/ML job postings across 12 countries, along with pivot-table summaries and a chart dashboard.

## File

`project_.xlsx`

## Sheets

| Sheet | Contents |
|---|---|
| `DASHBOARD` | Chart dashboard with 5 visuals summarizing the dataset |
| `Sheet2` | Pivot table: salary/job-count stats by Job Role → Work Mode → Country |
| `Sheet3` | Pivot tables: averages/counts by Job Role, Country, Experience Level, Work Mode, and Company Size |
| `global_ai_jobs` | Raw data — 90,000 records × 37 columns |

### DASHBOARD charts
1. Average Salary by Job Role
2. Jobs by Country
3. Average Salary by Experience Level
4. Jobs by Work Mode
5. Jobs by Company Size

## Raw data columns (`global_ai_jobs`)

| Column | Description |
|---|---|
| `Id` | Unique record identifier |
| `Country` | Country of the job (12 countries: Australia, Brazil, Canada, France, Germany, India, Japan, Netherlands, Singapore, UAE, UK, USA) |
| `Job_Role` | Role title (e.g., AI Engineer, Data Scientist, ML Engineer, NLP Engineer, Research Scientist, Software Engineer AI, Data Analyst, Computer Vision Engineer) |
| `Ai_Specialization` | AI focus area (e.g., LLM, Computer Vision, NLP, MLOps, Reinforcement Learning, Generative AI, Analytics, Forecasting) |
| `Experience_Level` | Entry / Mid / Senior / Lead |
| `Experience_Years` | Years of experience |
| `Salary_Usd` | Base salary in USD |
| `Bonus_Usd` | Bonus in USD |
| `Education_Required` | Minimum education (Bootcamp, Diploma, Bachelor, Master, PhD) |
| `Industry` | Employer's industry sector |
| `Company_Size` | Startup / Small / Medium / Large / Enterprise |
| `Interview_Rounds` | Number of interview rounds |
| `Year` | Posting year (2020–2026) |
| `Work_Mode` | Remote / Hybrid / Onsite |
| `Weekly_Hours` | Average weekly working hours |
| `Company_Rating` | Employer rating (out of 5) |
| `Job_Openings` | Number of open positions for that listing |
| `Hiring_Difficulty_Score` | Difficulty of filling the role |
| `Layoff_Risk` | Estimated layoff risk (0–1) |
| `Ai_Adoption_Score` | Company's AI adoption level |
| `Company_Funding_Billion` | Company funding, in $ billions |
| `Economic_Index` | Country/region economic index |
| `Ai_Maturity_Years` | Years the company has worked with AI |
| `Offer_Acceptance_Rate` | % of offers accepted |
| `Tax_Rate_Percent` | Local income tax rate |
| `Vacation_Days` | Annual vacation days |
| `Skill_Demand_Score` | Demand score for the required skills |
| `Automation_Risk` | Risk of the role being automated |
| `Job_Security_Score` | Job security score |
| `Career_Growth_Score` | Career growth potential score |
| `Work_Life_Balance_Score` | Work-life balance score |
| `Promotion_Speed` | Speed of promotion score |
| `Salary_Percentile` | Salary percentile within the dataset |
| `Cost_Of_Living_Index` | Cost of living index for the location |
| `Employee_Satisfaction` | Employee satisfaction score |
| `COUNTRIES TOTAL` | Helper column (pivot support) |
| `JOB ROLES` | Helper column (pivot support) |

## Key summary figures (from `Sheet3`)

- **Total job records:** 90,000
- **Average salary:** ~$96,546
- **Highest salary:** ~$300,622 (per Sheet2 summary box)
- **Work mode split:** Onsite 30,233 · Remote 30,005 · Hybrid 29,762
- **Company size split:** roughly even across Startup, Small, Medium, Large, Enterprise (~18,000 each)
- **By experience level (avg. salary):** Entry ~$61,328 · Mid ~$77,412 · Senior ~$104,608 · Lead ~$142,319
- **By country:** roughly 7,350–7,600 records each across the 12 countries
- Highest-paying roles on average: Research Scientist (~$109,798) and Machine Learning Engineer (~$102,122); lowest: Data Analyst (~$69,429)
- Highest-paying country overall: USA (~$138,791 avg for AI Engineer role); lowest: India (~$44,982 avg for AI Engineer role)

## Suggested uses

- Compensation benchmarking for AI/ML roles by country, role, and experience level
- Analyzing remote/hybrid/onsite trends in AI hiring
- Exploring correlations between company size, funding, and salary
- Studying automation risk, job security, and career growth by role/specialization

## Notes

- Data appears synthetic/aggregated (uniform ~7,300–7,600 records per country, evenly distributed company sizes) — useful for practice analytics, dashboarding, or teaching rather than as verified real-world compensation data.
- `Sheet2` and `Sheet3` are pivot tables built from the `global_ai_jobs` sheet; `DASHBOARD` visualizes those pivots as charts.
