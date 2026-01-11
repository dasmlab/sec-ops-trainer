# Identity & Access Management (IAM) Domain

## Overview

This domain covers modern Identity & Access Management technologies including OIDC (OpenID Connect), SAML (Security Assertion Markup Language), XACML (eXtensible Access Control Markup Language), and related authentication/authorization frameworks. A SecOps Standards Officer must understand how secure client-server methodologies work today, the bodies that govern them, and the technologies behind them.

## Priority: **HIGH** ⭐⭐

IAM is critical for modern security architectures. Understanding authentication, authorization, and identity federation technologies is essential for setting security policies and standards.

---

## Core Competency Areas

### 1. IAM Fundamentals

#### Required Knowledge

**Core Concepts:**
- Authentication vs Authorization
- Identity providers (IdP) and service providers (SP)
- Single Sign-On (SSO)
- Identity federation
- Multi-Factor Authentication (MFA)
- Privileged Access Management (PAM)
- Just-In-Time (JIT) access
- Zero Trust Architecture

**Access Control Models:**
- Role-Based Access Control (RBAC)
- Attribute-Based Access Control (ABAC)
- Discretionary Access Control (DAC)
- Mandatory Access Control (MAC)
- Policy-Based Access Control (PBAC)

#### Training Resources
- IAM fundamentals courses
- Identity and access management training
- SANS security courses (IAM coverage)
- Vendor-specific IAM training

---

### 2. OIDC (OpenID Connect)

#### Required Knowledge

**OIDC Fundamentals:**
- OAuth 2.0 foundation (OIDC is built on OAuth 2.0)
- OIDC protocol
- ID tokens vs access tokens
- OIDC flows (Authorization Code, Implicit, Hybrid, Client Credentials)
- OpenID Connect Core specification

**Key Concepts:**
- Identity provider (IdP)
- Relying party (RP)
- Client types (confidential, public)
- Scopes and claims
- UserInfo endpoint
- Discovery document (.well-known/openid-configuration)

**Security Considerations:**
- Token security
- Token validation
- Token lifecycle
- Redirect URI validation
- Client authentication
- PKCE (Proof Key for Code Exchange)

#### Training Resources

**OAuth 2.0 / OIDC Training:**
- OAuth 2.0 and OIDC courses
- Identity provider training
- OIDC implementation guides
- [OAuth 2.0 RFC 6749](https://tools.ietf.org/html/rfc6749)
- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html)

**Vendor Training:**
- Okta training (OIDC implementation)
- Azure AD training (Microsoft Identity Platform)
- Google Identity Platform training
- Auth0 training

**Red Hat:**
- Red Hat Identity Management courses
- Identity provider integration

#### Key Skills
- Understand OIDC protocol
- Design OIDC implementations
- Assess OIDC security
- Troubleshoot OIDC issues
- Develop OIDC policies

---

### 3. SAML (Security Assertion Markup Language)

#### Required Knowledge

**SAML Fundamentals:**
- SAML 2.0 protocol
- Identity provider (IdP) and service provider (SP)
- SAML assertions
- SAML protocols (AuthnRequest, Response, LogoutRequest, LogoutResponse)
- SAML bindings (HTTP Redirect, HTTP POST, Artifact)
- SAML profiles (Web Browser SSO, Enhanced Client/Proxy)

**Key Concepts:**
- SAML assertions (authentication, attribute, authorization decision)
- SAML attributes
- SAML name identifiers
- Assertion Consumer Service (ACS)
- Single Logout (SLO)
- SAML metadata

**Security Considerations:**
- XML Signature and Encryption
- SAML replay attacks
- Assertion expiration
- Certificate management
- Metadata security

#### Training Resources

