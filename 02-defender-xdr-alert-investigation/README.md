## 🖥️ Microsoft Defender XDR Portal

Microsoft Defender XDR provides a centralised security operations interface for monitoring, investigating, hunting, and responding to security threats.

The Microsoft Defender portal can be accessed at:

**https://security.microsoft.com**

The portal brings together security capabilities across identities, endpoints, email, cloud applications, threat intelligence, Microsoft Sentinel, and other Microsoft security services.

> **Note:** The features and navigation available in the Defender portal can vary depending on the products, subscriptions, permissions, and integrations configured in the tenant.

### 🧭 Defender XDR Portal Navigation

The left-hand navigation provides access to the major security capabilities available within the Microsoft Defender portal.

![Microsoft Defender XDR portal navigation](images/01-defender-xdr-navigation.png)

The main areas relevant to this SOC lab include:

| Portal Area | SOC Purpose |
|---|---|
| **Home** | Provides an overview of the security environment and access to important security information. |
| **Cases** | Helps security teams organise and manage investigations that may involve multiple incidents, tasks, evidence, and analyst activities. |
| **Exposure management** | Helps identify security weaknesses, vulnerabilities, attack paths, and other risks before they become security incidents. |
| **Investigation & response** | Provides capabilities for investigating incidents and alerts and performing appropriate response actions. |
| **Threat intelligence** | Provides threat intelligence that can be used to enrich investigations and analyse suspicious indicators, threats, and campaigns. |
| **Assets** | Provides visibility into users, devices, applications, and other assets involved in the security environment. |
| **Microsoft Sentinel** | Provides access to Microsoft Sentinel capabilities for SIEM, threat hunting, analytics, incident management, and automation. |
| **Identities** | Provides security visibility into users, accounts, authentication activity, and identity-related threats. |
| **Endpoints** | Provides visibility into devices, processes, files, vulnerabilities, and endpoint security activity. |
| **Email & collaboration** | Provides security capabilities for investigating phishing, malicious emails, attachments, URLs, and other collaboration threats. |
| **Cloud apps** | Provides visibility into cloud application activity, suspicious sessions, OAuth applications, and cloud-related threats. |
| **Cloud security** | Provides security visibility across cloud resources, workloads, vulnerabilities, configurations, and cloud-related threats. |
| **SOC optimization** | Helps security teams improve detection coverage, security controls, data usage, and overall SOC effectiveness. |
| **Reports** | Provides security reporting and information that can be used to understand trends and communicate security information. |
| **Learning hub** | Provides Microsoft security learning resources and guidance for understanding Defender capabilities. |
| **Trials** | Provides access to available Microsoft security trial offerings that can be used to evaluate additional security capabilities. |
| **More resources** | Provides access to additional Microsoft security resources and capabilities. |
| **System** | Provides access to system-level and administrative configuration within the Defender portal. |

---

### 🏠 Home

The **Home** page provides an overview of the Microsoft Defender environment.

It can act as the starting point for accessing security information, recommendations, incidents, investigations, and other Defender capabilities.

#### SOC Analyst Use

A SOC analyst may use Home to:

- Get an overview of the security environment.
- Access important security information.
- Navigate to incidents and investigations.
- Review security recommendations.
- Access commonly used Defender capabilities.

The Home page is primarily a starting point. Detailed investigations are normally performed through the dedicated investigation and hunting capabilities.

---

### 📂 Cases

The **Cases** section provides case-management capabilities for security operations.

Cases are useful when an investigation becomes larger than a single alert or incident.

For example:

```text
Case
│
├── Incident 1
├── Incident 2
├── Investigation Tasks
├── Indicators
├── Evidence
└── Analyst Notes
```

---
### 🛡️ Exposure Management

**Exposure management** helps security teams identify weaknesses and security risks across their environment.

It provides visibility into areas such as:

- Vulnerabilities
- Misconfigurations
- Exposed assets
- Attack paths
- Security weaknesses

---

#### SOC Analyst Use

A SOC analyst may use Exposure Management to:

- Identify vulnerable assets involved in an investigation.
- Understand potential attack paths.
- Review security weaknesses related to an incident.
- Prioritise security risks that require attention.

---

### 🔍 Investigation & Response

