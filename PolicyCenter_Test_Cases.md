# Guidewire PolicyCenter Test Cases

## Overview

This document contains sample test cases demonstrating Guidewire PolicyCenter workflow validation, policy administration testing, and regression testing activities.

---

# New Business

## TC-PC-001

### Title
Verify New Business policy can be created successfully.

### Priority
High

### Preconditions
- Customer record exists
- Product is available

### Steps
1. Create new account
2. Enter customer information
3. Select policy product
4. Complete quote
5. Bind policy

### Expected Result
Policy is successfully created and a policy number is generated.

---

## TC-PC-002

### Title
Verify required fields are enforced during New Business quote creation.

### Priority
High

### Steps
1. Start new quote
2. Leave required fields blank
3. Attempt to continue

### Expected Result
Validation messages appear and quote cannot proceed.

---

## TC-PC-003

### Title
Verify policy premium is generated after quote completion.

### Priority
High

### Steps
1. Create new quote
2. Enter valid risk information
3. Complete quote process

### Expected Result
Premium is calculated successfully.

---

# Rewrite Flow

## TC-PC-004

### Title
Verify rewrite transaction can be initiated.

### Priority
High

### Preconditions
- Existing policy available

### Steps
1. Open policy
2. Select Rewrite Transaction
3. Complete rewrite workflow

### Expected Result
Rewrite transaction completes successfully.

---

## TC-PC-005

### Title
Verify original policy information is retained during rewrite.

### Priority
Medium

### Steps
1. Process rewrite
2. Compare source and rewritten policy

### Expected Result
Required policy data is preserved.

---

# Renewal Testing

## TC-PC-006

### Title
Verify policy renewal job is generated.

### Priority
High

### Steps
1. Locate eligible policy
2. Run renewal process

### Expected Result
Renewal job is created.

---

## TC-PC-007

### Title
Verify renewal premium calculation.

### Priority
High

### Steps
1. Generate renewal quote
2. Review premium details

### Expected Result
Premium is calculated according to business rules.

---

## TC-PC-008

### Title
Verify renewal notice document is generated.

### Priority
High

### Steps
1. Complete renewal process
2. Access generated documents

### Expected Result
Renewal notice is available.

---

# Reinstatement Testing

## TC-PC-009

### Title
Verify canceled policy can be reinstated.

### Priority
High

### Steps
1. Select canceled policy
2. Initiate reinstatement
3. Complete transaction

### Expected Result
Policy status changes to Active.

---

## TC-PC-010

### Title
Verify reinstatement effective date.

### Priority
Medium

### Steps
1. Reinstate canceled policy
2. Review policy dates

### Expected Result
Effective date matches business requirements.

---

# Location Restrictions

## TC-PC-011

### Title
Verify restricted location cannot be added.

### Priority
High

### Steps
1. Create quote
2. Enter restricted location

### Expected Result
System displays restriction message.

---

## TC-PC-012

### Title
Verify approved location can be added.

### Priority
Medium

### Steps
1. Create quote
2. Enter approved location

### Expected Result
Location is accepted successfully.

---

# Rate Change Validation

## TC-PC-013

### Title
Verify updated rates are applied to new business quotes.

### Priority
High

### Steps
1. Create quote after rate deployment
2. Review premium

### Expected Result
New rates are reflected.

---

## TC-PC-014

### Title
Verify existing quotes use correct rate version.

### Priority
High

### Steps
1. Access existing quote
2. Review rating details

### Expected Result
Correct rate table version is applied.

---

# New Line Validation

## TC-PC-015

### Title
Verify new line of business can be added to policy.

### Priority
High

### Steps
1. Open policy
2. Add new line

### Expected Result
Line is added successfully.

---

## TC-PC-016

### Title
Verify mandatory fields for new line.

### Priority
Medium

### Steps
1. Add line
2. Leave required fields blank

### Expected Result
Validation messages appear.

---

# Document Validation

## TC-PC-017

### Title
Verify declaration page generation.

### Priority
High

### Steps
1. Bind policy
2. Generate documents

### Expected Result
Declaration page is generated correctly.

---

## TC-PC-018

### Title
Verify policy packet generation.

### Priority
High

### Steps
1. Complete policy binding
2. Review documents

### Expected Result
Policy packet is generated successfully.

---

## TC-PC-019

### Title
Verify customer information appears correctly on documents.

### Priority
High

### Steps
1. Generate policy documents
2. Compare document data to policy data

### Expected Result
Information matches exactly.

---

## TC-PC-020

### Title
Verify document generation after endorsement.

### Priority
Medium

### Steps
1. Process endorsement
2. Generate documents

### Expected Result
Updated documents are produced successfully.

---

# Summary

Coverage Areas:

- New Business
- Rewrite Transactions
- Renewals
- Reinstatements
- Location Restrictions
- Rate Changes
- New Lines of Business
- Policy Documents
- Validation Rules
- Regression Testing
