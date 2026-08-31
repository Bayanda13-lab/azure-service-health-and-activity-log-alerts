# Azure Service Health & Activity Log Alerts

![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-Cloud%20Computing-0078D4?logo=microsoftazure&logoColor=white)
![Azure Monitor](https://img.shields.io/badge/Azure%20Monitor-Alerts-0078D4)
![Service Health](https://img.shields.io/badge/Azure-Service%20Health-green)

## 📌 Project Overview

This project demonstrates how to configure **Azure Service Health and Activity Log alerts** using the Microsoft Azure Portal.

The objective was to create a **Service Health quick alert rule** that monitors Azure service issues and planned maintenance events and sends notifications through an Azure Action Group.

The alert rule created during the lab was:

```text
ar-gp-service-health
```

---

## 🎯 Objectives

The main objectives of this project were to:

- Configure an Azure Service Health alert.
- Monitor Azure service issues.
- Monitor planned maintenance events.
- Select Azure services and regions to monitor.
- Configure an Azure Action Group.
- Enable email notifications.
- Create and enable the alert rule.
- Validate the alert configuration.

---

## 🛠️ Technologies & Services Used

- Microsoft Azure
- Azure Portal
- Azure Service Health
- Azure Monitor
- Activity Log Alerts
- Azure Action Groups
- Email Notifications

---

## ⚙️ Alert Configuration

| Configuration | Value |
|---|---|
| Alert Rule Name | `ar-gp-service-health` |
| Resource Group | `rg-gp-monitoring-alerts` |
| Services | 257 selected |
| Regions | 60 selected |
| Event Type | Service Issues |
| Additional Event Type | Planned Maintenance |
| Action Group | `ag-gp-ops-email` |
| Notification Method | Email |
| Alert Status | Enabled |

---

# 📸 Screenshots

## 1. Create Service Health Quick Alert Rule

The following screenshot shows the configuration of the Azure Service Health alert rule.

![Create Service Health Alert Rule](<img width="1600" height="900" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/69112a44-179a-4ed4-89cd-e9d7d68ca0e6" />
)

### Configuration shown in the screenshot

- **Services:** 257 selected
- **Regions:** 60 selected
- **Event Type:** Service issues
- **Resource Group:** `rg-gp-monitoring-alerts`
- **Alert Rule Name:** `ar-gp-service-health`
- **Email Notification:** Enabled
- **Action Group:** `ag-gp-ops-email`
- **Enable alert rule upon creation:** Enabled

---

# 🚀 Implementation

## Step 1: Open Azure Service Health

1. Sign in to the Microsoft Azure Portal.
2. Search for **Service Health**.
3. Open **Service Health**.
4. Navigate to the alert configuration section.

---

## Step 2: Configure Services and Regions

Select the Azure services and regions that should be monitored.

The lab configuration used:

```text
Services: 257 selected
Regions: 60 selected
```

This allows the alert rule to monitor Azure platform events across the selected scope.

---

## Step 3: Configure Event Types

The alert was configured to monitor:

```text
Service Issues
Planned Maintenance
```

### Service Issues

Service issues provide information about Azure incidents that may affect cloud services.

### Planned Maintenance

Planned maintenance events notify administrators about scheduled Azure maintenance activities.

---

## Step 4: Configure the Action Group

Under the **Actions** section, select the required Action Group:

```text
ag-gp-ops-email
```

The Action Group is responsible for sending notifications when the alert condition is triggered.

---

## Step 5: Configure Alert Details

The alert details were configured as follows:

```text
Resource Group:
rg-gp-monitoring-alerts

Alert Rule Name:
ar-gp-service-health
```

The option:

```text
Enable alert rule upon creation
```

was enabled.

---

## Step 6: Create the Alert

Select **Create** to create the Service Health alert.

After creation, verify that the following alert rule exists:

```text
ar-gp-service-health
```

---

# 🔔 Alert Workflow

The alert configuration can be represented as:

```text
┌───────────────────────────────┐
│      Azure Service Health     │
│                               │
│  • Service Issues             │
│  • Planned Maintenance        │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│         Alert Rule            │
│                               │
│   ar-gp-service-health        │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│        Action Group           │
│                               │
│     ag-gp-ops-email           │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       Email Notification       │
│                               │
│       Operations Team          │
└───────────────────────────────┘
```

---

# 🧪 Validation

The Azure lab was successfully completed.

### Validation Checklist

- [x] Service Health alert configured
- [x] Service issues selected
- [x] Planned maintenance selected
- [x] Azure services selected
- [x] Azure regions selected
- [x] Action Group configured
- [x] Email notification configured
- [x] Resource group selected
- [x] Alert rule name configured
- [x] Alert enabled upon creation
- [x] Alert rule successfully created

---

# 🔐 Monitoring & Operational Benefits

Azure Service Health alerts can help IT and cloud operations teams monitor important Azure platform events.

Benefits include:

- Improved visibility into Azure service incidents.
- Notifications about planned maintenance.
- Faster incident awareness.
- Improved cloud operations.
- Better incident response.
- Reduced time to identify Azure platform issues.
- Centralized notification through Action Groups.

---

# 📚 Skills Demonstrated

This project demonstrates practical experience with:

- Azure Service Health
- Azure Monitor
- Activity Log Alerts
- Azure Action Groups
- Email Alert Notifications
- Azure Portal
- Cloud Monitoring
- Cloud Operations
- Incident Management
- Azure Administration
- Cloud Governance

---

# 💡 Key Learning

This project provided practical experience configuring Azure monitoring and alerting capabilities.

I learned how to configure a **Service Health quick alert rule**, select services and regions, configure event types, connect an Action Group, enable email notifications, and validate the completed alert.

This type of monitoring is important for maintaining visibility and improving response times in cloud environments.

---

# 🔮 Future Improvements

Possible improvements for a production environment include:

- Add SMS notifications.
- Add mobile push notifications.
- Create alerts for specific critical services.
- Create separate Action Groups for different teams.
- Integrate alerts with IT Service Management platforms.
- Use Azure Logic Apps for automated responses.
- Create Azure monitoring dashboards.
- Add additional Activity Log alerts.
- Implement escalation procedures for critical incidents.


```

---

# 👤 Author

## Bayanda Vundla

**Focus Areas:**

- Microsoft Azure
- Cloud Computing
- IT Infrastructure
- Cloud Monitoring
- Azure Administration
- Cloud Governance

---

## ⭐ Project Status

**Completed successfully**

Azure Service Health and Activity Log alert configuration was successfully completed and validated.
