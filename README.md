<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/logo-light.png">
    <img src="assets/logo-light.png" alt="Sylva Logo" width="160" height="160">
  </picture>
</p>

<h1 align="center">Sylva</h1>

<p align="center">
  <strong>A premium iOS application manager to import, sign, organize, and install IPA files on your device.</strong>
</p>

<p align="center">
  <a href="https://sylva.antonp29.dev"><strong>🌐 Use Web Signer (sylva.antonp29.dev)</strong></a>
</p>

---

## About Sylva

Sylva is a native iOS app designed to give you complete control over your applications. It allows you to import IPA files from various sources, sign them locally using your own certificates, and install them directly on your device.

## Key Features

- **Multi-Source Import**: Import IPA files from local Files, direct URLs, QR codes, or AltStore-style repositories.
- **Repository Browser**: Easily search, explore, and download apps from third-party repositories.
- **On-Device Signing**: Sign IPAs locally with comprehensive certificate and provisioning profile management.
- **Dylib Injection**: Inject customized `.dylib` tweaks directly into your IPAs with built-in presets.
- **Seamless Installation**: Install your signed apps through Sylva's local installation server pipeline.
- **App Library**: Manage all your signed and imported apps with clean metadata, icons, and status tracking.
- **Personalized Experience**: Choose your favorite theme color, toggle custom haptic feedback, and manage your storage.

## How to Install Sylva

To install Sylva on your device, you need to sign the IPA with your own signing certificate.

### Step 1: Download the IPA
Go to the **[Releases](https://github.com/AntonP29/Sylva-iOS-Releases/releases)** section of this repository and download the latest `.ipa` file.

### Step 2: Sign and Install
We provide a convenient web-based signer to install Sylva directly onto your device:

1. Open **[sylva.antonp29.dev](https://sylva.antonp29.dev)** in Safari on your iOS device.
2. Upload the downloaded Sylva `.ipa` file.
3. Upload your Apple Developer signing certificate (`.p12`) and provisioning profile (`.mobileprovision`).
4. Enter your certificate password.
5. Click **Sign & Install** and follow the prompts on your device.

---

## Requirements

- iOS 26.4 or later.
- A valid Apple Developer signing certificate (`.p12`) and provisioning profile (`.mobileprovision`) to sign and install the IPA.
- Safari on iOS is recommended when using the web signer.

## Credits

Made by **AntonP29**.

---

## Support / Donate

If you enjoy using Sylva, support the development on Cash App: [cash.app/$AntonP29](https://cash.app/$AntonP29)
