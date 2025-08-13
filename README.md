# 🏥 Healthcare Data Privacy & Security – Colab Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/Healthcare-Data-Privacy-Security/blob/main/healthcare_privacy_project.ipynb)

A Google Colab project implementing **data privacy, security, and compliance** techniques on a healthcare dataset.  
It covers **data cleaning, validation, encryption, role-based access control, regulatory compliance mocks, and a frequency analysis attack** on Caesar Cipher.

---

## 📌 Features
- **Data Cleaning** – Handles duplicates, missing values, formats, and categorical types.
- **Data Validation** – Uses `pandera` for schema validation with constraints (e.g., Age 0–120, Billing Amount ≥ 0).
- **Hashing** – Protects sensitive data using SHA-256.
- **Substitution Encryption** – Caesar Cipher encryption and decryption.
- **Access Control** – Implements Role-Based Access Control (RBAC) for data access management.
- **Regulatory Compliance (Mock)** – Simulated GDPR, CCPA, HIPAA operations.
- **Cryptanalysis** – Frequency Analysis attack on Caesar Cipher.
- **Profiling Reports** – Data profiling with `ydata_profiling`.

---

## 📂 Project Structure
Since this project is **entirely in a single Colab notebook**, the file structure is simple:
📦 Healthcare-Data-Privacy-Security
┣ 📜 healthcare_privacy_project.ipynb
┗ 📜 README.md

yaml
Copy
Edit

---

## 🚀 How to Run

### Option 1 – Open in Google Colab (Recommended)
1. Click the **Open in Colab** button above ☝️.
2. Run the notebook cells in sequence.

### Option 2 – Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Healthcare-Data-Privacy-Security.git
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the notebook in Jupyter:

bash
Copy
Edit
jupyter notebook healthcare_privacy_project.ipynb
🛠 Technologies Used
Python – Core programming

pandas – Data handling

pandera – Data validation

hashlib – Hashing

ydata_profiling – Data profiling

collections.Counter – Frequency analysis

Google Colab – Execution environment
