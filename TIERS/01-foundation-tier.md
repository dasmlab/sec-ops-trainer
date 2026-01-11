# Foundation Tier - Core Fundamentals

## Overview

The Foundation Tier establishes the fundamental knowledge and skills required for a SecOps Standards Officer. This tier focuses on building a solid technical foundation, with emphasis on Linux/Open Systems, basic networking, and introduction to security concepts.

## Duration
**6-12 months** (depending on prior experience and available time)

## Core Competencies

By the end of this tier, candidates should:
- Understand Linux/Open Systems fundamentals
- Have basic network troubleshooting skills
- Understand security fundamentals
- Be familiar with key standards bodies
- Have practical hands-on experience with live systems

---

## 1. Linux & Open Systems Fundamentals

### Priority: **HIGHEST** (Foundation for everything else)

#### Required Knowledge
- Linux command-line proficiency
- File system structure and permissions
- Process management
- Package management
- System administration basics
- Shell scripting fundamentals

#### RHEL-Focused Training Path

**Red Hat Training:**
- [Red Hat System Administration I (RH124)](https://www.redhat.com/en/services/training/rh124-red-hat-system-administration-i) - Linux fundamentals
- [Red Hat System Administration II (RH134)](https://www.redhat.com/en/services/training/rh134-red-hat-system-administration-ii) - Advanced Linux administration
- [Red Hat System Administration III (RH254)](https://www.redhat.com/en/services/training/rh254-red-hat-system-administration-iii) - Enterprise Linux deployment

**Certification Goal:**
- **RHCSA (Red Hat Certified System Administrator)**
  - [RHCSA Exam (EX200)](https://www.redhat.com/en/services/certification/rhcsa)
  - Prerequisites: RH124 + RH134 or equivalent experience
  - **This certification is HIGHLY RECOMMENDED before moving to Intermediate Tier**

#### Additional Resources
- [Red Hat Learning Subscription](https://www.redhat.com/en/services/training/learning-subscription)
- [Red Hat Documentation](https://access.redhat.com/documentation)
- Practice on live RHEL systems (set up lab environment)

#### Practical Experience Requirements
- Minimum 6 months hands-on Linux administration experience
- Deploy and manage RHEL systems in a lab or production environment
- Troubleshoot common system issues independently

---

## 2. OSI Model & Network Fundamentals

### Priority: **HIGH**

#### Required Knowledge

**OSI Model Overview:**
- Understanding of all 7 layers
- Focus on Layers 3, 4, 5, and 7 (critical for security)

**Layer 3 (Network Layer):**
- IP addressing (IPv4 and IPv6)
- Subnetting and CIDR notation
- Routing basics
- ICMP protocol
- IP packet structure

**Layer 4 (Transport Layer):**
- TCP vs UDP
- Port numbers and services
- TCP handshake and connection management
- Understanding of TCP flags

**Layer 5 (Session Layer / SSL/TLS - Security Context):**
- Introduction to encryption
- SSL/TLS basics
- Certificate concepts
- Security protocols

**Layer 7 (Application Layer):**
- HTTP/HTTPS protocols
- Common application protocols
- DNS fundamentals
- Web application basics

#### Training Resources

**Cisco Training (Recommended):**
- [CCNA (Cisco Certified Network Associate)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna.html)
  - Comprehensive networking foundation
  - Industry-standard certification
  - Covers OSI model in depth
  - **Highly recommended before Intermediate Tier**

**Alternative Training:**
- [CompTIA Network+](https://www.comptia.org/certifications/network)
- Linux networking courses (Red Hat, Linux Foundation)

#### Practical Labs
- Network troubleshooting exercises
- Wireshark packet analysis basics
- Setting up and configuring networks
- Understanding network traffic patterns

---

## 3. Security Fundamentals

### Priority: **HIGH**

#### Required Knowledge
- Confidentiality, Integrity, Availability (CIA triad)
- Defense in depth
- Least privilege principle
- Authentication vs Authorization
- Basic cryptography concepts
- Security threats and vulnerabilities overview
- Firewall basics
- Intrusion detection concepts

#### Training Resources

**Security+ or Equivalent:**
- [CompTIA Security+](https://www.comptia.org/certifications/security)
- Provides broad security foundation

**Red Hat Security:**
- [Red Hat Security: Linux in Physical, Virtual, and Cloud](https://www.redhat.com/en/services/training/rh415-red-hat-security-linux-physical-virtual-and-cloud)
- RHEL-specific security hardening

#### Key Topics to Master
- Linux security hardening
- File permissions and ACLs
- SELinux basics (RHEL-specific)
- Firewall configuration (firewalld, iptables basics)
- Log analysis basics

---

## 4. Standards Bodies Introduction

### Priority: **MEDIUM**

#### Required Knowledge
Familiarity with major standards bodies (detailed coverage in Intermediate/Advanced tiers):

**Must Know:**
- **NIST (National Institute of Standards and Technology)**
  - [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
  - [NIST SP 800 series](https://csrc.nist.gov/publications/sp800)

- **DISA (Defense Information Systems Agency)**
  - [DISA STIGs](https://public.cyber.mil/stigs/)
  - Understanding of STIG (Security Technical Implementation Guide)

- **CVE (Common Vulnerabilities and Exposures)**
  - [CVE Database](https://cve.mitre.org/)
  - [NVD (National Vulnerability Database)](https://nvd.nist.gov/)
  - Understanding vulnerability management

**Good to Know:**
- ISO/IEC 27001 (Information Security Management)
- HIPAA (Health Insurance Portability and Accountability Act) - if in healthcare
- ITSG (Information Technology Security Guidance - Canada)

#### Learning Resources
- Browse NIST publications (start with Cybersecurity Framework)
- Review DISA STIGs for RHEL
- Understand CVE identification and scoring (CVSS)
- Read industry security standards summaries

---

## 5. Command-Line & Automation Basics

### Priority: **MEDIUM**

#### Required Skills
- Bash scripting basics
- Command-line text processing (grep, sed, awk)
- System monitoring commands
- Log analysis from command line
- Basic automation concepts

#### Training Resources
- Red Hat System Administration courses (include scripting)
- [Linux Foundation - Introduction to Linux](https://training.linuxfoundation.org/training/introduction-to-linux/)
- Practice scripts for common administrative tasks

---

## Foundation Tier Completion Criteria

### Knowledge Checkpoints
- [ ] Can perform system administration tasks on RHEL independently
- [ ] Understands network troubleshooting at Layers 3, 4, and 7
- [ ] Can identify and explain basic security threats
- [ ] Familiar with at least one major standards body (NIST recommended)
- [ ] Understands the OSI model and can apply it to troubleshooting

### Certification Milestones
- [ ] **RHCSA (Red Hat Certified System Administrator)** - **REQUIRED**
- [ ] CCNA (Cisco Certified Network Associate) - **HIGHLY RECOMMENDED**
- [ ] CompTIA Security+ - Recommended

### Practical Experience
- [ ] Minimum 6 months hands-on Linux administration
- [ ] Configured and managed network services
- [ ] Performed security hardening on Linux systems
- [ ] Troubleshot network and system issues independently

### Next Steps
Once Foundation Tier is complete, proceed to [Intermediate Tier](02-intermediate-tier.md)

---

## Recommended Learning Order

1. **Start with Linux fundamentals** (RH124, RH134)
2. **Obtain RHCSA certification**
3. **Parallel track: Network fundamentals** (CCNA training)
4. **Security fundamentals** (Security+ or Red Hat Security course)
5. **Introduction to standards bodies** (self-study, reading)
6. **Build practical experience** (lab environment, real systems)

## Time Allocation (12-month path)

- Linux/RHEL: 40% of time
- Networking: 25% of time
- Security Fundamentals: 20% of time
- Standards Bodies: 10% of time
- Practical Experience: 5% of time (ongoing)

---

**See Also:**
- [Linux & RHEL Domain](../DOMAINS/linux-rhel.md)
- [OSI Layers Domain](../DOMAINS/osi-layers.md)
- [Standards Bodies Domain](../DOMAINS/standards-bodies.md)
- [Training Resources](../REFERENCE/training-resources.md)

