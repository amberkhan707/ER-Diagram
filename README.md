# ER-Diagram
Here you will learn about creation of ER Diagram

# Follow these steps you will be able to draw any ER Diagram
step1- Identify Entity set  
step2- Identify attributes and their types  
step3- Identify relationship and Constraints (i)mapping   
                                            (ii)Participants  
Let's make a ER model of Banking system  
step1:  
Bank  
Branch  
Account  
Loan   
Customers  
  
Step2:  
Bank-{Name,Code,Address} code is primary key 
Branch-{Branch_id,Name,Address} Branch_id is primary key  
Account-{Account type,account no.,Balance} account no. is primary key  
Loan-{Loan_id,loan type,amount} loann_id is primary key  
Customers-{customer_id,name,phone,address}  
  
step3:  
Bank has branck (complete participation) (M:N)  
Branck offers loan (1:N)  
Branck maintain account (1:N)  
Loan Availed by customer (M:N)  
Account hold by customer (M:N)   




                                            
