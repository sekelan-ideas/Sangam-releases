<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sangam-logo-dark.png">
  <img src="assets/sangam-logo.png" width="160" alt="Sangam logo">
</picture>

# Sangam

**Where friends and family meet**

A private, end-to-end encrypted messenger built for the people you care about.

![Version](https://img.shields.io/badge/version-1.9.1-3CB3D6)
![Platform](https://img.shields.io/badge/platform-Android%208.0%2B-2E8FAD)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-F88A32)
![Security](https://img.shields.io/badge/chats-end--to--end%20encrypted-brightgreen)

[Download the latest APK](../../releases/latest)

</div>

---

## ✨ Features

**Messaging**
- 💬 Text messages with reply, forward and edit-sent-messages
- 📷 Photos — crop, rotate and filter before sending
- 🎬 Videos and 🎤 voice notes, played inside the chat
- 📄 Documents (PDF and other files)
- 🕰️ Time capsules — messages that unlock at a time you choose
- ⭐ Starred messages, emoji reactions and in-chat search

**Private by default**
- 🔒 End-to-end encryption on every message (Signal protocol)
- 🕵️ Privacy controls — turn off read receipts and last seen
- 🔐 App lock with a password or your fingerprint
- 💾 Password-encrypted chat backup & restore

**Nice to use**
- 🎨 Per-chat themes, media gallery and animated typing dots
- 📤 Share photos to Sangam straight from the gallery
- 🔔 Notifications with sound, vibration and per-chat mute
- ⚡ Chats open instantly and sync fast, even on slow connections

## 🔐 Security

- **Signal protocol** (X3DH + Double Ratchet via libsignal) for every chat.
  The server stores only ciphertext; private keys never leave the device.
- Photos, videos, voice notes and documents are encrypted with
  AES-256-GCM before upload — their keys travel inside the E2EE messages.
- Signal protocol keys live in Android's Keystore-backed encrypted storage
  and are never transmitted.
- Backups are encrypted with a password only you know (PBKDF2 + AES-GCM).

## 🛠 Built with

| Layer | Technology |
|---|---|
| App | Kotlin, Jetpack Compose, Material 3 |
| Crypto | libsignal (Signal protocol), AES-256-GCM |
| Backend | Supabase (Postgres + Row Level Security, Storage, Edge Functions) |
| Notifications | Firebase Cloud Messaging |
| CI/CD | GitHub Actions — builds, signs and publishes every release |

## 📥 Download

Grab the newest APK from the [**Releases**](../../releases) page — no account needed.

> **Note:** this repository publishes the official Sangam releases. The
> application source is developed in a private repository.

## 📜 Versions

See the [Releases](../../releases) page for the full version history —
currently at **v1.9.1**.

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/sangam-logo-dark.png">
  <img src="assets/sangam-logo.png" width="72" alt="Sangam logo">
</picture>

**Sangam** · Where friends and family meet

</div>
