# OSI Model & Network Layers Domain

## Overview

The OSI (Open Systems Interconnection) model provides a framework for understanding network communications across seven layers. For a SecOps Standards Officer, deep understanding of Layers 3, 4, 5 (security context), and 7 is critical for security policy development and risk assessment.

## Learning Path by Layer

### Layer 1: Physical Layer
**Foundation Knowledge** (understood but not primary focus)
- Physical media (cables, fiber, wireless)
- Network hardware basics
- Physical security implications

---

### Layer 2: Data Link Layer
**Foundation Knowledge** (understood but not primary focus)
- MAC addresses
- Ethernet frames
- Switching concepts
- VLAN basics

---

### Layer 3: Network Layer ⭐ **CRITICAL**

#### Importance
Critical for security policy, routing security, network segmentation, and risk assessment.

#### Required Knowledge

**Core Concepts:**
- IP addressing (IPv4 and IPv6)
- Subnetting and CIDR notation
- Routing protocols (RIP, OSPF, BGP)
- ICMP protocol
- IP packet structure and headers
- Network addressing schemes
- NAT (Network Address Translation)
- VPN technologies (IPSec, GRE)

**Security Implications:**
- Network segmentation strategies
- Firewall rule design (network layer)
- Routing security
- IP spoofing prevention
- Network-based access control
- Subnet security policies

#### Training Resources

**Foundational:**
- [CCNA (Cisco Certified Network Associate)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna.html)
  - Comprehensive Layer 3 coverage
  - Industry standard certification
  - **Highly recommended**

