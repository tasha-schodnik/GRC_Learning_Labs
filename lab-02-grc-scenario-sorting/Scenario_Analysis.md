# GRC Scenario Analysis

> **Document Type:** GRC Scenario Analysis  
> **Assessment Type:** Simulated Training Exercise  
> **Organization:** Raccoon Cybersecurity Inc.  
> **Assessment Areas:** Governance, Risk, and Compliance  
> **Assessment Status:** Complete

---

## 1. Assessment Objective

The objective of this assessment was to evaluate simulated cybersecurity and business scenarios and determine whether the primary issue represented **Governance, Risk, or Compliance**.

Where multiple GRC concepts were present, the analysis also considered secondary issues and the reasoning supporting the final classification.

---

## 2. Classification Criteria

The following criteria were used as an initial decision framework:

| Classification | Primary Consideration |
|---|---|
| **Governance** | Who establishes direction, makes decisions, assigns responsibility, or provides oversight? |
| **Risk** | What potential event or condition could negatively affect the organization? |
| **Compliance** | Is the organization meeting an applicable requirement? |

Classification was based on the primary issue presented by the available facts rather than the presence of individual security-related terms.

---

## 3. Scenario Assessment Results

| ID | Scenario | Primary Classification | Secondary Consideration | Analyst Rationale |
|---|---|---|---|---|
| GRC-01 | Required security-awareness training was overdue for multiple employees. | Compliance | Risk | An established organizational requirement was not met. Incomplete training may also increase exposure to security threats. |
| GRC-02 | A customer portal did not require MFA, creating the possibility of account compromise. | Risk | — | No applicable requirement was identified. The primary concern was potential unauthorized access and resulting harm. |
| GRC-03 | Leadership established a cybersecurity risk-management program, assigned responsibility to the CISO, and required quarterly reporting. | Governance | Risk Management | The scenario established organizational direction, accountability, decision ownership, and executive oversight. |
| GRC-04 | A required regulatory safeguard had not been implemented. | Compliance | Risk | An applicable regulatory requirement was not satisfied. The missing safeguard may also expose the organization to security risk. |
| GRC-05 | More employees than necessary had access to sensitive customer information. | Risk | Access Control | Excessive access increased the possibility of future unauthorized access or disclosure. No specific requirement violation was identified. |
| GRC-06 | Leadership established a formal security-exception approval process and assigned high-risk approval authority to the CISO. | Governance | Risk | Leadership defined decision authority, responsibility, and oversight for security exceptions. |
| GRC-07 | Continued use of a vendor with previous security incidents could expose the organization to data loss, disruption, or reputational harm. | Risk | Third-Party Risk | The primary concern was potential future organizational harm associated with the vendor relationship. |
| GRC-08 | Privileged-access reviews were required every 90 days, but the latest review occurred six months earlier. | Compliance | Risk | The organization failed to perform the review within its required timeframe. |
| GRC-09 | The board established which risks required executive approval and required quarterly reporting of accepted high-level risks. | Governance | Risk | The board established risk decision authority, escalation requirements, and oversight responsibilities. |
| GRC-10 | A critical vulnerability remained unresolved for 45 days despite a 30-day remediation requirement. | Compliance | Risk | The remediation requirement was exceeded. The unresolved vulnerability also created potential for exploitation and unauthorized access. |

---

## 4. Key Observations

The assessment demonstrated that Governance, Risk, and Compliance issues frequently overlap.

A condition may create security risk while simultaneously representing a compliance failure. Governance may also determine who has authority to make decisions regarding that risk.

Classification should therefore consider the **primary issue being evaluated** while documenting relevant secondary concerns.

---

## 5. Analyst Conclusion

Based on the scenario analysis, GRC issues can be initially distinguished by identifying whether the situation primarily concerns:

- organizational direction, accountability, or decision authority;
- uncertainty and potential organizational harm; or
- adherence to an applicable requirement.

The assessment also demonstrated that the absence of a compliance requirement does not automatically indicate a Governance issue. When the primary concern is potential harm or uncertainty, the appropriate classification may instead be **Risk**.

Similarly, when an established requirement has already been violated, **Compliance may be the primary issue even when the violation also creates security risk**.

---

## 6. Assessment Limitation

This assessment was performed as a simulated training exercise. Conclusions were based solely on the facts provided within each scenario.

No production systems, organizational records, confidential information, or external evidence were used.
