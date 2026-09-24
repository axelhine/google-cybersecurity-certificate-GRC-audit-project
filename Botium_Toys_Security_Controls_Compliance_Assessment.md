# Botium Toys — Security Controls & Compliance Assessment

**Project type:** Google Cybersecurity Certificate — Risk Management Course Project
**Author:** Axel Hinrichs
**Scenario:** Botium Toys, a fictional small e-commerce/retail toy company, engaged a security assessment to evaluate its current controls and compliance posture against industry standards (PCI DSS, GDPR, SOC 2).

## Overview

This assessment evaluates Botium Toys' existing security controls and regulatory compliance practices, based on a prior scope, goals, and risk assessment report. Each control and compliance item below was evaluated as either **currently in place (Yes)** or **not currently in place (No)**, followed by prioritized recommendations to close the identified gaps.

## Controls Assessment

| Control | In Place? |
|---|---|
| Least Privilege | ❌ No |
| Disaster Recovery Plans | ❌ No |
| Password Policies | ❌ No |
| Separation of Duties | ❌ No |
| Firewall | ✅ Yes |
| Intrusion Detection System (IDS) | ❌ No |
| Backups | ❌ No |
| Antivirus Software | ✅ Yes |
| Manual Monitoring/Maintenance for Legacy Systems | ❌ No |
| Encryption | ❌ No |
| Password Management System | ❌ No |
| Physical Locks (offices, storefront, warehouse) | ✅ Yes |
| Closed-Circuit Television (CCTV) Surveillance | ✅ Yes |
| Fire Detection/Prevention (alarms, sprinklers) | ✅ Yes |

## Compliance Assessment

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice | Compliant? |
|---|---|
| Only authorized users have access to customers' credit card information | ❌ No |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment | ❌ No |
| Data encryption procedures are implemented for credit card transaction touchpoints and data | ❌ No |
| Secure password management policies are adopted | ❌ No |

### General Data Protection Regulation (GDPR)

| Best Practice | Compliant? |
|---|---|
| E.U. customers' data is kept private/secured | ❌ No |
| A plan is in place to notify E.U. customers within 72 hours of a data breach | ✅ Yes |
| Data is properly classified and inventoried | ❌ No |
| Privacy policies, procedures, and processes are enforced to document and maintain data | ✅ Yes |

### System and Organization Controls (SOC Type 1, SOC Type 2)

| Best Practice | Compliant? |
|---|---|
| User access policies are established | ❌ No |
| Sensitive data (PII/SPII) is kept confidential/private | ❌ No |
| Data integrity is ensured (consistent, complete, accurate, validated) | ✅ Yes |
| Data is available to individuals authorized to access it | ❌ No |

## Recommendations

Botium Toys must prioritize the deployment of missing security controls such as least privilege, separation of duties, disaster recovery plans, password policies, an IDS, continued legacy system management, encryption, and password management to address current vulnerabilities and ensure confidentiality of private information. To address the gaps in compliance, Botium Toys needs to utilize controls such as least privilege, separation of duties, and encryption. The company also needs to correctly classify assets to review if they need to implement more controls that can improve their security posture.
