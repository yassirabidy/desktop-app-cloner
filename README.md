# Desktop App Cloner

**Multiple accounts. Separate workspaces. One desktop.**

Run multiple independent instances of your favorite desktop applications side by side on Windows, without constantly signing in and out.

Use two Claude accounts, separate personal and work ChatGPT sessions, multiple Discord accounts, or dedicated VS Code environments for different projects.

Desktop App Cloner gives each clone its own profile, name, color, and desktop shortcut while keeping your original applications intact.

**Free to use • Windows 10 & 11 • No administrator rights required**

## 📥 Download

**[Download the Latest Release](https://github.com/yassirabidy/desktop-app-cloner/releases/latest)**

1. Open the latest release page.
2. Under **Assets**, download `DesktopAppCloner-<version>-Setup.exe`.
3. Run the installer to install Desktop App Cloner.
4. Launch the application and create your first clone.

The installer adds Start menu and desktop shortcuts and installs for your Windows user account without requiring administrator privileges.

To uninstall Desktop App Cloner, open **Settings › Apps** in Windows. Keep the app installed while you use clone desktop shortcuts.

The additional release files (`latest.yml` and `.blockmap`) are used for automatic updates and do not need to be downloaded manually.

> **Windows SmartScreen notice:** Desktop App Cloner is not currently code-signed, so Windows may display a security warning. If you trust the file and have verified that it came from this repository's official release, you can choose **More info → Run anyway**.

## ✨ Features

### Multiple accounts, simultaneously

Create separate environments for different accounts without having to sign out of the original app.

### Independent workspaces

Each clone has its own data directory and, for supported applications, its own authentication information, preferences, and configuration.

### Personalized clones

Assign custom names and colors to easily identify your different workspaces.

### One-click launching

Launch any clone directly from the management dashboard or through its dedicated Windows desktop shortcut.

### Clone management

Create, launch, stop, rename, recolor, and remove clones from a single interface.

### Current sign-in support

Keep using your existing application profile alongside separate clones by marking one clone per application to use your current sign-in.

### Automatic updates

Receive new releases directly through Desktop App Cloner without manually downloading and reinstalling each version.

### Original apps stay intact

Desktop App Cloner does not copy or modify the installed applications themselves. It launches supported applications using separate data locations.

## 🧩 Supported Applications

| Application | Status |
|---|---|
| Claude Desktop | ✅ Stable |
| ChatGPT Desktop (including Codex) | ✅ Stable |
| Visual Studio Code | ✅ Stable |
| Cursor | ✅ Stable |
| Windsurf | ✅ Stable |
| Google Chrome | ✅ Stable |
| Microsoft Edge | ✅ Stable |
| Brave Browser | ✅ Stable |
| Discord | ✅ Stable |
| Other Chromium / Electron applications | 🧪 Experimental |
| Other Windows applications | 🧪 Experimental |

**Experimental support:** You can attempt to clone additional applications using **Clone any other app**. Compatibility and independent sign-ins are not guaranteed. Try one first with an account you can sign in to again; an update to the target app may change how cloning works.

Some application features may still share operating-system resources or behave differently across clones. In particular, Claude Cowork, authentication callback routing, and simultaneous Cowork sessions have not been verified.

**Discord users:** Discord's browser sign-in handoff may initially select an account already signed in through your browser. To use another account, open the clone and choose your profile picture › **Switch Accounts** › **Add an Account**, then remove the first account from that clone.

## 🚀 How to Use

### 1. Create a clone

Open Desktop App Cloner, click **New Clone** (or press `Ctrl+N`), select an installed application, choose a name and color, and optionally create a desktop shortcut.

### 2. Launch your workspace

Click **Launch** on the clone's card or double-click the card. You can also use the desktop shortcut without opening the management interface first. Shortcuts launch silently, without a console window.

### 3. Manage your clones

Use the dashboard to monitor running clones, launch or stop them, change their appearance, refresh desktop shortcuts, and remove clones you no longer need.

Removing a clone deletes its desktop shortcut but does **not** delete its stored data. The removal dialog shows where that data is kept so you can manage the files separately. Renaming a clone also renames its desktop shortcut. Shortcuts that do not belong to Desktop App Cloner are never overwritten or deleted.

> Stopping a running clone immediately terminates only that clone's processes, including apps that remain in the system tray after their window closes. Save your work first to avoid losing unsaved changes.

## 🔄 Automatic Updates

Desktop App Cloner automatically checks for updates when it starts and periodically while running.

When a newer version is available, it downloads in the background. Once ready, you can restart to apply the update immediately or continue working and let it install the next time the application closes.

Updates preserve your existing clone profiles, sign-ins, data directories, and desktop shortcuts.

Clones that are already running keep running during an update.

**[View All Releases](https://github.com/yassirabidy/desktop-app-cloner/releases)**

## 💻 System Requirements

- Windows 10 or Windows 11
- Windows PowerShell 5.1 (included with Windows)
- Target desktop applications already installed
- Internet connection for downloading and receiving updates

**Administrator privileges are not required.**

## ❓ Frequently Asked Questions

**Does Desktop App Cloner duplicate my installed applications?**

No. It launches your existing installations with separate profile directories or supported isolation settings.

**Can I use different accounts at the same time?**

Yes, for supported applications. Each clone can maintain its own sign-in and settings, subject to limitations of the target application.

**Will I lose my accounts or profiles after updating?**

Normal application updates preserve existing clone data and configurations.

**Can I delete a clone without losing its data?**

Yes. Removing a clone from the dashboard does not delete its associated data directory.

**Do desktop shortcuts work when the manager isn't open?**

Yes. Clone shortcuts can launch through Desktop App Cloner without requiring the management window to remain open. The software must remain installed.

**Does Desktop App Cloner provide complete application sandboxing?**

No. Profile separation is not a security boundary, and some applications may still use shared system resources.

**Where is clone data stored?**

By default, Desktop App Cloner stores its profiles and clone data under `%APPDATA%\DesktopAppCloner`. Each clone's folder uses a generated ID rather than its display name. Removing a clone does not remove that folder.

**What happens to clones from an older version?**

Existing clone data is kept when the registry is upgraded. Older "Codex" clones become ChatGPT clones. Older "ChatGPT" clones that used ChatGPT Classic stay listed so you can remove them, but ChatGPT Classic is no longer supported. Their data is kept.

**Does Desktop App Cloner collect telemetry?**

No. Its network requests are for update checks to the GitHub Releases repository.

**Why is there a colored border around every window?**

That comes from the Windows setting **Settings › Personalization › Colors › Show accent color on title bars and window borders**. You can turn it off there.

## 🐛 Help & Feedback

Encountered a bug, found an incompatible application, or have a feature suggestion?

**[Report an Issue or Suggest a Feature](https://github.com/yassirabidy/desktop-app-cloner/issues)**

When reporting a problem, please include the application involved, your Windows version, your Desktop App Cloner version, and steps to reproduce the issue.

Do not include passwords, authentication tokens, or private profile data.

## ❤️ Support Development

Desktop App Cloner is free to use.

If it helps you manage your applications and saves you time, consider supporting its continued development.

**[Support via PayPal](https://paypal.me/yassirabidy)**

## 📄 Disclaimer

Desktop App Cloner is an independent, unofficial utility. It is not affiliated with, endorsed by, or sponsored by Anthropic, OpenAI, Microsoft, Google, Discord, or any other application vendor.

All application names and trademarks belong to their respective owners.

The project was developed with assistance from OpenAI Codex and Anthropic Claude, credited as development assistants rather than copyright owners or maintainers.

**Source code:** The source repository is private. This public repository is dedicated to software releases, downloads, user-facing documentation, and issue reporting. Public availability of release files does not grant an open-source license or redistribution rights.

---

**Desktop App Cloner — One desktop. Multiple workspaces.**

[Download Latest Release](https://github.com/yassirabidy/desktop-app-cloner/releases/latest) · [Report an Issue](https://github.com/yassirabidy/desktop-app-cloner/issues) · [Support Development](https://paypal.me/yassirabidy)
