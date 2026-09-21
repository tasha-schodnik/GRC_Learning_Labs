# 🏗️ RHP Enterprise Architecture

## Purpose

This document provides a high-level overview of the technology architecture supporting **Raccoon Health & Pharmacy (RHP)**.

RHP is a fictional small independent retail, compounding, and specialty pharmacy used for cybersecurity and Governance, Risk, and Compliance (GRC) home labs and portfolio projects.

The architecture described here establishes the simulated technical environment used as background information for risk assessments, control assessments, compliance reviews, policy development, third-party risk assessments, and other RHP GRC projects.

---

# 🏢 Architecture Overview

RHP operates from a single physical pharmacy location and uses a **cloud-first, hybrid technology model**.

The environment combines:

- On-premises pharmacy technology
- Employee workstations
- Local network infrastructure
- Network security devices
- Cloud and SaaS applications
- Identity and access-management services
- Third-party hosted services
- Pharmacy automation
- Environmental monitoring
- Patient-facing digital services
- Payment-processing services
- Backup and recovery services

Because RHP is a small organization, it maintains limited internal IT staff and relies on third-party providers for several technology and security capabilities.

---

# 🌐 Network Architecture

RHP maintains local network infrastructure at its pharmacy location to provide connectivity for employees, pharmacy systems, business systems, security technology, and connected devices.

The network environment includes:

- Wired network connectivity
- Wireless network connectivity
- Network switches
- Wireless access points
- Fortinet FortiGate firewall
- Internet connectivity
- Employee workstations
- Pharmacy systems
- Security systems
- Connected pharmacy technology

The **Fortinet FortiGate firewall** provides perimeter security between RHP's internal network and external networks.

Network security capabilities may include:

- Firewall rules
- Network traffic filtering
- Administrative access controls
- Security logging
- Network segmentation
- Secured wireless access

Detailed network configurations and firewall rules are maintained separately from this high-level architecture documentation.

---

# 💻 Endpoint Environment

RHP employees use pharmacy workstations to access pharmacy and business systems required for their job responsibilities.

Workstations may be used to access:

- PioneerRx
- Microsoft 365
- Pharmacy-related services
- Business applications
- Administrative systems
- Patient and prescription information

Endpoint security capabilities include:

- User authentication
- Endpoint protection
- Malware protection
- Security monitoring
- Screen locking
- Device encryption
- Security alerts

RHP uses an endpoint-security platform to provide malware prevention, endpoint monitoring, and threat-detection capabilities.

---

# 🔑 Identity & Access Architecture

**Microsoft Entra ID** serves as a primary identity and access-management platform for supported RHP cloud services.

Identity and access capabilities may include:

- Centralized user identities
- Authentication
- Multi-factor authentication (MFA)
- Role-based access
- Privileged-access restrictions
- Authentication logging
- Account administration

Some pharmacy systems maintain their own authentication mechanisms and may not rely directly on Microsoft Entra ID.

Examples include systems supporting:

- PIN or password authentication
- Biometric authentication
- Operator IDs
- Application-specific user accounts

Access requirements therefore vary by system and are documented in the **RHP System Inventory**.

---

# ☁️ Cloud & SaaS Environment

RHP relies on cloud and SaaS services for several business and security functions.

Cloud-based services include:

- Microsoft 365
- Microsoft Entra ID
- Endpoint-security services
- HR and payroll services
- Backup and recovery services
- Patient-facing digital services
- Other vendor-hosted business services

Cloud services may process or store:

- Business information
- Employee information
- Authentication information
- Patient information
- PHI/ePHI
- Documents
- Email
- Security telemetry
- Backup data

Access to cloud services is provided through authenticated internet-facing interfaces where applicable.

---

# 💊 Pharmacy Technology

## PioneerRx Pharmacy Management Software

PioneerRx supports core pharmacy operations including:

- Prescription processing
- Prescription filling
- Patient care
- Pharmacy workflow
- Patient information management

RHP uses a hybrid PioneerRx environment with technology located at the pharmacy and vendor-supported off-site/cloud capabilities.

