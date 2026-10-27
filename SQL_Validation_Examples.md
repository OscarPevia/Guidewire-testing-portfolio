# SQL Validation Examples

## Overview

Sample SQL queries used by QA Analysts to validate data integrity, verify business rules, and support application testing.

---

## Validate Missing Policy Numbers

```sql
SELECT *
FROM Policy
WHERE PolicyNumber IS NULL;
```

### Purpose

Identify policies missing required policy numbers.

---

## Validate Duplicate Policies

```sql
SELECT PolicyNumber,
       COUNT(*)
FROM Policy
GROUP BY PolicyNumber
HAVING COUNT(*) > 1;
```

### Purpose

Identify duplicate policy records.

---

## Validate Missing Customer Information

```sql
SELECT *
FROM Customer
WHERE Email IS NULL;
```

### Purpose

Identify customer records with missing email addresses.

---

## Validate Active Policies

```sql
SELECT *
FROM Policy
WHERE Status = 'Active';
```

### Purpose

Verify active policy records.

---

## Validate Renewal Transactions

```sql
SELECT *
FROM PolicyTransaction
WHERE TransactionType = 'Renewal';
```

### Purpose

Verify renewal transactions were created successfully.

---

## Validate Reinstatement Transactions

```sql
SELECT *
FROM PolicyTransaction
WHERE TransactionType = 'Reinstatement';
```

### Purpose

Verify reinstatement records exist.

---

## Validate Claim Records

```sql
SELECT *
FROM Claim
WHERE ClaimNumber IS NOT NULL;
```

### Purpose

Verify claim creation results.

---

## Validate Payment Records

```sql
SELECT *
FROM Payment
WHERE PaymentAmount > 0;
```

### Purpose

Verify issued payments contain valid amounts.

---

## Validate Billing Invoices

```sql
SELECT *
FROM Invoice
WHERE InvoiceStatus = 'Open';
```

### Purpose

Verify invoice generation.

---

## Validate Customer Search Results

```sql
SELECT *
FROM Customer
WHERE CustomerID = 10001;
```

### Purpose

Compare application search results with database records.

---

## Summary

Common QA Uses:

- Data Validation
- Record Verification
- Workflow Validation
- Claims Testing
- Billing Testing
- Policy Testing
- Regression Testing
- UAT Support
