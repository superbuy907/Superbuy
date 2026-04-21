# 🍏 Superbuy - Vállalati Hálózati Infrastruktúra

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.2-blue?style=for-the-badge)
![Category](https://img.shields.io/badge/Project-Network--Infrastucture-orange?style=for-the-badge)

Ez a tároló a **Superbuy** projekt teljes technikai implementációját tartalmazza. A hálózatot magas rendelkezésre állásra (HA), biztonságra és automatizált menedzsmentre terveztük.

---

### 📂 Gyors Navigáció
> A legfontosabb dokumentumok és a laborállomány elérése.

| Típus | Leírás | Elérés |
| :--- | :--- | :--- |
| 🏗️ | **Packet Tracer Lab** | [Letöltés (.pkt)](./project/Superbuy_final.pkt) |
| 📊 | **IP Címzési Terv** | [Megnyitás Google Sheets-ben](https://docs.google.com/spreadsheets/d/1j0ZOi8yoD4XCJ0Lp27ss7KFE7-TcpVIwsYtHFDRWBNo/edit?usp=sharing) |
| 📜 | **Műszaki Dokumentáció** | [DOKUMENTACIO.md megtekintése](./docs/DOKUMENTACIO.md) |
| 🤖 | **Ansible Útmutató** | [Letöltés (.docx)](./ansible_potencialis.docx) |

---

### ⚙️ Eszköz Konfigurációk
*A hálózati eszközök mentett állományai a `/configs` mappában találhatóak.*

<details>
<summary><b>▶ Kattints ide a konfigurációs fájlok listájához</b></summary>

* 🚀 **Fő Router (Kp):** [`Kp_config.txt`](./configs/Kp_config.txt)
* 🛡️ **Tartalék Router (Kp_Backup):** [`Kp_Backup_config.txt`](./configs/Kp_Backup_config.txt)
* 🔥 **ASA Tűzfal:** [`ASA_config.txt`](./configs/ASA_config.txt)
* 📦 **Raktár:** [`Raktar_config.txt`](./configs/Raktar_config.txt)
* 🚛 **Logisztika:** [`Logisztika_config.txt`](./configs/Logisztika_config.txt)
* 🌐 **ISP:** [`ISP_config.txt`](./configs/ISP_config.txt)

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
