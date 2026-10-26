# Guidewire ClaimsCenter Test Cases

## Overview

Sample test cases demonstrating Guidewire ClaimsCenter workflow validation, claim mappings, payment mappings, and regression testing.

---

## TC-CC-001

### Title
Verify new claim creation

### Priority
High

### Steps

1. Search for policy
2. Create new claim
3. Complete required claim information
4. Save claim

### Expected Result

Claim number is generated successfully.

---

## TC-CC-002

### Title
Verify claim cannot be created without required fields

### Priority
High

### Steps

1. Create new claim
2. Leave required fields blank
3. Attempt to save

### Expected Result

Validation messages appear.

---

## TC-CC-003

### Title
Verify claim status updates correctly

### Priority
Medium

### Steps

1. Open existing claim
2. Update claim status

### Expected Result

Claim status updates successfully.

---

## TC-CC-004

### Title
Verify payment subtype mapping

### Priority
High

### Steps

1. Open claim
2. Create payment
3. Select payment subtype

### Expected Result

Correct subtype mapping is displayed and transmitted downstream.

---

## TC-CC-005

### Title
Verify claim mapping to downstream systems

### Priority
High

### Steps

1. Create claim
2. Trigger integration process
3. Review mapped data

### Expected Result

All required fields map successfully.

---

## TC-CC-006

### Title
Verify payment issuance

### Priority
High

### Steps

1. Open eligible claim
2. Issue payment

### Expected Result

Payment is created successfully.

---

## TC-CC-007

### Title
Verify payment amount validation

### Priority
High

### Steps

1. Create payment
2. Enter invalid payment amount

### Expected Result

Validation message appears.

---

## TC-CC-008

### Title
Verify claim notes can be added

### Priority
Medium

### Steps

1. Open claim
2. Add note
3. Save claim

### Expected Result

Note is displayed successfully.

---

## TC-CC-009

### Title
Verify document attachment upload

### Priority
Medium

### Steps

1. Open claim
2. Upload document

### Expected Result

Document uploads successfully.

---

## TC-CC-010

### Title
Verify claim search by claim number

### Priority
Medium

### Steps

1. Enter claim number
2. Execute search

### Expected Result

Correct claim record is returned.

---

## Summary

Coverage Areas:

- Claim Creation
- Claim Validation
- Payment Processing
- Payment Subtype Mappings
- Claims Mappings
- Integration Validation
- Notes and Attachments
- Search Functionality
- Regression Testing
