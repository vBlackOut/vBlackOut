<h1 align="center">ProxyAuth</h1>
<p align="center"><img src="https://proxyauth.app/static/logo.jpg" height="200px" width="250px"/></p>
<p align="center">
  <b>A fast, secure and flexible authentication proxy written in Rust</b><br>
  🔐 HTTP/HTTPS • 🔄 Smart failover • ⚡ ChaCha20-Poly1305 + HMAC-SHA256 • configurable via YAML/JSON
</p>

<p align="center">
  <img src="https://img.shields.io/crates/v/proxyauth?style=flat-square" alt="Crate version">
  <img src="https://img.shields.io/badge/performance-+100k%20RPS-brightgreen?style=flat-square" alt="Benchmark">
  <img src="https://img.shields.io/github/license/vBlackOut/ProxyAuth?style=flat-square" alt="License">
</p>

---
## 🌐 Overview

**ProxyAuth** is a high-performance authentication gateway and reverse proxy built in Rust.  
It is designed to handle:

- 🔑 Secure token-based authentication
- 🕓 Dynamic expiration & rate limits
- 🌍 Multi-backend failover with cooldowns
- 📈 Real-time logging & stats

> **Why ProxyAuth?**
> - Faster than NGINX with Lua
> - Safer than plain HAProxy
> - Easier to integrate in modern infrastructures

---

## ⚙️ Features

- ✅ Token validation with HMAC
- ✅ Failover with progressive cooldown
- ✅ Benchmarked at **700,000 RPS** on a Threadripper

---

## 📦 Quick Install

```bash
cargo install proxyauth
```

### Or via install script:

```bash
curl -fsSL https://proxyauth.app/sh/install | bash
```

> 📄 [Full documentation](https://proxyauth.app/)

---

## 🔬 Benchmark

Tested on AMD Threadripper 5995WX:

➡️ [📊 View full benchmark (v0.7.2)](https://proxyauth.app/benchmark/0.7.2.html)

```text
📈 700,000 requests per second
🔐 TLS + ChaCha20-Poly1305 + HMAC-SHA256
⚙️ 64-thread CPU • 512GB RAM • NVMe SSD
```

---

---

## 🛡️ Security

- ✅ ChaCha20-Poly1305 encryption
- ✅ HMAC-SHA256 key derivation
- ✅ Process isolation with dedicated system user (`proxyauth`)
- ✅ Export cryptography configuration via GPG v6 <a href="https://crates.io/crates/sequoia-openpgp/2.0.0">sequoia-opengpg 2.0.0</a>

---

## ✨ Contributing

- 🤝 Contributions are welcome!
- Open an **issue** or a **pull request**
- Share the project and drop a ⭐ if you like it

---

## 🧠 Author

Made with ❤️ by [@vBlackOut](https://github.com/vBlackOut)

[![Website](https://img.shields.io/badge/Website-proxyauth.app-informational?style=flat-square)](https://proxyauth.app)

---

## 🧪 License
Licensed under the Apache 2.0 License. 
