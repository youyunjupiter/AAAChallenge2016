#AAAChallenge2016

##Basic Info
- Problem statement: to predict re-admission to hospital for diabetes patients. This is represented by the field called 'readmitted' in the training data.
- Evaluation method: AUC (Area Under Curve: Curve of true positive v.s. false positive. Good predictioin gives close to 1 AUC and bad preiction gives around 0.5 AUC.)
- Data: (<https://inclass.kaggle.com/c/sas-analytics-challenge/data>)
	More details: (<https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008>)

##Background
- Standard for A1Cresult: (<http://www.diabetes.co.uk/what-is-hba1c.html>)  
	Relation between A1C and blook glucose test: Blood glucose level is the concentration of glucose in your blood at a single point in time, i.e. the very moment of the test.This is measured using a fasting plasma glucose test, which can be carried out using blood taken from a finger or can be taken from a blood sample from the arm. However, fasting glucose tests provide an indication of your current glucose levels only, whereas the HbA1c test serves as an overall marker of what your average levels are over a period of 2-3 months. 
	
	| HbA1c       	|       mmol/mol      	|            % 	|
	|-------------	|:-------------------:	|-------------:	|
	| Normal      	|  Below 42 mmol/mol  	|   Below 6.0% 	|
	| Prediabetes 	|  42 to 47 mmol/mol  	| 6.0% to 6.4% 	|
	| Diabetes    	| 48 mmol/mol or over 	| 6.5% or over 	|
- Hoslital readmission:Readmissions are defined as an admission into any hospital within 30 days of a previous (or “index”) admission. Individual patients were followed regardless of whether the second admission was into the same or a different hospital. There is also no separation regarding whether the conditions that resulted in the second admission were in any way related to the earlier admission. For example, someone who was admitted the first time for symptoms relating to severe diabetes might show up as a readmission two weeks later because of an allergic reaction to a bee sting. (<http://www.hcup-us.ahrq.gov/reports/statbriefs/sb172-Conditions-Readmissions-Payer.pdf>)
 
##Impact on Insurance
- In summary, considering the high cose of diabetes treatment and increasing readmission rate in general hospital in Singapore, studying the factors for readmission prediction might help underwritter better assess the risk and actuaries propose premiem. 

- In Singapore,  
		■ The prevalence of DM has risen to 12.3% in 2013, from 8.2% in 2004 and 9% in 1998 [5–7], surpassing other Asian countries such as Hong Kong (9.5%), Japan (7.2%) and Taiwan (5.7%) [8]. Moreover, DM is the tenth leading cause of death in Singapore, accounting for 1.7% of total deaths in 2011 [9]. (<http://scholarbank.nus.edu.sg/bitstream/handle/10635/121587/2015-direct_medical_cost_type_diabetes-pub.pdf?sequence=1>)  
		■ The readmission rate for patients within 30 days after discharge from public hospitals was 11.7% in 2011 and 12.2% in both 2012 and 2013. Overall, our public hospital/ institution readmission rates are comparable to the United States, but higher than some other countries such as the United Kingdom.Several factors contribute to readmissions, such as the patient’s conditions and disease type, the quality of inpatient care, the transitions to primary and community care, and the follow-up care, including rehabilitation care. The home environment and family support is also an important contributing factor.  Readmission rates also vary across hospitals due to the different casemix (i.e. type and range of cases seen).(<https://www.moh.gov.sg/content/moh_web/home/pressRoom/Parliamentary_QA/2014/hospital-readmission-rates.html>)

- US has been working hard to reduce high readmission rate to reduce financial burden for medicare and improve health care quality.   
		■ In 2011, there were approximately 3.3 million adult 30-day all-cause hospital readmissions in the United States, and they were associated with about $41.3 billion in hospital costs.  
		■ For Medicaid patients, the three conditions with the largest number of 30-day all-cause readmissions were mood disorders (41,600
readmissions), schizophrenia (35,800 readmissions), and diabetes (23,700 readmissions). These conditions resulted in
about $839 million in hospital costs.  (<http://www.hcup-us.ahrq.gov/reports/statbriefs/sb172-Conditions-Readmissions-Payer.pdf>)
		■ Hospital Readmission Reduction Program (HRRP), established by the Centers for Medicare and Medicaid Services (CMS) has set its initiative on reducing the frequency of Medicare readmissions. In spite of recent improvements, the US still has the highest readmission rates compared to other developed countries (Dorland Health 2014; Joynt and Jha 2013; Kociol et al. 2012). While these findings suggest that readmission rates in the US are excessive and reducible, according to Sommers and Cunningham (2011), until wide-spread efforts are made to prevent readmission, the US healthcare system will shoulder a $16 billion burden (<http://misrc.umn.edu/wise/2014_Papers/63.pdf>)




