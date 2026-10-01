🔐 Wazuh Security Monitoring Lab

📌 Deskripsi

Project ini merupakan implementasi Wazuh sebagai platform Security Information and Event Management (SIEM) untuk melakukan monitoring keamanan pada lingkungan lab.

Project ini dibuat untuk mempelajari proses deployment Wazuh, pemasangan agent, monitoring endpoint Windows, serta pengujian File Integrity Monitoring (FIM).

---

🎯 Tujuan

- Memahami instalasi dan konfigurasi Wazuh.
- Menghubungkan endpoint Windows dengan Wazuh Manager.
- Melakukan monitoring aktivitas endpoint.
- Menguji fitur File Integrity Monitoring (FIM).
- Menganalisis security alert yang dihasilkan Wazuh.
- Mendokumentasikan proses investigasi keamanan.

---

🖥️ Lab Environment

| Komponen | Detail |
|---|---|
| Wazuh Manager | Ubuntu 24.04.5 LTS |
| Wazuh Version | 4.14.8 |
| Wazuh Dashboard | OpenSearch Dashboard |
| Endpoint | Windows 10 IoT Enterprise LTSC 2021 |
| Agent | Windows-SOC-Agent |
| Virtualization | VirtualBox |
| Network | NAT |

---

1. ⚙️ Wazuh Installation

Wazuh Manager diinstal pada Ubuntu menggunakan metode Quickstart.

Command yang digunakan:

```bash
curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh
sudo bash ./wazuh-install.sh -a
