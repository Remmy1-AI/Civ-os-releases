# Civ

**the money OS. A Better Life…**

## What Civ is

Civ is an AI operating system with its own private cloud computer. You sign in to your accounts once — trading, betting, banking, payments, socials — and Civ works inside them for you: tracks your money, builds the tools and systems that grow it, and handles the grind while you make the calls. It reports to you, confirms anything irreversible, and gives flagship power at a fair flat price instead of big-tech markups.

**Coming soon:** the private cloud computer, account sign-in, and Civ Cloud. Today's public assets are early personal-use laptop builds on an Ubuntu base (Wayfire + Civ shell). A MiniMax model key is needed for AI.

## Latest laptop update

**[civ-update-v0.1.34](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.34)** ← current `/releases/latest` for auto-update

| File | Notes |
|------|--------|
| `civ-bundle.tgz` | Signed update payload |
| `civ-bundle.tgz.minisig` | minisign signature |

Verify with the pubkey already on the laptop (`/etc/civ-os/update-pubkey.pub`). **Assets only** — no private keys, no secrets, no private-repo sources.

### Recent update tags

| Tag | Highlights |
|-----|------------|
| [0.1.34](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.34) | Files This laptop + storage; Drop expiry / New code |
| [0.1.33](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.33) | Civ Files v1; Drop Received → Files; files.* caps; term title align |
| [0.1.32](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.32) | Workarea maximize (no exclusive-zone strut); dock full-bleed; Drop LAN |
| [0.1.31](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.31) | Drop QR transfer; dark glass terminal |
| [0.1.30](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.30) | Glass terminal title bar; maximize above dock |
| [0.1.29](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.29) | Polkit Updates + honest progress; touchpad Settings |
| [0.1.28](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.28) | Minimize all soft-GL apps; dock restore |
| [0.1.27](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-update-v0.1.27) | Window dots right + hover; Wayland drag; wallpaper only in Settings |

## Full disk image (Windows setup)

**[civ-finish-v0.1.0](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-finish-v0.1.0)** (install-from-Windows path; separate from signed laptop updates)

| File | Notes |
|------|--------|
| `CivOS-Setup.exe` | Windows installer |
| `civ-finish.iso` | ~1.8 GB system image |
| `SHA256SUMS` | Checksums for both |

## Install on Windows (full image)

1. Download **CivOS-Setup.exe** from the [civ-finish release](https://github.com/Remmy1-AI/Civ-os-releases/releases/tag/civ-finish-v0.1.0).
2. If SmartScreen appears: **More info** → **Run anyway**.
3. Approve the admin prompt.
4. The wizard installs to the **whole disk**.

> **Warning:** This erases the **entire disk**, including Windows. Back up first. Turn BitLocker off. Plug in power. Use Wi-Fi. Secure Boot is supported.

## Verify checksums (full image)

In PowerShell, from the folder with your downloads:

```powershell
Get-FileHash .\CivOS-Setup.exe -Algorithm SHA256
Get-FileHash .\civ-finish.iso -Algorithm SHA256
```

Compare the hashes to the values in `SHA256SUMS` from the same release.

## Status / roadmap

**Now** — Laptop personal-use builds with signed auto-updates (Wayfire shell, Settings, Terminal, Drop).

**Next** — Civ Cloud with Civ ID; private cloud computer for account sign-ins.

## Disclaimer

This is early software. Use at your own risk. Civ is not financial advice.
