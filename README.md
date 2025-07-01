# Power Automate Flows 🚀

This repository contains a curated collection of Microsoft Power Automate flows created and used in real-world enterprise scenarios. These flows are designed to automate repetitive business processes, integrate with enterprise systems like SharePoint, SAP, and Outlook, and enhance productivity using low-code and AI-driven workflows.

## 🧩 Contents

| Flow Name                  | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `PDF-Viewer_Flow_V2.1`    | Retrieves PDF files from SharePoint based on path input and returns base64  |
| `Create_PDF_For_ESKER`    | Automatically generates and formats PDFs for invoice processing             |
| `Email_Notification_Flow` | Sends alert emails based on trigger conditions in SharePoint or Dataverse   |
| `User_Approval_Flow`      | Implements a multi-stage approval system integrated with Microsoft Teams    |

> 📁 Each folder includes: exported `.zip` flow package, definition JSON, and optional documentation.

---

## 🧠 Technologies & Connectors Used

- Power Automate (Cloud Flows)
- SharePoint Online
- Microsoft Teams
- OneDrive for Business
- Outlook 365
- Azure OpenAI (used in document automation flows)
- SQL Server

---

## 💼 Real-World Use Cases

- 📎 **Finance & Procurement**: Auto-generate and route invoices to ESKER for processing
- 🧾 **Document Automation**: Fetch, preview, and process PDF files dynamically in PowerApps
- 💬 **Approvals**: Notify and route decisions through Teams for compliance workflows
- 📩 **Email Automation**: Trigger alerts based on thresholds, status changes, or file uploads

---

## ⚙️ How to Import a Flow

1. Go to [Power Automate](https://make.powerautomate.com/)
2. Click **Solutions** → **Import**
3. Upload the `.zip` file from the flow folder
4. Configure required connections (SharePoint, Outlook, etc.)
5. Test using PowerApps or scheduled triggers

---