**Investigation & Response** provides the main capabilities used to investigate security incidents and alerts and perform response actions.

It brings together tools and information required during a security investigation.

#### SOC Analyst Use

A SOC analyst may use Investigation & Response to:

- Review incidents and alerts.
- Investigate suspicious activity.
- Examine affected entities.
- Review evidence and timelines.
- Perform response actions.
- Track the investigation from detection to resolution.

This is one of the most important areas of the Defender portal for day-to-day SOC operations.

---

### 🕵️ Threat Intelligence

**Threat Intelligence** provides information that can help analysts understand suspicious indicators and known threats.

Analysts can use threat intelligence to investigate indicators such as:

- IP addresses
- Domains
- URLs
- File hashes
- Threat actors
- Malware
- Campaigns

#### SOC Analyst Use

A SOC analyst may use Threat Intelligence to:

- Enrich an investigation with additional context.
- Check whether an indicator is associated with known threats.
- Investigate suspicious infrastructure.
- Identify relationships between indicators.
- Support the final investigation verdict.

---

### 🗂️ Assets

The **Assets** section provides visibility into assets within the organisation's security environment.

These may include:

- Users
- Devices
- Applications
- Mailboxes
- Other security-related assets

#### SOC Analyst Use

A SOC analyst may use Assets to:

- Identify affected users or devices.
- Investigate activity associated with an asset.
- Understand the relationship between assets and incidents.
- Review security information associated with an asset.

Understanding the affected asset is an important part of determining the scope and impact of an incident.

---

### 🛡️ Microsoft Sentinel

**Microsoft Sentinel** provides SIEM and security operations capabilities within the Microsoft security environment.

It can collect and analyse security data from Microsoft and other sources.

Key capabilities include:

- Security monitoring
- Log collection
- KQL queries
- Analytics rules
- Incident management
- Threat hunting
- Automation

#### SOC Analyst Use

A SOC analyst may use Microsoft Sentinel to:

- Investigate security incidents.
- Search security logs using KQL.
- Create and investigate detections.
- Correlate security events.
- Perform threat hunting.
- Automate response actions.

Microsoft Sentinel becomes particularly useful when security data from multiple sources needs to be analysed together.

---

### 👤 Identities

The **Identities** section provides security visibility into users, accounts, authentication activity, and identity-related threats.

Identity information can help analysts understand who performed an action and whether the activity was legitimate.

#### SOC Analyst Use

A SOC analyst may use Identities to:

- Investigate suspicious sign-ins.
- Review account activity.
- Investigate compromised accounts.
- Identify unusual authentication behaviour.
- Investigate identity-related alerts.
- Understand which user account is associated with an incident.

Identity investigation is especially important when investigating credential theft, account compromise, and lateral movement.

---

### 💻 Endpoints

The **Endpoints** section provides security visibility into devices and endpoint activity.

This can include information about:

- Devices
- Processes
- Files
- Applications
- Vulnerabilities
- Endpoint alerts
- Device activity

#### SOC Analyst Use

A SOC analyst may use Endpoints to:

- Investigate suspicious processes.
- Examine malicious files.
- Review device activity.
- Investigate endpoint alerts.
- Identify affected devices.
- Perform endpoint response actions.

Endpoint visibility is a key component of detecting and responding to malware, ransomware, and other endpoint-based attacks.

---

### 📧 Email & Collaboration

The **Email & Collaboration** section provides security capabilities for investigating threats delivered through email and collaboration services.

Common investigation areas include:

- Phishing emails
- Malicious attachments
- Malicious URLs
- Suspicious senders
- Email campaigns
- Collaboration threats

#### SOC Analyst Use

A SOC analyst may use Email & Collaboration to:

- Investigate reported phishing emails.
- Analyse suspicious messages.
- Investigate malicious attachments.
- Analyse URLs contained in emails.
- Search for similar messages across mailboxes.
- Identify users targeted by a phishing campaign.

Email investigation can help determine whether a suspicious email affected one user or multiple users.

---

### ☁️ Cloud Apps

The **Cloud Apps** section provides visibility into activity involving cloud applications.

It can help security teams understand how users and applications interact with cloud services.

Investigation areas may include:

- Cloud application activity
- User sessions
- Suspicious applications
- OAuth applications
- Application permissions
- Cloud-related threats

