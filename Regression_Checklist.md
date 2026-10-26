# Guidewire Regression Testing Checklist

## Overview

This checklist represents a sample regression suite used to validate critical business functionality after application changes, enhancements, or production fixes.

---

# PolicyCenter Regression

## New Business

- Verify account creation
- Verify quote generation
- Verify premium calculation
- Verify policy binding
- Verify policy issuance

## Rewrite Transactions

- Verify rewrite initiation
- Verify policy information retention
- Verify premium recalculation
- Verify successful policy issuance

## Renewals

- Verify renewal job creation
- Verify renewal quoting
- Verify premium calculation
- Verify renewal issuance
- Verify renewal document generation

## Reinstatements

- Verify policy reinstatement
- Verify reinstatement effective dates
- Verify premium validation

## Rate Changes

- Verify updated rates apply correctly
- Verify existing business uses appropriate rate version
- Verify premium calculations remain accurate

## Documents

- Verify declaration page generation
- Verify policy packet generation
- Verify renewal notices
- Verify endorsement documents

---

# ClaimsCenter Regression

## Claim Processing

- Verify claim creation
- Verify claim updates
- Verify claim search functionality
- Verify claim status transitions

## Payment Processing

- Verify payment creation
- Verify payment approval workflow
- Verify payment subtype mapping
- Verify payment issuance

## Integrations

- Verify downstream claim mappings
- Verify payment data mappings
- Verify claim synchronization

## Attachments

- Verify document upload
- Verify attachment retrieval
- Verify document visibility

---

# BillingCenter Regression

## Billing Accounts

- Verify billing account creation
- Verify billing account updates

## Payments

- Verify single payments
- Verify bulk payments
- Verify payment reversal processing

## Billing Workflows

- Verify invoice generation
- Verify billing statements
- Verify payment posting

---

# ProducerEngage Regression

## Policy Access

- Verify policy search
- Verify policy details display
- Verify quoting workflow

## Customer Access

- Verify customer search
- Verify customer profile display
- Verify account navigation

## Documents

- Verify document access
- Verify document download
- Verify document visibility

---

# User Access & Permissions

## Manager Permissions

- Verify manager account access
- Verify employee account switching

## Underwriter Permissions

- Verify account reassignment
- Verify underwriting access controls

## Security Validation

- Verify restricted users cannot access protected functionality
- Verify role-based permissions

---

# Exit Criteria

Regression testing is considered complete when:

- All critical test scenarios have executed
- No unresolved critical defects remain
- High-severity issues have been addressed
- Test evidence has been documented
- Business stakeholders approve results
