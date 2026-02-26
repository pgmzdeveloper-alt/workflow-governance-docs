# Workflow Governance for Jira - Official Documentation

Welcome to the official documentation for **Workflow Governance**, developed by PGMZ. This native Forge application helps Jira Administrators audit, monitor, and enforce workflow compliance across their entire Jira Cloud instance without the heavy overhead of traditional enterprise tools.

---

## 1. Getting Started

### Accessing the App
Once installed from the Atlassian Marketplace, you can access the governance center by following these steps:
1. Log in to your Jira Cloud instance as a Jira Administrator.
2. Click on the **Settings (gear icon)** in the top right corner.
3. Select **Apps**.
4. In the left-hand sidebar, under the *Workflow Governance* section, click on **Dashboard**.

---

## 2. Core Features & Navigation

### 2.1 Centralized Dashboard
The **Dashboard** is your central hub for instance compliance.
* **Compliance Score:** Displays the overall health of your Jira instance based on active policies.
* **Active Policies:** Shows the number of rules currently running.
* **Violations Detected:** Highlights any issues that break your governance rules.
* **Governance Details:** A quick-access table to review, edit, or check the status of specific policies across your monitored projects.

### 2.2 Custom Policy Builder
Jira Administrators can create custom rules to ensure workflows meet company standards.
1. Navigate to the **Policies** tab.
2. Click the **+ Create Policy** button.
3. **General & Strategy:** Define the *Policy Name* and *Version*.
4. **Governance Strategy:** Choose how the app should react when a violation occurs:
   * **Audit Only (Log Violation):** The app will silently record the violation in the Audit Logs without interrupting the user's workflow.
   * **Blocking (Prevent Action):** The app will actively block the user from transitioning the Jira issue until it complies with your organization's rule.

### 2.3 Scan History & Global Audits
Run global scans to retrospectively check your instance for compliance gaps.
* Navigate to **Scan History** to view the execution dates, status (e.g., COMPLETED), and findings of all global audits.
* Use the **Audit Logs** tab to investigate specific violations and identify which projects or issues need immediate attention.

---

## 3. Data Privacy & Security

Workflow Governance is built entirely on the Atlassian Forge platform. This means the app runs natively within Atlassian's secure infrastructure. 
For more details on how we handle data and respect data sovereignty, please review our [Privacy Policy](https://github.com/pgmzdeveloper-alt/privacy-policy).

---

## 4. Support & Service Level Agreement (SLA)

We are committed to providing friendly, speedy, and effective support for all our paid users. If you encounter any issues, bugs, or need configuration assistance, we are here to help.

### Support Channels
* **Email Support:** pgmz.developer@gmail.com
* **Bug Reports & Feature Requests:** Please email us with your Jira instance URL, screenshots, and a detailed description of the issue.

### Service Level Agreement (SLA)
* **Operating Hours:** Monday to Friday, 09:00 AM - 06:00 PM (Ecuador Time / ECT).
* **First Response Time:** We aim to respond to all critical support tickets within 24 business hours.
* **Resolution Time:** Varies depending on the complexity of the issue, but critical bugs affecting workflow blocking will be strictly prioritized.

---
*Developed by PGMZ. Smart workflow optimization for global teams.*
