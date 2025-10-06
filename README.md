# 👮 Puducherry Police - Digital IIF Forms Portal

## Project Objective

This project, developed during a cybersecurity internship at the **Puducherry Cyber Crime Police Station**, delivers a solution to modernize the criminal investigation documentation process.

The primary objective is to facilitate the digital creation of **Integrated Investigation Forms (IIF)** with a dual-purpose workflow:

1. **Digital Persistence:** Enable police personnel to input case data digitally, which is then automatically stored in a secure, centralized **Google Sheet Database** for real-time tracking, analysis, and data security.
2. **Official Printability:** Allow for the generation of clean, print-ready, and formatted hard copies of the forms (FIR, Arrest, Charge Sheet, etc.) for official case files and submission to the court, thereby bridging the gap between digital efficiency and mandatory procedural requirements.

***

## 🚀 Key Features

* **Secure Access Control:** Only valid **`@py.gov.in`** (or `@py.ac.in`) official emails can be used for system login and new user activation.
* **Full Verification Workflow:** New users must undergo **full OTP verification** via both email and mobile number during the registration process.
* **Print-Ready Forms:** Users **can print the form** directly from the browser to generate the mandatory physical records for court submission and case files.
* **Centralized Data Storage:** All validated form data is securely persisted and accessible via a cloud-based **Google Sheet** (or Google Sheets) backend.
* **Five Integrated IIF Forms:** Implementation of the five standard Integrated Investigation Forms (**IIF-1 through IIF-5**), covering every critical stage of an investigation (FIR, Crime Details, Arrest, Property Seizure, and Final Report/Charge Sheet).
* **Final Report Generation (IIF-5):** Generates the official Final Report or **Charge Sheet** ($u/s 173 Cr.P.C.$), summarizing the investigation's result, listing properties, witnesses, and the status of the accused.

***

## 🛠️ Technology Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3 | Structure and Styling (Optimized for both screen viewing and **Print CSS**). |
| **Logic** | JavaScript (Vanilla) | Form validation, navigation, data serialization, and communication with the backend. |
| **Database** | Google Sheets (via Google Apps Script) | Cloud-based, centralized data storage for PoC deployment and easy analytical reporting. |
| **Backend/API** | Google Apps Script | Serves as the serverless bridge to receive form data and append it to the Google Sheets. |

***

## 📂 Project screenshot

<img width="1919" height="940" alt="Screenshot 2025-10-06 110052" src="https://github.com/user-attachments/assets/40ff33e3-6cc6-42ce-b52e-73d056b503a1" />

<img width="1919" height="959" alt="Screenshot 2025-10-06 110142" src="https://github.com/user-attachments/assets/80073de8-ba2b-4181-818b-330c1b35a37f" />


