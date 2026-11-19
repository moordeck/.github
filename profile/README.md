# Moordeck

**Local-First Anti-Detect Fingerprint Browser & Standard Local API Engine**  
**本地优先的多开防关联指纹浏览器与标准 Local API 引擎**

---

## Highlights / 核心特性

- **Local-First Desktop App (`Moordeck.app`)**: Zero-login standalone operation on macOS Apple Silicon (`darwin-arm64`) with embedded SQLite WAL ledger and local `0600` AES-256-GCM encrypted vault for cookies, fingerprints, and proxy credentials.
- **Patched Anti-Detect Kernel (`moordeck-chromium`)**: Independently packaged `Ed25519`-signed Chromium builds (`mc-155-v1`, Chromium `155.0.8059.39`) with multi-version slot isolation, `netguard` private/CGNAT egress blocking, and non-proxied UDP prevention.
- **Standard Local API & `mdk` CLI**: Loopback REST API (`127.0.0.1:9112`) and `mdk` CLI for Playwright / Puppeteer automation, batch environment management, headless Linux daemon (`mdkd`), and window layout arrangement.
- **Optional Encrypted Team Sync**: Passwordless sign-in (Google OAuth PKCE / Email OTP) via [moordeck.com](https://moordeck.com) with team-scoped `HKDF-SHA256 + AES-256-GCM` envelope encryption and distributed lease locks.

---

## Quick Links / 快速入口

- **Website / 官网**: https://moordeck.com
- **Download / 客户端下载**: https://moordeck.com/download
- **Official Releases & Issue Tracker / 官方发行版与问题反馈**: https://github.com/moordeck/releases
- **Fingerprint & Proxy Diagnostics / 指纹与代理检测**: https://moordeck.com/check · https://moordeck.com/ip
- **CLI & API Docs / 接口文档**: https://moordeck.com/docs
- **Homebrew (macOS)**:
  ```bash
  brew install --cask moordeck/tap/moordeck
  ```
