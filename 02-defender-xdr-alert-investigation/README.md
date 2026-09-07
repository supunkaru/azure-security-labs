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
