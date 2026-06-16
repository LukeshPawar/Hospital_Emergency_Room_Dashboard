# 🏥 Hospital Emergency Room Dashboard

A data analytics dashboard built to uncover meaningful insights from Hospital Emergency Room data — helping stakeholders understand patient flow, wait times, departmental load, and satisfaction trends at a glance.

![Hospital Emergency Room Dashboard](<img width="1801" height="818" alt="Hospital Dashboard Final" src="https://github.com/user-attachments/assets/f7d44baa-addc-4372-b9f2-326e781bd748" />
)

---

## 📌 Project Overview

This project analyzes real-world Emergency Room data to answer key operational questions:

- How many patients visit the ER daily/monthly?
- What are the average patient wait times?
- Which departments receive the most referrals?
- How do satisfaction scores vary across age groups and patient types?
- What is the gender and race breakdown of ER patients?

The dashboard was built to support hospital administrators and healthcare analysts in making data-driven decisions to improve patient experience and resource allocation.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Hospital Emergency Room Data.csv` | Raw dataset containing 9,000+ ER patient records |
| `Hospital Dashboard Final .jpg` | Screenshot of the completed dashboard |
| `README.md` | Project documentation |

---

## 📊 Dataset

The dataset (`Hospital Emergency Room Data.csv`) contains **9,216 rows** of anonymized patient visit records with fields including:

- **Patient ID** — Unique identifier per visit
- **Date** — Date of ER visit
- **Patient Age** — Age of the patient
- **Patient Gender** — Gender of the patient
- **Patient Race** — Race/ethnicity of the patient
- **Department Referral** — Department the patient was referred to (e.g., General Practice, Orthopedics, Cardiology)
- **Admission Type** — Whether the patient was admitted or not
- **Patient Satisfaction Score** — Score (1–10) rated by the patient
- **Patient Wait Time** — Time (in minutes) spent waiting before being seen

---

## 📈 Key Metrics & Insights

The dashboard highlights the following KPIs:

- **Total Patients** — Overall volume of ER visits in the selected period
- **Average Wait Time** — Mean wait time across all visits (in minutes)
- **Average Satisfaction Score** — Mean patient satisfaction rating
- **% Administrative vs Non-Administrative Admissions** — Breakdown of admission types

### Visuals Included

- Patient visits by **day of the week** and **time of day** (heatmap)
- **Monthly patient volume** trend line
- **Department referral** distribution (bar chart)
- **Patient age group** breakdown
- **Gender and race** distribution (donut/bar charts)
- **Satisfaction score** by patient demographics

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel / Power BI** | Data cleaning, transformation, and dashboard creation |
| **CSV** | Raw data format |

> *(Update this section to reflect the exact tool — e.g., Power BI, Tableau, or Excel — used to build the dashboard.)*

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/LukeshPawar/-Hospital_Emergency_Room_Dashboard.git
   ```

2. **Open the dataset**
   Load `Hospital Emergency Room Data.csv` into your preferred BI tool (Power BI, Tableau, Excel, etc.).

3. **Explore the dashboard**
   Open the dashboard file or refer to `Hospital Dashboard Final .jpg` for a preview of the finished output.

---

## 💡 Insights Summary (November 2024 Snapshot)

- **464 patients** visited the ER in November 2024, with an average wait time of **35.19 minutes**.
- **Patient satisfaction score** averaged **5.09 / 10**, indicating room for service improvement.
- Admission was evenly split — **50% admitted** (231) and **50% not admitted** (233).
- **61% of patients** were attended to within time; **39%** experienced delays.
- **Gender breakdown:** 237 Female vs. 227 Male patients.
- The **30–44 age group** had the highest ER visits (95 patients), followed by 45–59 (85).
- **General Practice** (91) and **Orthopedics** (67) were the top referral departments; 252 patients required no referral.
- **Neurology** (6) and **Renal** (2) had the fewest referrals, suggesting lower specialist demand.

---

## 🙋 Author

**Lukesh Pawar**
[GitHub Profile](https://github.com/LukeshPawar)

---

## 📄 License

This project is open-source and available for educational and personal use. If you use this project or dataset, please give appropriate credit.
