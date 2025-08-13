# Qualys Certified Specialist: CyberSecurity Asset Management (CSAM) — Detailed Notes

---

## 1. Overview

CyberSecurity Asset Management (CSAM) is designed to provide organizations with full visibility of their internal and external IT assets, enrich asset data with business context, and deliver actionable insights for risk management.  

Core objectives:
- Discover and track all assets (known and unknown) across the enterprise.
- Normalize and classify assets for accurate inventory.
- Detect security risks such as End-of-Life (EoL), End-of-Support (EoS), and unauthorized software.
- Integrate asset intelligence into ITSM and CMDB systems.
- Continuously monitor for changes and anomalies.

---

## 2. Core Functional Areas

### 2.1 Asset Discovery
- **Internal Asset Discovery**  
  - Uses agents, scanner appliances, and passive sensors to identify devices in corporate networks.
  - Finds both managed and unmanaged assets.
  - Detects shadow IT, IoT, OT, and transient devices.
  
- **External Asset Discovery**  
  - Identifies internet-facing assets, domains, and IP ranges owned by the organization.
  - Includes assets from subsidiaries, mergers, and acquisitions.

### 2.2 Asset Inventory and Normalization
- Consolidates data from multiple sources into a unified inventory.
- Normalizes asset attributes (naming conventions, OS types, hardware identifiers).
- Groups related data points from different discovery methods into a single asset record.
- Prevents duplicate entries through correlation rules.

### 2.3 Asset Classification
- Categorizes assets by:
  - Operating System
  - Hardware type (server, workstation, network device, mobile)
  - Business function (production, development, testing)
  - Location and ownership
- Uses dynamic tagging to automate classification based on rules.
- Supports static tagging for fixed group assignments.

### 2.4 Asset Enrichment
- Adds business context such as:
  - Asset owner or department
  - Criticality to business operations
  - Location (physical site or cloud region)
- Incorporates lifecycle status (active, inactive, retired).
- Enhances asset data with vulnerability and compliance status.

---

## 3. Risk Insight Features

### 3.1 Product Lifecycle Tracking
- Identifies End-of-Life (EoL) and End-of-Support (EoS) software and hardware.
- Maintains a timeline for lifecycle milestones.
- Allows proactive planning for upgrades or replacements.

### 3.2 Unauthorized Software Detection
- Flags applications that are not approved for organizational use.
- Detects potentially risky or non-compliant software.
- Supports whitelisting of authorized applications.

### 3.3 Asset Criticality Scoring
- Assigns a score to each asset based on:
  - Business importance
  - Data sensitivity
  - Exposure level
- Helps prioritize remediation and monitoring efforts.

### 3.4 Continuous Monitoring
- Tracks changes in asset configurations and software.
- Detects new vulnerabilities or risk indicators.
- Issues alerts for policy violations or asset drift.

---

## 4. Data Collection and Architecture

### 4.1 Sensors and Data Sources
- **Cloud Agents:** Continuous monitoring on endpoints and servers.
- **Scanner Appliances:** Scheduled network scans for detailed assessment.
- **Passive Sensors:** Real-time network traffic analysis to find unmanaged devices.
- **API Integrations:** Data ingestion from cloud providers and third-party systems.

### 4.2 Data Flow
1. Sensors collect raw asset and configuration data.
2. Data is transmitted securely to the central platform.
3. Asset correlation and normalization are performed.
4. Business context and risk scores are applied.
5. Updated asset records are stored in the unified inventory.

---

## 5. Integration Capabilities

- Synchronization with CMDB platforms to ensure accurate and enriched asset data.
- Two-way integration with ITSM tools for incident and change management workflows.
- Data sharing with vulnerability management, compliance, and risk reporting modules.
- API-based access for custom automation and reporting.

---

## 6. Reporting and Dashboards

- **Inventory Reports:** List of all assets with key attributes and risk indicators.
- **Lifecycle Reports:** EoL/EoS summaries for hardware and software.
- **Software Inventory Reports:** Authorized vs. unauthorized software analysis.
- **Risk Exposure Dashboards:** Visualization of high-criticality assets and their vulnerabilities.
- **Change Tracking Views:** Historical asset state comparisons to detect modifications.

---

## 7. Key Terms

- **Asset Inventory:** Centralized list of all discovered and tracked assets.
- **Normalization:** Standardizing asset data into consistent formats.
- **Dynamic Tagging:** Automated classification based on predefined conditions.
- **EoL/EoS:** End-of-Life / End-of-Support — key risk indicators for hardware and software.
- **Asset Criticality Score:** Numerical value representing the importance of an asset to the organization.
- **Shadow IT:** Unapproved assets or services in use within the organization.

---

