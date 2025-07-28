# 🚢 Vessel Schedule Comparator  

A Streamlit-based tool I built to automate a tedious manual task at work: comparing vessel schedules from Word documents against CSV exports to ensure accuracy and catch discrepancies in units, dates, and vessel names.  

## ✨ Features
- 📄 **Parse Word schedules (.docx)** and extract vessel, date, ship line, agent, and cargo info  
- 📊 **Load vessel CSV schedules**, clean and standardize data automatically  
- 🔍 **Compare schedules** to find mismatches, missing vessels, or 0-unit errors  
- 🔧 **Custom text parsing** for car shipments and Petcoke M/T formats  
- 🚀 **Streamlit UI** for quick file uploads and instant comparison  

## 🛠️ Tech Stack
- **Python** – Pandas, Regex, Datetime  
- **Streamlit** – Lightweight web app for easy use at work  
- **python-docx** – Extract tables from Word schedules  

## 📂 How It Works
1. Upload a weekly vessel schedule in `.docx` format  
2. Upload the vessel schedule CSV from the port database  
3. The tool:
   - Parses and standardizes vessel names/dates
   - Cleans CSV data (removes duplicates and reservations)
   - Matches schedules and flags missing or mismatched entries  
