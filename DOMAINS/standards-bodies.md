# Standards & Compliance Bodies Domain

## Overview

A SecOps Standards Officer must have deep understanding of the standards bodies and compliance frameworks that govern security practices. This domain covers major standards organizations including DISA, NIST, ITSG (Canada), ISO, HIPAA, and related frameworks such as CVE, STIG, and others.

## Major Standards Bodies

### 1. NIST (National Institute of Standards and Technology) ⭐⭐⭐ **HIGHEST PRIORITY**

#### Overview
NIST is a U.S. federal agency that develops standards, guidelines, and best practices for cybersecurity. NIST frameworks are widely adopted globally.

#### Key Frameworks

**NIST Cybersecurity Framework (CSF)**
- [Official NIST CSF Website](https://www.nist.gov/cyberframework)
- **Five Core Functions:**
  1. **Identify** - Develop organizational understanding
  2. **Protect** - Develop safeguards
  3. **Detect** - Develop detection activities
  4. **Respond** - Develop response activities
  5. **Recover** - Develop recovery activities

- **Implementation Tiers:** 1 (Partial) through 4 (Adaptive)
- **Framework Profiles:** Current and Target states
- **Use Cases:** Risk management, compliance, security program maturity

**NIST SP 800-53 - Security and Privacy Controls**
- [NIST SP 800-53 Rev 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- Control families (20 families)
- Control baselines (Low, Moderate, High, Privacy)
- Control selection and tailoring
- Assessment procedures

**NIST SP 800-37 - Risk Management Framework (RMF)**
- [NIST SP 800-37 Rev 2](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final)
- **Seven Steps:**
  1. Prepare - Prepare for security and privacy risk management
  2. Categorize - Categorize systems and information
  3. Select - Select security and privacy controls
  4. Implement - Implement security and privacy controls
  5. Assess - Assess security and privacy controls
  6. Authorize - Authorize systems
  7. Monitor - Monitor security and privacy controls

**NIST SP 800-171 - Protecting Controlled Unclassified Information**
- [NIST SP 800-171 Rev 2](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final)
- For non-federal systems handling CUI
- 110 security controls
- CMMC (Cybersecurity Maturity Model Certification) alignment

**NIST SP 800 Series**
- Comprehensive library of cybersecurity publications
- [NIST SP 800 Series](https://csrc.nist.gov/publications/sp800)
- Covers various security topics

#### Training Resources
- [NIST Cybersecurity Framework Online Learning](https://www.nist.gov/cyberframework/framework)
- NIST RMF training courses (various providers)
- SANS courses covering NIST frameworks
- Industry training on NIST CSF and RMF
- CISSP (comprehensive NIST coverage)

#### Key Knowledge Areas
- NIST CSF implementation
- RMF process and steps
- Control selection and tailoring
- Risk assessment methodologies
- Continuous monitoring
- Authorization processes

---

### 2. DISA (Defense Information Systems Agency) ⭐⭐ **HIGH PRIORITY**

#### Overview
DISA provides IT support for the U.S. Department of Defense. DISA STIGs (Security Technical Implementation Guides) are widely used security configuration guides.

#### Key Resources

**STIGs (Security Technical Implementation Guides)**
- [DISA STIGs Portal](https://public.cyber.mil/stigs/)
- Security configuration guides for various technologies
- STIGs for operating systems (RHEL, Windows, etc.)
- STIGs for applications, databases, network devices
- STIGs for cloud platforms

**STIG Structure:**
- Vulnerabilities (V-numbers)
- Rules (requirements)
- Checks (assessment procedures)
- Fixes (remediation steps)

**SCAP (Security Content Automation Protocol)**
- Standardized format for security checklists
- SCAP content for STIGs
- SCAP validation tools

**SRGs (Security Requirements Guides)**
- Technology-agnostic security requirements
- Basis for STIG development

#### Training Resources
- DISA STIG documentation and guides
- [Red Hat OpenSCAP](https://www.open-scap.org/) - STIG implementation tools
- SCAP Workbench training
- STIG implementation courses

#### Key Knowledge Areas
- STIG structure and implementation
- STIG compliance tools (OpenSCAP)
- STIG validation and reporting
- STIG for RHEL (critical)
- SCAP content usage
- STIG compliance processes

---

### 3. CVE (Common Vulnerabilities and Exposures) ⭐⭐ **HIGH PRIORITY**

#### Overview
CVE provides a standardized identifier for security vulnerabilities. It's fundamental to vulnerability management.

#### Key Resources

**CVE Database**
- [CVE Website](https://cve.mitre.org/)
- CVE identifiers (CVE-YYYY-NNNNN format)
- CVE database search
- CVE assignment process

**NVD (National Vulnerability Database)**
- [NVD Website](https://nvd.nist.gov/)
- CVE entries with additional data
- **CVSS (Common Vulnerability Scoring System)**
  - Base, Temporal, Environmental scores
  - CVSS v3.1 and v4.0
  - Vulnerability severity ratings

**CNA (CVE Numbering Authorities)**
- Organizations authorized to assign CVEs
- Red Hat is a CNA

#### Training Resources
- CVE/NVD documentation
- CVSS scoring guides
- Vulnerability management training
- SANS vulnerability management courses

#### Key Knowledge Areas
- CVE identification and usage
- CVSS scoring and interpretation
- Vulnerability management lifecycle
- CVE assignment process
- Integration with patch management
- Security advisory interpretation

---

### 4. ITSG (Information Technology Security Guidance - Canada) ⭐ **REGIONAL PRIORITY**

#### Overview
ITSG provides security guidance for Canadian government organizations. Critical if working in or with Canadian organizations.

#### Key Resources

**ITSG-33 - IT Security Risk Management**
- Risk management framework
- Security control profiles
- Assessment procedures

**ITSG-38 - Network Security Zoning**
- Network segmentation guidance
- Security zones
- Zone protection requirements

**ITSG-22 - Baseline Security Requirements**
- Baseline security requirements
- Control objectives

**Canadian Centre for Cyber Security**
- [Cyber.gc.ca](https://www.cyber.gc.ca/)
- Comprehensive cybersecurity guidance
- Canadian cybersecurity standards
- Threat assessments

#### Training Resources
- ITSG documentation (official government sources)
- Canadian Centre for Cyber Security training
- Canadian government security training
- Industry training on Canadian requirements

#### Key Knowledge Areas
- ITSG-33 risk management framework
- ITSG-38 network security zoning
- Canadian security requirements
- Integration with other frameworks (NIST, ISO)

---

### 5. ISO/IEC Standards ⭐⭐ **HIGH PRIORITY**

#### Overview
International standards for information security management systems and controls.

#### Key Standards

**ISO/IEC 27001 - Information Security Management Systems (ISMS)**
- [ISO 27001 Standard](https://www.iso.org/standard/54534.html)
- ISMS requirements
- PDCA (Plan-Do-Check-Act) cycle
- Certification standard
- Audit requirements

**ISO/IEC 27002 - Information Security Controls**
- [ISO 27002 Standard](https://www.iso.org/standard/75652.html)
- Control objectives and controls
- 93 controls in 14 domains
- Implementation guidance

**ISO/IEC 27005 - Information Security Risk Management**
- Risk management standard
- Risk assessment methodologies
- Risk treatment options

**ISO/IEC 27017 - Cloud Security**
- Cloud-specific security controls
- Extension of ISO 27002

**ISO/IEC 27018 - Cloud Privacy**
- Cloud privacy protection

#### Training Resources
- ISO 27001 Lead Auditor training
- ISO 27001 Lead Implementer training
- ISO 27002 training
- ISO training providers (BSI, DNV, etc.)
- CISSP (ISO coverage)

#### Key Knowledge Areas
- ISMS implementation
- ISO 27001 certification process
- ISO 27002 controls
- Risk management (ISO 27005)
- Audit processes
- Continuous improvement

---

### 6. HIPAA (Health Insurance Portability and Accountability Act) ⭐ **INDUSTRY-SPECIFIC**

#### Overview
U.S. healthcare industry regulation for protecting health information.

#### Key Resources

**HIPAA Security Rule**
- Administrative safeguards
- Physical safeguards
- Technical safeguards
- Organizational requirements

**HHS Guidance**
- [HHS HIPAA Security Guidance](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- Official HIPAA guidance
- Security rule requirements

#### Training Resources
- HIPAA compliance training
- Healthcare security training
- Industry-specific training

#### Key Knowledge Areas
- HIPAA Security Rule requirements
- PHI (Protected Health Information) protection
- Administrative, physical, technical safeguards
- Business associate agreements
- HIPAA compliance assessment

---

### 7. PCI DSS (Payment Card Industry Data Security Standard) ⭐ **INDUSTRY-SPECIFIC**

#### Overview
Security standard for organizations handling payment card data.

#### Key Resources
- [PCI Security Standards Council](https://www.pcisecuritystandards.org/)
- PCI DSS requirements
- PCI DSS Self-Assessment Questionnaire (SAQ)
- PCI DSS certification

#### Training Resources
- PCI DSS training
- Payment card security training

---

### 8. GDPR (General Data Protection Regulation) ⭐ **REGIONAL**

#### Overview
EU regulation for data protection and privacy.

#### Key Resources
- [GDPR Official Website](https://gdpr.eu/)
- GDPR requirements
- Data protection principles
- Privacy by design

#### Training Resources
- GDPR compliance training
- Data protection training

---

## Integration & Framework Mapping

### Framework Comparison
- NIST CSF vs ISO 27001
- NIST RMF vs ISO 27005
- Mapping between frameworks
- Multi-framework compliance

### Common Controls
- Control mapping across frameworks
- Unified control frameworks
- Compliance automation

---

## Training Recommendations by Tier

### Foundation Tier
- **Focus**: Introduction to major standards bodies
- **Knowledge**: NIST CSF basics, STIG basics, CVE understanding
- **Resources**: NIST CSF learning, STIG documentation review

### Intermediate Tier
- **Focus**: Implementation of standards
- **Knowledge**: STIG implementation, NIST controls, CVE management
- **Resources**: STIG implementation training, NIST RMF training
- **Certifications**: Industry certifications in chosen standards

### Advanced Tier
- **Focus**: Policy development and framework integration
- **Knowledge**: Deep expertise in 2-3 frameworks, framework integration
- **Resources**: Lead Auditor/Implementer training, advanced framework courses
- **Certifications**: ISO 27001 Lead Auditor, NIST certifications

### Expert Tier
- **Focus**: Standards governance and strategic application
- **Knowledge**: Expert-level in multiple frameworks, standards development
- **Resources**: Standards working groups, executive training
- **Activities**: Standards interpretation, framework integration, policy development

---

## Key Resources Summary

### Official Sources
- NIST: [nist.gov](https://www.nist.gov)
- DISA STIGs: [public.cyber.mil/stigs/](https://public.cyber.mil/stigs/)
- CVE: [cve.mitre.org](https://cve.mitre.org)
- NVD: [nvd.nist.gov](https://nvd.nist.gov)
- ISO: [iso.org](https://www.iso.org)
- Canadian Cyber Security: [cyber.gc.ca](https://www.cyber.gc.ca)
- HIPAA: [hhs.gov/hipaa](https://www.hhs.gov/hipaa)

### Tools
- OpenSCAP (STIG implementation)
- SCAP Workbench
- Compliance scanning tools
- GRC (Governance, Risk, Compliance) platforms

---

## Practical Experience Requirements

### Foundation Tier
- Review standards documentation
- Understand basic compliance concepts
- Familiarity with one framework (NIST recommended)

### Intermediate Tier
- Implement standards (STIG, NIST controls)
- Use compliance tools (OpenSCAP)
- Vulnerability management with CVE

### Advanced Tier
- Develop compliance frameworks
- Integrate multiple standards
- Lead compliance initiatives

### Expert Tier
- Set organizational standards strategy
- Interpret standards for organization
- Integrate standards into policies
- Represent organization in standards discussions

---

**See Also:**
- [Foundation Tier](../TIERS/01-foundation-tier.md)
- [Intermediate Tier](../TIERS/02-intermediate-tier.md)
- [Advanced Tier](../TIERS/03-advanced-tier.md)
- [Glossary](../REFERENCE/glossary.md)
- [Training Resources](../REFERENCE/training-resources.md)

