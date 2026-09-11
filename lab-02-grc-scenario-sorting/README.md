# 🧪 Lab 02 — GRC Scenario Sorting

## 📌 Overview

This lab focused on developing the ability to distinguish between **Governance, Risk, and Compliance (GRC)** issues in realistic cybersecurity scenarios.

Ten simulated scenarios were evaluated to determine the **primary GRC issue** presented. Several scenarios contained overlapping GRC concepts, requiring identification of both the primary issue and any secondary concerns.

The exercise reinforced a simple initial classification framework:

**Governance → Who decides, owns, directs, or oversees?**

**Risk → What could go wrong?**

**Compliance → Are we meeting an applicable requirement?**

---

## 🎯 Objectives

- Distinguish between Governance, Risk, and Compliance issues
- Identify the primary issue presented in a GRC scenario
- Recognize when multiple GRC concepts overlap
- Support classifications with clear reasoning
- Translate cybersecurity situations into GRC-focused analysis

---

## 🔎 Scenario Analysis

The lab included scenarios involving:

- Security awareness requirements
- Authentication and MFA
- Risk management governance
- Regulatory safeguards
- Access control
- Security exception management
- Third-party/vendor risk
- Privileged access reviews
- Risk acceptance authority
- Vulnerability remediation

### Example — Risk

A customer-facing system lacked MFA, creating the possibility that customer accounts could be compromised.

**Classification:** Risk

**Reasoning:** The primary concern was potential future harm rather than failure to meet an identified requirement.

### Example — Governance

Executive leadership established a formal cybersecurity risk-management program, assigned responsibility to the CISO, and required quarterly reporting.

**Classification:** Governance

**Reasoning:** The scenario focused on organizational direction, accountability, ownership, and oversight.

### Example — Compliance

An internal policy required privileged-access reviews every 90 days, but evidence showed the most recent review occurred six months earlier.

**Classification:** Compliance

**Reasoning:** An established organizational requirement was not being met.

---

## ⚖️ Overlapping GRC Issues

The final scenario demonstrated how multiple GRC concepts can exist within the same issue.

An internal policy required critical vulnerabilities to be remediated within **30 days**. A critical vulnerability remained unresolved for **45 days**, and exploitation could result in unauthorized access to sensitive information.

**Primary Issue: Compliance**

The organization failed to meet its established vulnerability-remediation requirement.

**Secondary Issue: Risk**

The unresolved vulnerability created the potential for exploitation and organizational harm.

This demonstrated the importance of identifying both the **immediate GRC issue** and the **risk resulting from the condition**.

---

## 🧠 Key Learning

One important distinction identified during the lab was that the **absence of a compliance requirement does not automatically make an issue Governance**.

If a scenario primarily describes potential future harm or uncertainty, it may instead represent **Risk**.

Likewise, the presence of security risk does not automatically make Risk the primary classification. If an explicit requirement has already been violated, **Compliance may be the primary issue while Risk represents the potential consequence**.

---

## 💼 Skills Demonstrated

- Governance, Risk, and Compliance classification
- Risk identification
- Compliance analysis
- Governance and accountability recognition
- Scenario-based analysis
- Identification of overlapping GRC issues
- Evidence-based reasoning
- Security control analysis
- Professional GRC documentation

---

## 💡 Key Takeaway

Governance, Risk, and Compliance frequently overlap.

Effective GRC analysis requires determining **what the situation is primarily asking the analyst to evaluate**, while also recognizing related risks, requirements, responsibilities, and governance considerations.

---

## ⚠️ Lab Disclaimer

This is a simulated learning exercise created for cybersecurity and GRC skills development. No production systems, organizational data, or confidential information were used.
