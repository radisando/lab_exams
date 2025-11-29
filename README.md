## 🧪📊 Laboratory Exams Results
This project was originally created to help my family **visualize and track their blood exam results** more clearly. Using AI assistants (Julius AI and NotebookLM), I extracted and organized data from more than 100 PDF pages containing their exam values, dates, and results.

To make the project publicly shareable, I also built an anonymized dataset by randomizing and masking sensitive information. From this dataset, I generated interactive plots and dashboards that highlight trends and patterns over time.

The final dataset is optimized for use in Tableau, where the visualizations and screenshots included in this repository showcase the key insights.

🔗 Check the final result here: [Lab Exam Results - Tableau Dashboard](https://public.tableau.com/views/2025_11LaboratoryExamResultsv6/ENDashboard?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


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


--- 
### DEMO 
- Screenshot of final version:
<img width="900" height="550" alt="image" src="https://github.com/user-attachments/assets/b126e5ac-b448-4fe3-b69f-c93585db864b" />


- Screenshot of MVP version:
<img width="900" height="550" alt="image" src="https://github.com/user-attachments/assets/d9cde4f9-5401-41d7-862f-10e14b00e86e" />



