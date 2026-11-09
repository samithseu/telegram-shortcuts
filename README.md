# Telegram Shortcuts

Personal custom shortcuts for <span>
<svg xmlns="http://www.w3.org/2000/svg" width="18" height="14" viewBox="0 0 256 256"><defs><linearGradient id="SVG6DaOZcwt" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" stop-color="#2aabee"/><stop offset="100%" stop-color="#229ed9"/></linearGradient></defs><path fill="url(#SVG6DaOZcwt)" d="M128 0C94.06 0 61.48 13.494 37.5 37.49A128.04 128.04 0 0 0 0 128c0 33.934 13.5 66.514 37.5 90.51C61.48 242.506 94.06 256 128 256s66.52-13.494 90.5-37.49c24-23.996 37.5-56.576 37.5-90.51s-13.5-66.514-37.5-90.51C194.52 13.494 161.94 0 128 0"/><path fill="#fff" d="M57.94 126.648q55.98-24.384 74.64-32.152c35.56-14.786 42.94-17.354 47.76-17.441c1.06-.017 3.42.245 4.96 1.49c1.28 1.05 1.64 2.47 1.82 3.467c.16.996.38 3.266.2 5.038c-1.92 20.24-10.26 69.356-14.5 92.026c-1.78 9.592-5.32 12.808-8.74 13.122c-7.44.684-13.08-4.912-20.28-9.63c-11.26-7.386-17.62-11.982-28.56-19.188c-12.64-8.328-4.44-12.906 2.76-20.386c1.88-1.958 34.64-31.748 35.26-34.45c.08-.338.16-1.598-.6-2.262c-.74-.666-1.84-.438-2.64-.258c-1.14.256-19.12 12.152-54 35.686c-5.1 3.508-9.72 5.218-13.88 5.128c-4.56-.098-13.36-2.584-19.9-4.708c-8-2.606-14.38-3.984-13.82-8.41c.28-2.304 3.46-4.662 9.52-7.072"/></svg>
</span> Telegram Desktop which you can be change to your liking. Here are a list of the `action/keypresses` inside <a href="shortcuts-custom.json">shortcuts-custom.json</a>:

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

> [!TIP]
> Simply get the <a href="./shortcuts-custom.json">shortcuts-custom.json</a> file into your Telegram Desktop `/tdata` directory 😀

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
