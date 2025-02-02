AI-Driven Phishing Detection System

This project aims to develop an AI-driven phishing detection system that uses machine learning models to identify phishing emails and suspicious URLs. By analyzing email content, headers, and URLs, the system classifies emails as legitimate or phishing. The project leverages several datasets for email phishing detection, URL verification using Bloom filters, and domain legitimacy checking.

### Key Features:
- **Email Phishing Detection**: Uses machine learning models (BERT-based) to classify emails as phishing or legitimate.
- **URL Validation**: Integrates Bloom filters for fast URL validation, checking if the URLs belong to known malicious websites.
- **Domain Legitimacy Check**: Cross-references domain names with a dataset of legitimate domains to ensure the authenticity of email URLs.
- **Suspicious Activity Monitoring**: Scans email details and flags suspicious activity based on predefined rules and data patterns.

### Technologies Used:
- Python
- BERT (for phishing detection)
- PyBloom (for URL validation)
- Pandas, Scikit-learn (for data processing and model training)

### Installation:
To run the project locally, clone the repository and install the required dependencies:

git clone https://github.com/your-username/your-repository.git
cd your-repository
pip install -r requirements.txt


### Usage:
- Run the phishing detection script with your own email dataset to classify emails.
- Use the URL validation script to check the legitimacy of URLs from emails.
  
