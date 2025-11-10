# 🚀 IT Infrastructure Upgrade — Modernizing for Performance, Reliability, and Cost Efficiency

![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![VMware](https://img.shields.io/badge/VMware-Hybrid-green)
![HPE](https://img.shields.io/badge/HPE-3PAR-success)
![PowerShell](https://img.shields.io/badge/PowerShell-Automation-lightblue)

> **Objective:** Modernize and standardize IT infrastructure across multiple business units — achieving 99.9% uptime and 20% cost savings.

---

## 📑 Table of Contents
1. [Overview](#overview)
2. [Problem](#problem)
3. [Solution Approach](#solution-approach)
4. [Implementation Highlights](#implementation-highlights)
5. [Results](#results)
6. [Tech Stack](#tech-stack)
7. [Lessons Learned](#lessons-learned)
8. [Next Steps](#next-steps)
9. [Author](#author)

---

## 🧭 Overview

A full-scale modernization of the company’s IT environment covering compute, storage, and automation.  
Legacy systems were migrated to a standardized Windows Server 2022 hybrid platform, with PowerShell and SCCM automation driving operational consistency and cost reduction.

---

## ❌ Problem

Before the upgrade, infrastructure was fragmented and inconsistent across departments:

- Outdated **Windows Server 2008–2016** installations
- Multiple unmanaged **VMware and Hyper-V** environments
- Fragmented storage (legacy NAS, low-capacity SANs)
- Manual patching and high human error rates
- Unplanned downtime and escalating maintenance costs

These inefficiencies led to reduced productivity, unpredictable outages, and difficulty meeting compliance and performance requirements.

---

## ✅ Solution Approach

**Goal:** Modernize without disrupting core business operations.

1. **Standardize** — Consolidate workloads under Windows Server 2022.  
2. **Automate** — Use PowerShell and SCCM for patching and reporting.  
3. **Optimize** — Upgrade compute/storage to scalable platforms (HPE 3PAR, Synology, EMC).  
4. **Monitor & Govern** — Improve visibility and automate compliance reporting.

---

## 🧩 Implementation Highlights

### 🖥️ 1. Server Migration
- Migrated all business units to **Windows Server 2022**
- Deployed a **VMware + Hyper-V hybrid** environment for flexibility
- Unified Active Directory and Group Policy for secure, centralized management

**Outcome:** Improved server response times by 35% and reduced physical footprint by decommissioning legacy hosts.

---

### 💾 2. Compute & Storage Modernization
- Rolled out **HPE ProLiant Gen10** servers and **HPE 3PAR SAN** as core storage
- Integrated **Synology NAS** and **Dell EMC Unity** for tiered backup and archival
- Enabled deduplication, replication, and snapshot recovery

**Outcome:** Reduced storage latency by 40%, improved backup success to 99.9%.

---

### ⚙️ 3. Automation & Patch Management
- Implemented **Microsoft SCCM** for patch scheduling and compliance
- Created PowerShell scripts for routine admin tasks (user creation, updates, logs)
- Defined maintenance windows and automatic post-patch verification

**Outcome:** 60% reduction in manual workload, near-zero patch-related downtime.

---

### 📊 4. Performance & Uptime Monitoring
- Centralized monitoring with **vCenter** and **Windows Admin Center**
- Built PowerShell health reports summarizing uptime and resource utilization
- Introduced weekly executive summaries for visibility across departments

**Outcome:** Sustained **99.9% uptime** across all critical workloads.

---

## 🧮 Results

| Metric | Before | After |
|--------|---------|-------|
| Server OS Mix | 2008–2016 | Standardized on 2022 |
| Uptime | ~97.5% | **99.9%** |
| Backup Reliability | 85% | **99.9%** |
| Maintenance Effort | Manual | **Automated via SCCM & PowerShell** |
| Annual IT Costs | Baseline | **20% Reduction** |

---

## 🧰 Tech Stack

`Windows Server 2022` • `VMware vCenter` • `Hyper-V` • `HPE 3PAR` • `Synology NAS` • `EMC Unity`  
`SCCM` • `PowerShell` • `Windows Admin Center`

---

## 💡 Lessons Learned

- **Standardization saves hours.** Unified configurations mean fewer escalations and faster recovery.  
- **Automation compounds value.** Even small scripts save days when multiplied across hundreds of systems.  
- **Hybrid isn’t compromise — it’s strategy.** Combining VMware and Hyper-V provided flexibility and redundancy.  
- **Communicate in metrics.** Translating uptime and cost savings into business terms built executive confidence.

---

## 🔭 Next Steps

- Introduce **Azure Arc** for hybrid cloud governance  
- Expand **Intune** endpoint compliance  
- Deploy **Power BI** for live infrastructure and uptime reporting

---

## 👤 Author

**Tendai Choruwa**  
Senior Infrastructure & Cloud Architect  
🔗 [linkedin.com/in/tendaichoruwa](https://www.linkedin.com/in/tendaichoruwa)  
💻 [github.com/tendaichoruwa](https://github.com/tendaichoruwa)

---

## 🏁 Repository Details

This project is maintained in  
👉 [**tendaichoruwa/IT-Infrastructure-Upgrade**](https://github.com/tendaichoruwa/IT-Infrastructure-Upgrade)


