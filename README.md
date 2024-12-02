# Customer Banking System

## Description
The Customer Banking System is a Python project that simulates basic banking functionalities, allowing users to create and manage savings and certificate of deposit (CD) accounts. Users can input their initial balance, interest rate, and duration in months to calculate interest earned and updated account balances. This project demonstrates object-oriented programming concepts, including the creation of classes and methods, as well as calculations based on user input.

## Features
- Creation of savings and CD accounts
- Interest calculation based on user-defined parameters
- Updated balance display following interest accrual
- User-friendly input prompts

## Requirements
- Python 3.x
- Basic understanding of Python programming
- Files included:
  - `Accounts.py`: Contains the `Account` class with methods for balance and interest management
  - `savings_account.py`: Implements the savings account functionality
  - `cd_account.py`: Implements the CD account functionality
  - `customer_banking.py`: Main interface for user interaction

## Installation
To set up the project, follow these instructions:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-banking-system
   ```

## Usage
1. Run the main program:
   ```bash
   python customer_banking.py
   ```
2. Follow the prompts to enter details for the savings and CD accounts:
   - Enter the initial balance
   - Input the interest rate (APR)
   - Specify the number of months to calculate interest
3. The program will display the interest earned and the updated account balances.

## Example
```
Enter savings account balance: 1000
Enter savings account interest rate (APR): 5
Enter number of months for savings account: 12
Interest earned on savings account: $50.00
Updated savings account balance: $1050.00

Enter CD account balance: 2000
Enter CD account interest rate (APR): 3
Enter number of months for CD account: 6
Interest earned on CD account: $30.00
Updated CD account balance: $2030.00
```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.



 
