### Demo Video link : https://drive.google.com/file/d/1i_6oWJH7dTLHBDQvpidB-MhdKWJwUxIn/view?usp=sharing
### Document link : https://docs.google.com/document/d/1VZkie1NwYNsKFQ8z1-iZB6UZUcgi39n5nJfgpOtTlnc/edit?usp=sharing
### Presntation (PPT) link : https://drive.google.com/file/d/107lYOpoYtZXxozNH7myI2cvQeZK4SYE1/view?usp=sharing

# Integrated Banking Operations Hub With AI Integrated : A Salesforce Solution

### Project Overview
This CRM project establishes an Integrated Banking Hub to unify critical financial operations: Loan Management, Wealth Management, and Regulatory Compliance. The platform automates high-volume lending decisions through Flows and Approval Processes, provides financial advisors with real-time portfolio valuation, and enforces security by creating an automated audit trail for compliance. The key business need addressed is replacing fragmented, manual processes with a secure, centralized, and efficient system.

###**Objectives**
The main goals of building this CRM were to achieve operational efficiency and enhance regulatory posture.
- **Automate Lending:** Implement intelligent routing to ensure high-value loans (>₹20 Lakhs) receive mandatory manager review via an Approval Process, while low-value loans are auto-approved for streamlined booking.
- **Enable Real-Time Advice:** Calculate client portfolio value and goal progress dynamically using Apex Triggers and Roll-Up logic to enable proactive financial advice.
- **Ensure Compliance:**  Establish a foundational Audit Log for critical changes and centralize risk monitoring using custom objects and automated Flows.
- **Visibility:** Deliver custom Lightning Web Component (LWC) dashboards for personalized, role-specific insights across all modules.

### Key Features and Use Cases

This project will be a masterclass in Salesforce development, covering all the topics from your training calendar. It's unique because it integrates multiple business processes into a single solution.

**1. Loan Management Module**
- **Use Case:** Digitize the loan application, approval, and repayment process.
- **Key Features:** Includes automated risk scoring, a multi-step approval process, and an automated audit trail.

**2. Wealth & Portfolio Management Module**
- **Use Case:** Centralize the tracking of a client's investment portfolio, assets, and goals.
- **Key Features:** Provides automatic calculation of portfolio value (using Apex/Roll-Up logic), real-time asset tracking, and a dynamic LWC dashboard for advisors.

**3. Compliance & Risk Management Module**
- **Use Case:** Monitor and manage regulatory compliance and risk events across the bank.
- **Key Features:** A system to track regulations, audit major changes (via Flow), and send alerts for compliance issues.

---

### Phase 1: Problem Understanding & Industry Analysis

**1. Requirement Gathering**
- **What we'll build:** A single platform to manage client records, loan applications, investment portfolios, and compliance regulations.
- **Key features:** We will need to build custom objects for each module and use automation to connect them.

**2. Stakeholder Analysis**
- **Loan Officers:** They will use the **Loan Management Module** to process applications.
- **Wealth Advisors:** They will use the **Wealth Management Module** to manage client portfolios.
- **Compliance Officers:** They will use the **Compliance Module** to enforce regulations across the entire system.
- **Management:** They will get a complete picture of the bank's operations, financial performance, and risk exposure.

**3. Business Process Mapping**
- **Proposed Process:** A client's information is entered once. A loan officer can open a loan application for them. A wealth advisor can create an investment portfolio. All these actions are tracked by the compliance module, ensuring every step is secure and compliant.

**4. Industry-specific Use Case Analysis**
- This project is highly innovative because it addresses the problem of **data silos** in financial institutions. Instead of building three separate projects, you're building a single integrated platform, which is what real companies do.

**5. AppExchange Exploration**
- We'll explore AppExchange for tools like **DocuSign** for e-signatures, **DocGen** for document generation, and a free API to get dummy **stock prices**.

### How this Project Covers Every Topic

- **Admin:** You'll build multiple objects, implement **Approval Processes** for loans, and create **Validation Rules** for compliance.
- **Developer:** You'll use an **Apex Trigger** to calculate portfolio value, **Batch Apex** to update market data, and **Scheduled Apex** to send monthly compliance reports.
- **UI (LWC):** You'll build a custom **LWC** dashboard for each module (loan, wealth, compliance) to give a personalized experience.
- **Integration:** You'll use **REST callouts** and **Named Credentials** to get real-time stock prices.
