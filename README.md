# Phishing Campaign for Victoria Police – Database Design and Analysis

## Project Overview (Power BI, Database Design, Cybersecurity Analytics, Data Modelling)
This project focuses on phishing campaigns targeted at the Victorian Police Department, with the goal of improving how phishing simulation results are captured, stored, and analysed.  
The solution uses Microsoft Power BI and relational database design to create a clean, normalised data structure that supports detailed analysis and automated reporting.

Key details about the project:
- Built around phishing simulation datasets covering multiple police departments and roles.
- Designed in First (1NF), Second (2NF), and Third Normal Form (3NF) to ensure clean, consistent, and reliable data.
- Captures metrics such as email open rates, click rates, attachment downloads, phishing reports, training completions, compliance verification, and officer feedback.
- Covers multiple audiences: Uniformed Officers, Detectives, Administrative Staff, IT and Cybersecurity teams.
- Transforms raw campaign results into actionable insights that inform training, awareness programs, and departmental policy updates.
- Creates a database foundation that integrates seamlessly with Power BI dashboards for real-time monitoring.

The outcome is a relational model that eliminates redundancy, supports fast querying, and enables departments to act quickly on phishing risk trends.  
This approach turns scattered simulation data into a central decision-making resource for strengthening cyber resilience.

---

## Databases Designed
Three separate but connected databases were created, each serving a different purpose:

1. **Campaign Manager Database**
   - Holds campaign details such as start/end dates, target audience, phishing templates, website URLs, open rates, click rates, and reporting metrics.
   - Enables quick evaluation of training impact and compliance by department and role.

2. **Police Department Database**
   - Stores officer information including department, rank, location, and email interaction history.
   - Tracks which officers opened phishing emails, clicked links, opened attachments, or reported phishing attempts.

3. **HR Manager Database**
   - Focuses on officer training records, compliance status, campaign feedback, and satisfaction ratings.
   - Links training data directly to campaign outcomes to show the relationship between awareness programs and behaviour.

---

## Skills Demonstrated
- End-to-end database design from raw data to 3NF.
- Data modelling to reduce redundancy and improve data integrity.
- Linking officer behaviour data with campaign results for multi-dimensional analysis.
- Creating a structure optimised for integration with BI tools.
- Cybersecurity data analysis to identify high-risk departments, roles, and behaviours.
- Automating phishing campaign reporting for faster decision-making.

---

## Key Insights from the Data
- Uniformed Officers opened 85% of phishing emails and clicked 60% of links, showing high engagement but also a training gap.
- Detectives and Investigators reported 70% of phishing attempts via PhishHook, showing strong awareness.
- IT and Cybersecurity staff recorded no phishing clicks and had an 80% success rate at avoiding attacks, likely due to their expertise.
- Departments showed varying compliance verification rates, suggesting that training and policy enforcement should be tailored by group.
- Linking training records with behaviour showed that not all trained officers applied their knowledge in real scenarios.

---

## Benefits of the Database Design
- Eliminates duplicate records, ensuring all data is accurate and consistent.
- Makes it possible to run complex queries, such as finding the highest-risk roles by department.
- Automates the process of com
