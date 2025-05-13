# ATM_Simulator

💳 ATM Simulation in Java
This project is a console-based ATM Simulation System written in Java. It mimics real-world ATM functionalities including account creation, login authentication, deposits, withdrawals with daily limits, balance inquiry, and PIN management.

🛠 Features
🔐 Secure Login System using Account Number and 4-digit PIN

🧾 Create New Bank Accounts with custom account number, PIN, and initial balance

💰 Withdraw Money with a daily withdrawal limit (₹20,000)

💵 Deposit Money with instant balance update

📊 Check Account Balance

🔁 Change ATM PIN securely

📆 Reset Daily Withdrawal Limit (simulated on logout)

🔄 Flow of Operation
Main Menu:

Create a new account

Login to an existing account

Exit

After Login:

Withdraw Money

Deposit Money

Check Balance

Change PIN

Logout (Resets daily withdrawal limit)

🧑‍💻 Technologies Used
Java (Core)

Console-based I/O

ArrayList to manage multiple bank accounts

Simple object-oriented design (BankAccount class)

📝 Example Usage
plaintext
Copy
Edit
--- ATM Main Menu ---
1. Create Account
2. Login to ATM
3. Exit
Enter your choice: 1
Enter Account Holder Name: Alice
Enter Account Number: 123456
Set 4-digit PIN: 1234
Enter Initial Balance: 50000
Account created successfully!

--- ATM Main Menu ---
2. Login to ATM
Enter Account Number: 123456
Enter PIN: 1234
Login successful!

--- ATM Transaction Menu ---
1. Withdraw Money
2. Deposit Money
3. Check Balance
4. Change PIN
5. Logout
