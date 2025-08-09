# 📂 Multi-Extension Folder-Based Data Cleaning Project  

**Project Type:** Practical | Automation | Real-World Data Cleaning  
**Tools Used:** Power Query | Advanced Excel  
**Duration:** [Add Duration Here]  

---

## 📖 Project Overview  

This project focused on managing a **complex data cleaning and consolidation process** involving **multiple file formats** —  
`.csv`, `.txt`, `.xlsx`, `.pdf`, and `.accdb`.  

All files were located in a **master folder**, containing **disorganized data** from different **years** and **work shifts**.  
The raw data suffered from **inconsistent naming conventions**, **varied structures**, and **format-specific challenges**.  

The **primary goal** was to design and implement an **automated process** to import, transform, and clean all files,  
finally producing a **single, unified, and well-structured Excel workbook** ready for analysis.  

---

## 🎯 Project Objectives  

- Automate the **import and consolidation** of mixed-format files.  
- Apply **format-specific cleaning techniques** for each file type.  
- Standardize and **normalize datasets** for consistency.  
- Organize final cleaned outputs into **clear, logical sections**.  
- Build a **scalable ETL (Extract, Transform, Load) process** for future data updates.  

---

## ⚙ Approach & Execution  

### **1. Folder-Based Import Automation**  
- Used **Power Query’s Folder Connector** to automatically import **all files** from the master folder in one go.  
- Ensured the process can **refresh automatically** when new files are added.  

### **2. File Extension-Specific Processing**  
- Created **duplicate queries** for each file extension (`.csv`, `.txt`, `.xlsx`, `.pdf`, `.accdb`).  
- Filtered files by extension to **apply unique cleaning logic** to each type.  

### **3. Dynamic Transformation Logic**  
- Applied **Invoke Custom Function** to dynamically expand and transform files without manual intervention.  

### **4. Handling Complex Formats**  
- Developed **custom logic** for `.pdf` and `.accdb` files due to their non-tabular structures.  
- Extracted tables from PDFs and imported Access tables into Power Query for further transformation.  

### **5. Data Cleaning & Standardization**  
- Standardized **column names** for uniformity.  
- Applied **correct data types** (text, number, date).  
- Fixed **formatting issues**, removed extra spaces, and replaced invalid values.  
- Applied **error handling** to ensure clean outputs.  

### **6. Organized Final Output**  
- Loaded cleaned data into **separate worksheets** within a single Excel workbook, organized **by file type**.  

---

## 🧠 Key Skills Demonstrated  

- **Folder-Based Automation:** Batch import and refresh of mixed-format files using Power Query’s folder connector.  
- **Query Duplication & Filtering:** Extension-wise data processing with dedicated queries for `.csv`, `.txt`, `.xlsx`, `.pdf`, and `.accdb`.  
- **Advanced Data Extraction:** Dynamic parsing and expansion of nested or complex data using Invoke Custom Function.  
- **Format-Specific Solutions:** Custom Power Query steps to handle non-standard `.pdf` and Access database formats.  
- **Data Cleaning & Standardization:** Applied splitting, trimming, error handling, and consistent formatting techniques.  
- **Structured Loading:** Organized clean datasets in separate sheets within a single Excel workbook.  
- **Scalable ETL Workflow:** Built a reusable and scalable process to accommodate ongoing data updates and multiple formats.

---

## 🛠 Tools Used  

- **Microsoft Power Query** — For automation, transformation, and cleaning.  
- **Advanced Excel** — For structured loading and final output organization.  

---

## 📊 Project Outcome  

- Delivered a **robust and reusable ETL solution** capable of handling multiple file formats.  
- Achieved a **fully automated refresh process** — adding new files to the folder updates the Excel output instantly.  
- Greatly improved **efficiency**, **accuracy**, and **consistency** in data processing workflows.  
- Enhanced practical expertise in **multi-format data handling** within Power Query.  

---

## 📂 Repository Contents  

| File Name / Folder | Description |
|--------------------|-------------|
| `/Raw Data Files` | Original messy data files with multiple extensions. |
| `Multi-Extension Power Query Workbook.xlsx` | Main Excel file containing all Power Query transformations. |
| `Project Documentation.pdf` | Detailed explanation of project steps and logic. |
| `Presentation.pptx` | Visual presentation of the project workflow. |
| `Data Cleaning Report.png` | Snapshot of the cleaned dataset report. |

---

## 🚀 How to Use This Project  

1. **Download or Clone** this repository.  
2. Place all raw data files in the `Raw Data Files` folder.  
3. Open the `Multi-Extension Power Query Workbook.xlsx` file.  
4. Refresh the queries in Power Query to see **cleaned outputs**.  
5. Review the final results in separate worksheets organized by file type.  

---

## 🌟 Future Enhancements  

- Integrating with **Power BI Dataflows** for cloud-based automation.  
- Creating **validation rules** to flag inconsistent data before processing.  
- Adding a **dashboard** to visualize trends from the consolidated dataset.  

---

## 📷 Project Snapshot  

![Data Cleaning Report](./Data%20Cleaning%20Report.jpg)  

 

