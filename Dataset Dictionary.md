### 1. Age: (numeric)age of the client who might have taken loan

2. Job: type of job of the client (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3. Marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4. Education: Education of the client is mentioned(categorical: primary, secondary, tertiary and unknown) The level of education has significant impact on the amount of balance client has.

5. Default: has credit in default? (categorical: 'no','yes','unknown')

6. Balance: Balance of the individual client in the bank account
7. Housing: if the client has taken housing loan or not (categorical: 'no','yes','unknown')
8. Loan: has personal loan or no is given in the respective columb (categorical: 'no','yes','unknown')
9. Contact - it describes the contact details of the client i.e whether the contact is cellular,unknown or telephone
10. Day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11. Month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
12. Duration: last contact duration, in seconds (numeric).
13. Campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
14. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
15. previous: number of contacts performed before this campaign and for this client (numeric)
16. poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
17. Output variable (desired target): Y: has the client subscribed a term deposit? (binary: 'yes','no')
