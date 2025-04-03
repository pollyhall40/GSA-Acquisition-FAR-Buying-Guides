# 1. Data Rights and Ownership

## 1.1 Ownership of Government Data and Work Products

The Government retains all rights, title, and interest in and to all data, content, documents, test materials, records, software configurations, metadata, logs, or other materials uploaded to, stored within, processed by, or generated through the SaaS platform (collectively, "Government Data").

The Government shall have unlimited rights to all such materials and shall determine the scope of publication, distribution, and use. The SaaS provider shall not claim ownership of, use, or sell Government Data for any purpose outside of this Agreement.

## 1.2 SaaS Provider's Obligation to Deliver Work Products

The SaaS provider shall provide the Government with access to and the ability to export:

1. All Government Data in a machine-readable, non-proprietary format upon request; and
2. All configurations, logs, workflows, and integrations with government systems upon contract termination or expiration.

The SaaS provider shall also provide comprehensive system documentation to ensure the Government retains control over its data and configurations, including:

- Data schemas
- APIs and integration points
- System logs and audit trails

## 1.3 Return or Retention of Government Data

Upon termination or expiration of this Agreement, the SaaS provider shall:

1. Provide the Government with all Government Data in a commonly used, non-proprietary format within **[x] days**;
2. Permanently delete all Government Data from its systems and certify such deletion in writing, unless retention is required by federal law or regulation; and
3. Ensure all backups, secondary storage, and disaster recovery sites are purged of Government Data, except where retention is required by law.

The SaaS provider shall not retain, use, or distribute any Government Data after contract termination except as legally required and with prior Government approval.

# 2. Data Storage and Security

## 2.1 Data Storage Location

All Government Data shall be stored exclusively within the United States in compliance with:

- Federal Risk and Authorization Management Program (FedRAMP) **Low/Moderate/High** (as applicable)
- OMB Memorandum M-19-17 (Cloud Smart Policy)
- National Institute of Standards and Technology (NIST) Special Publication 800-53

The SaaS provider shall not transfer, replicate, or process Government Data outside of U.S. jurisdictions without explicit written approval from the Government.

## 2.2 Security Standards and Compliance

The SaaS provider shall comply with all applicable federal security and privacy requirements, including but not limited to:

- FedRAMP **Low/Moderate/High** Baseline (as applicable)
- FISMA (Federal Information Security Modernization Act)
- NIST 800-171 (Controlled Unclassified Information Security Requirements)
- GSA IT Security Procedural Guide 2100.1
- Zero Trust Architecture principles (OMB Memorandum M-22-09)

# 3. Data Encryption and Security Measures

## 3.1 Encryption of Government Data

The SaaS provider shall encrypt all Government Data using the following standards:

- **In transit:** Transport Layer Security (TLS 1.2 or higher)
- **At rest:** AES-256 encryption or higher
- **Backups:** Encryption consistent with FedRAMP and NIST requirements

The SaaS provider shall not use proprietary encryption methods without Government approval.

## 3.2 Access Controls and Authentication

The SaaS provider shall implement Role-Based Access Control (RBAC) and require:

- Multi-Factor Authentication (MFA) for all users accessing Government Data
- Logging and monitoring of all privileged access and administrative actions
- Separation of duties to prevent unauthorized modifications to Government systems

## 3.3 Security Incident and Data Breach Notification

In the event of a **security breach or unauthorized access** involving Government Data, the SaaS provider shall:

1. Notify the Government **within [X] hours** of discovery;
2. Provide a detailed incident report within **[Y] days**, including scope, impact, mitigation measures, and corrective actions;
3. Fully cooperate with the Government's investigation and remediation efforts, including adherence to:
   - OMB Memorandum M-22-09 (Enhancing Cybersecurity with Zero Trust Architecture)
   - GSA breach reporting guidelines
   - NIST Cybersecurity Framework (CSF) for incident response
