# 🌟 NPCAtool (Nutanix Prism Central Audit Tool)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://www.microsoft.com/windows/)

 Audit Tool for Nutanix Prism Central with Modern GUI and Enhanced Security.

## ✨ Features

- 🔍 **Multi-PC Audit**: Simultaneous collection from multiple Prism Central instances.
- 📊 **Detailed Excel Reports**: Automatic export with comprehensive analysis (VMs, Clusters, Security, Capacity, RBAC, Data Protection).
- 🎨 **Modern Interface**: Professional, corporate-grade UI.
- 🛡️ **Connection Verification**: Automatic pre-check of credentials and connectivity before audit.
- ⚡ **Optimized Performance**: Parallel collection (multi-threading) for rapid data gathering.
- 📈 **Capacity Analysis**: Advanced Storage Effective calculations with Prism Capacity API.

## 🚀 Installation & Usage

### 1. Download
Download the latest executable from the **[Releases](../../releases)** page.
- `NPCAtool.exe`

### 2. Run
Double-click the executable to launch the application. No installation requirement is needed.

### 3. Audit
1. Enter your Prism Central IP, Username, and Password.
2. (Optional) Click `+` to add more Prism Central instances for a parallel audit.
3. Click **Start Audit**.
4. The tool will verify credentials and start collecting data.
5. Once finished, the Excel report will open automatically.

## 📊 Report Content

The generated Excel report includes the following sheets:

1. **SUMMARY**: Complete Prism Central overview (System info, Global inventory, Consistency analysis).
2. **VMS**: Detailed list of virtual machines (Resources, Power status, Associations).
3. **CLUSTERS**: Managed clusters inventory (Capacity, Software versions, Network).
4. **HOSTS**: Physical servers list (Hardware model, Hypervisor status).
5. **IMAGES**: VM images catalog.
6. **CATEGORIES**: Taxonomy and categorization.
7. **SUBNETS**: Network configuration (VLANs, IP pools).
8. **PROTECTION RULES**: Protection policies (Schedules, Retention).
9. **RECOVERY PLANS**: Disaster recovery plans configuration.
10. **SECURITY COMPLIANCE**: Security compliance guide (Aide, Banner, SSH, SNMP).
11. **CLUSTER PERFORMANCE**: Performance metrics (IOPS, Bandwidth, Latency).
12. **CLUSTER CAPACITY**: Detailed capacity analysis (CPU, Memory, Storage Effective).

## 🛡️ Anti-Virus Note

**False Positives:**
Some antivirus software might flag the executable because it is not digitally signed. This is a common issue with independent software.
- The application is safe and runs locally on your machine.
- It only communicates with the Prism Central IPs you provide.
- You can whitelist the application if necessary.

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## 👤 Author

**Yassine GAOUTI**
- 📧 yassine.gaouti@gmail.com
- 🌐 www.npcatool.com

---
**⭐ If this tool helps you, please give it a star!**
