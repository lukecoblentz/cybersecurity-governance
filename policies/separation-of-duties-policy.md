# Separation of Duties & Access Governance Policy

## Overview
This academic security governance project develops a **Separation of Duties (SoD)** policy for **Bankwise Credit Union**, a fictional financial institution. The case study considers how excessive access and overlapping responsibilities can increase the risk of fraud, unauthorized transactions, and human error.

> **Project context:** This is a proposed policy from university coursework, not documentation of a deployed access-control program or a completed compliance audit.

## Objective
- Explain the security purpose of separation of duties.
- Define organizational scope and policy responsibilities.
- Recommend least-privilege and role-based access safeguards.
- Address situations where limited staffing prevents complete duty separation.
- Communicate the business value of SoD to executive leadership.

---

## Security Problem
In the fictional case, one employee had sufficient privileges to both **create and approve transactions** without independent review. Concentrating these responsibilities in one account increases the risk of misconduct or mistakes going undetected.

### Risks Identified
- Fraudulent or unauthorized transactions
- Excessive user privileges
- Conflicts of interest
- Unreviewed administrative changes
- Inadequate accountability

---

## Policy Design

### 1. Policy Statement
Bankwise Credit Union will separate critical job duties so that no individual employee has excessive control over sensitive systems, financial transactions, or organizational information.

### 2. Purpose
Reduce fraud, errors, and unauthorized access while promoting responsible access governance and GLBA-aware information protection.

### 3. Scope
The proposed policy applies to employees, contractors, organizational branches, and Bankwise-owned IT systems, including email, internet access, customer data, and financial systems.

### 4. Proposed Security Controls
- **Least privilege:** Restrict access to what each employee needs for their role.
- **Role-based access:** Assign permissions according to approved job functions.
- **Independent approval:** Have managers authorize access requests.
- **Separate provisioning:** Have IT grant access following approval.
- **Access reviews:** Periodically examine privileges and activity.
- **Logging and monitoring:** Support detection and investigation of inappropriate actions.

### 5. Access Procedures
1. A manager reviews and approves a request for sensitive access.
2. IT grants only the permissions necessary for the approved duties.
3. The organization reviews permissions and relevant activity as needed.
4. Where feasible, employees responsible for initiating sensitive actions are different from those approving them.

### 6. Exceptions & Compensating Controls
Smaller teams may be unable to separate every task across different employees. The proposed policy allows additional approvals, independent reviews, or monitoring as compensating safeguards. Unclear or disputed responsibilities are escalated to management.

---

## Governance Concepts Explored
The research component examined static separation of duties and the challenge of determining whether new permissions create conflicts. The reading discussed an approach to safety checking that filters irrelevant users and permissions to reduce the number of combinations evaluated.

This research was **summarized and analyzed** in the coursework; the project did not implement or benchmark the algorithm.

---

## Executive Recommendation
The central recommendation to Bankwise leadership is to avoid assigning one employee end-to-end control over high-risk financial transactions. Splitting initiation and approval across different individuals makes unauthorized activity harder to conceal and creates a consistent process for handling potential violations.

---

## Key Findings
- Excessive access is both a security and a governance risk.
- Transaction approval and execution should be separated when practical.
- Least privilege, role-based access, and periodic review reinforce SoD.
- Smaller organizations may need documented compensating controls.

## Lessons Learned
- An effective access policy must address both technical permissions and organizational roles.
- Management approval and IT provisioning should not be treated as the same function.
- A policy needs a realistic exception approach when staffing limits ideal segregation.

## Skills Demonstrated
- Separation of duties policy design
- Identity and access governance
- Role-based access and least privilege
- Fraud-risk analysis
- Compensating control selection
- Executive-level security communication

---

## Conclusion
This project proposes a separation of duties policy for a fictional credit union facing overlapping transaction privileges. It demonstrates how clear responsibilities, independent approvals, access reviews, and compensating controls can strengthen accountability and reduce preventable security risks.
