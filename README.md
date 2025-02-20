# **Implement an `BankAccount` Class**
### **Objective**
In this assignment, you will create a `BankAccount` class with attributes for an account holder's details, checking and savings balances, and methods to deposit, withdraw, and transfer money.

### **Instructions**
1. Define a class called `BankAccount` with the following **attributes**:
   - `account_holder` (string): Name of the account holder.
   - `account_number` (integer): A unique account number.
   - `address` (string): Address of the account holder.
   - `checking` (float): The balance in the checking account.
   - `savings` (float): The balance in the savings account.

2. Implement the following **methods**:
   - `deposit(amount, account_type)`: Adds money to either the checking or savings account.
   - `withdraw(amount, account_type)`: Deducts money from the specified account if sufficient funds are available.
   - `transfer(amount, from_account, to_account)`: Moves money between checking and savings if sufficient funds exist.
   - `get_balance(account_type)`: Returns the balance of either checking or savings.
   - `__str__()`: Returns a string representation of the account details.

3. Write a test program that:
   - Creates two `BankAccount` objects with different account holders.
   - Deposits and withdraws money.
   - Transfers money between checking and savings.
   - Prints account details using `__str__()`.

### **Example Output**
```plaintext
Account Holder: John Doe
Address: 123 Main St
Account Number: 123456
Checking Balance: $500.00
Savings Balance: $1,000.00

Depositing $200 into checking...
New Checking Balance: $700.00

Withdrawing $300 from savings...
New Savings Balance: $700.00

Transferring $200 from checking to savings...
Transfer successful. New balances:
Checking: $500.00
Savings: $900.00

Withdrawing $1,200 from savings...
Insufficient funds!

Final Account Details:
Account Holder: John Doe
Address: 123 Main St
Account Number: 123456
Checking Balance: $500.00
Savings Balance: $900.00
```

