# GenAI Financial Analysis Chatbot | BCG Job Simulation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Project Overview
This repository contains the work completed for the **BCG GenAI Job Simulation** on Forage. [cite_start]The scenario simulates a project within the GenAI consulting team at **BCG X**, where I acted as a Junior Data Scientist[cite: 38].

[cite_start]The objective was to develop an AI-powered chatbot capable of extracting and analyzing key financial data from 10-K and 10-Q documents to assist with financial inquiries[cite: 41, 45].

## 📂 Repository Structure

### [Task 1: Data Extraction & Analysis](./Task%201%20-%20Data%20Extraction%20&%20Analysis)
[cite_start]**Focus:** Data Preparation and Initial Analysis [cite: 50]
* [cite_start]**Objective:** Extract key financial data from 10-K documents and lay the groundwork for AI-driven insights[cite: 53].
* **Activities:**
    * [cite_start]Analyzed financial statement components and performance metrics[cite: 56].
    * [cite_start]Cleaned and formatted data for processing in an AI model[cite: 61].
    * [cite_start]Identified significant financial trends and indicators[cite: 60].

### [Task 2: AI Chatbot Development](./Task%202%20-%20AI%20Chatbot%20Development)
[cite_start]**Focus:** Logic Implementation and NLP [cite: 62]
* [cite_start]**Objective:** Develop a rule-based AI chatbot to transform data into interactive insights[cite: 65].
* **Activities:**
    * [cite_start]Implemented logic to extract company names and years from user queries[cite: 88].
    * [cite_start]Developed functions to handle inquiries for Total Revenue, Net Income, and Profitability[cite: 89].
    * [cite_start]Integrated exception handling for invalid years or companies[cite: 86].

---

## 🤖 Chatbot Capabilities
[cite_start]The chatbot acts as a simple rule-based AI assistant designed to answer questions about the financial performance of **Microsoft, Tesla, and Apple**[cite: 87].

### [cite_start]Supported Metrics [cite: 88]
* **Total Revenue**
* **Net Income**
* **Profitability Metrics (Margin)**
* **Year-over-Year Trends** (Fiscal Years: 2021, 2022, 2023)

### Testing & Results
[cite_start]The following test queries were executed to validate the system logic[cite: 80, 81, 82, 83, 86]:

| Query | Chatbot Output | Status |
| :--- | :--- | :--- |
| *"What is Apple's total revenue in 2021?"* | *"Apple's total revenue in 2021 is 365817."* | ✅ **Pass** |
| *"What is the trend of net income for Tesla in 2020?"* | *"Please enter a valid year."* | ✅ **Pass** (Error Handling) |
| *"How has Microsoft's net profit changed in 2022...?"* | *"The net profit for Microsoft in 2022 was 72738."* | ⚠️ **Limitation Found** |

---

## ⚠️ Known Limitations
Based on the testing phase, the current iteration has the following limitations:
1.  [cite_start]**Trend Calculation:** When asked about the "trend" or "change" in Net Income, the bot currently returns the absolute value rather than the percentage change[cite: 93].
2.  **Scope:** Restricted to three specific companies and the years 2021–2023. [cite_start]Queries outside this scope trigger error messages[cite: 91].
3.  **NLP:** The system relies on simple keyword matching. [cite_start]It handles specific phrases well but may fail with complex or ambiguous natural language queries[cite: 93].

---

## 📜 Certificate
![Certificate Preview](./Certificate/certificate_preview.png)
[View Full Completion Certificate](./Certificate/Completion_Certificate.pdf)

---

## ⚖️ Disclaimer
*This project was completed as part of the **BCG GenAI Job Simulation** on Forage. [cite_start]It is for educational purposes only and **does not represent an employment relationship** with Boston Consulting Group[cite: 17]. [cite_start]The work presented here demonstrates the skills learned and practiced during the simulation program[cite: 31].*
