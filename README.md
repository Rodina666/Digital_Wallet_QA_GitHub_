# Digital Wallet QA Portfolio

## Project Overview
A Software Testing / QA portfolio project for a **fictional Digital Wallet demo application**.

The project covers:
- Functional testing
- API testing
- Negative testing
- Boundary Value Analysis
- Equivalence Partitioning
- Regression testing
- Authorization testing
- Security-oriented negative testing
- Requirement Traceability
- Defect reporting
- Test execution planning

> **Important:** This is a fictional/demo QA project. It is not connected to a real banking or financial service. Execution results are intentionally marked as `TBD` / `NOT EXECUTED` until an actual demo environment is available.

## Application Scope

### In Scope
- Registration
- Login
- OTP
- Balance
- Add Money
- Withdraw
- Transfer
- Beneficiaries
- Transaction History
- Password Change
- Session / Authorization

### Out of Scope
- Real identity verification
- Real banking settlement
- Real-world money movement
- External statement reconciliation
- Penetration testing
- Production security certification

## Repository Structure

```text
01_Requirements/
02_Test_Plan/
03_Test_Scenarios/
04_Test_Cases/
05_Test_Data/
06_API_Testing/
07_Defects/
08_Traceability/
09_Execution/
10_Regression/
11_Evidence/
12_Project_Documentation/
```

## Test Coverage
The portfolio defines 8 primary test scenarios and 8 detailed test cases covering authentication, OTP, balance/withdrawal validation, transfer validation, beneficiary validation, authorization, and transaction history.

## API Testing
The Postman collection contains mock/demo checks for:
- `POST /login`
- `GET /balance`
- `POST /transfer`
- `GET /transactions`

No live financial API is used.

## Defects
The defect examples are **illustrative/sample defects**, not confirmed production issues.

## Evidence
Execution screenshots should be added to `11_Evidence/` only after actual execution against a demo environment.

## Author
Ragaa Amer
