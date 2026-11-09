# Telegram Shortcuts

Personal custom shortcuts for <img src="https://cdn.samith.dev/f/BQACAgUAAxkDAAIbYmrxl2WfIvOYWS85ROsPwUQvL-sqAAJ1IwAC2tOQV-8ite-SZIoDPQQ/telegram-icon.svg" height="14" title="Telegram Icon" alt="Telegram Icon"/> Telegram Desktop which you can be change to your liking. Here are a list of the `action/keypresses` inside <a href="shortcuts-custom.json">shortcuts-custom.json</a>:

<table>
  <thead>
    <tr>
      <th>Actions</th>
      <th>Keypresses</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Switch to account 1</td>
      <td><kbd>ctrl + shift + 1</kbd></td>
    </tr>
    <tr>
      <td>Switch to account 2</td>
      <td><kbd>ctrl + shift + 2</kbd></td>
    </tr>
    <tr>
      <td>Switch to account 3</td>
      <td><kbd>ctrl + shift + 3</kbd></td>
    </tr>
    <tr>
      <td>Archive selected chat</td>
      <td><kbd>ctrl + shift + h</kbd></td>
    </tr>
    <tr>
      <td>Set schedule message</td>
      <td><kbd>ctrl + shift + s</kbd></td>
    </tr>
    <tr>
      <td>Show scheduled message of selected chat</td>
      <td><kbd>ctrl + alt + s</kbd></td>
    </tr>
    <tr>
      <td>Preview the chat</td>
      <td><kbd>ctrl + p</kbd></td>
    </tr>
    <tr>
      <td>Stash message</td>
      <td><kbd>ctrl + shift + alt + s</kbd></td>
    </tr>
    <tr>
      <td>AI compose apply</td>
      <td><kbd>ctrl + shift + a</kbd></td>
    </tr>
    <tr>
      <td>Show rich editor</td>
      <td><kbd>ctrl + shift + r</kbd></td>
    </tr>
  </tbody>
</table>

If you're interested in these shortcuts as well, you can apply it via Installation section below ⬇️

## Installation

> [!IMPORTANT]
> ⚠️ Do not run unfamiliar commands in the `/tdata` directory, as it contains your Telegram account session. Doing so could allow hackers to access your account, even if two-factor authentication is enabled.
>
> _You can trust this command because it simply downloads a text (JSON) file and saves it. There are no other suspicious activities._ 😀

> [!TIP]
> Simply get the <a href="./shortcuts-custom.json">shortcuts-custom.json</a> file into your Telegram Desktop `/tdata` directory

---

> [!NOTE]
>
> - Install Telegram Desktop first before applying these shortcuts.<br/>
> - Shortcuts for <a href="#linux">linux</a> might not be working depending on your Telegram installed directory from source _(e.g. Flatpak, Snap, AppImage, etc.)_

---

### Windows

```powershell
iwr "https://github.com/samithseu/telegram-shortcuts/raw/main/shortcuts-custom.json" -OutFile "$ENV:APPDATA/Telegram Desktop/tdata/shortcuts-custom.json"
```

### Linux

```bash
curl -L -o "$(find ~/ -type d -name "Telegram*" 2>/dev/null | head -n 1)/tdata/shortcuts-custom.json" "https://github.com/samithseu/telegram-shortcuts/raw/main/shortcuts-custom.json"
```

> [!NOTE]
> Please restart Telegram Desktop after applying the shortcuts!
