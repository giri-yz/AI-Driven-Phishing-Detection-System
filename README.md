AI-Driven Phishing Detection System
This project develops an AI-driven phishing detection system that uses machine learning models to identify phishing emails and suspicious URLs. By analyzing email content, headers, and URLs, the system classifies emails as legitimate or phishing. It leverages multiple datasets for phishing detection, URL validation using Bloom filters, and domain legitimacy checking.

Features
Email Phishing Detection:
Uses BERT-based machine learning models to classify emails as phishing or legitimate.

URL Validation:
Integrates Bloom filters for fast and efficient URL validation, checking if URLs belong to known malicious websites.

Domain Legitimacy Check:
Cross-references domain names against a dataset of legitimate domains to ensure the authenticity of email URLs.

Suspicious Activity Monitoring:
Scans email details and flags suspicious activity based on predefined rules and data patterns.

Technologies Used
Python

BERT (for phishing detection)

PyBloom (for URL validation)

Pandas, Scikit-learn (for data processing and model training)

Installation
To run the project locally, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/giri-yz/Suspicious_email_checker
Navigate into the project folder:

bash
Copy
Edit
cd Suspicious_email_checker
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
1. Phishing Detection
Run the script to classify emails:

bash
Copy
Edit
python phishing_detection.py
2. URL Validation
Use the URL validation script to check the legitimacy of URLs:

bash
Copy
Edit
python url_validation.py
Note:
Make sure to update the dataset paths in the scripts with your own data files before running.

Pre-trained Model
The large BERT model file required for phishing detection can be downloaded from the following link:
Download Model File

License
This project is for educational and research purposes only.

🔥 Happy Hunting! Stay Secure 🔥
