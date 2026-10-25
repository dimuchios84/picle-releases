<h1><img src="PicleIcon.png" alt="picle app icon" width="72" height="72"> picle</h1>

**A free, closed-source screenshot and annotation app for macOS.**

Select an area, add freehand notes, arrows or numbered markers, and save or share your screenshot. Upload to your own SFTP server and copy a verified public HTTPS link.

[![Support picle on Ko-fi](https://img.shields.io/badge/Support%20picle-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/dimuchio) [![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-0070BA?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/dimuchio)

## Download

[**Download picle for macOS**](https://github.com/dimuchios84/picle-releases/releases/download/v0.1.26-preview.1/picle-0.1.26-30-macOS-arm64-preview.dmg) · [Release notes and SHA-256](https://github.com/dimuchios84/picle-releases/releases/tag/v0.1.26-preview.1)

**picle 0.1.26 Preview · Build 30 · macOS 14+ · Apple Silicon (arm64)**

Intel Macs are not supported by this installer. New installations start in **English**, independently of the macOS language. Choose **Settings → General → Language → Русский** to use Russian. The choice is saved and the app's interface switches immediately.

> **First-launch notice:** this preview uses an Apple Development certificate. It is not signed with Developer ID and has not been notarized by Apple. macOS may block the first launch; successful launch on every Mac is not guaranteed. See [Install and open](#install-and-open).

## What picle does

- Start area selection from the menu bar or a global shortcut (default **⇧⌘2**, with alternatives in settings).
- Use the actual macOS rectangle selector, crosshair, coordinates and Escape cancellation.
- Add freehand strokes, arrows and automatically numbered circles.
- Choose annotation colors and line width, with undo and redo.
- Save locally as PNG, JPEG or Automatic, or copy the annotated image to the clipboard.
- Upload over SFTP using a password or SSH key/agent. Saved secrets use macOS Keychain; server host keys are verified.
- Copy the public link only after both upload and HTTPS image verification succeed.
- Use English or Russian.

## Your server, your links

Local saving and copying do not require a server. **Online sharing requires your own SFTP account and a working public HTTPS website. Hosting is not included.**

Configure the host, port, username, authentication method, remote folder and matching public base HTTPS URL in **Settings → Connection**. The remote folder must already exist and correspond to the URL served by your website. Use **Test connection** to check access. Compare first-connection host-key fingerprints with your hosting provider before trusting them.

Uploaded filenames contain ten random letters and digits, plus the image extension. Anyone with a public link can view the uploaded image. Random filenames are not access control; use suitable server-side protection for sensitive material.

picle requests screen-recording permission to capture the selected area. It creates screenshots and does not record audio. Operating-system permission dialogs and third-party Services follow macOS's language.

## Install and open

1. Download the DMG from the official link above.
2. Open it and drag **picle.app** to **Applications**.
3. Read **Read Me First.txt**, eject the disk image and open picle from Applications.
4. If macOS blocks this unnotarized preview and you trust the official download, follow [Apple's instructions](https://support.apple.com/102445) to allow this app through **System Settings → Privacy & Security → Open Anyway**. Confirm the per-app prompt if offered.
5. When taking your first screenshot, allow picle under **Privacy & Security → Screen & System Audio Recording**. Confirm a restart if macOS requests it.

Keep Gatekeeper enabled. Do not remove quarantine attributes or disable macOS security. If macOS reports malware or damage, stop and verify the download. A managed Mac may prevent a per-app exception; contact its administrator if necessary.

## Support development

picle is free to use for personal and internal business purposes. Donations are optional and unlock no features.

If picle helps you, you can [support development on Ko-fi](https://ko-fi.com/dimuchio) or [donate via PayPal](https://paypal.me/dimuchio). A donation is voluntary support, not a purchase of ownership, distribution rights, a subscription, or guaranteed future features or support.

## Usage terms

picle is proprietary software, not open source. Install and use official copies free of charge for your personal or internal business work. Redistribution, resale, repackaging, modification and derivative releases require the copyright holder's prior written permission, subject to mandatory rights and third-party licenses. See the [picle Freeware License](LICENSE.md).

Please share this official download page rather than upload copies elsewhere. This repository contains public product information and official releases, **not picle's application source code**. GitHub's automatic “Source code” ZIP/TAR files contain only this repository's public documents and artwork. Use the DMG to install the app.

## Feedback and support

Report bugs or suggest improvements through [GitHub Issues](https://github.com/dimuchios84/picle-releases/issues). Include your macOS version, Mac model, picle version and steps to reproduce. For upload problems, describe your server setup without sharing secrets. Remove passwords, SSH keys, access tokens and private screenshots from reports.

---

Developed by [dimuchio](https://github.com/dimuchios84). [Ko-fi](https://ko-fi.com/dimuchio) · [PayPal](https://paypal.me/dimuchio).
