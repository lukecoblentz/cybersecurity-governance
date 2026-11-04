# Remote Access & Home Network Security Policy

## Overview
This academic security governance project develops a remote access policy for **Bankwise Credit Union**, a fictional financial institution. The policy addresses the risks of employees accessing organizational systems outside the corporate network, including unauthorized access, compromised credentials, unsecured networks, lost devices, and data exposure.

The deliverable combines organizational policy requirements with a short employee-facing home network security training guide.

> **Project context:** University coursework using a fictional case study. The controls below are **proposed policy requirements**, not evidence of a production deployment, security audit, or regulatory certification.

## Objective
- Define secure requirements for employees, managers, and contractors using remote access.
- Identify risks and appropriate safeguards for the remote access domain.
- Establish responsibilities for access approval, configuration, monitoring, and reporting.
- Explain practical home network and endpoint security expectations to remote employees.

---

## Security Risks & Proposed Controls

| Risk | Proposed safeguard |
| --- | --- |
| Unauthorized access | Multi-factor authentication (MFA) and strong passwords |
| Unsecured remote networks | Organization-approved encrypted VPN connections |
| Malware infection | Antivirus, firewalls, and security updates |
| Stolen credentials | Login monitoring and prompt compromise reporting |
| Exposure of customer data | Encryption and least-privilege access |
| Lost or stolen devices | Device encryption and IT-managed access revocation |
| Unapproved remote access software | Restrict access to approved applications |

---

## Policy Design

### 1. Policy Statement
Bankwise Credit Union employees must use approved remote access methods, secure connections, and MFA when accessing organizational systems remotely. Remote users must follow the organization's Acceptable Use Policy and applicable customer-information protection requirements, including those associated with the Gramm-Leach-Bliley Act (GLBA).

### 2. Purpose
Protect customer information and internal systems from unauthorized remote access while allowing employees to perform approved work outside organizational facilities.

### 3. Scope
Applies to employees, managers, temporary staff, and contractors using remote access. Covered assets include computers, mobile devices, networks, email, online banking platforms, and customer databases. Personally owned devices require IT approval and must meet organizational security requirements.

### 4. Security Standards
The proposed policy specifies:
- An approved VPN using AES-256 encryption and secure connection protocols, such as IKEv2/IPsec or TLS 1.2 or later.
- MFA for remote access.
- Current antivirus protection, firewalls, and security updates on endpoints.
- Monitoring of remote access and permission restrictions based on job responsibilities.

These are requirements proposed in the class exercise; actual technology selections would need to be validated against an organization's architecture and risk requirements.

### 5. Access Procedures & Responsibilities
1. Employees request remote access approval from their department manager.
2. IT verifies endpoint compliance and configures the approved VPN and MFA.
3. Employees complete required security awareness training.
4. Management approves access; IT provisions the access separately to support separation of duties.
5. Employees promptly report suspicious activity and missing devices.
6. IT periodically reviews permissions and removes access when no longer required.

**Policy owner:** Information Security Officer  
**Approval authority:** Senior Management  
**Proposed version:** 1.0  
**Approval status:** Pending Approval  
**Review frequency:** Annually

---

## Implementation Considerations
- **Home network variability:** Employees may use personal routers or unsecured connections; provide clear minimum security requirements.
- **User adoption:** MFA and remote access restrictions may require setup support and explanations of their purpose.
- **Permission disputes:** Department managers and the Information Security Officer should review disagreements over access and responsibilities.
- **Governance:** Policy changes should be reviewed annually and approved by senior management.

---

## Employee Training: Home Network Security
The accompanying training material emphasizes six practices:

1. **Secure connections:** Use approved VPN connections and avoid unsecured public Wi-Fi and unauthorized software.
2. **Home Wi-Fi:** Use strong passwords, WPA2 or WPA3 encryption, and updated router firmware.
3. **Passwords:** Use strong credentials and MFA; never share logins.
4. **Devices:** Maintain antivirus protection and firewalls; report missing devices immediately.
5. **Customer information:** Use customer data only for approved work purposes and on approved devices.
6. **Incident reporting:** Immediately report phishing, malware, unauthorized access, or possible breaches to IT.

---

## Key Findings
- Remote work introduces risks involving both identity and endpoint security.
- VPNs, MFA, device controls, and least privilege provide complementary layers of protection.
- Separating access authorization from provisioning creates accountability.
- Employee training helps translate policy statements into daily practices.

## Lessons Learned
- A usable policy needs a defined owner, approval authority, scope, and review cycle.
- Technical controls need corresponding approval, provisioning, and reporting procedures.
- Remote security extends beyond the VPN to home networks, devices, and employee behavior.

## Skills Demonstrated
- Security policy development
- Remote access risk analysis
- Identity and access governance
- MFA, VPN, and endpoint security requirements
- GLBA-aware policy design
- Employee security awareness documentation

## References Used in the Coursework
- [Stanford University — VPN Service](https://uit.stanford.edu/service/vpn)
- [UC Davis Health — Safeguarding PHI in a Remote Environment](https://health.ucdavis.edu/compliance/privacy/safeguarding-phi-medical-information-in-remote-environment)
- [Center for Internet Security — Telework Security Guide](https://www.cisecurity.org/insights/white-papers/cis-telework-security-guide)
- [NIST — Telework Security Basics](https://www.nist.gov/blogs/cybersecurity-insights/telework-security-basics)
- [NCUA — Cybersecurity Considerations for Remote Work](https://ncua.gov/regulation-supervision/letters-credit-unions-other-guidance/cybersecurity-considerations-remote-work)

---

## Conclusion
This case study develops a proposed remote access policy and supporting user training for a fictional credit union. It illustrates how governance, access controls, secure connectivity, endpoint protections, and employee awareness work together to reduce remote access risks.
