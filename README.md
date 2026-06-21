# Enterprise Security Penetration Test

A penetration testing assessment was performed as part of an Enterprise Security Management course at the South Dakota School of Mines & Technology.

This project documents the methodology, findings, and remediation recommendations from a controlled penetration testing engagement against an intentionally vulnerable lab environment. The assessment focused on identifying security weaknesses, validating vulnerabilities, and demonstrating the impact of common security misconfigurations.

> **Disclaimer:** This assessment was performed in an authorized academic lab environment for educational purposes. All testing activities were conducted on systems specifically designed for cybersecurity training and learning.

---

## Project Overview

The objective of this engagement was to assess the security posture of a target system through:

* Network discovery
* Service enumeration
* Vulnerability identification
* Credential exposure analysis
* Remote access exploitation
* Privilege escalation
* Security recommendations

The assessment culminated in obtaining administrative-level access and documenting all findings in a formal penetration testing report.

---

## Skills Demonstrated

### Cybersecurity

* Penetration Testing
* Vulnerability Assessment
* Service Enumeration
* Reconnaissance
* Privilege Escalation
* Security Reporting
* Risk Analysis
* Linux Administration

### Tools Used

* Kali Linux
* Nmap
* ARP-Scan
* Metasploit Framework
* MySQL
* PostgreSQL
* Git
* Linux Command Line

---

## Assessment Methodology

The assessment followed a structured penetration testing process:

1. Reconnaissance
2. Enumeration
3. Vulnerability Identification
4. Exploitation
5. Privilege Escalation
6. Documentation
7. Remediation Recommendations

---

## Key Findings

### Database Credential Exposure

Weak or exposed credentials allowed unauthorized access to backend services.

**Impact**

* Unauthorized access to sensitive information
* Increased attack surface
* Potential lateral movement opportunities

**Recommendation**

* Enforce strong password policies
* Rotate credentials regularly
* Restrict administrative access

---

### Information Disclosure

Sensitive information was discovered through publicly accessible resources and exposed files.

**Impact**

* Disclosure of internal information
* Facilitation of additional attacks

**Recommendation**

* Implement proper access controls
* Conduct periodic content reviews
* Remove unnecessary public exposure

---

### Source Control Exposure

Exposed source control artifacts revealed sensitive project information.

**Impact**

* Potential disclosure of credentials
* Exposure of internal application structure

**Recommendation**

* Restrict repository access
* Remove secrets from source control
* Implement secure development practices

---

### Remote Code Execution

Misconfigured services allowed execution of commands on the target system.

**Impact**

* System compromise
* Unauthorized access
* Potential privilege escalation

**Recommendation**

* Apply security updates
* Limit service exposure
* Harden system configurations

---

### Privilege Escalation

A privilege escalation vulnerability enabled elevated access to the operating system.

**Impact**

* Full system compromise
* Administrative-level control

**Recommendation**

* Maintain current patch levels
* Apply least-privilege principles
* Perform regular vulnerability assessments

---

### Included Documentation

The repository includes a sanitized version of the original penetration testing report containing:

* Assessment objectives
* Methodology
* Screenshots of findings
* Technical analysis
* Remediation recommendations
* Final conclusions

---

## Learning Outcomes

This project provided hands-on experience with:

* Network reconnaissance techniques
* Service enumeration
* Vulnerability validation
* Exploitation workflows
* Privilege escalation techniques
* Professional security documentation
* Risk assessment and remediation planning

The engagement reinforced the importance of secure configuration management, credential protection, patch management, and defense-in-depth security principles.

---

## Report

A sanitized copy of the original assessment report is included in this repository:

The report has been reviewed to remove personal academic information while preserving the technical findings and assessment methodology.

---

## Future Improvements

* Additional vulnerability validation techniques
* Expanded reporting metrics
* Automated enumeration workflows
* Security hardening verification procedures
* Integration with vulnerability management processes

```
```
