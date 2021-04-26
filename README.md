# Data-Science-Portfolio3-Bank-Term-Deposit-Subscription-Prediction

# Table Of Contents:

### Objective Of The Project
- A Portuguese Banking Institution needs to understand which of their existing customers are most likely to invest in a term deposit. They launched a tele-marketing campaign to run an experiment on approximately 41000 customers and analyse the differences between the ones who do opt for a TD and the ones who do not.

### What is the need of this analysis?
- If with the use of data visualisation and statistical analysis, it can be comprehensively confirmed, how the customers who agrees to procure a TD is different from the customers who do not, the organization can further use these discovered differences to establish the profile of their potential customers and focus more on the customers that closely resemble the profile of the potential customers to the business.
- So, By performing the exploratory data analysis on this bank marketing dataset the aim is to gather patterns and insights that can help the bank to attract more customers for its 'term deposit' campaign which in tern will help to grow the business.
- positive class = customers who agree to procure a TD (y = yes)
- negative class = customers who agree to procure a TD (y = no)

### What is explored?
- Performed data-driven analysis to discover the profile of customers who are most likely to buy the Term Deposit. The profile is discovered by investigating the data points available using different analysis lile - take one feature at a time i.e. univariate analysis, also with multiple data points visualized together i.e bi-variate analysis.

### Technical Aspect
The project is divided into major 6 parts:
- Data Quality Check or inspection of the data.
- Descriptive statitics or summary statistics.
- Exploratory Data Analysis.
- Data Pre-processing.
- Model Building.
- Model Evaluation.
- Conclusion.

### About the dataset: Feature information:
##### bank client data:
- age (numeric)
- job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
- marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
- education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
- default: has credit in default? (categorical: 'no','yes','unknown')
- housing: has housing loan? (categorical: 'no','yes','unknown')
- loan: has personal loan? (categorical: 'no','yes','unknown')

##### data related with the last contact of the current campaign:
- contact: contact communication type (categorical: 'cellular','telephone')
- month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
- day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
- duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

##### Other features:
- campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
- pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
- previous: number of contacts performed before this campaign and for this client (numeric)
- poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

##### social and economic context attributes
- emp.var.rate: employment variation rate - quarterly indicator (numeric)
- cons.price.idx: consumer price index - monthly indicator (numeric)
- cons.conf.idx: consumer confidence index - monthly indicator (numeric)
- euribor3m: euribor 3 month rate - daily indicator (numeric)
- nr.employed: number of employees - quarterly indicator (numeric)


### Challenges Faced
- Data cleaning
- High number of features
- Handling multi labelled categorical columns

### Conclusion

