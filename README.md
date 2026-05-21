<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=1000&color=9B59B6&center=true&vCenter=true&width=600&lines=VPN+Script;DevCulture+Full+VPN+Installer;SSH+%7C+Xray+%7C+OpenVPN+%7C+SlowDNS" alt="Typing SVG" />

<br/>

[![Part of DevCulture](https://img.shields.io/badge/ecosystem-DevCulture-9b59b6?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/tuyulbodo99)
[![Shell](https://img.shields.io/badge/shell-bash-1a1a2e?style=for-the-badge&logo=gnubash&logoColor=white)](https://github.com/tuyulbodo99/vpnscript)
[![Xray](https://img.shields.io/badge/Xray-latest-6c3483?style=for-the-badge)](https://github.com/XTLS/Xray-core)
[![Sync](https://img.shields.io/badge/sync-auto-5b2c6f?style=for-the-badge&logo=sync&logoColor=white)](https://github.com/tuyulbodo99/devculture-vps/blob/main/sync.sh)

</div>

---

## 🟣 Overview

**VPNScript** adalah installer VPN lengkap dari ekosistem DevCulture. Mendukung SSH, Xray terbaru, OpenVPN, SlowDNS, haproxy, noobzvpn, dan sistem manajemen pengguna premium.

> 🔗 **Terhubung penuh dengan ekosistem DevCulture** — disinkronkan otomatis via `sync.sh`

---

## 🌐 Ekosistem DevCulture

| Repo | Fungsi |
|------|--------|
| [`devculture-vps`](https://github.com/tuyulbodo99/devculture-vps) | 🏠 Core installer & panel |
| [`hokagescript`](https://github.com/tuyulbodo99/hokagescript) | ⚙️ Menu & service scripts |
| **[`vpnscript`](https://github.com/tuyulbodo99/vpnscript)** | 🔒 **VPN installer lengkap** ← Anda di sini |
| [`vps-script`](https://github.com/tuyulbodo99/vps-script) | 🔧 SSH tunnel |
| [`ijin`](https://github.com/tuyulbodo99/ijin) | 🛡️ License system |

---

## ⚡ Instalasi

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)
```

### Update via Ekosistem

```bash
# Update semua komponen DevCulture sekaligus:
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/sync.sh)
```

---

## 📦 Protokol & Port

| Protokol | Port |
|----------|------|
| OpenSSH | 22, 53, 2222, 2269 |
| SSH WebSocket | 80 |
| SSH SSL WebSocket | 443 |
| Stunnel5 | 222, 777 |
| Dropbear | 109, 143 |
| BadVPN / UDPGW | 7100–7300 |
| Nginx | 81 |
| Xray VMess TLS | 443 |
| Xray VMess Non-TLS | 80 |
| Xray VLess TLS | 443 |
| Xray Trojan WS/gRPC | 443 |
| SlowDNS | 53 |

---

## 🗂️ Struktur Repo

```
vpnscript/
├── premi.sh            # Installer utama (full VPN)
├── update.sh           # Update semua service
├── ssh/                # SSH & WebSocket configs
├── config/             # Xray & Nginx configs
├── bot/                # Telegram bot
├── menu/               # Menu interaktif
├── udp-custom/         # UDP custom tunnel
└── files/              # File pendukung
```

---

## 🔧 Fitur

- ✅ Xray Core versi terbaru (auto-detect)
- ✅ SSL via acme.sh (Let's Encrypt / ZeroSSL)
- ✅ HAProxy stream multiplexer
- ✅ NoobzVPN support
- ✅ Auto-reboot + cron scheduler
- ✅ Fail2Ban protection
- ✅ Notifikasi Telegram otomatis
- ✅ Manajemen user SSH & Xray
- ✅ Terhubung ke sistem ijin terpusat

---

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-@devculturebot-9b59b6?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/devculturebot)
[![GitHub](https://img.shields.io/badge/GitHub-tuyulbodo99-1a1a2e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tuyulbodo99)

<sub>© 2024 DevCulture VPS Store · Part of <a href="https://github.com/tuyulbodo99">tuyulbodo99</a> Ecosystem</sub>

</div>
