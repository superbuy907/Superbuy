# Superbuy - Vállalati Hálózati Infrastruktúra

Ez a tároló tartalmazza az **Superbuy** projekt teljes technikai dokumentációját, konfigurációs fájljait és hálózati terveit.

## 📌 Gyorslinkek a Dokumentációhoz
* 📊 [Interaktív IP Címzési Táblázat (Google Sheets)](https://docs.google.com/spreadsheets/d/1j0ZOi8yoD4XCJ0Lp27ss7KFE7-TcpVIwsYtHFDRWBNo/edit?usp=sharing)
* 📜 [Részletes Megvalósulási Dokumentáció (PDF/MD)](./DOKUMENTACIO.md)

---

## ⚙️ Eszköz Konfigurációk (.txt)
*Kattints az eszköz nevére a konfigurációs fájl megnyitásához:*

| Eszköz Típusa | Eszköz Neve | Konfigurációs Fájl |
| :--- | :--- | :--- |
| **Fő Router** | Kp | [📄 Kp_config.txt](./main/Kp_config.txt) |
| **Tartalék Router** | Kp_Backup | [🛡️ Kp_Backup_config.txt](./main/Kp_Backup_config.txt) |
| **Tűzfal** | ASA | [🔥 ASA_config.txt](./main/ASA_config.txt) |
| **Telephely** | Raktár | [📦 Raktar_config.txt](./main/Raktar_config.txt) |
| **Telephely** | Logisztika | [🚛 Logisztika_config.txt](./main/Logisztika_config.txt) |
| **Szolgáltató** | ISP | [🌐 ISP_config.txt](./main/ISP_config.txt) |

---

## 🛠️ Alkalmazott Technológiák
- **HA (High Availability):** HSRP (Hot Standby Router Protocol)
- **Routing:** OSPFv2 (Open Shortest Path First)
- **VPN:** GRE (Generic Routing Encapsulation) Site-to-Site Tunnelek
- **Biztonság:** Cisco ASA tűzfal, ACL szűrés
- **Automatizáció:** Python szkriptek a menedzsmenthez

![**Logikai Topológia**](https://github.com/superbuy907/Superbuy/blob/main/K%C3%A9perny%C5%91k%C3%A9p%202026-04-20%2011-11-34.png?raw=true)

---
*Készült a hálózati szakmai vizsgához - 2026*




