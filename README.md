# Bank_Marketing

Goal: Predict if the client will subscribe a bank term deposit or not.

Variables:
1.  age (numeric)
2.  job : type of job (categorical: "admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown")
3.  marital : marital status (categorical: "divorced","married","single")
4.  education (categorical: "primary","secondary","tertiary","unknown")
5.  default: has credit in default? (categorical: "no","yes")
6.  housing: has housing loan? (categorical: "no","yes")
7. loan: has personal loan? (categorical: "no","yes")
8. contact: contact communication type (categorical: "cellular","telephone","unknown")
9. day
10. month
11. duration: last contact duration, in seconds (numeric)
12. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric)
14. previous: number of contacts performed before this campaign and for this client (numeric)
15. poutcome: outcome of the previous marketing campaign (categorical: "failure","other","success","unknown")
16. deposit - has the client subscribed a term deposit? (binary: "yes","no")

Machine Learning Model used: Decision Tree Classifier
