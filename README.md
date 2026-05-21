<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=1000&color=9B59B6&center=true&vCenter=true&width=600&lines=VPN+Script;DevCulture+Full+VPN+Installer;SSH+%7C+Xray+%7C+OpenVPN+%7C+SlowDNS" alt="Typing SVG" />

<br/>

[![Part of DevCulture](https://img.shields.io/badge/ecosystem-DevCulture-9b59b6?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/tuyulbodo99)
[![Shell](https://img.shields.io/badge/shell-bash-1a1a2e?style=for-the-badge&logo=gnubash&logoColor=white)](https://github.com/tuyulbodo99/vpnscript)
[![Xray](https://img.shields.io/badge/Xray-latest-6c3483?style=for-the-badge)](https://github.com/XTLS/Xray-core)
[![OS](https://img.shields.io/badge/OS-Ubuntu%20%7C%20Debian-2c2c54?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/tuyulbodo99/vpnscript)

</div>

---

## ⚡ Install — Satu Perintah, Langsung Jalan

> **Copy → Paste → Enter. Selesai.**

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)
```

### 🔄 Update Script

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/update.sh)
```

### 🔄 Sync Semua Komponen DevCulture

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/sync.sh)
```

---

## 🟣 Overview

**VPNScript** adalah installer VPN lengkap dari ekosistem DevCulture. Mendukung SSH, Xray terbaru, OpenVPN, SlowDNS, haproxy, noobzvpn, dan sistem manajemen pengguna premium.

> 🔗 **Terhubung penuh dengan ekosistem DevCulture** — disinkronkan otomatis via `sync.sh`

---

## 🌐 Ekosistem DevCulture

| Repo | Fungsi | One-Click Install |
|------|--------|-------------------|
| [`devculture-vps`](https://github.com/tuyulbodo99/devculture-vps) | 🏠 Core installer | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/install.sh)` |
| [`hokagescript`](https://github.com/tuyulbodo99/hokagescript) | ⚙️ Menu scripts | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/hokagescript/main/setup.sh)` |
| **[`vpnscript`](https://github.com/tuyulbodo99/vpnscript)** | 🔒 **VPN installer** ← ini | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)` |
| [`vps-script`](https://github.com/tuyulbodo99/vps-script) | 🔧 SSH tunnel | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vps-script/main/install)` |
| [`ijin`](https://github.com/tuyulbodo99/ijin) | 🛡️ License DB | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/ijin/main/check-ijin.sh)` |

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

## ✅ Fitur

- Xray Core versi terbaru (auto-detect)
- SSL via acme.sh (Let's Encrypt / ZeroSSL)
- HAProxy stream multiplexer
- NoobzVPN support
- Auto-reboot + cron scheduler
- Fail2Ban protection
- Notifikasi Telegram otomatis
- Manajemen user SSH & Xray
- Terhubung ke sistem ijin terpusat

---

## 🔧 Requirements

| Item | Detail |
|------|--------|
| OS | Debian 10/11/12 · Ubuntu 20.04/22.04 |
| Akses | **Root** |
| Domain | Pointing ke IP VPS |

---

<div align="center">

[![Telegram](https://img.shields.io/badge/Order%20%26%20Support-@devculturebot-9b59b6?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/devculturebot)
[![GitHub](https://img.shields.io/badge/GitHub-tuyulbodo99-1a1a2e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tuyulbodo99)

<sub>© 2024 DevCulture VPS Store · Part of <a href="https://github.com/tuyulbodo99">tuyulbodo99</a> Ecosystem</sub>

</div>
