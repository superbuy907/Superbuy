# 🍏 Superbuy - Vállalati Hálózati Infrastruktúra

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-v6.2-blue?style=for-the-badge)
![Category](https://img.shields.io/badge/Project-Network--Infrastucture-orange?style=for-the-badge)

Ez a tároló a **Superbuy** projekt teljes technikai implementációját tartalmazza. A hálózatot magas rendelkezésre állásra (HA), biztonságra és automatizált menedzsmentre terveztük.

---

### 📂 Gyors Navigáció
> A legfontosabb dokumentumok és a laborállomány azonnali elérése.

| Típus | Leírás | Elérés |
| :--- | :--- | :--- |
| 🏗️ | **Packet Tracer Lab** | [📥 Letöltés (.pkt)](https://github.com/superbuy907/Superbuy/raw/main/project/maov6.pkt) |
| 📊 | **IP Címzési Terv** | [🔗 Megnyitás Google Sheets-ben](https://docs.google.com/spreadsheets/d/1j0ZOi8yoD4XCJ0Lp27ss7KFE7-TcpVIwsYtHFDRWBNo/edit?usp=sharing) |
| 📜 | **Műszaki Dokumentáció** | [📄 Letöltés (.md)](https://github.com/superbuy907/Superbuy/raw/main/docs/DOKUMENTACIO.md) |
| 🤖 | **Ansible Útmutató** | [📥 Letöltés (.docx)](https://github.com/superbuy907/Superbuy/raw/main/docs/Ansible_Dokumentacio.docx) |

---

### ⚙️ Eszköz Konfigurációk
*A hálózati eszközök mentett állományai a `/configs` mappában találhatóak.*

<details>
<summary><b>▶ Kattints ide a konfigurációs fájlok listájához</b></summary>

* 🚀 **Fő Router (Kp):** [Kp_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/Kp_config.txt)
* 🛡️ **Tartalék Router (Kp_Backup):** [Kp_Backup_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/Kp_Backup_config.txt)
* 🔥 **ASA Tűzfal:** [ASA_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/ASA_config.txt)
* 📦 **Raktár:** [Raktar_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/Raktar_config.txt)
* 🚛 **Logisztika:** [Logisztika_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/Logisztika_config.txt)
* 🌐 **ISP:** [ISP_config.txt](https://github.com/superbuy907/Superbuy/raw/main/configs/ISP_config.txt)

</details>

---

### 🛠️ Alkalmazott Technológiák
- **HA (High Availability):** `HSRP` redundancia az alapértelmezett átjáróhoz.
- **Routing:** Dinamikus `OSPFv2` útvonalválasztás.
- **VPN:** `GRE` Site-to-Site tunnelek a telephelyek között.
- **Biztonság:** Cisco `ASA` tűzfal és `ACL` szűrés.
- **Automatizáció:** `Ansible` alapú menedzsment dokumentáció.

---
<p align="center">
  <i>Készült a hálózati szakmai vizsgához - 2026</i><br>
  <b>Superbuy Project Team</b>
</p>
