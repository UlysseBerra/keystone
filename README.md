# Payment System

## Project Overview
The project aims to develop a secure and efficient Java-based payment system. This document outlines the requirements and specifications for the development team.

## Objectives
1. Implement a user authentication and authorization system using a token-based approach.
2. Ensure end-to-end encryption for sensitive transaction data.
3. Utilize PostgreSQL for relational database management, storing user accounts, and transaction history.

## Functional Requirements

### User Authentication and Authorization
1. **User Registration:**
   - Users should be able to register by providing necessary information.
   - Implement validation checks for user input.

2. **User Login:**
   - Secure user login with token-based authentication.
   - Include a "forgot password" mechanism.

### Transaction Management

1. **Transaction Processing:**
   - Allow users to initiate financial transactions securely.
   - Implement validation checks for transaction data.

2. **End-to-End Encryption:**
   - Ensure that all transaction data is encrypted end-to-end.

### Database Management

1. **User Accounts:**
   - Store user data securely in a relational database.
   - Include necessary fields such as username, email, and *hashed* passwords.

2. **Transaction History:**
   - Maintain a comprehensive transaction history for each user.
   - Design an efficient database schema to store transaction data.

## Non-Functional Requirements

### Security

1. **Data Encryption:**
   - Employ encryption algorithms for data security.

2. **Authorization Control:**
   - Define access controls to restrict unauthorized access to sensitive data.

### Usability

1. **User Interface:**
   - Create an intuitive and user-friendly interface for good user interaction.

2. **Error Handling:**
   - Implement clear error messages and handling mechanisms.

## Deadlines

- 2023-11-29: project setup + database integration
- 2023-12-06: transaction processing w/ encryption
- 2023-12-20: accounts + auth
- 2024-01-10: GUI/web access

## Technologies

- Backend: REST API written in Java and Kotlin using the Spring Boot framework to communicate with a PostgreSQL database
- Frontend: SvelteKit frontend using Svelte to call the API
- Misc: Git versioning system with GitHub repository, IntelliJ IDEA for backend and VSCode for frontend

## Task Sharing

- Samuel
    - backend logic
        - including but not limited to encryption + password hashing
- Ulysse
    - frontend development
    - database integration
    - API design

Happy coding!