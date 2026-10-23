# Desktop App Cloner

**Run separate accounts of your desktop apps side by side on Windows.** Two Claude sign-ins, a work and a personal ChatGPT, a Discord for gaming, a VS Code per client: each clone has its own sign-in, its own name and color, and its own desktop shortcut.

**[⬇ Download the latest version](https://github.com/yassirabidy/desktop-app-cloner/releases/latest)** · Windows 10 & 11 · Free

<p align="center"><img src="screenshots/01-all-clones.png" alt="All your clones in one place" width="75%"></p>

## Download and install

1. Open the **[latest release](https://github.com/yassirabidy/desktop-app-cloner/releases/latest)**.
2. Under **Assets**, download **`DesktopAppCloner-<version>-Setup.exe`**.
3. Double-click it and click **Yes** when Windows asks for administrator permission. It installs for all users of the PC (in Program Files), adds Start menu and desktop shortcuts, and opens the app. The app itself runs without administrator rights.

The other files in a release (`latest.yml` and the `.blockmap`) are used by the app to update itself; you don't need to download them.

**"Windows protected your PC"?** The app is not code-signed yet, so Windows SmartScreen may warn about it the first time. Click **More info › Run anyway**. Only do this for files downloaded from this page.

**"Smart App Control blocked an app that may be unsafe"?** On PCs with Smart App Control turned on, Windows blocks apps that are not code-signed, and this message has no **Run anyway** button. There is no way to allow just this one installer. A signed version is planned; until then the installer can't run on these PCs. You can check the setting in **Windows Security › App & browser control › Smart App Control**. Turning it off applies to every app and can't be turned back on without reinstalling Windows, so we don't recommend it just for this app.

**Requirements:** Windows 10 or 11, and the apps you want to clone already installed.

## Supported apps

Claude · ChatGPT (with Codex) · Discord · VS Code · Cursor · Windsurf · Google Chrome · Microsoft Edge · Brave — plus **any other app** you add yourself (experimental).

## How it works

### 1. Pick an app

The app opens on **Home**, which shows the apps you can clone. Click one to start.

<p align="center"><img src="screenshots/00-home.png" alt="The Home page" width="75%"></p>

You can also click **New clone** from any page. Apps installed on your PC are ready to clone; the others are greyed out. **Any other app** lets you pick a program file yourself.

<p align="center"><img src="screenshots/02-new-clone-picker.png" alt="Choosing an app to clone" width="75%"></p>

### 2. Name it and choose a color

Give the clone a name, pick a color, and decide whether it gets its own desktop shortcut. The clone starts as a fresh, signed-out copy of the app — sign in there with your other account.

<p align="center"><img src="screenshots/03-new-clone-details.png" alt="Naming a new clone" width="75%"></p>

### 3. Launch, stop and manage your clones

**All clones** lists every clone you've made, grouped by app. Every clone has a card: **Launch** opens it, the green dot shows which ones are running, and the red **■** stops a running clone (also the ones hiding in the system tray). Click an app in the sidebar to see only its clones.

<p align="center"><img src="screenshots/04-app-page.png" alt="The clones of one app" width="75%"></p>

The **⋮** menu lets you rename and recolor a clone, create or refresh its desktop shortcut, open its data folder, or remove it.

<p align="center"><img src="screenshots/05-clone-menu.png" alt="The clone menu" width="75%"></p>

### 4. Remove a clone when you no longer need it

Removing a clone deletes its shortcut and **its data** (sign-ins, chats, settings and cache), so your disk doesn't fill up over time. The original app and your other clones are never touched.

<p align="center"><img src="screenshots/06-remove-clone.png" alt="Removing a clone" width="75%"></p>

## Light or dark

Switch themes with the sun/moon button at the top right. Your choice is remembered.

<p align="center"><img src="screenshots/08-light-all-clones.png" alt="Light theme" width="75%"></p>

## Updates

The app updates itself from this page. A new version downloads in the background while you work. It installs when you close the app, right away if you click **Restart**, or by itself 15 minutes after it finishes downloading if you keep the app open (it waits until you're done with any open dialog). Windows asks for administrator permission each time an update installs. Your clones, their sign-ins and their shortcuts are kept.

## About and support

<p align="center"><img src="screenshots/07-about.png" alt="About page" width="75%"></p>

Desktop App Cloner is free. If it saves you time, you can support it with a donation on **[PayPal](https://paypal.me/yassirabidy)**.

Found a problem or have an idea? **[Open an issue](https://github.com/yassirabidy/desktop-app-cloner/issues).**

---

**Discord tip:** a new Discord clone may sign itself in with the account that is open in your web browser. To use another account, open the clone, click your profile picture at the bottom left, choose **Switch Accounts › Add an Account**, then remove the first account from that clone.

This is an unofficial app, not affiliated with Anthropic, OpenAI, Microsoft, Google, Discord or other app makers.
