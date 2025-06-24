# 🔍 Custom Field Usage Analyzer – Salesforce

**Version:** 1.0  
**Author:** Naman Singh  
**Install Link:** [Install Package](https://login.salesforce.com/packaging/installPackage.apexp?p0=04tJ1000000onQU)

---

## 📌 Overview

The **Custom Field Usage Analyzer** is a Salesforce Lightning-based utility designed to help developers and admins:

- **Identify underutilized or unused custom fields**
- **Export usage data to CSV**
- **Auto-populate field lists** for objects

It helps you optimize org cleanliness, improve data model hygiene, and support decision-making for field deprecation.

---

## 🚀 Features

✅ Analyze field usage count for any object  
✅ Auto-populate all custom field API names for a given object  
✅ Export results to a clean, ready-to-use CSV  
✅ Works with Lightning Experience  
✅ Clean and minimal UI with fast performance

---

## 📸 Screenshots

### 🎯 Analyze Button  
![Analyze Button](/ss2.png)  
> Helps analyze field usage so less-used fields can be flagged for removal.

---

### ⚙️ Auto Populate  
![Auto Populate](/ss1.png)  
> Auto-populates all custom fields for the object mentioned in the **Object API Name** field.

---

## 🛠️ Components

| Component Type     | Name                              |
|--------------------|-----------------------------------|
| **App**            | Field Usage Analyzer              |
| **Lightning Page** | Field_Usage_Analyzer              |
| **LWC**            | customFieldUsageAnalyzer          |
| **Apex Class**     | CustomFieldUsageAnalyzerController |
| **Test Class**     | CustomFieldUsageAnalyzerControllerTest |
| **Tab**            | Field Usage Analyzer              |

---

## 🧪 How to Use

1. Navigate to **App Launcher → Field Usage Analyzer**
2. Enter your **Object API Name** (e.g., `Account`)
3. Use one of the options:
    - Click `Auto Populate All Custom Fields` to fetch all custom fields
    - OR enter comma-separated custom field API names manually
4. Click `Analyze` to view field usage count and last modified date
5. Click `Export to CSV` to download the results for offline analysis

---

## 🎯 Benefits

- Quickly identify fields that are never or rarely used
- Maintain clean, efficient org data models
- Plan field retirement confidently
- Speed up admin and developer decision-making
- Improve org performance by decluttering unused fields

---

## 🧩 Version Details

- **Version Name:** Initial Version  
- **Version Number:** 1.0  
- **Release Date:** June 23, 2025

---

## 📦 Installation

Click the link below to install in your Salesforce org:

🔗 [Install via Salesforce](https://login.salesforce.com/packaging/installPackage.apexp?p0=04tJ1000000onQU)

---

## 🧾 License

MIT License (or your preferred license)

