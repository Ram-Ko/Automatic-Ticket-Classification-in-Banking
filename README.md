# Automatic-Ticket-Classification-in-Banking

**Problem Description:**
Build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

**About Dataset:**
 Contains complaint description, Complaint ID, Mode in which complaint received and Company Name
 
 **EDA:**
 Removed special charactes from complaint, Lemmatize words and Consider only nouns in the text
 
 **Solution:**
 
 Using topic modelling identify topics like Banking, Credi card, Loan ,Dispute and others 
 Classify the data using topic modelling
 After classifying the data apply Logistic Regression and got 95% accuracy.
