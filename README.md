# Microsoft Entra Device Code Flow Protection

## Overview

This project demonstrates how Microsoft Entra Conditional Access and Microsoft Graph can be used to evaluate and mitigate risks associated with OAuth Device Code Flow authentication.

The objective was to understand how Device Code Flow operates, identify associated security risks, deploy Conditional Access controls, and validate policy behavior using Microsoft Entra sign-in logs.

---

## What is Device Code Flow?

Device Code Flow is an OAuth 2.0 authentication method designed for devices that have limited input capabilities or do not support a traditional browser experience.

Examples include:

- Smart TVs
- Conference room systems
- IoT devices
- Command-line applications

The flow allows a user to authenticate on a secondary device while granting access to the requesting application.

While legitimate, Device Code Flow has become increasingly relevant from a security perspective because it can be abused in phishing and social engineering attacks.

---

## Project Objectives

- Understand OAuth Device Code Flow authentication.
- Review associated identity security risks.
- Deploy Conditional Access controls.
- Explore Microsoft Graph policy deployment.
- Validate policy behavior through sign-in logs.
- Improve overall identity security posture.

---

## Technologies Used

- Microsoft Entra ID
- Conditional Access
- Microsoft Graph
- OAuth 2.0
- Microsoft Entra Sign-In Logs
- Identity and Access Management (IAM)

---

## Implementation Process

### Phase 1: Research and Planning

- Reviewed Device Code Flow authentication.
- Identified security concerns associated with the authentication method.
- Evaluated available Conditional Access controls.

### Phase 2: Microsoft Graph Deployment

- Connected to Microsoft Graph.
- Reviewed existing Conditional Access policies.
- Built a Conditional Access policy definition.
- Deployed the policy through Microsoft Graph.

### Phase 3: Validation

- Reviewed Microsoft Entra Sign-In Logs.
- Evaluated authentication behavior.
- Verified policy deployment.
- Compared expected outcomes against actual results.

### Phase 4: Optimization

- Refined policy configuration.
- Aligned controls with the intended security objective.
- Revalidated implementation through monitoring and testing.

---

## Security Benefits

Implementing controls around Device Code Flow can help organizations:

- Reduce identity-based attack surfaces.
- Improve authentication security.
- Strengthen Conditional Access governance.
- Increase visibility into authentication activity.
- Support Zero Trust security principles.

---

## Key Lessons Learned

### Successful Deployment Does Not Always Mean Successful Security

Security controls should always be validated after deployment to ensure they address the intended risk.

### Visibility Matters

Microsoft Entra Sign-In Logs provide critical insight into authentication behavior and policy effectiveness.

### Identity Security Requires Continuous Review

Policies should be reviewed regularly to ensure they continue to address evolving threats and business requirements.

### Microsoft Graph Is a Powerful Administrative Tool

Automation and infrastructure-as-code approaches can significantly improve policy management, consistency, and scalability.

---

## Outcome

This project reinforced the importance of validating security controls after deployment and demonstrated how Microsoft Graph and Microsoft Entra Conditional Access can be used together to strengthen identity security.

By focusing on Device Code Flow authentication, the project provided practical experience in authentication flow controls, policy validation, and identity governance within Microsoft Entra ID.

---

## Author

Tega Avwaghwaruvwe

Cloud Engineer | Microsoft Entra ID | Azure Security | Identity & Access Management (IAM) | Cloud Security

GitHub: https://github.com/tegs3

Medium: https://medium.com/@tegaaruvwe