# AI-Driven Phishing Detection System

This project develops an **AI-driven phishing detection system** that uses **machine learning models** to identify phishing emails and suspicious URLs.  
By analyzing email content, headers, and URLs, the system classifies emails as **legitimate** or **phishing**.  
It leverages multiple datasets for phishing detection, URL validation, and domain legitimacy checking.

A **flagship innovation** of this system is the development of a **Chrome extension** that provides **real-time phishing detection** while browsing.  
Once installed, the extension actively monitors any hyperlink the user hovers over.  
If the link appears suspicious, the model instantly alerts the user — offering **immediate, on-the-fly protection** against phishing attacks during web surfing.

---

## Features

- **Email Phishing Detection**  
  Uses BERT-based machine learning models to classify emails as phishing or legitimate.

- **URL Validation**  
  Integrates Bloom filters for fast and efficient URL validation, checking if URLs belong to known malicious websites.

- **Domain Legitimacy Check**  
  Cross-references domain names against a dataset of legitimate domains to ensure the authenticity of email URLs.

- **Suspicious Activity Monitoring**  
  Scans email details and flags suspicious activity based on predefined rules and data patterns.

---

## Technologies Used

- Python
- CNN (for URL verification)
- BERT (for email phishing detection)
- Pandas, Scikit-learn (for data processing and model training)

---

## Installation

Download all the project files from the Google Drive link below and set them up locally.
```bash
https://drive.google.com/drive/folders/1PRQr5YKLq5YWdyLNIEhLC76s7Cs7UVOx?usp=drive_link
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```

---

##  Usage

Run the script to start the application:
```bash
python main.py
```

> **Note:**  
> Update the dataset paths inside the scripts with your own file locations.

---
## License

This project is for educational and research purposes only.
---



#  Project Status

This project is **still under active development**.  
Exciting features like a **dashboard** for visual monitoring and **cloud integration** for scalable deployment are currently being worked on!  

**Contributions are warmly welcome** to make this project even better! 🚀





# Stay Secure! 


