# LEGO Timesheet Analytics

## Project Description
This project analyzes timesheet data to evaluate workforce utilization and identify inefficiencies in project execution.
The analysis focuses on understanding how working hours are distributed and how they impact overall performance.

---

## Business Questions
- How does **Productive Utilization (PU)** change over time?
- What is the ratio between **billable and non-billable hours**?
- Are there specific periods or teams with unusually low efficiency?
- What insights can support better workforce planning?

---

## Dataset
- The dataset consists of employee timesheet records.
- Key fields include:
  - Date
  - Employee / Team
  - Project
  - Billable hours
  - Non-billable hours
- The data used in this repository is **sampled / anonymized** for demonstration purposes.
<img width="1877" height="740" alt="image" src="https://github.com/user-attachments/assets/cfb56778-4f49-4b88-b7de-fcc2d64f8211" />
<img width="1336" height="853" alt="image" src="https://github.com/user-attachments/assets/65f81421-6c53-46cd-8c08-27a029a38a44" />

---

## Analysis Approach
1. Data cleaning and validation
2. Calculation of key metrics:
   - Productive Utilization (PU)
   - Billable vs. non-billable ratio
3. Trend analysis over time
4. Identification of abnormal patterns and inefficiencies

---

## Key Metrics Explained
<img width="1631" height="1216" alt="image" src="https://github.com/user-attachments/assets/9ce93943-5c6a-4736-9744-df48f772b45b" />
<img width="1740" height="896" alt="image" src="https://github.com/user-attachments/assets/f1cbcbaa-001a-4df9-bd4a-d1e3d835437c" />

---

## Key Insights
- PU showed noticeable fluctuations across different periods.
- In Germany, LMP00001501 shows a very low level of PU.
<img width="1199" height="319" alt="image" src="https://github.com/user-attachments/assets/83cc813b-2e15-4177-a1c1-795a4b3555b6" />
- In Mexico, LMP00001501 shows a very low level of PU.
<img width="1289" height="192" alt="image" src="https://github.com/user-attachments/assets/030601c1-6de5-4828-92c3-3e996743acbd" />
--> Main reason leads to low PU in these 2 countries.
  
- In PRC, LMP00001501 shows a sustainable PU; the recent downward trend is due to the completion of its projects.
<img width="1154" height="293" alt="image" src="https://github.com/user-attachments/assets/79f1a157-e697-4c11-b7f0-2a2220b84061" />

- LMP00001503 is the best-performing project in 2025, sustaining a high PU of 97% with costs reaching up to £4M.
<img width="1732" height="190" alt="image" src="https://github.com/user-attachments/assets/35cf1b66-201a-4fdb-b12b-d6f306471d16" />

- Unapproval rates increases due to overhead department. They are non-billable department so they often submit timesheet late. 
<img width="1884" height="355" alt="image" src="https://github.com/user-attachments/assets/2bbd902e-632f-43d3-b80f-89670a01507a" />

---

## Solutions
- review the objectives of LMP00001501, if they are not able to convert to valuable output --> Consider project termination or restructuring.
- reduce meeting hours. Just maintaining meeting related to decisions and deliveries.
- set up early-warning so that their department could easily control timesheet and improve approval rate.
---

## Tools Used
- Python
- SQL
- Excel
- Power BI (for visualization)

---

## Project Structure
├── data/
│ └── sample_timesheet.csv
├── notebooks/
│ └── analysis.ipynb
├── README.md

## Author
**Lai Thuy Binh**  
Data Analyst
