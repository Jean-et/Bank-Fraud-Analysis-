# Bank-Fraud-Analysis-
## Bank Fraud Pattern Detection 
![](https://github.com/Jean-et/Bank-Fraud-Analysis-/blob/main/data%20analytics.png)
# Introduction:
At LOL Bank Pvt. Ltd., safeguarding the security and integrity of financial transactions is paramount. With the surge in online transactions and digital banking activities, fraudulent transactions have become a significant threat to both the bank and its customers. With increasingly more on-line transactions and digital banking activities, fraudulent transactions has increased significantly and pose as a danger to both the financial institution and its customers. Fraudulent activities, along with unauthorized account get right of entry to, identification robbery, and suspicious transaction patterns, bring about economic losses.

## Fraud Detection & Prevention Outlook | LOL Bank Pvt. Ltd.
i) Safeguard transactions by identifying fraud patterns in historical data (amounts, locations, devices, merchants).

ii) Combat rising threats: unauthorized access, identity theft, and suspicious transactions causing financial/customer trust losses.

iii) Analyze trends to flag high-risk transactions and fraud-prone behaviors (e.g., unusual merchant categories).

iv) Develop a real-time dashboard to visualize fraud hotspots and suspicious activities.

v) Strengthen detection systems with actionable insights for faster response.

vi) Reduce fraud losses by 30% and boost customer confidence in digital banking

To cope with this developing subject, LOL Bank Pvt. Ltd. Is in search of a strategy to stumble on and save you fraudulent transactions in real time. This includes analyzing ancient transaction records, consisting of account info, transaction quantities, service provider records, and time stamps, to pick out patterns indicative of fraudulent conduct. The intention is to construct a robust fraud detection gadget that may distinguish among legitimate transactions and probably fraudulent ones, with minimal fake positives.


## Key Metrics:  

1. Is fraud more prevalent at certain hours ?
2. Which locations are more prone to fraudulent activities?
3. Which account types are more prone to fraud?
4. Are certain merchant categories more prone to fraud?
5. Which device type are most vulnerable to fraud?
6. What is the trend of fraud over time?

## Data Available:

The dataset includes historic transaction facts, which includes transaction information consisting of: Transaction ID, timestamp, quantity, transaction type (e.G., withdrawal, deposit, switch) Customer account information (e.G., account ID, age, location) Merchant info (e.G., service provider ID, vicinity, enterprise) Device and community-associated metadata It might also encompass previous fraudulent pastime flags or labels for education gadget getting to know models. Objective:

Develop a gadget which could routinely become aware of suspicious or potentially fraudulent transactions in real-time. Minimize false positives to avoid blockading valid transactions at the same time as ensuring excessive detection accuracy for fraudulent sports. Improve the detection of rising fraud strategies that won't be effortlessly detected with traditional regulations-based totally structures. Solution Approach:

Use gadget getting to know algorithms (e.G., Random Forest, SVM, Neural Networks) to construct predictive fashions. Implement function engineering to create meaningful capabilities from raw transaction information that can assist locate fraud. Develop anomaly detection strategies to flag transactions that deviate from regular consumer behavior. Incorporate a remarks loop for model retraining to keep up with evolving fraud patterns.

## Challenges:

The dataset is probably imbalanced, with fraudulent transactions representing best a small fraction of total transactions, which makes detection greater tough. There may be issues with information privateness and security, requiring careful handling of touchy purchaser information. Real-time processing demands high computational strength and performance to maintain a smooth user experience. By addressing those demanding situations, LOL Bank Pvt. Ltd. Goals to create a comprehensive fraud detection gadget that no longer only secures purchaser finances but additionally complements operational efficiency and strengthens its function as a depended on financial group.**

## SKILLS / TECHNIQUES USED FOR THIS PROJECT 
- Data Gathering 
- Data Cleaning and Preprocessing 
- Data Visualization 
- Power BI  And Excel 
- Dashboard Automation

## Expected Outcomes:
- Develop a Robust Fraud Detection System: Analyze Historical Data: Examine transaction details such as transaction ID, timestamp, amount, type, customer account information, merchant details, and device/network metadata.
- Machine Learning Integration: Utilize algorithms to learn from transaction history, identify emerging fraud strategies, and adapt to evolving threats.
- Real-Time Detection: Flag suspicious transactions instantly, providing actionable insights for bank employees to take prompt action.
- Minimize False Positives: Ensure high detection accuracy for fraudulent activities while avoiding the blocking of legitimate transactions.

