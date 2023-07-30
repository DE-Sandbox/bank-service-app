# Business Requirements Document (BRD) for Bank Payments Service App

## 1. Introduction

### 1.1 Purpose
The purpose of this document is to outline the business requirements for the development of a payments service app for a bank. The app aims to provide customers with a convenient and secure platform to perform various payment-related activities.

### 1.2 Scope
The payments service app will include the following features:
1. User Registration and Authentication: Allow users to register and authenticate securely to access their accounts.
2. Account Dashboard: Provide customers with a personalized dashboard displaying account information and transaction summaries.
3. Bill Payments: Enable customers to pay bills for utilities, credit cards, loans, etc., directly through the app.
4. Transaction History: Allow customers to view their transaction history with detailed information about each transaction.
5. Transfer: Enable customers to transfer funds between their own accounts and to other parties using IBAN transfers.

## 2. Business Objectives

### 2.1 Improved Customer Experience
The app should offer a user-friendly and intuitive interface that enhances the overall customer experience when conducting financial transactions.

### 2.2 Secure Transactions
Security is of utmost importance. The app must employ robust encryption and authentication mechanisms to ensure the safety and confidentiality of customer data and transactions.

### 2.3 Payment Efficiency
The app should enable fast and seamless payment processing, reducing transaction processing times and increasing efficiency.

## 3. Features and Functionality

### 3.1 User Registration and Authentication

- Users should be able to register using their bank account credentials or through multi-factor authentication (MFA).

### 3.2 Account Dashboard

- Customers should have access to a personalized dashboard displaying account balance, recent transactions, and a summary of their payment activities.

### 3.3 Bill Payments

- Customers should be able to pay bills for utilities, credit cards, loans, etc., directly through the app.
- Option to save and manage biller information for quick and easy payments.

### 3.4 Transaction History

- Customers should be able to view their transaction history with detailed information about each transaction.

### 3.5 Transfer

- Customers should be able to transfer funds between their own accounts within the bank using IBAN transfers.
- Customers should be able to initiate outgoing transfers to other parties using recipient IBAN account numbers.

### 3.6 Security Features

- Multi-layered security to prevent unauthorized access and fraud detection mechanisms.
- Two-factor authentication for sensitive operations.

## 4. Non-Functional Requirements

### 4.1 Performance

- The app should handle a high volume of concurrent users without significant performance degradation.
- Response times for critical operations should be minimized.

### 4.2 Security

- Compliance with industry-standard security protocols and data encryption practices.


### 4.3 Reliability

- The app must be reliable and available for customers at all times, with minimal downtime for maintenance.

## 5. Constraints

Ignored (pet project)

## 6. Assumptions

-- IBAN will be mocked (pet project) 

## 7. Risks

- Possible security vulnerabilities that could lead to unauthorized access or data breaches.
- Technical challenges in integrating with legacy systems or third-party services.

## 8. Approval

Ignored (pet project)
