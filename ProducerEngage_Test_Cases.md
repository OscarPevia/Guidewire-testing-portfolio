# Guidewire ProducerEngage Test Cases

## Overview

Sample test cases demonstrating ProducerEngage workflow validation, customer access, policy viewing, document access, and search functionality.

---

## TC-PE-001

### Title
Verify customer search returns correct account

### Priority
High

### Steps

1. Enter customer name
2. Execute search

### Expected Result

Correct customer account is displayed.

---

## TC-PE-002

### Title
Verify customer search using account number

### Priority
High

### Steps

1. Enter account number
2. Execute search

### Expected Result

Matching account is returned.

---

## TC-PE-003

### Title
Verify policy details display correctly

### Priority
High

### Steps

1. Open customer account
2. Select policy

### Expected Result

Policy information displays correctly.

---

## TC-PE-004

### Title
Verify active policies are visible

### Priority
Medium

### Steps

1. Open customer profile
2. Review policy list

### Expected Result

All active policies are displayed.

---

## TC-PE-005

### Title
Verify document download functionality

### Priority
High

### Steps

1. Open customer policy
2. Select document
3. Download file

### Expected Result

Document downloads successfully.

---

## TC-PE-006

### Title
Verify declaration page access

### Priority
Medium

### Steps

1. Open policy
2. Select declaration page

### Expected Result

Declaration page opens successfully.

---

## TC-PE-007

### Title
Verify customer contact information display

### Priority
Medium

### Steps

1. Open customer account

### Expected Result

Customer contact information is displayed accurately.

---

## TC-PE-008

### Title
Verify navigation to billing information

### Priority
Medium

### Steps

1. Open customer account
2. Select billing information

### Expected Result

Billing information displays successfully.

---

## TC-PE-009

### Title
Verify user permissions restrict unauthorized access

### Priority
High

### Steps

1. Login with restricted user
2. Attempt unauthorized action

### Expected Result

Access is denied.

---

## TC-PE-010

### Title
Verify hyperlinks navigate to correct pages

### Priority
Medium

### Steps

1. Open customer profile
2. Select available links

### Expected Result

Links navigate correctly without errors.

---

## Summary

Coverage Areas:

- Customer Search
- Account Access
- Policy Viewing
- Document Access
- Contact Information
- Billing Information
- Permissions Testing
- Navigation Validation
