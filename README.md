# Telegram Shortcuts

Personal custom shortcuts for <img height="12px" src="https://api.iconify.design/logos:telegram.svg" /> Telegram Desktop which you can be change to your liking. Here are a list of the `action/keypresses` inside <a href="shortcuts-custom.json">shortcuts-custom.json</a>:

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
      <td><kbd>Ctrl + Shift + 1</kbd></td>
    </tr>
    <tr>
      <td>Switch to account 2</td>
      <td><kbd>Ctrl + Shift + 2</kbd></td>
    </tr>
    <tr>
      <td>Switch to account 3</td>
      <td><kbd>Ctrl + Shift + 3</kbd></td>
    </tr>
    <tr>
      <td>Archive selected chat</td>
      <td><kbd>Ctrl + Shift + h</kbd></td>
    </tr>
    <tr>
      <td>Set schedule message</td>
      <td><kbd>Ctrl + Shift + s</kbd></td>
    </tr>
    <tr>
      <td>Show scheduled message of selected chat</td>
      <td><kbd>Ctrl + Alt + s</kbd></td>
    </tr>
    <tr>
      <td>Preview the chat</td>
      <td><kbd>Ctrl + p</kbd></td>
    </tr>
  </tbody>
</table>

If you're interested in these shortcuts as well, you can apply it via Installation section below ⬇️

## Installation

> [!TIP]
> Simply get the <a href="./shortcuts-custom.json">shortcuts-custom.json</a> file into your Telegram Desktop `/tdata` directory 😀

---

> [!NOTE]
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
