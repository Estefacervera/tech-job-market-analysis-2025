
# 💼 Tech Job Market Analysis – Roles, Skills & Benefits (2025)

This project analyzes the 2025 tech job market using a dataset of job postings to explore:
- Most in-demand roles
- Required technical skills
- Salary ranges
- Work modalities (Remote, Hybrid, Onsite)
- Leadership trends

---

## 🎯 Project Objective

The main goal is to generate actionable insights from tech job listings, and categorize them based on responsibilities, tools, and seniority levels.

---

## 🧰 Tools Used

- Power BI (visualization, modeling)
- Power Query (data transformation)
- Python in Power BI (role classification)
- N8n (automation)
- Google Gemini API (LLM for structured extraction)

---

## ⚙️ Data Processing Overview

- Role titles were classified into categories: **AI**, **Data**, **Software**, or **Other**
- Descriptions were processed using **Google Gemini** via N8n to extract:
  - Job category
  - Required studies
  - Work modality
  - Skills
  - Experience
  - Leadership

---

## 📊 Key Visuals

- Total job openings and average salary
- Job categories by count
- Salary vs experience
- Work modality distribution
- Most required technical skills

![Dashboard](images/dashboard_1.png)

---

## 📌 Insights

- 64% of roles are onsite
- Most jobs require 3–6 years of experience
- Top skills: Python, SQL, R, TensorFlow
- AI-related roles offer the highest salary on average

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `JobMarket2025.pbix` | Power BI dashboard with full analysis |
| `jobs_dataset.xlsx` | Raw dataset with original job postings |
| `LLM Analysis Jobs.xlsx` | Enriched dataset with structured outputs from LLM |
| `jobs categories.json` | N8n automation flow using Google Gemini |
| `README.md` | This project summary |

---

## 🔗 Related Links

- [View in Notion](https://www.notion.so/Tech-Job-Market-Analysis-2025-236ceee0eafa81d49d68feb7ec4ec681) 
- 

---

## 📬 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/estefania-cervera/) or follow me for more dashboards and automation use cases.
