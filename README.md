# 🛡️ MediSure Health — Cybersecurity GRC Assessment (NIST CSF 2.0)

**Client:** MediSure Health *(Fictional Healthcare Startup)*  
**Prepared by:** GRC Advisor  
**Framework Used:** NIST Cybersecurity Framework (CSF) 2.0  
**Date:** September 2025

---

## 📚 Table of Contents

1. Executive Summary  
2. Business Context  
3. Governance Overview  
4. Risk Management Approach  
5. NIST CSF 2.0 Maturity Alignment  
6. Current Profile Overview  
7. Target Profile (Tier 4 – Adaptive)  
8. Gap Analysis Summary  
9. Risk Register (Sample)  
10. HIPAA Security Rule Mapping  
11. Strategic Roadmap  
12. Security Metrics & KPIs  
13. Framework References  

---

## 1. Executive Summary

This GRC (Governance, Risk, and Compliance) report assesses the cybersecurity posture of **MediSure Health**, a cloud-first healthcare startup handling electronic Protected Health Information (ePHI) in compliance with HIPAA regulations.

Using the **NIST CSF 2.0**, the report identifies current maturity tiers, highlights security weaknesses, and recommends a **phased roadmap** toward achieving a **Tier 4 Adaptive** security profile.

### 🔍 Key Highlights

- **Current CSF Tier:** Tier 1 – Partial  
- **Target CSF Tier:** Tier 4 – Adaptive  
- **Critical Gaps:** Governance, access control, monitoring, incident response  
- **Timeframe to Target:** 18+ months (phased)

---

## 2. Business Context

| Attribute         | Details                                         |
|------------------|-------------------------------------------------|
| **Industry**      | Digital Health / Healthcare SaaS               |
| **Size**          | ~150 employees                                 |
| **Compliance**    | HIPAA (U.S. Healthcare Regulation)             |
| **Infrastructure**| Cloud-first (SaaS / PaaS), hybrid assets       |
| **Data Processed**| ePHI, PII, clinical records, billing info      |
| **Critical Systems** | EHR Platform, Mobile App, Cloud Dashboards, Third-Party Integrations |

---

## 3. Governance Overview

### 🔎 Current Gaps

- No defined cybersecurity governance framework  
- Security operations are reactive and IT-driven  
- No Chief Compliance or Privacy Officer (CCPO)  
- Executive involvement is informal and undocumented  

### 🛠️ Recommendations

- Create and implement a **Cybersecurity Governance Policy**  
- Appoint a **Chief Compliance & Privacy Officer (CCPO)**  
- Form a **Security Steering Committee**  
- Establish board-level security reporting

---

## 4. Risk Management Approach

### 📉 Current State

- No centralized or documented risk register  
- Risks handled at the project level without standardization  
- Third-party/vendor risks are not formally assessed  

### 📈 Target State

- Maintain an enterprise-wide **Risk Register**  
- Perform **quarterly risk assessments**  
- Enforce onboarding/offboarding controls for vendors  
- Align risk program to **HIPAA** and **NIST CSF 2.0**

---

## 5. NIST CSF 2.0 Maturity Alignment

| **CSF Function** | **Description**                          | **Current Tier** | **Target Tier** |
|------------------|-------------------------------------------|------------------|-----------------|
| **Govern**       | Strategy, policy, oversight               | Tier 1           | Tier 4          |
| **Identify**     | Asset inventory, risk classification      | Tier 1           | Tier 4          |
| **Protect**      | Access control, encryption, DevSecOps     | Tier 2           | Tier 4          |
| **Detect**       | Monitoring, SIEM, threat detection         | Tier 1           | Tier 4          |
| **Respond**      | Incident response, communication           | Tier 1           | Tier 3          |
| **Recover**      | Backups, continuity, resilience            | Tier 1           | Tier 3          |

---

## 6. Current Profile Overview

### 🔻 Summary of Key Weaknesses

- No MFA or secure access policies in place  
- No PHI classification or formal asset inventory  
- No SIEM, alert thresholds, or monitoring defined  
- No IR Plan, breach notification procedures, or BCP testing  
- No governance roles or compliance officer

---

