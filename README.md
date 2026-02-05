# Access Control Incident Review, Payroll Transaction

## Overview
This repository documents an investigation into an attempted unauthorized
payroll transaction caused by access control weaknesses. The review
analyzes access log activity, identifies authentication and authorization
failures, and recommends mitigations to reduce the likelihood of similar
incidents in the future.

## Objective
- Review access log data related to a payroll incident
- Identify access control weaknesses
- Distinguish authentication and authorization failures
- Recommend mitigations to improve access controls

## Incident Summary
A payroll deposit was initiated toward an unknown bank account and was
successfully stopped before completion. The finance manager confirmed the
transaction was not authorized. Log analysis indicated that valid user
credentials were used, pointing to access control issues rather than a
technical system failure.

## Findings
The user account involved had sufficient privileges to initiate sensitive
payroll actions without additional verification. Access controls did not
enforce role-based restrictions or separation of duties, allowing a single
account to perform high-risk financial operations.

## Recommendations
- Implement role-based access control to restrict payroll functionality
  to authorized finance personnel.
- Require multi-factor authentication and secondary approval for payroll
  and banking changes.

## Outcome
Strengthening access controls reduces the likelihood of unauthorized
financial activity by limiting access scope and enforcing additional
verification for high risk actions.

---

Prepared by: Sambou Kamissoko  
LinkedIn: https://www.linkedin.com/in/sambouk/
