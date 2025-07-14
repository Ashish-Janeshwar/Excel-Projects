# 📊 Minute Mapping System – Excel Automation Template

A powerful Excel-based solution designed to process VoIP call data (CDRs) by mapping traffic to carriers using IP addresses. Built to streamline traffic analysis and ensure accurate billing in IPRN/VoIP environments.

---

## 🔧 Purpose

This system enables telecom or VoIP teams to:
- Accurately map each call’s duration to the correct carrier via IP address
- Generate daily, weekly, and monthly summaries automatically
- Detect mismatches and reduce billing disputes
- Create a clean and structured dashboard for internal review

---

## 📂 Files Included

1. **IP Mapping File (Working File 1)**  
   - Sheet 1: Carrier list with mapped IPs  
   - Sheet 2: Paste raw CDR (Call Detail Records) data  
   - Uses Excel formulas (e.g., `SUMIF`) to calculate total minutes per IP

2. **Minute Mapping Dashboard (Working File 2)**  
   - Sheet "H": Consolidated daily totals, weekly summaries, and comparison table  
   - Sheets W1–W5: Weekly breakdowns  
   - Sheets 1–31: Individual day-wise input sheets

3. **Sample CDR File**  
   - Dummy data for easy understanding and testing

---

## 🔄 How It Works

- Paste CDR data into **Sheet 2** of the IP File  
- Total minutes per IP are calculated based on mapped carriers  
- Daily totals are transferred to the correct date sheet in the Dashboard  
- Final summaries and comparisons are automatically updated

---

## ✅ Final Output

- Daily, weekly, and monthly total minutes per carrier  
- Dashboard for traffic analysis and performance tracking  
- Final comparison table to detect mismatches and errors  
- Excel-based logic only (no VBA or external tools)

---

## 🎯 Designed For

- Internal teams managing **IPRN/VoIP traffic**
- Telecom finance & operations teams verifying usage and billing
- Business analysts automating telecom reporting systems

---

> 💡 Built in Excel using SUMIF logic, conditional formatting, linked summaries, and structured workflows.
