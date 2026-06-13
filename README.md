# 🧪 Medical Records Validation System (Python)

A simple Python project that validates and checks the integrity of medical records using structured rules, regex validation, and functional programming techniques.

---

## 📌 Project Overview

This project simulates a basic **data validation system** for medical records.  
Each patient record is checked to ensure:

- Correct data structure (list of dictionaries)
- Required keys are present
- Each field follows strict validation rules
- Invalid fields are detected and reported

---

## ⚙️ Features

### ✅ Data Structure Validation
- Ensures input is a `list` or `tuple`
- Ensures each item is a `dictionary`

### 🔑 Key Validation
Each record must contain exactly:

```python
patient_id
age
gender
diagnosis
medications
last_visit_id
