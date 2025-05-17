# MHS Automated Invoicing Integration (Salesforce ↔ QuickBooks)

This project automates invoicing workflows for **Mountain Heritage Systems (MHS Technologies)** by integrating Salesforce and QuickBooks using **DBSync**, an ETL and integration platform. It eliminates double data entry, improves accuracy, and streamlines the quote-to-cash lifecycle.

## 🏢 Business Context

- **Client**: MHS Technologies (Est. 1979)
- **Industry**: Smart Home Automation, Network, Fire & Security
- **Problem**: Manual entry between Salesforce and QuickBooks led to delays, errors, and inefficiencies.
- **Goal**: Automate and secure financial data flow with real-time sync.

## 🔧 Solution Overview

- **ETL Approach**: ETL (Extract, Transform, Load) is a process used to:
  - **Extract** data from one system (Salesforce invoices, QuickBooks payments)
  - **Transform** the format or structure to match the receiving system’s schema
  - **Load** the clean data into the target application (e.g., QuickBooks or Salesforce)

- **Platform Used**: [DBSync](https://www.mydbsync.com/)
- **Integration Points**:
  - Invoices from Salesforce → QuickBooks
  - Payments from QuickBooks → Salesforce
- **Features**:
  - Real-time synchronization
  - Error handling and logging
  - User role-based automation

## 🎬 Demonstration Walkthroughs

⚠️ *Access to demonstration videos is restricted to authorized personnel due to sensitive client systems and data visibility.*

- Internal stakeholders may request access to:
  - Salesforce to QuickBooks Invoice Sync walkthrough
  - QuickBooks Payment Sync to Salesforce demo

## 🚀 Implementation Details

- Created and tested ETL flows for two-way syncing.
- Configured transformation logic in DBSync to map invoice and payment fields accurately.
- Coordinated VPN access to MHS systems for remote development and testing.
- Configured logging, automation schedules, and record validation.

- Notes:
  - Legacy (past) invoices were not synced retroactively.
  - Ongoing maintenance will be handled by a third-party integrator.

## ✅ Benefits Delivered

- **Faster Processing**: Reduced workflow time by automating invoice creation and status updates.
- **Improved Accuracy**: Fewer human errors and real-time data integrity.
- **Time & Cost Savings**: Minimizing manual labor and redundant data entry.
- **User Experience**: Streamlined UIs and fewer steps for daily operations.

## 💡 Key Takeaways

- Applied ETL concepts in a real-world client setting.
- Gained hands-on experience with:
  - Salesforce object structures and custom layouts
  - DBSync mapping and transformation logic
  - VPNs and remote system deployment
- Developed communication and project coordination skills in a professional environment.

---

📁 _Developed by Isaac Krueger, Brian Smith, Keegan Walker, and Nick Baumler as part of the CIS Capstone experience at Appalachian State University._
