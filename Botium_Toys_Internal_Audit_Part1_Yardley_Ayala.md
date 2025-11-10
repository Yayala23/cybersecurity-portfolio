Botium Toys — Internal Security Audit (NIST CSF Alignment)

Audit Objective:
To evaluate existing cybersecurity controls and identify risks impacting Botium Toys’ compliance with the NIST CSF
PCI DSS, GDPR as the company expands e- commerce operations internationally.

Controls and Compliance Checklist

| NIST CSF Function        | Control Question                                                            | Status  | Summary                                                               |
| ------------------------ | --------------------------------------------------------------------------- | ------- | --------------------------------------------------------------------- |
| **Identify**             | Has the organization inventoried all IT assets and data flows?              | **Yes** | Asset inventory exists but not fully updated for new cloud resources. |
| **Protect**              | Are encryption and authentication controls applied to all critical systems? | **Yes** | MFA and encryption active, but not yet enforced for all employees.    |
| **Detect**               | Are security events logged and correlated in a centralized SIEM?            | **No**  | Logs collected but not automatically correlated.                      |
| **Respond**              | Is there a documented incident response plan with assigned roles?           | **No**  | Response duties are informal; plan draft in progress.                 |
| **Recover**              | Are business continuity and data recovery procedures tested regularly?      | **No**  | Backups are created but restoration testing not documented.           |
| **Compliance (PCI DSS)** | Are credit card transactions processed through PCI-compliant systems?       | **Yes** | Uses third-party payment processor in full compliance.                |
| **Compliance (GDPR)**    | Are EU customer data requests (access/deletion) handled properly?           | **No**  | No defined mechanism for data subject requests.                       |

Recommendations

* Enforce multi-factor authentication (MFA) on all systems.

* Fully implement and test an Incident Response Plan.

* Configure SIEM correlation rules for real-time alerts.

* Test backup recovery procedures quarterly.

* Create GDPR data handling workflows and update the privacy notice.

  