PioneerRx processes sensitive pharmacy and healthcare information including PHI/ePHI, prescription information, patient information, insurance/claims information, and billing information.

---

## ScriptPro Pharmacy Automation

ScriptPro supports prescription fulfillment by automating portions of the dispensing process.

The system operates within the physical pharmacy environment and interacts with prescription and medication information required for dispensing operations.

If ScriptPro becomes unavailable, pharmacy staff may continue dispensing through manual processes, although operational efficiency may be reduced.

---

## Rees Scientific Monitoring System

RHP uses Rees Scientific technology to support cleanroom and environmental monitoring associated with compounding operations.

The system supports monitoring and recording environmental conditions relevant to RHP's sterile and hazardous-drug compounding activities.

The architecture includes local monitoring components with vendor/cloud-supported capabilities.

Environmental monitoring records may support regulatory and operational requirements associated with RHP's compounding environment.

---

# 💳 Payment Processing

RHP uses a third-party payment-processing environment to process retail and patient payment transactions.

The payment environment may process:

- Payment-card information
- Transaction information
- Limited customer or patient information

Where practical, payment processing is separated from core pharmacy-processing functions.

The payment environment may be subject to applicable **PCI DSS** requirements.

---

# 🔒 Physical Security

RHP maintains physical-security technology at the pharmacy location.

Physical-security capabilities may include:

- Video surveillance
- Intrusion detection
- Facility monitoring
- Security-event recording
- Controlled administrative access

Physical-security services may rely on a third-party monitoring or technology provider.

---

# 💾 Backup & Recovery

RHP uses backup and recovery capabilities to protect designated business and system information.

Backup architecture may include:

- Local system backups
- Vendor-managed backups
- Cloud backup services
- Off-site backup storage
- System-specific recovery capabilities

Backup data may contain sensitive business information, PII, PHI, or ePHI depending on the source system.

Recovery responsibilities vary by system and vendor.

---

# 🔗 Third-Party Dependencies

RHP relies on third-party providers for several important technology and operational capabilities.

Technology-related dependencies include:

- Pharmacy management services
- Pharmacy automation
- Environmental monitoring
- Cloud productivity services
- Identity services
- Endpoint security
- Network security
- Physical security
- Payment processing
- HR and payroll
- Backup and recovery
- Patient-facing digital services

Additional operational vendors support pharmaceutical procurement, pharmacy supplies, office supplies, and pharmaceutical waste management.

Detailed vendor relationships are maintained in the **RHP Vendor Inventory**.

---

# 🔄 High-Level Information Flows

Information moves between RHP employees, internal systems, cloud services, pharmacy technologies, patients, and third-party providers.

Examples include:

**Patients → RHP Pharmacy Systems**  
Prescription, patient, insurance, refill, and contact information enters RHP pharmacy workflows.

**RHP Workstations → Pharmacy & Business Systems**  
Employees use authenticated workstations to access systems required for pharmacy and administrative activities.

**RHP Systems → Third-Party Services**  
Information may be exchanged with pharmacy technology providers, cloud services, payment processors, healthcare services, and other authorized vendors.

**RHP Systems → Backup Services**  
Designated business and system information is copied to approved backup and recovery services.

**Security Systems → Logs / Security Monitoring**  
Network, endpoint, identity, and application technologies may generate security logs and alerts used for monitoring and investigation.

Detailed information flows are represented in the **RHP Data-Flow Diagram**.

---

# 📚 Related RHP Documentation

This architecture document should be used with the following RHP environment artifacts:

- **RHP System Inventory**
- **RHP Data-Flow Diagram**
- **RHP Vendor Inventory**
- **RHP Requirements Register**
- **RHP Policy Inventory**
- **RHP Security Objectives**
- **RHP Stakeholder Directory**

Together, these documents establish the simulated organizational and technical context used throughout RHP GRC projects.

---

## ⚠️ Portfolio Note

This document describes a fictional architecture created with AI assistance for cybersecurity and GRC home labs.

The architecture serves as **simulated source information** for hands-on projects. Risk identification, risk ratings, control assessments, compliance determinations, findings, remediation decisions, and other analyst conclusions are developed separately as part of the individual RHP GRC projects.
