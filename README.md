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
| **Fő Router** | Kp | [📄 Kp_config.txt](./Kp_config.txt) |
| **Tartalék Router** | Kp_Backup | [🛡️ Kp_Backup_config.txt](./Kp_Backup_config.txt) |
| **Tűzfal** | ASA | [🔥 ASA_config.txt](./ASA_config.txt) |
| **Telephely** | Raktár | [📦 Raktar_config.txt](./Raktar_config.txt) |
| **Telephely** | Logisztika | [🚛 Logisztika_config.txt](./Logisztika_config.txt) |
| **Szolgáltató** | ISP | [🌐 ISP_config.txt](./ISP_config.txt) |

---

## 🛠️ Alkalmazott Technológiák
- **HA (High Availability):**
- **Routing:** OSPFv2
- **VPN:** GRE  Site-to-Site Tunnelek
- **Biztonság:** Cisco ASA tűzfal, ACL szűrés
- **Automatizáció:** [Ansible](./Ansible_Dokumentacio) szkriptek a menedzsmenthez
---
*Készült a hálózati szakmai vizsgához - 2026*