# Visualization and Analysis 
![](https://github.com/Jean-et/Bank-Fraud-Analysis-/blob/main/GitHUB%20bank%20trasaction%20.jpg)

![](https://github.com/Jean-et/Bank-Fraud-Analysis-/blob/main/Github%20fraud%20analysis.jpg)

# Insights
With all these techniques, we were able to draw valuable insights and make data-driven decisions from the dataset. 
1. There was a total of ₹200,000 banking transactions with an amount total of 9.91bn. 
2. There was a fraud rate of 5% with over ₹10K fraud transactions corresponding to an amount of ₹497M meaning every 1:20 transaction was a fraud. 
3. The peak fraud transactions happened at Kavaratti Lakshadweep with 332 occurrences, followed by Chandigarh, Chandigarh with 288 occurrences.     
4. The highest fraud transactions happened on 6th January 2025 with 210 fraudulent activities, followed by 11th and 29th January both having 190 occurrences.
5. The highest fraud activity occurred at 10 am with 111 occurrences followed by 11pm with 103 occurrences.
6. There was an almost equal distribution of transactions in all three Account Types for Non-fraudulent, while Business Account Type had a slight edge exposure of 34.06% to fraudulent activities 
7. Both Device type and merchant categories had almost equal transaction activities among their various component for Non-fraud transactions while Desktop With a figure of ₹2,544 was the most used Device Type, followed by POS for Fraud and Clothing with ₹ 1734, followed by groceries were the most merchant categories for fraud.

**Breakdown of Peak Fraud Hours**

🕙 10 AM
High Transaction Volume: 
- Fraud blends in with morning business activity.
- Employee Distraction: Busy workflows lead to oversight of suspicious patterns.

🌙 11 PM
Reduced Monitoring: 
- Lower security staffing and delayed response to alerts.
- Spike in Online Fraud: Less immediate notification checks by users.

🌆 6 PM
- End-of-Day Fatigue: Reduced vigilance from employees/customers.
- Pre-Closure Rush: Fraudsters exploit limited verification time.


**You can interact with the live visualization [HERE](https://github.com/Jean-et/Bank-Fraud-Analysis-/blob/main/Report%20on%20Fraud%20Power%20BI.pbix)**


# Recommendations & Conclusion 
## Fraud Prevention 
- Wider Device Security Needed: Fraud occurs across all platforms, so enhanced multi-channel security & behavioral analytics must cover POS, ATMs, desktops, and mobile banking.

- Merchant Fraud Detection Systems: Fraud is more common in retail transactions (clothing, groceries, restaurants), so merchant transaction monitoring, merchant verification & AI-based fraud scoring should be strengthened to mitigate the occurrences of fraud.

- Stronger Business Account Protection: Business accounts experience the highest fraud rate, requiring better authentication and real-time risk monitoring. Implement stricter authentication & transaction limits.

- Enhanced Nighttime Monitoring: Fraud occurs mostly during late-night hours, suggesting a need for automated fraud detection systems that function 24/7. Implement AI-powered anomaly detection for unusual hours.

- Geographical Risk Management: Banks should strengthen fraud detection in high-risk locations and impose extra authentication steps for transactions originating from remote areas. Increase fraud monitoring in less urbanized regions.

- Deploy AI-powered real-time fraud detection to flag unusual transactions (e.g., rapid high-value payments or activity from high-risk locations) and Strengthen authentication with MFA for high-value transactions and biometric verification (fingerprint/facial recognition) for mobile banking.

## To Conclude
The analysis of bank transactions highlights significant fraud risks across various channels, including online, ATM, and POS transactions. Fraud is prevalent in business accounts, certain merchant categories, and specific geographic locations, with high occurrences during off-peak hours. The proposed fraud mitigation strategies will significantly reduce fraudulent activities. Implementing these measures, along with customer awareness programs and regulatory compliance checks, will enhance the security of LOL Bank Pvt. Ltd.’s banking operations. A proactive and adaptive fraud prevention approach will ensure long-term protection against evolving financial threats while protecting customer’s assets.






