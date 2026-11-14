# Civ

**the money OS. A Better Life…**

## What Civ is

Civ is an AI operating system with its own private cloud computer. You sign in to your accounts once — trading, betting, banking, payments, socials — and Civ works inside them for you: tracks your money, builds the tools and systems that grow it, and handles the grind while you make the calls. It reports to you, confirms anything irreversible, and gives flagship power at a fair flat price instead of big-tech markups.

**Coming soon:** the private cloud computer, account sign-in, and Civ Cloud. Today's release is an early personal-use build: laptop install on an Ubuntu base. It boots into Civ's typography session where you type a request. A MiniMax model key is needed for AI.

## What's in this release

**[civ-finish-v0.1.0](/releases/latest)**

| File | Notes |
|------|--------|
| `CivOS-Setup.exe` | Windows installer |
| `civ-finish.iso` | ~1.8 GB system image |
| `SHA256SUMS` | Checksums for both |

## Install on Windows

1. Download **CivOS-Setup.exe** from the [latest release](/releases/latest).
2. If SmartScreen appears: **More info** → **Run anyway**.
3. Approve the admin prompt.
4. The wizard installs to the **whole disk**.

> **Warning:** This erases the **entire disk**, including Windows. Back up first. Turn BitLocker off. Plug in power. Use Wi-Fi. Secure Boot is supported.

## Verify checksums

In PowerShell, from the folder with your downloads:

```powershell
Get-FileHash .\CivOS-Setup.exe -Algorithm SHA256
Get-FileHash .\civ-finish.iso -Algorithm SHA256
```

Compare the hashes to the values in `SHA256SUMS` from the same release.

## Status / roadmap

**Now** — Laptop personal-use build (Ubuntu base; typography session; MiniMax key for AI).

**Next** — Auto-updates; Civ Cloud with Civ ID; private cloud computer for account sign-ins.

## Disclaimer

This is early software. Use at your own risk. Civ is not financial advice.
