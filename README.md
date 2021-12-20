# Utility Company Simulation

A simulation between two banks and a utility company, where the utility company has an account with Bank A and a paying customer will have an account with either Bank A or Bank B.

**NB: This project will be completed after the completion of the Advanced React course I'm currently work on that can be found [HERE](https://github.com/JamieSWE/sick-fits)**

## Technologies to be Used:
1. ASP.NET Core MVC
2. ASP.NET Web API
3. gRPC
4. Bootstrap 
5. Toastr (to handle notifications)

## Project Breakdown:
## Utility Company
### Bill
1. Generate bills for customers

### Administrator
1. CRUD a bill for a customer
2. View all pending bills
3. View all paid bills

### Customer
1. Register with the utility company
2. View his/her pending bills
3. View history of a bills paid
4. Pay their bills in full (using a credit/debit card
- ASP.NET Web API will be used to facilitate communication between the utility company and Bank A
- gRPC will be used to facilitate communication between the utility company and Bank B (*WILL HAVE TO RESEARCH THIS AS I'VE NEVER USED IT BEFORE*)

## Bank A
### Administrator
1. CRUD customer
2. CRUD teller
3. Assign user to a role
### Teller
1. Make deposit to customer accounts
2. Make withdrawal from customer accounts
3. View all customers
4. View all customer transactions
### Customer
1. View all his/her account details
2. View all transactions conducted on his/her account

## Bank B
### Administrator
1. CRUD customer
2. CRUD teller
3. Assign user to a role
### Teller
1. Make deposit to customer accounts
2. Make withdrawal from customer accounts
3. View all customers
4. View all customer transactions
### Customer
1. View all his/her account details
2. View all transactions conducted on his/her account