**SAML Training:**
- SAML implementation courses
- Identity provider training (Okta, Azure AD, etc.)
- SAML protocol guides
- [SAML 2.0 Technical Overview](http://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html)
- [SAML 2.0 Core Specification](http://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf)

**Vendor Training:**
- Okta SAML training
- Azure AD SAML training
- Other IdP SAML training

**Red Hat:**
- Red Hat Identity Management (FreeIPA/IdM)
- SAML integration courses

#### Key Skills
- Understand SAML protocol
- Design SAML implementations
- Assess SAML security
- Troubleshoot SAML issues
- Develop SAML policies

---

### 4. XACML (eXtensible Access Control Markup Language)

#### Required Knowledge

**XACML Fundamentals:**
- Policy-based access control
- XACML architecture
- Policy Decision Point (PDP)
- Policy Enforcement Point (PEP)
- Policy Administration Point (PAP)
- Policy Information Point (PIP)

**Key Concepts:**
- XACML policies
- XACML rules
- XACML requests and responses
- Attributes and attribute values
- Combining algorithms
- Obligations

**Security Considerations:**
- Policy design and security
- Attribute security
- Policy evaluation security
- Performance considerations

#### Training Resources

**XACML Training:**
- XACML implementation courses
- Policy-based access control training
- [XACML 3.0 Standard](http://docs.oasis-open.org/xacml/3.0/xacml-3.0-core-spec-os-en.html)
- XACML guides and documentation

**Vendor Training:**
- XACML implementation platforms
- Policy management platforms

#### Key Skills
- Understand XACML architecture
- Design XACML policies
- Assess XACML implementations
- Develop XACML policies

---

### 5. Modern IAM Concepts

#### Required Knowledge

**Zero Trust Architecture:**
- Zero Trust principles
- "Never trust, always verify"
- Identity as the perimeter
- Continuous verification
- Least privilege access
- Micro-segmentation

**Privileged Access Management (PAM):**
- Privileged account management
- Just-In-Time (JIT) access
- Privileged session management
- Secrets management
- PAM solutions and architectures

**Multi-Factor Authentication (MFA):**
- Authentication factors (something you know, have, are)
- MFA methods (TOTP, SMS, push, hardware tokens)
- Adaptive authentication
- Risk-based authentication

**Identity Federation:**
- Federated identity models
- Trust relationships
- Federation protocols (SAML, OIDC)
- Cross-domain authentication

**Single Sign-On (SSO):**
- SSO architectures
- SSO protocols (SAML, OIDC)
- SSO security considerations
- SSO implementation patterns

#### Training Resources
- Zero Trust Architecture training
- PAM solution training
- MFA implementation courses
- Identity federation courses
- SANS security courses (IAM coverage)

---

### 6. IAM Architecture & Design

#### Required Knowledge

**IAM Architecture:**
- IAM architecture patterns
- Identity provider architecture
- Service provider integration
- Directory services (LDAP, Active Directory)
- Identity stores

**Access Management:**
- Access control architectures
- Policy engines
- Authorization models
- Access decision points
- Access enforcement

**Identity Lifecycle:**
- User provisioning
- User deprovisioning
- Account lifecycle management
- Identity synchronization
- Identity governance

#### Training Resources
- IAM architecture courses
- Directory services training
- Identity lifecycle management courses
- Access management training

---

### 7. Red Hat Identity Management

#### Required Knowledge

**Red Hat Identity Management (IdM):**
- FreeIPA-based identity management
- LDAP/Kerberos integration
- Certificate management
- DNS integration
- SSSD (System Security Services Daemon)
- Integration with Linux systems

**Red Hat Directory Server:**
- LDAP directory services
- Directory architecture
- Directory security

#### Training Resources

**Red Hat Training:**
- [Red Hat Identity Management (RH362)](https://www.redhat.com/en/services/training/rh362-red-hat-identity-management)
  - **RECOMMENDED for IAM domain**
  - FreeIPA/IdM training
  - Identity management for RHEL

- Red Hat Directory Server courses
- Identity integration courses

**Certification:**
- [Red Hat Certified Specialist in Identity Management](https://www.redhat.com/en/services/certification/identity-management)

---

## Training by Tier

### Foundation Tier
**Focus**: IAM fundamentals

**Knowledge:**
- Authentication vs Authorization
- Basic IAM concepts
- SSO basics
- MFA basics

---

### Intermediate Tier
**Focus**: IAM implementation and protocols

**Training:**
- SAML implementation courses
- OIDC/OAuth 2.0 courses
- Identity provider training
- Red Hat Identity Management (if RHEL focus)

**Knowledge:**
- SAML protocol understanding
- OIDC protocol understanding
- Identity provider configuration
- SSO implementation

**Experience:**
- SSO implementation
- Identity provider configuration
- Basic IAM troubleshooting

---

### Advanced Tier
**Focus**: IAM architecture and advanced concepts

**Training:**
- IAM architecture courses
- Zero Trust Architecture training
- PAM training
- Advanced IAM protocols (XACML)
- [SANS SEC530: Defensible Security Architecture](https://www.sans.org/course/defensible-security-architecture-engineering) (includes IAM)

**Knowledge:**
- IAM architecture design
- Zero Trust principles
- PAM architectures
- XACML understanding
- Advanced authentication/authorization

**Experience:**
- IAM architecture design
- Zero Trust implementation
- PAM implementation
- Strategic IAM planning

---

### Expert Tier
**Focus**: Strategic IAM standards and policy

**Experience:**
- Set IAM security standards
- Strategic IAM architecture decisions
- IAM policy development
- Cross-functional IAM guidance
- IAM risk assessment

---

## Security Policy Development

### Authentication Policies
- Authentication requirements
- MFA requirements
- Password policies
- Authentication methods
- Risk-based authentication policies

### Authorization Policies
- Access control policies
- RBAC/ABAC policies
- Privileged access policies
- Just-In-Time access policies
- Zero Trust policies

### Identity Management Policies
- Identity lifecycle policies
- Provisioning/deprovisioning policies
- Identity governance policies
- Directory policies

### Federation Policies
- Identity federation policies
- Trust relationship policies
- SSO policies
- Protocol-specific policies (SAML, OIDC)

---

## Integration with Other Domains

### OSI Layers
- Application layer security (Layer 7)
- Authentication/authorization in applications
- Protocol security (SAML, OIDC, XACML)

### Standards Bodies
- IAM compliance requirements
- NIST IAM guidance
- ISO 27001 IAM controls
- Industry-specific IAM requirements

### Linux/RHEL
- Red Hat Identity Management
- SSSD integration
- LDAP/Kerberos integration
- Linux authentication/authorization

### Virtualization/Containers
- Identity in containers
- RBAC in Kubernetes/OpenShift
- Service accounts
- Identity in cloud environments

### Networking
- Network-based access control (NAC)
- Authentication in network access
- VPN authentication
- Network security and identity

---

## Key Resources

### Protocol Specifications
- [OAuth 2.0 RFC 6749](https://tools.ietf.org/html/rfc6749)
- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html)
- [SAML 2.0 Core Specification](http://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf)
- [XACML 3.0 Standard](http://docs.oasis-open.org/xacml/3.0/xacml-3.0-core-spec-os-en.html)

### Identity Providers
- Okta documentation
- Azure AD (Microsoft Identity Platform) documentation
- Google Identity Platform documentation
- Auth0 documentation
- Red Hat Identity Management documentation

### Standards Bodies
- NIST IAM guidance
- ISO/IEC 27001 IAM controls
- Industry-specific IAM standards

---

## Practical Experience Requirements

### Foundation Tier
- Basic IAM understanding
- Understanding of authentication/authorization
- Basic SSO understanding

### Intermediate Tier
- SSO implementation
- Identity provider configuration
- Basic IAM troubleshooting
- SAML/OIDC configuration

### Advanced Tier
- IAM architecture design
- Zero Trust implementation
- PAM implementation
- Strategic IAM planning
- Advanced IAM protocols

### Expert Tier
- Strategic IAM standards
- IAM policy development
- Architecture security reviews
- Cross-functional IAM guidance
- IAM risk assessment

---

**See Also:**
- [Advanced Tier](../TIERS/03-advanced-tier.md)
- [OSI Layers Domain](./osi-layers.md)
- [Linux & RHEL Domain](./linux-rhel.md)
- [Standards Bodies Domain](./standards-bodies.md)
- [Training Resources](../REFERENCE/training-resources.md)

