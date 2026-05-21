<div align="center">

<img src="https://raw.githubusercontent.com/tuyulbodo99/devculture-vps/main/assets/cyberpunk-typing.png" width="100%" alt="DevCulture VPN - Cyberpunk" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=DevCulture+VPN+Script;Full+VPN+Installer;OpenVPN+%2B+WireGuard+%2B+SlowDNS;Ubuntu+22.04+Ready)](https://git.io/typing-svg)

<br/>

![GitHub Stars](https://img.shields.io/github/stars/tuyulbodo99/vpnscript?style=for-the-badge&color=a855f7&labelColor=0d0d0d)
![Platform](https://img.shields.io/badge/Platform-Ubuntu%2022.04-a855f7?style=for-the-badge&logo=ubuntu&logoColor=white&labelColor=0d0d0d)
![Shell](https://img.shields.io/badge/Shell-Bash%205-7c3aed?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=0d0d0d)

</div>

---

<div align="center">

### 🚀 ONE-CLICK INSTALL

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)
```

</div>

---

## 📦 Protokol VPN yang Didukung

<table>
<tr>
<td width="33%">

**🔵 OpenVPN**
- TCP & UDP
- SSL/TLS encrypted
- Config file (.ovpn)
- Multi-platform

</td>
<td width="33%">

**🟢 WireGuard**
- Ultra-fast & modern
- Low latency
- Config QR code
- Mobile friendly

</td>
<td width="33%">

**🟣 SlowDNS**
- Bypass firewall ketat
- DNS-based tunnel
- Inject payload support
- Free internet trick

</td>
</tr>
<tr>
<td width="33%">

**⚡ Shadowsocks**
- AEAD encryption
- Socks5 proxy
- Multi-user support

</td>
<td width="33%">

**🔴 V2Ray / Xray**
- VLESS + Reality
- VMess WebSocket
- Trojan TLS
- gRPC support

</td>
<td width="33%">

**🟠 SSH Tunnel**
- HTTP Injector
- NPay / NetSpark
- WebSocket config

</td>
</tr>
</table>

---

## 🛠️ Perintah

### Install VPN Lengkap
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/premi.sh)
```

### Install OpenVPN Saja
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/openvpn.sh)
```

### Install WireGuard Saja
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/wireguard.sh)
```

### Install SlowDNS Saja
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/slowdns.sh)
```

### Update Script
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tuyulbodo99/vpnscript/main/update.sh)
```

---

## 📱 Format Config Client

```
# HTTP Injector / NPay
Host      : [IP VPS]
Port SSH  : 22 / 80 / 443
Username  : [user]
Password  : [pass]
Payload   : GET wss://bug.com/ HTTP/1.1[crlf]Host: bug.com[crlf]Upgrade: websocket[crlf][crlf]

# OpenVPN
remote [IP VPS] 1194
proto udp
dev tun
... (lihat file .ovpn yang dihasilkan)

# WireGuard
[Interface]
PrivateKey = ...
Address = 10.0.0.2/24
DNS = 8.8.8.8
[Peer]
PublicKey = ...
Endpoint = [IP VPS]:51820
AllowedIPs = 0.0.0.0/0
```

---

## 🌐 Ekosistem DevCulture

| Repository | Fungsi |
|------------|--------|
| 🟣 [devculture-vps](https://github.com/tuyulbodo99/devculture-vps) | Core Panel + SSH + WebSocket |
| 🟣 [hokagescript](https://github.com/tuyulbodo99/hokagescript) | Menu Layanan & Services |
| 🟣 [vpnscript](https://github.com/tuyulbodo99/vpnscript) | Full VPN Installer |
| 🟣 [vps-script](https://github.com/tuyulbodo99/vps-script) | SSH Tunnel Setup |
| 🟣 [ijin](https://github.com/tuyulbodo99/ijin) | Sistem Lisensi & Perizinan |

---

## 🖥️ Persyaratan

| OS | RAM | Storage | Akses |
|----|-----|---------|-------|
| Ubuntu 20.04 / 22.04 LTS | Min 512 MB | Min 5 GB | Root |

---

<div align="center">

**DevCulture VPS Store** · [github.com/tuyulbodo99](https://github.com/tuyulbodo99) · [@devculturebot](https://t.me/devculturebot)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=a855f7&height=80&section=footer)

</div>
