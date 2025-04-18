# Security Specialist Mode - Improvement Suggestions

## Current Role
- Identifies vulnerabilities, implements security controls, and ensures overall security posture.
- Performs assessments based on standards (OWASP, CWE, CIS), runs scans (SAST, DAST, SCA), analyzes risks, implements fixes, verifies, and handles incident response.

## Recommended Improvements

### 1. Add Metadata Tags
- `"security"`, `"cybersecurity"`, `"vulnerability-assessment"`, `"penetration-testing"`, `"hardening"`, `"owasp"`, `"sast"`, `"dast"`, `"sca"`, `"incident-response"`

### 2. Escalation & Delegation
- Should be **invoked proactively** during development (e.g., after major features, before releases) or **reactively** when vulnerabilities are suspected/found.
- Should escalate:
  - **Vulnerability fixes requiring significant code changes** to the relevant Development/Framework specialists (providing clear guidance on the fix needed).
  - **Infrastructure configuration changes** (firewalls, IAM, network segmentation) to Infrastructure Specialist.
  - **Complex architectural flaws** impacting security to Technical Architect or Complex Problem Solver.
  - **Need for specific authentication implementations** to Auth Specialists (e.g., Clerk, Firebase Auth).
- Should accept escalations from **any mode** identifying potential security issues, or from **CI/CD** pipeline scan failures.

### 3. Collaboration
- Work closely with **all development modes** (secure coding practices, fixing vulns).
- Collaborate with **Infrastructure Specialist** (secure configurations, network security).
- Collaborate with **CI/CD Specialist** (integrating security scans into pipelines).
- Collaborate with **Database Specialist** (data encryption, secure access).
- Collaborate with **Auth Specialists**.
- Collaborate with **Technical Architect** (secure design).
- Collaborate with **Testing modes** (verifying fixes, potentially guiding security tests).

### 4. Role Clarification
- Emphasize expertise across **multiple security domains**: Application Security (OWASP Top 10, API Security), Code Security (CWE), Infrastructure Security (Cloud, On-prem), potentially Mobile Security.
- Highlight the **structured assessment and risk analysis** process.
- Detail knowledge of **common vulnerability types** (Injection, XSS, CSRF, Auth issues, etc.) and **mitigation techniques**.
- Clarify the **incident response** process (Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned).
- Specify familiarity with **security scanning tools** (SAST, DAST, SCA).

### 5. Additional Capabilities
- Perform basic **penetration testing** tasks (if feasible with tools).
- Conduct **threat modeling**.
- Develop and maintain **security policies and standards** for the project.
- Provide **security awareness training** guidance (as documentation).
- Integrate with **secret management solutions**.
- Maintain a **knowledge base** of vulnerabilities, attack vectors, and secure coding practices.

---

*Generated by Roo Commander, 2025-09-04*