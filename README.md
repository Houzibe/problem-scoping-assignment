**-----------------------------------------------------------------------------------------------**<br>
                                  **AI ACCELERATOR PROGRAM** <br>
                                 **PROBLEM SCOPING ASSIGNMENT** <br>
                                            **By** <br>
                                        **Houzibe Denis** <br>
                                       **dhouzibe1@gmail.com** <br>
									**Submitted on 25 February, 2026** <br>
**-----------------------------------------------------------------------------------------------** <br>
**PROBLEM SCOPING** <br>
**1- Problem:** <br>
Anomaly Detection for Suspicious Claims in Health Insurance <br>
**2- Problem Statement:** <br>
Health Insurance Fraud represents billions in annual losses, but the traditional detection systems fail to adapt to evolving fraudulent claims patterns. <br>
**3- Stakeholder Analysis:** <br>
**a. Primary stakeholder:** <br>
-	Health Maintenance Organizations (HMOs): responsible for claims verification and payment. They are the direct financial risk bearer. <br> 
**b. Secondary stakeholder:** <br>
-	Healthcare Providers (Hospitals, Pharmacies, Labs, Opticals, Dentals, etc): They submit claims. <br>
-	Policyholders/patients: They are the beneficiaries and are impacted by rising premiums and potential denial of care if funds are mismanaged. <br>
**c. Tertiary Stakeholder (the regulator & industry body):**
-	The National Health Insurance Authority (NHIA) sets the rules and standards. Also, they define the regulatory framework and reporting requirements. <br>
**4- Current Solutions & Limitations** <br>
**a. Current Solution** <br>
•	Manual Auditing: Claims are reviewed by human auditors after payment or on a random sample basis. This is a slow, expensive, and highly subjective process. <br>
•	Simple Rule-Based Systems: Basic software flags claims that exceed a certain amount, are for a specific high-cost procedure, or come from a provider with a history of issues. For example, "Flag any single claim over ₦500,000." <br>
**b.Limitations of Current Solutions:** <br>
•	Reactive, Not Proactive: Most detection happens after the money has been paid, making recovery difficult and costly. The goal is prevention, not just detection. <br>
•	Inability to Detect Complex Schemes: Simple rules fail to catch sophisticated fraud, such as:
o	Billing for non-existent beneficiaries ("Ghost Patients"). <br>
o	Upcoding: Billing for a more expensive service than was actually performed. <br>
o	Unbundling: Billing for the individual components of a single procedure to get a higher total payment. <br>
o	Collusion: Patients and providers working together to file false claims. <br>

**5- Proposed AI Opportunity:** <br> 
I proposed to develop and deploy an AI-Powered Anomaly Detection Platform for Suspicious Claims in Health Insurance. This system will learn normal patterns of behavior and automatically flag outliers for investigation, making the process proactive, intelligent, and efficient. <br>
The platform will consist of two key AI/ML components: <br>
**a. Supervised Learning Model for Known Fraud:** This model will be trained on historical claims data that have been previously labeled as "fraudulent" or "legitimate." It will learn the complex signatures of known fraud types (upcoding, phantom billing) and automatically flag new claims that closely resemble these past patterns. <br>
**b. Unsupervised Learning Model for Anomaly Detection:** This is the core innovation. Instead of looking for known fraud, this model will learn what "normal" looks like for a specific provider, patient demographic, or procedure. It will then flag statistical anomalies that deviate significantly from the norm. <br>
**6- Success Metrics** <br>
The success of the AI solution will be measured by its impact on efficiency, financial savings, and deterrence.
- Claims Audit Turnaround Time:	From 15 days per batch to 5 days per batch (67% reduction). <br>
- Investigator Cases per Day: 5x increase in high risks claims detection. <br>
- Value of Fraud/Error Detected: From ₦50 million identified/year to ₦150 million identified/year. <br>
**7- Potential Data Sources** <br>
The primary data source is partnering HMO. Historical Claims Data is the most critical dataset.


