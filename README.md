# Email-Banking-System
Email Banking System is a C# application that enables users to perform banking operations such as account creation, deposit, withdrawal, and balance inquiry. It provides seamless integration with email service to send notifications to users for different banking activities. Tech Stack: C#, NET Framework, SMTP, Singleton Pattern

## Features

- **Account Management**: Users can create bank accounts with basic customer details.
- **Deposit and Withdrawal**: Users can deposit money into their accounts and withdraw funds when needed.
- **Balance Inquiry**: Users can check their account balances at any time.
- **Notifications**:
  - SMS Notifications: Users receive SMS alerts for account creation, deposit, withdrawal, and balance inquiry.
  - Email Notifications: Users also receive email notifications for the same banking activities.

## Technologies Used

- **C#**: The project is implemented in C# language, providing a robust and efficient solution.
- **.NET Framework**: Utilizes the .NET Framework for building Windows applications.
- **SMTP Client**: Incorporates SMTP client for sending email notifications.
- **Twilio API**: Integration with Twilio for sending SMS notifications.

## Design Patterns

- **Singleton Pattern**: The `DataManagement` class utilizes the Singleton design pattern to ensure that only one instance of the `Customer` object is created throughout the application's lifecycle. This pattern is implemented to manage customer data efficiently and prevent unnecessary object creation.

## How to Use

1. Clone the repository to your local machine.
2. Open the project in Visual Studio or any compatible IDE.
3. Compile and run the application.
4. Follow the on-screen prompts to navigate through the banking operations.
5. Ensure that SMTP server details are properly configured for email notifications.

## Contributions

Contributions are welcome! If you have any suggestions, bug fixes, or feature enhancements, feel free to open an issue or submit a pull request.


## Authors

- [NURANA ZEYNALLI](https://github.com/Znurana)
