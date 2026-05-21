<div align="center">

<img src="https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/assets/cyberpunk-typing.png" width="100%" alt="DevCulture VPN Script — DevCulture Cyberpunk" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&pause=1000&color=A855F7&center=true&vCenter=true&width=650&lines=DevCulture+VPN+Script;Full+VPN+Installer+OpenVPN+WireGuard+SlowDNS;Ubuntu+22.04+%7C+Multi-Port+%7C+TCP+%2B+UDP)](https://git.io/typing-svg)

<br/>

![Stars](https://img.shields.io/github/stars/tuyulbodo99/vpnscript?style=for-the-badge&color=a855f7&labelColor=0d0d0d)
![Platform](https://img.shields.io/badge/Ubuntu-22.04-a855f7?style=for-the-badge&logo=ubuntu&logoColor=white&labelColor=0d0d0d)
![Shell](https://img.shields.io/badge/Bash-5.x-7c3aed?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=0d0d0d)
![TCP+UDP](https://img.shields.io/badge/Protocol-TCP%20%2B%20UDP-a855f7?style=for-the-badge&labelColor=0d0d0d)

<br/>

<img src="https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/assets/online.svg" alt="NGINX ONLINE" />

</div>

---

<div align="center">

### 🚀 ONE-CLICK INSTALL

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)
```

</div>

---

## 📡 Port & Protokol

| # | Protokol | Port | Tipe |
|---|----------|------|------|
| 1 | OpenSSH | 22 | TCP |
| 2 | Dropbear | 109, 143 | TCP |
| 3 | SSH WebSocket | 80 | TCP |
| 4 | SSH SSL WebSocket | 443 | TCP |
| 5 | Stunnel (SSL Tunnel) | 777 | TCP |
| 6 | UDPGW / BadVPN | 7300 | **UDP** |
| 7 | SlowDNS | 5300 | **UDP** |
| 8 | OpenVPN | 1194 TCP / 2200 UDP | TCP+UDP |
| 9 | WireGuard | 51820 | **UDP** |

---

## 🔗 Format Connection String

```
user@pass:host:port

Contoh per protokol:
  vpnuser@pass:host:22      → OpenSSH
  vpnuser@pass:host:1194    → OpenVPN TCP
  vpnuser@pass:host:2200    → OpenVPN UDP
  vpnuser@pass:host:51820   → WireGuard
  vpnuser@pass:host:5300    → SlowDNS
  vpnuser@pass:host:7300    → UDPGW (UDP)

SlowDNS format:
  vpnuser@pass:host:5300:dns:ns1.devculture.id
```

---

## 📱 Config HTTP Injector / NPay / NetSpark

```
Proxy Type   : SSH
SSH Host     : [IP VPS kamu]
SSH Port     : 22
SSH User     : [username]
SSH Pass     : [password]
Remote Proxy : 127.0.0.1:8080
Listen Port  : 8989

Payload:
GET wss://bug.com/ HTTP/1.1[crlf]
Host: bug.com[crlf]
Upgrade: websocket[crlf][crlf]
```

---

## 🌐 Config OpenVPN

```
Protocol     : TCP / UDP
Server       : [IP VPS kamu]
Port TCP     : 1194
Port UDP     : 2200
Auth         : Username + Password
```

---

## ⚡ Config WireGuard

```
[Interface]
PrivateKey   = [diisi otomatis saat install]
Address      = 10.8.0.2/24
DNS          = 1.1.1.1

[Peer]
PublicKey    = [diisi otomatis saat install]
Endpoint     = [IP VPS]:51820
AllowedIPs   = 0.0.0.0/0
```

---

## 📦 Fitur Utama

- Installer OpenVPN (TCP + UDP)
- Installer WireGuard
- Installer SlowDNS + Nameserver NS
- Installer UDPGW / BadVPN
- Update script satu perintah
- Health check semua service

---

## 🛠️ Perintah Utama

```bash
# Install (satu perintah)
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)

# Cek kesehatan semua service setelah install
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/healthcheck.sh)

# Update script
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/update.sh)
```

---

## 🌐 Ekosistem DevCulture

| Repo | Fungsi | One-Click Install |
|------|--------|-------------------|
| 🟣 [devculture-vps](https://github.com/tuyulbodo99/devculture-vps) | Core Panel SSH + WebSocket | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/install.sh)` |
| 🟣 [hokagescript](https://github.com/tuyulbodo99/hokagescript) | Menu Layanan & Services | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/hokagescript/main/setup.sh)` |
| 🟣 [vpnscript](https://github.com/tuyulbodo99/vpnscript) | Full VPN (OpenVPN+WG+SlowDNS) | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)` |
| 🟣 [vps-script](https://github.com/tuyulbodo99/vps-script) | SSH Tunnel Setup | `bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vps-script/main/install)` |

---

## 🖥️ Persyaratan

| OS | RAM | Storage | Akses |
|----|-----|---------|-------|
| Ubuntu 20.04 / 22.04 LTS | Min 512 MB | Min 5 GB | Root |

---

<div align="center">

**DevCulture VPN Script** · [github.com/tuyulbodo99](https://github.com/tuyulbodo99) · [@devculturebot](https://t.me/devculturebot)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=a855f7&height=80&section=footer)

</div>
