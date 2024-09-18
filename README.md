
# Demo Bank Software - Manual Testing

This project is a manual testing framework for the  Bank web application. The application provides an online banking platform with basic functionalities for customers and managers. This README provides an overview of the project's features, requirements, and how to navigate through the testing process.
## Mind Mapping
![Bank](https://github.com/user-attachments/assets/802366d7-c2c6-45d9-8507-627d8b746ef2)


## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [User Roles](#user-roles)
4. [Modules](#modules)
5. [Requirements](#requirements)
6. [Getting Started](#getting-started)
7. [Usage](#usage)
8. [Testing Scope](#testing-scope)
9. [Documentation](#documentation)
10. [Contact](#contact)

## Introduction

The Bank project aims to provide an online banking facility with limited initial features, with plans to expand functionality over time. This project focuses on manual testing of the current features provided.

## Features

- Customer and Manager login
- Basic banking functionalities like balance inquiry, fund transfer, mini statements, etc.
- Customer management (Add, Edit, Delete)
- Account management (Add, Edit, Delete)
- Security features like change password

## User Roles

- **Manager**: Has access to customer and account management functions.
- **Customer**: Can access personal banking functions such as fund transfer, balance inquiry, etc.

## Modules

### Manager Modules
- Add, Edit, Delete Customer
- Add, Edit, Delete Account
- Fund Transfer
- Deposit, Withdrawal
- Mini Statement
- Customized Statement

### Customer Modules
- Balance Inquiry
- Fund Transfer
- Mini Statement
- Customized Statement
- Change Password

## Requirements

### Software Requirements
- **Browser**: Google Chrome (version 27 or above)
- **Operating System**: Cross-platform support (Windows, Linux, macOS)

### Technical Requirements
- Web-based application compatible with modern web browsers.
- Easy to use and intuitive interface for users with basic computer knowledge.

## Getting Started

To begin testing the Guru99 Bank application:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sadmanpieal/demo_bank_software_manual_testing.git
    ```

2. **Access the Application**:
   - Open the application in Google Chrome.

3. **Test Scenarios**:
   - Test scenarios and cases can be found in the `test-cases` directory (if available).

## Usage

### Login

- **Manager**: Access managerial functions like customer and account management.
- **Customer**: Access personal banking features like balance inquiry and fund transfer.

### Sample Functionalities

- **Add Customer (Manager)**:
  - Navigate to "Add Customer" and fill in the necessary fields.
- **Fund Transfer (Customer)**:
  - Select "Fund Transfer" and provide source and destination account numbers along with the amount.

## Testing Scope

- **In-Scope**: Functional testing of features like login, fund transfer, balance inquiry, etc.
- **Out-of-Scope**: Non-functional testing like performance, stress testing, and automation testing.

## Documentation

- **Software Requirements Specification**: Details about the functional and non-functional requirements.
- **Mockups**: Visual representations of key pages and functionalities.

For detailed documentation, refer to:
- [Software Requirements Specification (SRS)](SRS_V1.pdf)
- [Mockup Designs](Mockup Design.pdf)
