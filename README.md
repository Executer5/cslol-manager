🛠️ CSLOL Manager

The next-generation mod manager for League of Legends, built by the League Toolkit organization. CSLOL Manager is the modern successor to cslol-manager, rebuilt from the ground up with a Rust backend and a React-based UI.

Releases License: MIT/Apache-2.0 Windows 10+ FOSSA Status

📸 Screenshots

Mod Library | Workshop | Settings

✨ Features

**Mod Library** — Install, enable, disable, reorder, and uninstall mods with a visual card-based interface. Supports drag-and-drop installation.

**Profile Management** — Create multiple profiles to quickly switch between different mod configurations.

**Workshop (Creator Tools)** — Build and package your own mods with a full project editor, layer management, and .modpkg export.

**Mod Inspector** — Preview mod contents and metadata before installing.

**Overlay Patcher** — Apply your mods to League of Legends with a single click. Real-time progress tracking keeps you informed.

**Automatic Updates** — The app checks for new versions and can update itself in the background.

**Theming** — Dark and light themes with a fully customizable accent color and optional backdrop images.

## Supported Mod Formats

| Format   | Description                                                                                                |
| -------- | ---------------------------------------------------------------------------------------------------------- |
| .modpkg  | LeagueToolkit mod package — the recommended format with full metadata, thumbnails, and multi-layer support |
| .fantome | Legacy Fantome format — automatically recognized and fully supported                                       |

## 🚀 Getting Started

### Prerequisites

* Windows 10 or 11 (64-bit). macOS and Linux support is planned.
* League of Legends — a valid game installation.

### Installation

1. Go to the latest release.
2. Download the .msi installer (recommended) or the NSIS .exe installer.
3. Run the installer and launch CSLOL Manager.
4. On first launch, the app will attempt to auto-detect your League of Legends installation. If it can't find it, you'll be prompted to select the game folder manually.

### Installing Mods

1. Download a mod in .modpkg or .fantome format from your preferred source.
2. Drag and drop the file onto the CSLOL Manager window, or use the install button.
3. Enable the mod in your library and click Run to start the patcher.

## ⚖️ License & Reuse

CSLOL Manager is open-source under a dual MIT / Apache-2.0 license — you may choose either.

FOSSA Status

### cslol-dll.dll Policy

This application bundles cslol-dll.dll, the core injection module originally from cslol-manager. Its use and redistribution are governed by the CSLOL DLL License Addendum.

If you are a developer looking to reuse this DLL in your own launcher or tool, you must comply with the following:

* **Re-signing** — You may not redistribute the DLL with the official signature. You must re-sign it using your own publicly trusted code-signing certificate.
* **Transparency** — You must publish your certificate's SHA-256 fingerprint and the DLL's SHA-256 hash in your project's documentation or about page.
* **Anti-Skinhacking** — You must implement technical measures to prevent the use of "skinhacking" (replicating paid content) and competitive advantage mods.
* **No Reverse Engineering** — Patching or tampering with the DLL itself is strictly prohibited.

For full terms, see LICENSE-CSLOL.md.

## ⚠️ Disclaimer

Use at your own risk. This software is not endorsed by or affiliated with Riot Games.

**Server support:** Officially supports Riot-operated servers. Asian servers and Garena are not officially supported and may experience issues.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

If you'd like to build CSLOL Manager from source or work on the codebase, see the Development Guide.

Developed by the League Toolkit organization.
