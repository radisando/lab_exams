## 🧪📊 Laboratory Exams Results

This project was created to visualize my parents’ blood exam results in a more friendly and understandable way (for them and also for their doctors to follow-up).
To show that here publicly, I've built here a dataset by anonymizing and randomizing values, and generated interactive plots and dashboards to explore trends over time. 
The final dataset is designed to be easily analyzed and visualized in Tableau, with screenshots showcasing key visual insights.

- 🔗 Check the final result in Tableau: [Lab Exam Results Dashboard]([https://public.tableau.com/views/2025_11LaboratoryExamResultsv6/ENDashboard?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


### 🚀 Features

- Data Generation – Randomized and anonymized results for multiple patients (A, B, C, D) based on realistic reference ranges.

- Controlled Randomization – Exam results and dates are varied while staying consistent with medical reference limits.

- Date & Patient Manipulation – Supports manual and automated adjustments of exam dates and patient identifiers.

- Visualization Ready – Dataset is clean and ready for plotting with Python (Seaborn/Matplotlib) or loading into Tableau.

- Export Options – Save the dataset in Excel or CSV format for easy sharing and reporting.

### 🧩 Repository Structure
```bash
lab_exams/
│
├── data_prep.ipynb                # Jupyter notebook: data generation & visualization
├── blood_exam_results.xlsx        # Example original Excel file
├── blood_exam_results_output.csv  # Example exported CSV file
├── README.md                      # Project overview & instructions
└── screenshots/                   # Tableau dashboards & Seaborn plot screenshots
```


### 🖥️ Python Notebook

- Loads original Excel dataset.

- Cleans headers and standardizes formats (dates, DOB, units).

- Generates synthetic patients and randomized exam results.

- Provides interactive Seaborn plots per exam, showing results over time for all patients.

- Outputs final dataset in Excel or CSV format.
  

### 📊 Visualizations

- Line charts using Seaborn for any exam, comparing all patients with different colors.

- Exam results vs. date, with clear legends and markers.

- Designed for seamless export to Tableau for richer dashboards.
  

### 💻 Tableau Integration

- Load the exported Excel/CSV into Tableau.

- Create dashboards showing trends of exam results across patients.

- Include filters for exam type, patient, or date range.


## DEMO 
- Example screenshots of MVP version:
  <img width="1285" height="794" alt="image" src="https://github.com/user-attachments/assets/d9cde4f9-5401-41d7-862f-10e14b00e86e" />
