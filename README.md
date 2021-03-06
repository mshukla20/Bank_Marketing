# Bank_Marketing
Bank-Marketing-Data-Analysis:
Multi variate analysis of Banking Marketing campaigns (over phone) of a Portuguese banking institution. Source of the Data : https://archive.ics.uci.edu/ml/datasets/bank+marketing

## Main Objective:
The main purpose of the analysis is to predict whether a client will subscribe a term deposit or not in this bank.

## Attribute Information:
The dataset consist of 45211 records and 17 attributes.

## Input variables:
Bank Client data:
1 - age (numeric)

2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

5 - default: has credit in default? (categorical: 'no','yes','unknown')

6 - housing: has housing loan? (categorical: 'no','yes','unknown')

7 - loan: has personal loan? (categorical: 'no','yes','unknown')

8 - balance: average yearly balance, in euros (numeric)

## Related with the last contact of the current campaign:
9 - contact: contact communication type (categorical: 'cellular','telephone')

10 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

11 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

12 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

## Other attributes:
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

15 - previous: number of contacts performed before this campaign and for this client (numeric)

16 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

## Social and economic context attributes:
17 - emp.var.rate: employment variation rate - quarterly indicator (numeric)

18 - cons.price.idx: consumer price index - monthly indicator (numeric)

19 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)

20 - euribor3m: euribor 3 month rate - daily indicator (numeric)

21 - nr.employed: number of employees - quarterly indicator (numeric)

## Output variable (desired target):
22 - y - has the client subscribed a term deposit? (binary: 'yes','no')
