# OlympicsDataMigration
# 🔁 Data Migration & Transformation: GitHub → Azure Data Lake Gen2 → Databricks

## 📦 Overview

This project demonstrates a simple data migration pipeline where raw Olympic datasets were sourced from GitHub and migrated into Azure Data Lake Gen2.
---

## 🚀 Steps Performed

1. **Source Identification**  
   - Public CSV datasets related to the Tokyo Olympics.

2. **Data Ingestion**  
   - ✅ `medals.csv` and `entriesgender.csv` were directly copied from GitHub using HTTPS links.  
   - ✅ Remaining files were manually uploaded into the Azure Data Lake Gen2 container (`raw/`).

3. **Cloud Storage Setup**  
   - Azure Blob Storage Gen2 was configured to act as the centralized data lake.  
   - Files were organized and verified within the container.

![Screenshot (83)](https://github.com/user-attachments/assets/cd2f6e0f-464a-47e2-a023-b3c256d18f19)


## 🗂️ Files Used

| File Name            | Source          | Notes                    |
|----------------------|------------------|---------------------------|
| medals.csv           | GitHub (HTTPS)   | Medal tallies             |
| entriesgender.csv    | GitHub (HTTPS)   | Gender-based participation|
| athletes.csv         | Manual Upload    | Athlete metadata          |
| countries.csv        | Manual Upload    | Country codes/names       |
| sports.csv           | Manual Upload    | Sport classification      |
| events.csv           | Manual Upload    | Olympic event details     |

---

## 🧰 Tools & Technologies

- **Azure Blob Storage Gen2**
- **GitHub** (Data Source)
- **Azure Portal** (for manual file upload & storage management)

---

## 🧠 Learnings

- Performing lightweight data engineering without needing a full ETL pipeline tool  
- Migrating cloud-hosted public data to private cloud infrastructure

---

## 👩‍💻 Author

**Yashitha**  
4th Year CSE (Data Science)  
AMC Engineering College, VTU  
AWS Certified Cloud Practitioner ☁️

---

## 📌 Next Steps (Optional Enhancements)

- Automate the ingestion using Azure Data Factory  
- Create dimension/fact tables and load into Snowflake  
- Build a simple dashboard using Power BI or Streamlit