- [CompTIA Network+](https://www.comptia.org/certifications/network)
  - Good foundational coverage

**Advanced:**
- [CCNP Enterprise](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/professional/ccnp-enterprise.html)
  - Advanced routing and switching
  - Enterprise network design

**Red Hat:**
- Network configuration in RHEL courses
- Advanced networking in Red Hat System Administration courses

#### Practical Skills
- Design network addressing schemes
- Configure routing (static and dynamic)
- Understand routing security implications
- Design network segmentation
- Troubleshoot network layer issues
- Assess network architecture from security perspective

---

### Layer 4: Transport Layer ⭐ **CRITICAL**

#### Importance
Critical for understanding connection-oriented vs connectionless security, port-based security policies, and application security.

#### Required Knowledge

**Core Concepts:**
- TCP (Transmission Control Protocol)
  - TCP handshake (SYN, SYN-ACK, ACK)
  - Connection states
  - TCP flags (SYN, ACK, FIN, RST, PSH, URG)
  - Flow control and congestion control
  - TCP sequence numbers

- UDP (User Datagram Protocol)
  - Connectionless communication
  - Use cases
  - Security implications

- Port numbers and services
  - Well-known ports (0-1023)
  - Registered ports (1024-49151)
  - Dynamic/private ports (49152-65535)
  - Port-based security policies

**Security Implications:**
- TCP vs UDP security models
- Port-based firewall rules
- Connection state tracking
- TCP session hijacking
- DDoS attacks (TCP SYN flood, UDP flood)
- Port scanning and reconnaissance

#### Training Resources

**Foundational:**
- CCNA (comprehensive Layer 4 coverage)
- CompTIA Network+
- [SANS SEC503: Intrusion Detection In-Depth](https://www.sans.org/course/intrusion-detection-in-depth)
  - Deep packet analysis including Layer 4

**Practical Labs:**
- Wireshark packet analysis
- TCP/UDP traffic analysis
- Port scanning exercises
- Firewall rule design

#### Practical Skills
- Analyze TCP/UDP traffic
- Design port-based security policies
- Understand connection state tracking
- Troubleshoot transport layer issues
- Assess transport layer security risks

---

### Layer 5: Session Layer / Security Context ⭐⭐ **HIGHLY CRITICAL**

#### Importance
From a security perspective, Layer 5 is often considered the "security layer" where SSL/TLS, encryption, and secure session establishment occur. This is **critical** for SecOps Standards Officers.

#### Required Knowledge

**SSL/TLS Protocols:**
- SSL (Secure Sockets Layer) - deprecated
- TLS (Transport Layer Security) versions (1.0, 1.1, 1.2, 1.3)
- TLS handshake process
- Cipher suites
- Certificate-based authentication
- Perfect Forward Secrecy (PFS)

**PKI (Public Key Infrastructure):**
- Public/private key cryptography
- Digital certificates
- Certificate Authorities (CAs)
- Certificate chains
- Certificate validation
- Certificate revocation (CRL, OCSP)
- Certificate lifecycle management

**Cryptography Basics:**
- Symmetric encryption
- Asymmetric encryption
- Hash functions
- Digital signatures
- Key exchange mechanisms

**Security Protocols:**
- IPSec (for VPNs)
- SSL/TLS for application security
- DTLS (Datagram TLS)

**Security Implications:**
- Certificate management policies
- TLS configuration and hardening
- PKI architecture
- Certificate-based authentication
- Encryption at rest vs in transit
- Key management

#### Training Resources

**Comprehensive:**
- [SANS SEC542: Web App Penetration Testing](https://www.sans.org/course/web-app-penetration-testing-ethical-hacking)
  - Deep SSL/TLS coverage
  - Certificate security

- [SANS SEC530: Defensible Security Architecture](https://www.sans.org/course/defensible-security-architecture-engineering)
  - PKI and encryption

**Red Hat:**
- Security courses covering SSL/TLS configuration
- Certificate management in RHEL

**OWASP:**
- [OWASP Transport Layer Protection Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Protection_Cheat_Sheet.html)
- TLS/SSL configuration guidance

**Self-Study:**
- RFC 8446 (TLS 1.3)
- PKI documentation
- Certificate management guides

#### Practical Skills
- Configure and manage TLS/SSL
- Design PKI architectures
- Implement certificate management
- Harden TLS configurations
- Troubleshoot SSL/TLS issues
- Assess encryption security posture
- Develop certificate policies

---

### Layer 6: Presentation Layer
**Foundation Knowledge** (understood but not primary focus)
- Data encoding and encryption (in application context)
- Data compression
- Character encoding (ASCII, UTF-8)

---

### Layer 7: Application Layer ⭐ **CRITICAL**

#### Importance
Critical for application security policy, understanding application protocols, and setting security standards for application development.

#### Required Knowledge

**Core Protocols:**
- **HTTP/HTTPS**
  - HTTP methods (GET, POST, PUT, DELETE, etc.)
  - HTTP headers
  - Status codes
  - Cookies and session management
  - HTTPS (HTTP over TLS)
  - HTTP/2 and HTTP/3

- **DNS (Domain Name System)**
  - DNS queries and responses
  - DNS record types (A, AAAA, CNAME, MX, TXT)
  - DNS security (DNSSEC)
  - DNS over HTTPS (DoH)
  - DNS security threats

- **SMTP/POP3/IMAP** (Email protocols)
  - Email security
  - SPF, DKIM, DMARC

- **FTP/FTPS/SFTP**
  - File transfer security

- **SSH (Secure Shell)**
  - Secure remote access
  - SSH key management

**Application Security Concepts:**
- OWASP Top 10
- Web application security
- API security
- Application protocol security
- Application-layer firewalls
- Content filtering

**Security Implications:**
- Application security policies
- Web application firewall (WAF) policies
- API security standards
- Application protocol security
- Content security policies
- Application-layer attacks

#### Training Resources

**Application Security:**
- [SANS SEC542: Web App Penetration Testing](https://www.sans.org/course/web-app-penetration-testing-ethical-hacking)
  - Comprehensive application layer security

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
  - Application security risks

- Web application security courses
- API security training

**DNS Security:**
- DNS security courses
- DNSSEC implementation guides

**Red Hat:**
- Application security in RHEL context
- Web server security (Apache, Nginx)

#### Practical Skills
- Assess application protocol security
- Design application security policies
- Understand web application security
- Review API security implementations
- Develop application security standards
- Assess application-layer security posture

---

## Integration Across Layers

### Security Architecture Perspective
A SecOps Standards Officer must understand:
- How security works across layers (defense in depth)
- Security controls at each layer
- Layer interaction and dependencies
- End-to-end security architecture

### Policy Development
- Network layer security policies (Layer 3)
- Transport layer security policies (Layer 4)
- Encryption and certificate policies (Layer 5)
- Application security policies (Layer 7)

### Risk Assessment
- Layer-specific risk assessment
- Cross-layer risk analysis
- Architecture security reviews
- Threat modeling across layers

---

## Training Recommendations by Tier

### Foundation Tier
- **Focus**: Layers 3, 4, 7 basics
- **Certifications**: CCNA, Network+
- **Skills**: Basic network troubleshooting, understanding protocols

### Intermediate Tier
- **Focus**: Layer 5 (SSL/TLS, PKI), advanced Layers 3, 4, 7
- **Certifications**: CCNP Security (if networking focus), Security+
- **Skills**: SSL/TLS configuration, network security implementation

### Advanced Tier
- **Focus**: Security architecture across layers, policy development
- **Skills**: Multi-layer security design, security policy development
- **Certifications**: CISSP (covers network security)

### Expert Tier
- **Focus**: Strategic security architecture, standards development
- **Skills**: Setting security standards, risk assessment, architecture reviews

---

## Key Resources

### Standards & Specifications
- [RFC 8446 - TLS 1.3](https://tools.ietf.org/html/rfc8446)
- [RFC 5246 - TLS 1.2](https://tools.ietf.org/html/rfc5246)
- [OWASP Transport Layer Protection](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Protection_Cheat_Sheet.html)
- [NIST Guidelines for SSL/TLS](https://csrc.nist.gov/publications/detail/sp/800-52/rev-2/final)

### Tools
- Wireshark (packet analysis)
- tcpdump (command-line packet capture)
- OpenSSL (SSL/TLS testing)
- nmap (network scanning)
- curl (HTTP/HTTPS testing)

### Glossaries
- [Network Glossary](../REFERENCE/glossary.md)
- OSI model terminology

---

## Practical Experience Requirements

### Foundation Tier
- Basic network troubleshooting
- Understanding packet flow
- Basic firewall rule design

### Intermediate Tier
- SSL/TLS configuration and management
- Network security implementation
- Packet analysis skills

### Advanced Tier
- Multi-layer security architecture design
- Security policy development
- Risk assessment across layers

### Expert Tier
- Strategic security architecture
- Standards development
- Cross-layer security guidance

---

**See Also:**
- [Foundation Tier](../TIERS/01-foundation-tier.md)
- [Intermediate Tier](../TIERS/02-intermediate-tier.md)
- [Networking Domain](./networking-routing.md)
- [Training Resources](../REFERENCE/training-resources.md)

