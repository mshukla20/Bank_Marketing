Age: (numeric)age of the client who might have taken loan

Job: type of job of the client (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
Marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
Education: Education of the client is mentioned(categorical: primary, secondary, tertiary and unknown) The level of education has significant impact on the amount of balance client has.
Default: has credit in default? (categorical: 'no','yes','unknown')
Balance: Balance of the individual client in the bank account
Housing: if the client has taken housing loan or not (categorical: 'no','yes','unknown')
Loan: has personal loan or no is given in the respective columb (categorical: 'no','yes','unknown')
Contact - it describes the contact details of the client i.e whether the contact is cellular,unknown or telephone
Day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
Month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
Duration: last contact duration, in seconds (numeric).
Campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
Output variable (desired target): Y: has the client subscribed a term deposit? (binary: 'yes','no')
