# User Acceptance Testing (UAT) Scenarios

## Overview

This document contains representative UAT scenarios used to validate Guidewire workflows and business requirements.

---

# UAT-001

## Business Process

New Business Policy Creation

### Objective

Validate that users can create and bind a new policy successfully.

### Test Steps

1. Create a new account
2. Enter customer information
3. Select product
4. Complete quote
5. Bind policy

### Expected Business Outcome

Policy is successfully issued and available for servicing.

### Result

Pass

---

# UAT-002

## Business Process

Policy Renewal

### Objective

Validate renewal workflow functionality.

### Test Steps

1. Locate renewable policy
2. Process renewal
3. Review premium
4. Issue renewal

### Expected Business Outcome

Renewed policy is issued with correct premium.

### Result

Pass

---

# UAT-003

## Business Process

Policy Reinstatement

### Objective

Validate reinstatement of canceled policies.

### Test Steps

1. Locate canceled policy
2. Initiate reinstatement
3. Complete workflow

### Expected Business Outcome

Policy returns to active status.

### Result

Pass

---

# UAT-004

## Business Process

Claim Creation

### Objective

Validate users can create a claim against an active policy.

### Test Steps

1. Search for policy
2. Create claim
3. Save claim

### Expected Business Outcome

Claim is created successfully.

### Result

Pass

---

# UAT-005

## Business Process

Payment Processing

### Objective

Validate claim payment processing.

### Test Steps

1. Open claim
2. Create payment
3. Approve payment

### Expected Business Outcome

Payment is successfully issued.

### Result

Pass

---

# UAT-006

## Business Process

Bulk Payment Workflow

### Objective

Validate billing users can process bulk payments.

### Test Steps

1. Select multiple invoices
2. Submit payment
3. Verify posting

### Expected Business Outcome

Payments are applied successfully.

### Result

Pass

---

# UAT-007

## Business Process

Customer Search

### Objective

Validate CRM search functionality.

### Test Steps

1. Search by customer ID
2. Open customer profile

### Expected Business Outcome

Correct customer information is displayed.

### Result

Pass

---

# UAT-008

## Business Process

Manager Account Switching

### Objective

Validate managers can access assigned employee accounts.

### Test Steps

1. Login as manager
2. Select employee account
3. Switch context

### Expected Business Outcome

Manager gains appropriate access.

### Result

Pass

---

# UAT-009

## Business Process

Underwriter Reassignment

### Objective

Validate account reassignment functionality.

### Test Steps

1. Open account
2. Reassign underwriter
3. Save changes

### Expected Business Outcome

Account ownership updates successfully.

### Result

Pass

---

# UAT Sign-Off Criteria

- Critical business workflows validated
- No open critical defects
- Business stakeholders approve test results
- Requirements have been satisfied

## Status

Approved
