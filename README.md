<h1 align="center">App Store</h1>

<div align="center">

<p><i>A secure, independent, and native application store for LineageOS with Material 3 design.</i></p>

[![LineageOS](https://img.shields.io/badge/LineageOS-167C80?style=for-the-badge&logo=lineageos&logoColor=white)](https://lineageos.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![Material 3](https://img.shields.io/badge/Material%203-00668B?style=for-the-badge&logo=materialdesign&logoColor=white)](https://m3.material.io/)
[![Active](https://img.shields.io/badge/Status-Active-2EA44F?style=for-the-badge)](#)

</div>

## About

**App Store** is an independent, native Android application manager designed to provide secure, seamless, and automated application installations and updates for LineageOS devices.

Forked from [GrapheneOS AppStore](https://github.com/GrapheneOS/AppStore), this release is tailored for our custom LineageOS distribution, featuring full **Material 3 (Material You)** theming, adaptive dynamic icons, and independent catalog integration.

## Features

- **Material 3 Design:** Complete Material You dynamic theming, monochrome themed icon support, and fluid animations.
- **Cryptographic Security:** Repository metadata is authenticated using Ed25519 public key signatures (`signify`).
- **Seamless Updates:** Automatic background check and one-tap unattended installation.
- **Independent Ecosystem:** Host and distribute your own applications, browsers, and service packages.

## Available Applications

| Application | Package Name | Source |
| :--- | :--- | :--- |
| **Titanium Browser** | `io.github.jqssun.helium` | [jqssun/android-titanium-browser](https://github.com/jqssun/android-titanium-browser) |
| **LineageOS Info** | `org.lineageos.info` | [rhythmcreative/Info](https://github.com/rhythmcreative/Info) |
| **Google Play Store** | `com.android.vending` | Google (Official Verified) |
| **Google Play Services** | `com.google.android.gms` | Google (Official Verified) |
| **Google Services Framework** | `com.google.android.gsf` | Google (Official Verified) |

## Repository Configuration

| Property | Value |
| :--- | :--- |
| **Catalog Base URL** | `https://rhythmcreative.github.io/apps-repository` |
| **Signing Algorithm** | Ed25519 (`signify`) |
| **Client Status** | Production / Active |

## Building

```bash
git clone https://github.com/rhythmcreative/AppStore.git
cd AppStore
./gradlew assembleRelease
```

## Disclaimer

This is an independent open-source project based on the GrapheneOS AppStore and is not affiliated with Google or GrapheneOS.

<div align="center">

<p>Made with ❤️ from rhythmcreative.</p>

</div>
