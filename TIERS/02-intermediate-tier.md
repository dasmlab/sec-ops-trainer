# Intermediate Tier - Security Implementation

## Overview

The Intermediate Tier builds upon foundational knowledge to develop practical security implementation skills. This tier focuses on hands-on security work, advanced system administration, and deeper understanding of compliance frameworks.

## Duration
**12-18 months** (building on Foundation Tier)

## Core Competencies

By the end of this tier, candidates should:
- Implement security controls and remediations
- Have advanced Linux administration skills (RHEL)
- Understand and implement compliance requirements
- Have deep knowledge of multiple standards bodies
- Be capable of security tooling and automation
- Understand network security implementations

---

## 1. Advanced Linux & RHEL Administration

### Priority: **HIGHEST**

#### Required Knowledge
- Advanced system administration
- Performance tuning
- High availability concepts
- Advanced security hardening
- SELinux configuration and management
- Systemd deep dive
- Advanced scripting and automation

#### RHEL-Focused Training Path

**Red Hat Training:**
- [Red Hat System Administration III (RH254)](https://www.redhat.com/en/services/training/rh254-red-hat-system-administration-iii) - If not completed in Foundation
- [Red Hat Enterprise Linux Troubleshooting (RH342)](https://www.redhat.com/en/services/training/rh342-red-hat-enterprise-linux-troubleshooting)
- [Red Hat Security: Linux in Physical, Virtual, and Cloud (RH415)](https://www.redhat.com/en/services/training/rh415-red-hat-security-linux-physical-virtual-and-cloud)
- [Red Hat Enterprise Linux Automation with Ansible (RH294)](https://www.redhat.com/en/services/training/rh294-red-hat-enterprise-linux-automation-ansible)

**Certification Goals:**
- **RHCE (Red Hat Certified Engineer)** - [EX294 Exam](https://www.redhat.com/en/services/certification/rhce)
- **RHCSE (Red Hat Certified Specialist in Security: Linux)** - Advanced security specialization
- Alternative: Red Hat Certified Specialist certifications in areas of interest

#### Key Skills to Develop
- SELinux policy creation and management
- Advanced firewall configuration (firewalld, iptables)
- System hardening based on CIS Benchmarks and DISA STIGs
- Performance optimization and capacity planning
- Automation with Ansible (critical for scale)
- Container basics (Podman, buildah)

#### Practical Experience Requirements
- 12+ months advanced Linux administration
- Implemented security hardening on production systems
- Automated security compliance checks
- Troubleshot complex system issues

---

## 2. Network Security Implementation

### Priority: **HIGH**

#### Required Knowledge

**Advanced Networking:**
- VPN technologies (IPSec, SSL VPN)
- Network segmentation strategies
- DMZ design and implementation
- Load balancing and high availability
- Network monitoring and analysis

**Security Technologies:**
- Firewall rules and policy development
- Intrusion Detection/Prevention Systems (IDS/IPS)
- Network Access Control (NAC)
- DDoS mitigation strategies
- Network forensics

#### Training Resources

**Cisco Training:**
- [CCNP Security (Cisco Certified Network Professional Security)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/professional/ccnp-security.html)
- [Cisco CyberOps Associate](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/cyberops-associate.html)

**Red Hat Networking:**
- Network security courses integrated in RHEL security training
- Advanced firewall management

**Other Resources:**
- [SANS SEC503: Intrusion Detection In-Depth](https://www.sans.org/course/intrusion-detection-in-depth)
- Practical labs with network security tools

#### Key Skills
- Design and implement secure network architectures
- Configure and manage firewalls (iptables, firewalld, commercial firewalls)
- Analyze network traffic for security threats
- Implement network segmentation
- Troubleshoot network security issues

---

## 3. OSI Layer 5 Deep Dive (SSL/TLS Security)

### Priority: **HIGH**

#### Required Knowledge
- SSL/TLS protocols in detail
- Certificate lifecycle management
- PKI (Public Key Infrastructure)
- Certificate Authorities (CAs)
- Certificate validation and revocation
- TLS configuration and hardening
- Perfect Forward Secrecy
- Certificate pinning

#### Training Resources
- [SANS SEC542: Web App Penetration Testing](https://www.sans.org/course/web-app-penetration-testing-ethical-hacking) (covers TLS/SSL)
- Red Hat security courses (TLS configuration)
- PKI management courses
- Self-study: [OWASP Transport Layer Protection Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Protection_Cheat_Sheet.html)

#### Practical Skills
- Configure and manage TLS/SSL certificates
- Implement certificate automation
- Harden TLS configurations
- Understand and implement certificate-based authentication
- Troubleshoot SSL/TLS issues

---

## 4. Standards Bodies - Implementation Focus

### Priority: **HIGH**

#### NIST Deep Dive

**Key Frameworks:**
- [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework)
  - Identify, Protect, Detect, Respond, Recover functions
  - Implementation tiers
  - Profile development

- [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) - Security and Privacy Controls
  - Control families
  - Control baselines
  - Implementation guidance

- [NIST SP 800-171](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final) - Protecting Controlled Unclassified Information
- [NIST SP 800-37](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final) - Risk Management Framework

**Training Resources:**
- NIST CSF training (various providers)
- [NIST Cybersecurity Framework Online Learning](https://www.nist.gov/cyberframework/framework)
- Industry training on NIST frameworks

#### DISA STIG Implementation

**Key Knowledge:**
- Understanding STIG structure
- STIG for RHEL implementation
- STIG compliance tools (OpenSCAP, SCAP Workbench)
- STIG validation and reporting

**Resources:**
- [DISA STIGs Portal](https://public.cyber.mil/stigs/)
- [Red Hat OpenSCAP](https://www.open-scap.org/)
- [Red Hat Compliance](https://www.redhat.com/en/topics/security/compliance) documentation
- STIG implementation guides for RHEL

**Practical Skills:**
- Implement STIG compliance on RHEL systems
- Use OpenSCAP for compliance scanning
- Generate compliance reports
- Remediate STIG findings

#### CVE & Vulnerability Management

**Key Knowledge:**
- CVE database and scoring (CVSS)
- Vulnerability management lifecycle
- Patch management processes
- Security advisories (RHEL Security Advisories)
- Vulnerability scanning tools

**Resources:**
- [NVD (National Vulnerability Database)](https://nvd.nist.gov/)
- [CVE Database](https://cve.mitre.org/)
- [Red Hat Security Advisories](https://access.redhat.com/security/security-updates)
- Vulnerability scanning tools (OpenVAS, Nessus, Qualys)

**Practical Skills:**
- Perform vulnerability assessments
- Prioritize vulnerabilities based on risk
- Manage patch cycles
- Integrate vulnerability management into CI/CD

#### ISO/IEC 27001

**Key Knowledge:**
- ISO 27001 standard structure
- Information Security Management System (ISMS)
- Control objectives and controls
- Audit requirements

**Resources:**
- ISO 27001 training courses
- [ISO/IEC 27001:2013 Standard](https://www.iso.org/standard/54534.html)
- Industry training providers

#### ITSG (Canada)

**Key Knowledge:**
- ITSG-33 (IT Security Risk Management)
- ITSG-38 (Network Security Zoning)
- Canadian government security requirements

**Resources:**
- [Canadian Centre for Cyber Security](https://www.cyber.gc.ca/)
- ITSG publications and guidance
- Canadian security compliance training

#### HIPAA (if applicable)

**Key Knowledge:**
- HIPAA Security Rule
- Administrative, Physical, and Technical Safeguards
- Compliance requirements for healthcare

**Resources:**
- HIPAA compliance training
- [HHS HIPAA Security Guidance](https://www.hhs.gov/hipaa/for-professionals/security/index.html)

---

## 5. Security Tooling & Automation

### Priority: **HIGH**

#### Required Knowledge
- Security scanning and assessment tools
- Configuration management (Ansible, Puppet, Chef)
- Security automation frameworks
- SIEM basics
- Log aggregation and analysis
- Security orchestration

#### Training Resources

**Ansible (Red Hat):**
- [Red Hat Enterprise Linux Automation with Ansible (RH294)](https://www.redhat.com/en/services/training/rh294-red-hat-enterprise-linux-automation-ansible)
- [Red Hat Ansible Automation Platform](https://www.redhat.com/en/technologies/management/ansible) training

**Security Tools:**
- OpenSCAP (compliance scanning)
- OWASP tools
- Security scanning tools training
- SIEM training (Splunk, ELK Stack, QRadar)

**Practical Skills:**
- Automate security compliance checks
- Implement security configuration management
- Build security monitoring and alerting
- Integrate security into DevOps workflows

---

## 6. Application Security Basics (Layer 7)

### Priority: **MEDIUM**

#### Required Knowledge
- Web application security concepts
- OWASP Top 10
- API security
- Secure coding practices overview
- Application security testing basics

#### Training Resources
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- Web application security courses
- Red Hat application security training (if available)

#### Key Skills
- Understand common web application vulnerabilities
- Review application security assessments
- Provide security guidance to development teams

---

## 7. Logging, Monitoring & Incident Response Basics

### Priority: **MEDIUM**

#### Required Knowledge
- Centralized logging (rsyslog, journald, centralized systems)
- Log analysis and correlation
- Security monitoring basics
- Incident response fundamentals
- Forensic analysis basics

#### Training Resources
- Red Hat system administration courses (logging)
- SANS courses on incident response
- SIEM training

#### Practical Skills
- Configure centralized logging
- Analyze security logs
- Understand incident response procedures
- Basic forensic analysis

---

## Intermediate Tier Completion Criteria

### Knowledge Checkpoints
- [ ] Can implement security controls based on standards (NIST, DISA STIG)
- [ ] Advanced RHEL administration and hardening
- [ ] Network security implementation skills
- [ ] Deep understanding of multiple standards bodies
- [ ] Security automation capabilities
- [ ] SSL/TLS and PKI management

### Certification Milestones
- [ ] **RHCE (Red Hat Certified Engineer)** or **RHCSE (Red Hat Certified Specialist in Security)** - **REQUIRED**
- [ ] CCNP Security or equivalent - Recommended
- [ ] Industry certifications in chosen standards (NIST, ISO, etc.) - Recommended

### Practical Experience
- [ ] 12+ months security implementation experience
- [ ] Implemented compliance frameworks (STIG, NIST, etc.)
- [ ] Security automation implementation
- [ ] Network security design and implementation
- [ ] Led security remediation projects

### Next Steps
Once Intermediate Tier is complete, proceed to [Advanced Tier](03-advanced-tier.md)

---

## Recommended Learning Order

1. **Advanced RHEL administration** (RH254, RH342, RH415)
2. **Obtain RHCE or RHCSE certification**
3. **Standards implementation** (NIST, DISA STIG) - parallel track
4. **Security automation** (Ansible, OpenSCAP)
5. **Network security** (CCNP Security or equivalent)
6. **SSL/TLS deep dive**
7. **Build practical implementation experience**

## Time Allocation (18-month path)

- Advanced Linux/RHEL: 30% of time
- Standards Implementation: 25% of time
- Security Tooling/Automation: 20% of time
- Network Security: 15% of time
- SSL/TLS & PKI: 10% of time

---

**See Also:**
- [Advanced Tier](03-advanced-tier.md)
- [Standards Bodies Domain](../DOMAINS/standards-bodies.md)
- [Linux & RHEL Domain](../DOMAINS/linux-rhel.md)
- [Networking Domain](../DOMAINS/networking-routing.md)

