# Control Assessment Workpaper

> **Document Type:** Control Assessment Workpaper  
> **Assessment Type:** Simulated Training Exercise  
> **Control Area:** Access Control / Workstation Security  
> **Assessment Status:** Complete

---

## 1. Control Information

| Field | Details |
|---|---|
| **Control ID** | AC-01 *(fictional internal identifier)* |
| **Control Name** | Automatic Workstation Screen Lock |
| **Control Owner** | IT Operations |
| **Control Type** | Technical / Preventive |
| **Assessment Focus** | Operating Effectiveness |
| **Assessment Result** | Not Effective |

---

## 2. Control Requirement

Employee workstations are required to automatically lock after the organization's defined period of inactivity.

The purpose of this requirement is to reduce the risk of unauthorized access to unattended workstations.

---

## 3. Control Objective

Verify that employee workstations automatically lock after the required inactivity period and require the user to regain authorized access before resuming use.

---

## 4. Assessment Objective

Determine whether the automatic workstation screen-lock control is implemented and operating in accordance with the organization's defined requirement.

---

## 5. Assessment Method

**Methods Used:**

- Examine
- Test

The assessment reviewed simulated workstation configuration information and observed screen-lock behavior.

---

## 6. Evidence Reviewed

| Evidence ID | Evidence Description | Evidence Type |
|---|---|---|
| E-01 | Workstation automatic-lock configuration information | Configuration Evidence |
| E-02 | Observed workstation screen-lock behavior | Test Evidence |

**Evidence Limitation:**  
This assessment was performed as a simulated training exercise. Evidence represents fictional assessment information rather than records obtained from a production environment.

---

## 7. Test Procedure

1. Identify the organization's automatic screen-lock requirement.
2. Review the workstation's automatic-lock configuration.
3. Observe whether the workstation automatically locks after the required inactivity period.
4. Compare the observed behavior and configuration against the defined requirement.
5. Determine whether the control is operating effectively.

---

## 8. Expected Condition

The workstation should automatically lock within the organization's required inactivity period.

The configuration should demonstrate that the automatic-lock setting is implemented in accordance with the defined requirement.

---

## 9. Observed Condition

The workstation did not automatically lock within the required inactivity period.

The available configuration information also did not demonstrate that the required automatic-lock setting had been properly implemented.

---

## 10. Test Result

| Test | Expected Result | Observed Result | Status |
|---|---|---|---|
| Automatic Screen Lock | Workstation automatically locks within the required inactivity period | Workstation did not automatically lock within the required period | **Failed** |

---

## 11. Assessment Conclusion

Based on the evidence reviewed and testing performed, the automatic workstation screen-lock control was determined to be **not operating effectively**.

The observed workstation behavior did not meet the organization's defined inactivity requirement, and the available configuration evidence did not demonstrate that the required setting had been properly implemented.

---

## 12. Finding

### Screen-Lock Configuration Does Not Meet Defined Requirement

**Condition:**  
The assessed workstation did not automatically lock within the organization's required inactivity period.

**Criteria:**  
Employee workstations are required to automatically lock after the organization's defined period of inactivity.

**Cause:**  
The available evidence did not establish the specific cause of the configuration gap.

**Effect / Risk:**  
An unattended workstation may remain accessible longer than permitted, increasing the opportunity for unauthorized access to organizational systems or information.

---

## 13. Recommendation

IT Operations should review the workstation's automatic screen-lock configuration and configure the control to meet the organization's established inactivity requirement.

After remediation, the control should be retested to verify that the configuration is implemented correctly and operates as required.

---

## 14. Remediation Tracking

| Field | Status |
|---|---|
| **Finding Status** | Open |
| **Remediation Owner** | IT Operations |
| **Corrective Action Required** | Yes |
| **Retest Required** | Yes |
| **Target Completion Date** | To Be Determined |
| **Retest Result** | Pending |

---

## 15. Final Assessment Status

**Control Effectiveness:** ❌ Not Effective  
**Finding Identified:** Yes  
**Remediation Required:** Yes  
**Retesting Required:** Yes

---

## Workpaper Note

This document is a simulated GRC workpaper created for portfolio and skills-development purposes. It does not represent an assessment of a real organization, production system, or employee workstation.
