# GenAI Financial Analysis Chatbot | BCG Job Simulation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Project Overview
This repository contains the work completed for the **BCG GenAI Job Simulation** on Forage. The scenario simulates a project within the GenAI consulting team at **BCG X**, where I acted as a Junior Data Scientist[cite: 38].

[cite_start]The objective was to develop an AI-powered chatbot capable of extracting and analyzing key financial data from 10-K and 10-Q documents to assist with financial inquiries[cite: 41, 45].

## 📂 Repository Structure

### [Task 1 Data Extraction and Initial Analysis](https://github.com/sunnyai79/BCG-GenAI-Job-Simulation/tree/main/Task%201%20Data%20extraction%20and%20initial%20analysis)
**Objective:** Extract key financial data from 10-K documents and lay the groundwork for AI-driven insights.
**Activities:**
    * Analyzed financial statement components and performance metrics.
    * Cleaned and formatted data for processing in an AI model.
    * Identified significant financial trends and indicators.

### [Task 2 Developing an AI-powered financial chatbot](https://github.com/sunnyai79/BCG-GenAI-Job-Simulation/tree/main/Task%202%20Developing%20an%20AI-powered%20financial%20chatbot)
**Objective:** Develop a rule-based AI chatbot to transform data into interactive insights.
**Activities:**
    * Implemented logic to extract company names and years from user queries.
    * Developed functions to handle inquiries for Total Revenue, Net Income, and Profitability.
    * Integrated exception handling for invalid years or companies.

---

## 🤖 Chatbot Capabilities
The chatbot acts as a simple rule-based AI assistant designed to answer questions about the financial performance of **Microsoft, Tesla, and Apple**.

### Supported Metrics
* **Total Revenue**
* **Net Income**
* **Profitability Metrics (Margin)**
* **Year-over-Year Trends** (Fiscal Years: 2021, 2022, 2023)

### Testing & Results
The following test queries were executed to validate the system logic:

| Query | Chatbot Output | Status |
| :--- | :--- | :--- |
| *"What is Apple's total revenue in 2021?"* | *"Apple's total revenue in 2021 is 365817."* | ✅ **Pass** |
| *"What is the trend of net income for Tesla in 2020?"* | *"Please enter a valid year."* | ✅ **Pass** (Error Handling) |
| *"How has Microsoft's net profit changed in 2022...?"* | *"The net profit for Microsoft in 2022 was 72738."* | ⚠️ **Limitation Found** |

---

## ⚠️ Known Limitations
Based on the testing phase, the current iteration has the following limitations:
1.  **Trend Calculation:** When asked about the "trend" or "change" in Net Income, the bot currently returns the absolute value rather than the percentage change.
2.  **Scope:** Restricted to three specific companies and the years 2021–2023. Queries outside this scope trigger error messages.
3.  **NLP:** The system relies on simple keyword matching.It handles specific phrases well but may fail with complex or ambiguous natural language queries.

---

## 📜 Certificate
[View Full Completion Certificate](https://github.com/sunnyai79/BCG-GenAI-Job-Simulation/blob/main/Certificate.jpg)

---

## ⚖️ Disclaimer
*This project was completed as part of the **BCG GenAI Job Simulation** on Forage. It is for educational purposes only and **does not represent an employment relationship** with Boston Consulting Group. [cite_start]The work presented here demonstrates the skills learned and practiced during the simulation program.*
