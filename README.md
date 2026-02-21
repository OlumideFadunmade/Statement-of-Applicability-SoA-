# Statement of Applicability (SoA) - UK Care Home’s Enterprise Risk Assessment Simulation 
# 1.0 Purpose

This Statement of Applicability (SoA) defines the security controls selected for implementation within the scope of the Information Security Management System (ISMS), in accordance with:

- ISO/IEC 27001:2022 Clause 6.1.3

- Annex A control objectives and controls

The SoA documents:

- Which Annex A controls are applicable
- Justification for inclusion or exclusion
- Implementation status
- Linkage to identified risks

# 2.0 ISMS Scope

The ISMS applies to:

- Resident care management systems
- Medication systems
- Microsoft 365 environment
- Payroll system
- On-premise file server
- CCTV systems
- Staff HR records

# 3.0 Risk Assessment Reference

This SoA is based on:
- Enterprise Risk Register (Version 1.0)
- CIA Impact Assessment
- Threat Modelling Results
- Risk Acceptance Criteria approved by management

# 4.0 Annex A Control Applicability Matrix
Below is a portfolio-appropriate SoA extract (not all 93 controls shown).
# 4.1 Organisational Controls (Clause 5 – 37 Controls)
| Control ID | Control Name                                   | Applicable | Justification                      | Implementation Status | Linked Risks |
| ---------- | ---------------------------------------------- | ---------- | ---------------------------------- | --------------------- | ------------ |
| A.5.1      | Policies for Information Security              | Yes        | Required for ISMS governance       | Partially Implemented | All          |
| A.5.7      | Threat Intelligence                            | No         | SME scale, risk managed via MSP    | Not Implemented       | N/A          |
| A.5.17     | Authentication Information                     | Yes        | Required to mitigate phishing risk | Planned (MFA rollout) | R2           |
| A.5.18     | Access Rights                                  | Yes        | Required for least privilege       | Partially Implemented | R4           |
| A.5.19     | Information Security in Supplier Relationships | Yes        | SaaS reliance                      | Partially Implemented | R5           |
| A.5.23     | Information Security for Use of Cloud Services | Yes        | Cloud-based care systems           | Implemented           | R1           |
| A.5.24     | Incident Management Planning and Preparation   | Yes        | Required for ransomware risk       | Planned               | R1           |

# 4.2 People Controls (Clause 6 – 8 Controls)
| Control ID | Control Name                       | Applicable | Justification                | Implementation Status      | Linked Risks |
| ---------- | ---------------------------------- | ---------- | ---------------------------- | -------------------------- | ------------ |
| A.6.1      | Screening                          | Yes        | Protect vulnerable residents | Implemented                | R7           |
| A.6.3      | Information Security Awareness     | Yes        | Phishing & insider risk      | Planned (Training rollout) | R2           |
| A.6.5      | Responsibilities After Termination | Yes        | Prevent orphaned accounts    | Partially Implemented      | R4           |

# 4.3 Physical Controls (Clause 7 – 14 Controls)
| Control ID | Control Name                    | Applicable | Justification                | Implementation Status | Linked Risks |
| ---------- | ------------------------------- | ---------- | ---------------------------- | --------------------- | ------------ |
| A.7.2      | Physical Entry Controls         | Yes        | Protect server & CCTV access | Implemented           | R6           |
| A.7.4      | Physical Security Monitoring    | Yes        | CCTV in use                  | Implemented           | R6           |
| A.7.9      | Security of Assets Off-Premises | Yes        | Laptops used remotely        | Planned               | R2           |

# 4.4 Technological Controls (Clause 8 – 34 Controls)
| Control ID | Control Name                                    | Applicable | Justification              | Implementation Status | Linked Risks |
| ---------- | ----------------------------------------------- | ---------- | -------------------------- | --------------------- | ------------ |
| A.8.2      | Privileged Access Rights                        | Yes        | Reduce admin abuse risk    | Partially Implemented | R2           |
| A.8.8      | Management of Technical Vulnerabilities         | Yes        | Protect against ransomware | Planned               | R1           |
| A.8.13     | Backup                                          | Yes        | Critical for care records  | Partially Implemented | R1           |
| A.8.14     | Redundancy of Information Processing Facilities | Yes        | Server failure risk        | Not Implemented       | R3           |
| A.8.23     | Web Filtering                                   | Yes        | Reduce phishing exposure   | Implemented           | R2           |

# 5.0 Excluded Controls

Controls marked as "Not Applicable" are excluded based on:

- Organisational size and complexity
- Lack of certain technologies (e.g., no in-house development)
- Risk-based justification

All exclusions are documented and approved by management.

# 6.0 Control Implementation Status Definitions

- Implemented – Control fully operational and evidenced
- Partially Implemented – Some components exist, improvements required
- Planned – Approved but not yet implemented
- Not Applicable – Justified exclusion

# 7.0 Management Approval

This Statement of Applicability has been reviewed and approved by senior management.

Signed: ________________________

Name: Registered Manager

Date: ________________________
