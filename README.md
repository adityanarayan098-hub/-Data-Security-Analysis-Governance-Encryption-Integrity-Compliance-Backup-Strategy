# 🔐 Data Security Analysis & Governance: Encryption, Integrity & Compliance

## 📌 Overview
This project focuses on implementing a comprehensive data security strategy for a payment processing company (JFin Payments) handling sensitive customer and financial data.

The objective was to ensure **Confidentiality, Integrity, and Availability (CIA Triad)** of data through governance policies, encryption techniques, integrity validation, and backup strategies.

---

## 🚨 Problem Statement
JFin Payments manages highly sensitive data including:
- Customer financial data  
- Employee information  
- Internal communications  
- Intellectual property  

This creates challenges in:
- Data protection & privacy  
- Regulatory compliance  
- Risk management  
- Secure data storage & transmission  

---

## 🛡️ Key Implementations

### 🔹 1. Data Governance & Policies
- Implemented:
  - Data Classification Policy  
  - Access Control Policy (RBAC, Least Privilege)  
  - Incident Response Policy  

✔ Ensured compliance with regulations like:
- GDPR  
- PCI-DSS  

---

### 🔹 2. Data Classification
Categorized data into:
- 🔴 Confidential (PII, financial data)  
- 🟡 Internal (emails, reports)  
- 🟢 Public (blogs, published content)  

✔ Reduced risk of data leakage and improved handling practices  

---

### 🔹 3. Regulatory Compliance
Designed security policies:
- Data Encryption (AES-256, TLS 1.2+)  
- Data Retention & Secure Disposal  
- Breach Notification Policy  
- Vendor Security Compliance  

✔ Improved legal and regulatory readiness  

---

### 🔹 4. Data Confidentiality (Disk Encryption)
- Generated **RSA 2048-bit key**  
- Implemented disk encryption  
- Secured sensitive data at rest  

✔ Prevented unauthorized access  

---

### 🔹 5. Data Integrity (Hash Verification)
- Used **SHA-256 hashing**  
- Verified file integrity by comparing hashes  

✔ Ensured data was not altered or tampered  

---

### 🔹 6. VM Security Hardening
- Enforced strong password policy  
- Configured account lockout policy  
- Enabled audit logging  
- Secured system configurations  

✔ Reduced risk of brute-force & unauthorized access  

---

### 🔹 7. Data Availability (Backup Strategy)
Designed backup strategy:

| Data Type     | Frequency        | Retention |
|--------------|----------------|----------|
| Confidential | Real-time/Daily | 1 Year   |
| Internal     | Weekly          | 90 Days  |
| Public       | Monthly         | 30 Days  |

✔ Ensured business continuity and disaster recovery  

---

## 🛠️ Tools & Technologies
- VirtualBox  
- Cryptography (RSA, SHA-256)  
- Windows Security Policies  
- Data Security Frameworks  
- Compliance Standards (GDPR, PCI-DSS)  

---

## 📊 Project Workflow
1. Analyze data types & risks  
2. Implement governance policies  
3. Apply encryption techniques  
4. Verify data integrity  
5. Harden VM security  
6. Design backup strategy  

---

## 📚 Key Learnings
- Data governance & classification  
- Encryption and cryptographic techniques  
- Regulatory compliance  
- Risk management  
- Backup and disaster recovery planning  

---

## 🎯 Future Improvements
- Implement automated data monitoring  
- Integrate SIEM for data security logs  
- Use cloud-based encryption (AWS KMS, Azure Key Vault)  
- Add DLP (Data Loss Prevention) solutions  

---

## 📸 Screenshots
- Disk Encryption Setup  
- Hash Verification Output  
- VM Security Policies  
- Backup Process  

(Add your screenshots here)

---

## ⚠️ Disclaimer
This project is created for educational purposes only.  
All security implementations should be used ethically and legally.

---

## 📬 Contact
- GitHub: Aditya Narayan  
- LinkedIn: www.linkedin.com/in/adityanarayan2990  