#### SOC Analyst Use

A SOC analyst may use Cloud Apps to:

- Investigate suspicious cloud application activity.
- Review unusual user sessions.
- Investigate suspicious OAuth applications.
- Identify potentially risky application access.
- Investigate cloud-based threats.

---

### ☁️ Cloud Security

The **Cloud Security** section provides security visibility across cloud resources and workloads.

It helps security teams identify and investigate security issues affecting cloud environments.

Investigation areas may include:

- Cloud resources
- Cloud workloads
- Vulnerabilities
- Misconfigurations
- Identity activity
- Cloud threats

#### SOC Analyst Use

A SOC analyst may use Cloud Security to:

- Investigate suspicious cloud activity.
- Review cloud security alerts.
- Identify vulnerable cloud resources.
- Investigate cloud misconfigurations.
- Understand threats affecting cloud workloads.

---

### 🎯 SOC Optimization

**SOC Optimization** helps security teams improve the effectiveness of their security operations.

It can help identify opportunities to improve:

- Detection coverage
- Security controls
- Data sources
- Security configurations
- Investigation capabilities

#### SOC Analyst Use

A SOC analyst or security engineer may use SOC Optimization to:

- Identify gaps in detection coverage.
- Improve security monitoring.
- Review recommendations.
- Identify areas where security controls can be strengthened.
- Improve the overall effectiveness of SOC operations.

---

### 📊 Reports

The **Reports** section provides security-related reporting and information.

Reports can help security teams understand security activity and trends across the environment.

#### SOC Analyst Use

A SOC analyst may use Reports to:

- Review security trends.
- Understand security activity over time.
- Monitor security metrics.
- Support investigation reporting.
- Provide security information to other teams.

Reports are generally more focused on visibility and analysis than on performing individual investigations.

---

### 📚 Learning Hub

The **Learning Hub** provides Microsoft security learning resources and guidance.

It can help analysts understand Microsoft security products and capabilities.

#### SOC Analyst Use

A SOC analyst may use Learning Hub to:

- Learn about Defender capabilities.
- Understand new security features.
- Improve product knowledge.
- Access Microsoft security guidance.
- Support ongoing technical development.

---

### 🧪 Trials

The **Trials** section provides access to available Microsoft security trial offerings.

Trials can be useful when building a security lab or evaluating additional security capabilities.

#### SOC Analyst Use

For a security lab, Trials may be used to:

- Evaluate additional Microsoft security products.
- Enable capabilities required for practical exercises.
- Test security features before purchasing a subscription.
- Expand the lab environment for additional investigation scenarios.

> **Note:** Available trials and licensing options can vary depending on the tenant, account, region, and Microsoft licensing changes.

---

### 📖 More Resources

**More Resources** provides access to additional Microsoft security capabilities and related resources within the Defender environment.

The available options may vary depending on the tenant and enabled services.

#### SOC Analyst Use

A SOC analyst may use this area to:

- Discover additional security capabilities.
- Access related Microsoft security services.
- Navigate to additional security resources.
- Explore functionality that may support an investigation.

---

### ⚙️ System

The **System** section provides access to system-level and administrative functionality within the Defender portal.

The available options depend on the user's permissions and enabled Microsoft security services.

#### SOC Analyst Use

Depending on their role and permissions, security team members may use System to:

- Review security-related configuration.
- Manage applicable settings.
- Configure supported security capabilities.
- Access administrative options.

> **Note:** Many administrative functions require appropriate permissions and may not be available to standard SOC analyst accounts.

---

## 🔄 Defender XDR Investigation Flow

The different areas of the Defender portal can work together during a security investigation.

A typical investigation may follow this flow:

```text
Security Event
      │
      ▼
Detection / Alert
      │
      ▼
Incident
      │
      ▼
Investigation & Response
      │
      ├───────────────┬────────────────┐
      ▼               ▼                ▼
   Endpoint         Identity        Email
      │               │                │
      └───────────────┼────────────────┘
                      ▼
              Threat Intelligence
                      │
                      ▼
                Threat Hunting
                      │
                      ▼
                 Final Verdict
                      │
              ┌───────┴───────┐
              ▼               ▼
            Benign          Malicious
                              │
                              ▼
                       Response Actions
                              │
                              ▼
                          Remediation



