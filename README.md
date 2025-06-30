# 💰 Bank Account Simulation in Java

This Java console application simulates a simple **bank account system** that allows users to perform basic banking operations such as deposits, withdrawals, viewing balance, and transaction history.

## 📌 Features

* ✅ Create a bank account with an initial balance
* 💵 Deposit money
* 💸 Withdraw money
* 📊 View current balance
* 📜 View detailed transaction history
* 📁 Simple and clean console-based user interface

## 🛠️ Technologies Used

* Java (Core Java)
* Java Collections (`ArrayList`)
* Scanner for console input

## 🧾 How It Works

1. User enters their name, account number, and initial balance.
2. The menu offers the following options:

   * Deposit money
   * Withdraw money
   * View current balance
   * View transaction history
   * Exit the application

Each transaction is stored in a history log for future reference.

## 🧪 Sample Run

```text
Welcome to the Bank Account Simulation
Enter Account Holder Name: Vishnu
Enter Account Number: 1234567890
Enter Initial Balance: 5000

--- Menu ---
1. Deposit
2. Withdraw
3. View Balance
4. View Transaction History
5. Exit
Enter your choice: 1
Enter deposit amount: 2000
Deposit successful.

--- Menu ---
Enter your choice: 2
Enter withdrawal amount: 1000
Withdrawal successful.

--- Menu ---
Enter your choice: 3
Current Balance: $6000.0

--- Menu ---
Enter your choice: 4

Transaction History:
Account created with balance: $5000.0
Deposited: $2000.0
Withdrawn: $1000.0
```

## 🚀 How to Run

### Prerequisites

* Java JDK installed (version 8 or above)
* A text editor or IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)

### Steps

1. Save the code in a file named `BankAccountSimulation.java`.
2. Open terminal/command prompt.
3. Compile the program:

   ```bash
   javac BankAccountSimulation.java
   ```
4. Run the compiled program:

   ```bash
   java BankAccountSimulation
   ```

## 📂 Project Structure

```
BankAccountSimulation.java
README.md
```

## 📌 Note

* The application does **not use file storage** or databases. All account data and transaction history are stored in memory and will reset after the program exits.

## 🙋‍♂️ Author

**Vishnu Vardhan Reddy Madadi**

---