## 7. Target Profile (Tier 4 – Adaptive)

### 🎯 Desired Cybersecurity Posture

- **Govern:** Strategic cybersecurity leadership and risk-aligned planning  
- **Identify:** Full asset inventory with business impact classification  
- **Protect:** Secure-by-design processes, encryption, integrated DevSecOps  
- **Detect:** Advanced SIEM with threat intelligence feeds  
- **Respond:** HIPAA-aligned, tested IR plans and communication workflows  
- **Recover:** Automated DR with routine simulations and resilience drills

---

## 8. Gap Analysis Summary

| **Domain**         | **Gap Description**                              | **Business Impact**                             |
|--------------------|--------------------------------------------------|-------------------------------------------------|
| **Asset Management**| No PHI classification or asset tracking         | Regulatory noncompliance, data leaks            |
| **Access Control**  | No MFA, weak offboarding process                | Insider threats, unauthorized access            |
| **Governance**      | No policies or compliance officer               | Poor accountability, audit risk                 |
| **Detection**       | No monitoring, SIEM, or thresholds              | Slow incident detection and containment         |
| **Incident Response**| No IR Plan, breach workflow                    | Legal exposure, prolonged downtime              |
| **Data Security**   | No encryption or DLP implemented                | ePHI disclosure risk, HIPAA violation           |

---

## 9. Risk Register (Sample)

| ID  | Risk Description                  | Likelihood | Impact   | Owner           | Status            |
|-----|----------------------------------|------------|----------|------------------|-------------------|
| R1  | Unauthorized access to ePHI      | High       | Critical | CIO              | Mitigation Planned|
| R2  | No backup or disaster recovery   | Medium     | High     | IT Operations    | Not Started       |
| R3  | No incident response plan        | High       | High     | Security Lead    | In Progress       |
| R4  | Insecure APIs with vendors       | Medium     | High     | DevSecOps Team   | Not Started       |

---

## 10. HIPAA Security Rule Mapping

| HIPAA Standard                         | CSF Function | Control Description                          |
|----------------------------------------|--------------|-----------------------------------------------|
| 164.308(a)(1) – Security Management    | Govern       | Establish and operate a risk management program |
| 164.310 – Physical Safeguards          | Protect      | Control physical access and workstation security |
| 164.312(a)(2) – Unique User ID         | Protect      | Enforce individual authentication              |
| 164.308(a)(6) – Security Incidents     | Respond      | Define and implement incident response procedures|

---

## 11. Strategic Roadmap

### 🔹 Short-Term (0–6 months)

- Enforce **MFA** across all applications  
- Publish **cybersecurity & privacy policies**  
- Appoint **HIPAA Compliance Officer (CCPO)**  
- Build **asset inventory** with PHI classification  

### 🔸 Mid-Term (6–18 months)

- Deploy **SIEM**, integrate with cloud apps  
- Launch company-wide **HIPAA & security training**  
- Test and refine **Incident Response Plan**  
- Begin **vendor security reviews** and **BAA tracking**

### 🔺 Long-Term (18+ months)

- Automate **patching & vulnerability scans**  
- Join **H-ISAC** for threat intelligence sharing  
- Establish **KPI-based governance model**  
- Conduct **quarterly tabletop simulations**

---

## 12. Security Metrics & KPIs

| Metric                         | Current Value | Target Value | Notes                                |
|--------------------------------|----------------|----------------|--------------------------------------|
| % of Assets Classified         | < 20%          | 100%          | Needed for HIPAA PHI protection      |
| MFA Adoption Rate              | ~30%           | 100%          | Priority enforcement metric          |
| IR Plan Testing Frequency      | 0              | Quarterly     | HIPAA/NIST CSF required              |
| Workforce Training Completion  | ~10%           | 100%          | Tracks awareness and compliance gaps |

---

## 13. Framework References

- [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework)
- [NIST SP 800-53 Rev 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [HIPAA Security Rule (45 CFR Part 164)](https://www.hhs.gov/hipaa)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [OWASP Secure Software Design Principles](https://owasp.org/www-project-secure-software-development/)


- **MITRE ATT&CK for Healthcare**
- **OWASP Secure Software Design Principles**

---

