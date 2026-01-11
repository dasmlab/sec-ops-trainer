# Linux & Open Systems Domain (RHEL-Focused)

## Overview

Linux and open systems expertise is the **foundation** for a SecOps Standards Officer. This domain emphasizes Red Hat Enterprise Linux (RHEL) as the primary platform, with practical deployment experience on live systems being essential.

## Priority: **HIGHEST** ⭐⭐⭐

Linux/Open Systems knowledge is fundamental to all other domains. A SecOps Standards Officer must have deep, practical experience with Linux systems, with RHEL being the primary focus for enterprise environments.

---

## Core Competency Areas

### 1. Linux Fundamentals

#### Required Knowledge
- Command-line proficiency
- File system hierarchy (FHS)
- File permissions and ownership
- Process management
- User and group management
- Package management (RPM, yum, dnf)
- System services and daemons
- Logging (syslog, journald)
- Text processing (grep, sed, awk, cut, sort)

#### RHEL-Specific
- Red Hat package management
- Red Hat subscription management
- Red Hat support and documentation access

#### Training Resources

**Red Hat Training (Primary Path):**
- [Red Hat System Administration I (RH124)](https://www.redhat.com/en/services/training/rh124-red-hat-system-administration-i)
  - Linux fundamentals
  - Essential command-line skills
  - File system and permissions
  - User management

- [Red Hat System Administration II (RH134)](https://www.redhat.com/en/services/training/rh134-red-hat-system-administration-ii)
  - Advanced administration
  - Network services
  - System services
  - Process management

- [Red Hat System Administration III (RH254)](https://www.redhat.com/en/services/training/rh254-red-hat-system-administration-iii)
  - Enterprise Linux deployment
  - Network services advanced
  - Security services
  - Automation basics

**Red Hat Learning Subscription:**
- [Red Hat Learning Subscription](https://www.redhat.com/en/services/training/learning-subscription)
  - Comprehensive training library
  - Self-paced learning
  - Hands-on labs

**Certification Goal - Foundation Tier:**
- **[RHCSA (Red Hat Certified System Administrator)](https://www.redhat.com/en/services/certification/rhcsa)**
  - Exam: EX200
  - **REQUIRED before Intermediate Tier**
  - Prerequisites: RH124 + RH134 or equivalent experience

---

### 2. Advanced Linux Administration

#### Required Knowledge
- Advanced system administration
- Performance tuning
- System monitoring and troubleshooting
- Advanced storage management (LVM, RAID)
- Network configuration advanced
- Kernel and modules
- Systemd advanced
- High availability basics
- Backup and recovery

#### RHEL-Specific
- RHEL-specific features
- Red Hat cluster technologies
- Red Hat storage solutions
- RHEL subscription and support

#### Training Resources

**Red Hat Training:**
- [Red Hat Enterprise Linux Troubleshooting (RH342)](https://www.redhat.com/en/services/training/rh342-red-hat-enterprise-linux-troubleshooting)
  - System troubleshooting
  - Performance analysis
  - Problem resolution

- [Red Hat Enterprise Linux Performance Tuning (RH442)](https://www.redhat.com/en/services/training/rh442-red-hat-enterprise-linux-performance-tuning)
  - Performance optimization
  - System tuning
  - Resource optimization

**Certification Goal - Intermediate Tier:**
- **[RHCE (Red Hat Certified Engineer)](https://www.redhat.com/en/services/certification/rhce)**
  - Exam: EX294 (Ansible automation)
  - **HIGHLY RECOMMENDED for Intermediate Tier**
  - Prerequisites: RHCSA

---

### 3. Linux Security

#### Required Knowledge

**Security Fundamentals:**
- File permissions and ACLs
- User and group security
- SUID/SGID security
- Password policies
- Account security

**SELinux (Security-Enhanced Linux):**
- SELinux concepts (labels, contexts, policies)
- SELinux modes (enforcing, permissive, disabled)
- SELinux policy management
- SELinux troubleshooting
- SELinux policy customization

**Firewall Configuration:**
- firewalld (RHEL 7+)
- iptables (legacy, understanding)
- Firewall zones and services
- Firewall rules and policies

**System Hardening:**
- Security configuration baselines
- CIS Benchmarks for RHEL
- DISA STIG for RHEL
- Security scanning and remediation
- Log security and monitoring

**Cryptography:**
- Encryption at rest (LUKS)
- Encryption in transit (SSL/TLS)
- GPG encryption
- Key management

**Audit and Compliance:**
- auditd (Linux Audit Daemon)
- Compliance scanning (OpenSCAP)
- Security assessment tools
- Compliance reporting

#### Training Resources

**Red Hat Training:**
- [Red Hat Security: Linux in Physical, Virtual, and Cloud (RH415)](https://www.redhat.com/en/services/training/rh415-red-hat-security-linux-physical-virtual-and-cloud)
  - **CRITICAL COURSE for security**
  - SELinux deep dive
  - Security hardening
  - Compliance tools (OpenSCAP)

- [Red Hat SELinux Policy Administration (RH429)](https://www.redhat.com/en/services/training/rh429-red-hat-selinux-policy-administration)
  - Advanced SELinux
  - Policy customization

**Certification Goal - Intermediate Tier:**
- **[RHCSE (Red Hat Certified Specialist in Security: Linux)](https://www.redhat.com/en/services/certification/red-hat-certified-specialist-security-linux)**
  - Security specialization
  - **RECOMMENDED for Intermediate Tier**

**Security Resources:**
- [CIS Benchmarks - RHEL](https://www.cisecurity.org/cis-benchmarks/)
- [DISA STIGs - RHEL](https://public.cyber.mil/stigs/)
- [Red Hat Security Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/security_hardening/index)

---

### 4. Automation & Configuration Management

#### Required Knowledge

**Ansible (Red Hat):**
- Ansible architecture
- Playbooks and roles
- Inventory management
- Modules and plugins
- Ansible Vault (secrets management)
- Automation best practices

**Scripting:**
- Bash scripting advanced
- Python scripting (recommended)
- Automation scripts
- Task automation

#### Training Resources

**Red Hat Training:**
- [Red Hat Enterprise Linux Automation with Ansible (RH294)](https://www.redhat.com/en/services/training/rh294-red-hat-enterprise-linux-automation-ansible)
  - **REQUIRED for RHCE**
  - Ansible automation
  - Playbook development

- [Red Hat Ansible Automation Platform](https://www.redhat.com/en/technologies/management/ansible) training
  - Advanced Ansible
  - Ansible Tower/AAP

**Certification:**
- RHCE (includes Ansible automation)
- [Red Hat Certified Specialist in Ansible Automation](https://www.redhat.com/en/services/certification/ansible)

---

### 5. Containerization (Podman/Containers)

#### Required Knowledge
- Container concepts
- Podman (RHEL container runtime)
- Container images
- Container security
- Container orchestration basics

#### Training Resources

**Red Hat Training:**
- Red Hat container training
- Podman documentation
- Container security courses

**Note:** Deep containerization covered in Virtualization & Containerization domain

---

### 6. System Architecture & Design

#### Required Knowledge
- System architecture design
- High availability architectures
- Load balancing
- Disaster recovery
- Capacity planning
- Infrastructure design

#### Training Resources

**Red Hat Training:**
- High availability courses
- System architecture courses
- [Red Hat Certified Architect (RHCA)](https://www.redhat.com/en/services/certification/rhca)
  - Advanced certification track
  - Multiple specializations

---

## RHEL Certification Path

### Recommended Certification Progression

#### Foundation Tier
- **RHCSA (Red Hat Certified System Administrator)**
  - Exam: EX200
  - Prerequisites: RH124 + RH134
  - **REQUIRED**

#### Intermediate Tier
- **RHCE (Red Hat Certified Engineer)**
  - Exam: EX294 (Ansible automation)
  - Prerequisites: RHCSA
  - **HIGHLY RECOMMENDED**

- **RHCSE (Red Hat Certified Specialist in Security: Linux)**
  - Security specialization
  - **RECOMMENDED**

#### Advanced Tier
- **RHCA (Red Hat Certified Architect)**
  - Requires 5 Red Hat certifications
  - Multiple specialization paths
  - **RECOMMENDED for Advanced Tier**

**Specializations:**
- Security track
- Cloud track
- DevOps track
- Infrastructure track

---

## Training by Tier

### Foundation Tier
**Focus**: Core Linux skills and RHCSA certification

**Required Training:**
- RH124 (System Administration I)
- RH134 (System Administration II)

**Certification:**
- RHCSA (EX200) - **REQUIRED**

**Experience:**
- 6+ months hands-on Linux administration
- Deploy and manage RHEL systems
- Basic troubleshooting

---

### Intermediate Tier
**Focus**: Advanced administration, security, automation

**Required Training:**
- RH254 (System Administration III) - if not completed
- RH294 (Ansible Automation)
- RH415 (Security)

**Recommended Training:**
- RH342 (Troubleshooting)
- RH429 (SELinux Policy) - if security focus

**Certification:**
- RHCE (EX294) - **HIGHLY RECOMMENDED**
- RHCSE (Security) - **RECOMMENDED**

**Experience:**
- 12+ months advanced Linux administration
- Security hardening implementation
- Automation implementation
- Production system management

---

### Advanced Tier
**Focus**: Architecture, specialization, strategic skills

**Required Training:**
- Specialized courses based on path
- Advanced security courses
- Architecture courses

**Certification:**
- RHCA (Red Hat Certified Architect) - **RECOMMENDED**
- Specialized certifications

**Experience:**
- Architecture design
- Security policy development
- Team leadership
- Strategic planning

---

### Expert Tier
**Focus**: Strategic Linux knowledge, standards development

**Certification:**
- Maintain RHCA or equivalent
- Continuous learning

**Experience:**
- Set Linux security standards
- Influence Linux adoption strategies
- Strategic technology decisions
- Standards development

---

## Practical Experience Requirements

### Foundation Tier
- Minimum 6 months hands-on Linux administration
- Deploy and manage RHEL systems
- Basic system administration tasks
- Troubleshoot common issues

### Intermediate Tier
- 12+ months advanced Linux administration
- Security hardening on production systems
- Automation implementation
- SELinux management
- Compliance implementation (STIG, CIS)

### Advanced Tier
- Architecture design experience
- Security policy development
- Team leadership
- Strategic technology decisions

### Expert Tier
- Strategic Linux expertise
- Standards development
- Cross-functional influence
- Strategic technology evaluation

---

## Key Resources

### Red Hat Resources
- [Red Hat Training Portal](https://www.redhat.com/en/services/training)
- [Red Hat Learning Subscription](https://www.redhat.com/en/services/training/learning-subscription)
- [Red Hat Certification](https://www.redhat.com/en/services/certification)
- [Red Hat Documentation](https://access.redhat.com/documentation)
- [Red Hat Customer Portal](https://access.redhat.com/)

### Security Resources
- [DISA STIGs - RHEL](https://public.cyber.mil/stigs/)
- [CIS Benchmarks - RHEL](https://www.cisecurity.org/cis-benchmarks/)
- [Red Hat Security Advisories](https://access.redhat.com/security/security-updates)
- [OpenSCAP](https://www.open-scap.org/)

### Community Resources
- [Red Hat Developer](https://developers.redhat.com/)
- Linux documentation
- Community forums

---

## Linux Distribution Knowledge

### Primary Focus: RHEL
- Red Hat Enterprise Linux (primary)
- CentOS Stream (community RHEL)
- Rocky Linux / AlmaLinux (RHEL rebuilds)

### Secondary Knowledge (Understanding)
- Other enterprise Linux distributions (SUSE, Ubuntu Server)
- Community distributions (Debian, Fedora)
- Understanding differences and similarities

---

**See Also:**
- [Foundation Tier](../TIERS/01-foundation-tier.md)
- [Intermediate Tier](../TIERS/02-intermediate-tier.md)
- [Standards Bodies Domain](./standards-bodies.md) - STIG for RHEL
- [Training Resources](../REFERENCE/training-resources.md)
- [Certifications](../REFERENCE/certifications.md)

