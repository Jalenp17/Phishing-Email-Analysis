# Phishing-Email-Analysis
# 🚨 Phishing Email Analysis | SOC Investigation

## 📌 Overview

This project documents a phishing email investigation conducted using a structured SOC playbook. The objective was to determine whether the email was malicious and assess any potential impact.

---

## 🎯 Objectives

* Analyze email metadata and content
* Identify indicators of compromise (IOCs)
* Validate malicious artifacts (URL)
* Perform SIEM log analysis
* Determine if the alert is a true positive

---

## 🛠️ Tools Used

* Lets Defend (SIEM)
* VirusTotal (threat intelligence)
* Email header analysis
* SOC playbook methodology

---

## 🔍 Investigation Summary

### Step 1: Email Analysis

* Extracted:

  * Timestamp
  * SMTP address
  * Sender & recipient
  * Email content review

✅ Email content was suspicious

---

### Step 2: URL Analysis

* Identified URL within email
* Submitted to VirusTotal

🚨 Result: **Malicious URL detected**

---

### Step 3: Email Security Check

* Verified whether the email was delivered or blocked

✅ Email was successfully blocked

---

### Step 4: SIEM Log Analysis

* Searched for related activity in Splunk
* Investigated potential communication with C2 IP

✅ No additional hosts contacted the malicious IP

---

## 🧠 Conclusion

* Phishing email confirmed as **True Positive**
* No further compromise detected
* Attack successfully mitigated

---

## 📊 Skills Demonstrated

* Phishing Analysis
* Threat Intelligence Validation
* SIEM Log Analysis
* Incident Response Workflow
* SOC Playbook Execution

---

## 📸 Screenshots

<img width="758" height="404" alt="Screenshot 2026-03-25 201433" src="https://github.com/user-attachments/assets/4fc16743-4f28-488e-ae56-5f457c109404" />
Playbook 1
<img width="711" height="369" alt="Screenshot 2026-03-25 201446" src="https://github.com/user-attachments/assets/b3897b39-d013-4a28-9e6d-a2b1dbbf0960" />
Playbook 2
<img width="753" height="443" alt="Screenshot 2026-03-27 171115" src="https://github.com/user-attachments/assets/8ec30565-4c54-4764-87da-57d56b186f59" />
Playbook 3
<img width="733" height="319" alt="Screenshot 2026-03-27 171146" src="https://github.com/user-attachments/assets/32b5ecbf-08a0-4144-8325-5b72c7e29474" />
playbook 4
<img width="975" height="396" alt="Screenshot 2026-03-25 201808" src="https://github.com/user-attachments/assets/7b6c4991-59eb-41ef-8f13-ab9dfbcbe18f" />
Suspicious email
<img width="829" height="325" alt="Screenshot 2026-03-25 201858" src="https://github.com/user-attachments/assets/8e76d487-6787-48c7-980f-5b9fecd17c73" />
URL Scan 1
<img width="957" height="378" alt="Screenshot 2026-03-25 202020" src="https://github.com/user-attachments/assets/f1b49a1f-f3e2-4c4c-a932-710c4af88750" />
URL Scan 2
<img width="919" height="292" alt="Screenshot 2026-03-25 203704" src="https://github.com/user-attachments/assets/83cb03b6-8efe-4e41-bf8b-8fe26502d927" />
Analysis results
