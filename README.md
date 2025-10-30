# Lead Capture v2

> Automated Lead Capture system using Google Sheets & Gmail in n8n — with admin notifications, client follow-ups, and global error handling.

---

## ⚙️ Features

- 📄 **Google Sheets Trigger** — Detects new leads when a row is added  
- ✉️ **Auto Email to Admin** — Instantly notifies admin of a new lead  
- 🛠 **Edit Fields Node** — Cleans and formats data  
- 📊 **Append Row in Sheet** — Updates records after formatting  
- 👥 **B2B / Individual Client Split** — Routes leads dynamically using IF logic  
- 📬 **Confirmation & Follow-up Emails** — Sent automatically for both lead types  
- 🚨 **Error Handling System** — Global workflow to manage and log failures

---

## 🧩 Workflow Structure


---

## ⚠️ To Enable Error Handling

Import **both** workflows:

1. `lead-capture-v2.json`  
2. `error-handler.json`

Then go to:  
**Workflow Settings → Error Workflow → Select “Error Handler”**

If only `lead-capture-v2.json` is imported,  
error handling will not activate and n8n will show  
**“Linked Error Workflow not found.”**

---

## 📦 Files

| File | Description |
|------|--------------|
| `lead-capture-v2.json` | Main workflow for lead management |
| `error-handler.json` | Global error handler sub-workflow |

---

## 🧠 Notes

- Recommended to use with **Google Sheets & Gmail OAuth credentials**  
- Works perfectly for **B2B or individual client lead pipelines**  
- Fully customizable for **CRM or marketing automations**

---

**Created by:** Hussain Faizi  
**Version:** v2.0  
**Automation Platform:** [n8n.io](https://n8n.io)
