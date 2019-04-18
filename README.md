# Healthcare-Claim-Analysis
An analysis of the factors correlated with costs of healthcare
Summary:
The factors that influence healthcare costs are notoriously hard to decipher. Costs associated with common procedures vary widely from patient to patient, even when controlling for geographic location, care setting, and complications. I took a deep dive into a set of health insurance claims data with the intention of creating a model that could predict costs for a common procedure and identify the factors associated with higher costs. 

Data Source:
Received from Octavia LLC, a startup formerly incubated by Intellectual Ventures whose focus was on providing information to enable patients to make more informed healthcare decisions. The data represents a small portion of the Health Insurance Claims filed in the State of Utah during the year 2016.

Feature Engineering: 
Nine features were engineered to improve model performance, including notably:
•	Whether the procedure was performed on a weekend
•	Whether the claim was part of capitation plan
•	Care Setting
•	Geographic Location

Models:
 Linear Regression, Random Forest Regression, and Gradient Boosting Regression

Tools Used:
Pandas, NumPy, sklearn, matplotlib

Results: 
What I found is that the costs are impossible to predict and seem to be not influenced by identifiable features or market forces. However, patterns emerge in the data that invite further modeling and analysis.
