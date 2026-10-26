# Guidewire BillingCenter Test Cases

## Overview

Sample test cases covering billing workflows, invoice generation, payment processing, and bulk payment validation.

---

## TC-BC-001

### Title
Verify billing account creation

### Priority
High

### Steps

1. Create customer account
2. Initiate billing account creation
3. Save account

### Expected Result

Billing account is created successfully.

---

## TC-BC-002

### Title
Verify invoice generation

### Priority
High

### Steps

1. Create policy
2. Process billing cycle
3. Review invoice

### Expected Result

Invoice generates successfully with correct premium amount.

---

## TC-BC-003

### Title
Verify single payment processing

### Priority
High

### Steps

1. Locate invoice
2. Submit payment
3. Process transaction

### Expected Result

Payment posts successfully.

---

## TC-BC-004

### Title
Verify bulk payment processing

### Priority
High

### Steps

1. Select multiple invoices
2. Submit bulk payment

### Expected Result

All invoices are paid successfully.

---

## TC-BC-005

### Title
Verify partial payment processing

### Priority
Medium

### Steps

1. Open invoice
2. Submit partial payment

### Expected Result

Remaining balance is calculated correctly.

---

## TC-BC-006

### Title
Verify overpayment handling

### Priority
Medium

### Steps

1. Submit payment greater than invoice balance

### Expected Result

System handles overpayment according to business rules.

---

## TC-BC-007

### Title
Verify payment reversal

### Priority
High

### Steps

1. Process payment
2. Reverse payment

### Expected Result

Payment is reversed successfully.

---

## TC-BC-008

### Title
Verify delinquency processing

### Priority
High

### Steps

1. Allow invoice to become overdue
2. Execute delinquency process

### Expected Result

Account enters delinquency status.

---

## TC-BC-009

### Title
Verify billing statement generation

### Priority
Medium

### Steps

1. Process billing cycle
2. Generate statements

### Expected Result

Statements are generated successfully.

---

## TC-BC-010

### Title
Verify invoice search functionality

### Priority
Low

### Steps

1. Search by invoice number

### Expected Result

Correct invoice is returned.

---

## Summary

Coverage Areas:

- Billing Accounts
- Invoices
- Single Payments
- Bulk Payments
- Partial Payments
- Overpayments
- Payment Reversals
- Delinquency
- Billing Statements
- Search Functionality
