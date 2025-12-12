# 🌟 NPCAtool (Nutanix Prism Central Audit Tool)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://www.microsoft.com/windows/)

**NPCAtool** is a **security-focused audit tool for Nutanix Prism Central**, designed for administrators, architects, and consultants who need **clear visibility, fast analysis, and actionable reports**.

---

## 🚧 Project Status

NPCAtool is in **active development**.

- The tool is actively used for Prism Central audits
- Features and reports evolve continuously
- Feedback from real environments is highly appreciated

👉 I am actively looking for **beta testers** (Nutanix Admins / Architects / Consultants).

---

## ✨ Features

- 🔍 **Multi-Prism Central Audit**  
  Collect data simultaneously from multiple Prism Central instances.

- 📊 **Comprehensive Excel Reports**  
  Automatic export covering:
  - VMs
  - Clusters
  - Hosts
  - Capacity
  - Security
  - RBAC
  - Data Protection
  - Performance

- 🎨 **Modern & Professional UI**  
  Clean, corporate-grade interface designed for daily operations.

- 🛡️ **Connection & Credential Validation**  
  Pre-check of connectivity and credentials before audit execution.

- ⚡ **High Performance Collection**  
  Parallel API calls using multi-threading.

- 📈 **Advanced Capacity Analysis**  
  Storage Effective calculations using Prism Capacity APIs.

---

## 🚀 Installation & Usage

### 1️⃣ Download
Download the latest executable from the **[Releases](../../releases)** page.

- `NPCAtool.exe`
- Always use the **latest release**

---

### 2️⃣ Run
Double-click the executable to start the application.  
✅ No installation required.

---

### 3️⃣ Run an Audit
1. Enter **Prism Central IP**, **Username**, and **Password**
2. (Optional) Click `+` to add additional Prism Central instances
3. Click **Start Audit**
4. Credentials and connectivity are validated automatically
5. The Excel report opens automatically when the audit completes

---

## 📊 Report Content

The generated Excel report includes the following worksheets:

1. **SUMMARY** – Global Prism Central overview  
2. **VMS** – Virtual machines inventory  
3. **CLUSTERS** – Managed clusters details  
4. **HOSTS** – Physical hosts inventory  
5. **IMAGES** – VM images catalog  
6. **CATEGORIES** – Taxonomy and categorization  
7. **SUBNETS** – Network configuration  
8. **PROTECTION RULES** – Protection policies  
9. **RECOVERY PLANS** – Disaster recovery configuration  
10. **SECURITY COMPLIANCE** – Security baseline checks  
11. **CLUSTER PERFORMANCE** – Performance metrics  
12. **CLUSTER CAPACITY** – Capacity analysis (CPU, Memory, Storage Effective)

---

## 🔐 Security & Privacy

NPCAtool is built with **security-first principles**:

- ✅ Runs **100% locally** on the user's machine
- ✅ No data is sent to any external server
- ✅ No credentials are stored (used only in memory)
- ✅ Direct communication with Nutanix Prism Central APIs only

**No cloud backend.  
**No telemetry.  
**No hidden network communication.**

---

## 📦 Source Code Availability

The source code is not publicly available at this stage.

Reason:
- The project is proprietary
- Internal architecture is still evolving

📌 This does **not** impact security or transparency:
- Local execution only
- No external communication

The source code may be opened in the future depending on the project direction.

---

## 🛡️ Anti-Virus Notice

Some antivirus products may report **false positives** because the executable is not digitally signed.

- This is common for independent software
- The application runs locally and is safe
- Only the Prism Central endpoints provided by the user are contacted
- Whitelisting the executable may be required

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Yassine Gaouti**

- 📧 Email: yassine.gaouti@gmail.com  
- 🌐 Website: https://www.npcatool.com

---

⭐ If NPCAtool helps you, please consider giving it a star or sharing feedback.
