# AI-Driven Phishing Detection System

This project develops an **AI-driven phishing detection system** that uses **machine learning models** to identify phishing emails and suspicious URLs.  
By analyzing email content, headers, and URLs, the system classifies emails as **legitimate** or **phishing**.  
It leverages multiple datasets for phishing detection, URL validation using **Bloom filters**, and domain legitimacy checking.

---

## 🚀 Features

- **Email Phishing Detection**  
  Uses BERT-based machine learning models to classify emails as phishing or legitimate.

- **URL Validation**  
  Integrates Bloom filters for fast and efficient URL validation, checking if URLs belong to known malicious websites.

- **Domain Legitimacy Check**  
  Cross-references domain names against a dataset of legitimate domains to ensure the authenticity of email URLs.

- **Suspicious Activity Monitoring**  
  Scans email details and flags suspicious activity based on predefined rules and data patterns.

---

## 🛠️ Technologies Used

- Python
- CNN (for URL veerification)
- BERT (for email phishing detection)
- Pandas, Scikit-learn (for data processing and model training)

---

## 🧩 Installation

Clone the repository:
```bash
git clone https://github.com/giri-yz/Suspicious_email_checker
```

Navigate into the project folder:
```bash
cd Suspicious_email_checker
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```

---

## ⚙️ Usage

### 1. Phishing Detection

Run the script to classify phishing emails:
```bash
python phishing_detection.py
```

### 2. URL Validation

Run the script to validate URLs:
```bash
python url_validation.py
```

> **Note:**  
> Update the dataset paths inside the scripts with your own file locations.

---

## 📦 Pre-trained Model

The BERT model file needed for phishing detection can be downloaded from:  
[👉 Download Model File](https://drive.google.com/drive/folders/1PRQr5YKLq5YWdyLNIEhLC76s7Cs7UVOx?usp=drive_link)

---

## 📜 License

This project is for educational and research purposes only.

---

# 🔥 Happy Hunting! Stay Secure! 🔥

