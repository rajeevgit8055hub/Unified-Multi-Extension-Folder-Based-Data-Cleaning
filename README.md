# Multi-Extension Folder-Based Data Cleaning Project
---

## Project Overview

This project involved managing a complex data cleaning and consolidation task with multiple file formats — `.csv`, `.txt`, `.xlsx`, `.pdf`, and `.accdb`.  
All files were stored in a master folder containing disorganized data from different years and work shifts with inconsistent naming and structure.

The main goal was to automate the import, transformation, and cleaning of all these files into a single, unified, and well-structured Excel workbook.

---

## Approach & Execution

- Used Power Query’s **Folder Connector** to import all files from the master folder at once.  
- Created duplicate queries to handle each file extension separately with tailored transformation logic.  
- Filtered files by extension and used **Invoke Custom Functions** to dynamically expand and transform file contents.  
- Developed special logic for `.pdf` and `.accdb` files due to their unique, non-tabular formats.  
- Cleaned, standardized column names and data types, and fixed errors across all datasets.  
- Loaded cleaned data into separate Excel worksheets, organized by file type for clarity.

---

## Key Skills Demonstrated

- **Folder-Based Automation:** Batch import and refresh of mixed-format files using Power Query’s folder connector.  
- **Query Duplication & Filtering:** Extension-wise data processing with dedicated queries for `.csv`, `.txt`, `.xlsx`, `.pdf`, and `.accdb`.  
- **Advanced Data Extraction:** Dynamic parsing and expansion of nested or complex data using Invoke Custom Function.  
- **Format-Specific Solutions:** Custom Power Query steps to handle non-standard `.pdf` and Access database formats.  
- **Data Cleaning & Standardization:** Applied splitting, trimming, error handling, and consistent formatting techniques.  
- **Structured Loading:** Organized clean datasets in separate sheets within a single Excel workbook.  
- **Scalable ETL Workflow:** Built a reusable and scalable process to accommodate ongoing data updates and multiple formats.

---

## Tools Used

- Power Query  
- Advanced Excel

---

## Project Type

Practical | Automation | Real-World Data Cleaning

---

## Outcome

Created a robust and scalable ETL model for diverse file formats, greatly enhancing practical skills in Power Query and data automation workflows.

---

## Repository Contents

- Raw data files with multiple extensions  
- Power Query Excel workbook with all queries  
- Project documentation and presentation files  
- Data Cleaning Report image (shown above)

---

Feel free to explore, fork, and use this project for learning and improving your own Power Query skills!

---

*For any questions or feedback, please contact [your email or GitHub profile].*
![Data Cleaning Report](./Data%20Cleaning%20Report.png)
