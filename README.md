# Sadeem for Windows — official release files

This repository distributes Windows installers and signed update metadata only. Application source, signing keys and user data are not stored here. No paid hosting, certificates, Actions workflows or subscriptions are used.

**Current version: 1.0.0**

- [Download the Windows x64 installer](https://github.com/ShadowUR0/sadeem-releases/releases/download/v1.0.0/Sadeem_1.0.0_x64-setup.exe)
- [Release notes and signed assets](https://github.com/ShadowUR0/sadeem-releases/releases/tag/v1.0.0)
- [Permanent HTTPS update manifest](https://github.com/ShadowUR0/sadeem-releases/releases/latest/download/latest.json)

## Existing Sadeem 0.3.5 installations

Version 0.3.5 contains no default release endpoint. Install this newer version once, or download [the signed channel](https://github.com/ShadowUR0/sadeem-releases/releases/download/v1.0.0/sadeem-update-channel.json) and [its signature](https://github.com/ShadowUR0/sadeem-releases/releases/download/v1.0.0/sadeem-update-channel.json.sig) into the same folder and import the JSON under Settings → Help & About → Application updates. Enable automatic checks there if desired. Installation and restart always require your approval.

## العربية

[تنزيل مثبت سديم لويندوز](https://github.com/ShadowUR0/sadeem-releases/releases/download/v1.0.0/Sadeem_1.0.0_x64-setup.exe). لمستخدمي 0.3.5: ثبّت الإصدار الجديد مرة واحدة، أو استورد ملف القناة الموقّع مع توقيعه من الإعدادات ← المساعدة وحول ← تحديثات التطبيق. يبقى تنزيل التحديث وتثبيته وإعادة التشغيل باختيارك.

Accounts, encryption keys, conversations and settings remain in the existing local application-data folder. The installer has a Tauri update signature; Windows Authenticode signing is not configured. Downloading an update does not install it automatically.