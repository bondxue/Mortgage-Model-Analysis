# Mortgage-Model-Analysis
FRE 9733 Big Data semester project

<<<<<<< HEAD
<<<<<<< HEAD
**in process...**
=======
(**in process...**)
>>>>>>> 14f91d2371e90bcc1ff7184af5c42337b2ce421a


### Mortgage Intro
A typical mortgage in the US has the following structure.
+ A borrower purchases a house, pays 20% of the purchase price and borrows 80%.
+ The house is pledged as collateral for the loan.
+ Each month, the borrower makes payments on the loan.

### Simple Mortgage Model 

In our simplified mortage model, we only include three starting states:

* `Loan is Paid`:  *P*

* `Current`:  *C*

* `30 days delinquent`:  *3*

The next month can be one of three states.

* Borrower makes the payment: *C → C*

* Borrower skips the payment, goes 30 days delinquent: *C → 3*

* Borrower prepays the loan: *C → P*

#### Regressors for a given loan 

* `size`: The size of the loan in dollars at origination

* `LTV`: The loan size as a fraction of house size at origination

* `balance`: the current size of the loan

* `MTMLTV`: The current balance divided by the estimated house value

* `rate`: The interest rate of the loan in the current month

* `incentive`: The difference between rate and the inferred market rate

* `age`: Age of the loan in months

* `status`: (always *C* in this case)

* `next status`: one of {*P, C, 3*}

### Logistic Regression vs Random Forest 


<<<<<<< HEAD

=======

**update soon...**
>>>>>>> db74d97822310f8447d86b5dab65b6c37d4d6fc3
=======

>>>>>>> 14f91d2371e90bcc1ff7184af5c42337b2ce421a
