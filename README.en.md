# Lattice (English)

[中文](README.md) | **English**

Lattice is a native file manager for Windows, written from scratch in C++ with Win32 and Direct2D: a single exe that starts fast and stays light. **It's completely free, with no ads.**

This repository is Lattice's release repository. It holds only the installer and the update manifest.

## Download

Get the latest **LatticeSetup.exe** from [GitHub Releases](https://github.com/ryzewang1994/Lattice_release/releases/latest) or [Gitee releases](https://gitee.com/ryze_king/Lattice_release/releases) (faster in mainland China). Run it to install or upgrade in place.

Each release also includes an `update.json` (version, size, SHA-256). The installer's SHA-256 is printed at the end of the release notes, so you can verify the file yourself.
In the app, Settings → System → Check for updates lets you pick GitHub or Gitee as the update source.

Requirements: Windows 10 / 11 (x64).

## Features

- **Tabs and panes**: tabs, tab groups and one-click cleanup; up to four panes side by side, drag files between them to copy or move.
- **Fast**: instant home page, whole-disk indexed search (reads the NTFS file table directly when running as administrator), search from the address bar.
- **Built-in terminal**: a real terminal on ConPTY + libvterm (cmd / PowerShell / Git Bash / WSL), as a bottom panel or a full tab.
  The folder follows the terminal and the terminal follows the folder. Split panes, broadcast input, quick commands, inline suggestions, output highlighting, session recording and playback.
- **SSH / SFTP**: connect to saved servers in one click, with key / ssh-agent login, jump hosts and port forwarding. Remote folders and the terminal's `cd` follow each other.
- **Network places and cloud storage**: SMB, FTP, SFTP, WebDAV, S3-compatible storage; phones and cameras (MTP).
- **Its own transfer engine**: copy, move, delete, compress and extract with progress and animations. Large files are split automatically to get past FAT32's 4 GB limit.
- **Lock check**: right-click a file → "Check what's locking it" to see which program, and which chain of processes, holds it, then unlock it the recommended way.
- **Disk space analysis**: a treemap shows what's taking up space.
- **Preview**: images, video, music, PDF, Markdown, code and archive contents in the side panel; image gallery, music player and bookshelf.
- **Context menu and custom commands**: a redesigned right-click menu where you can add your own commands.
- **Themes**: light / dark / follow system, built-in theme packs, and a theme editor for colors, wallpaper and glass effects.
- **Portable USB edition**, multiple languages (简体中文 / English / Español), automatic update checks.

Each release's notes (in Chinese) list what changed.

## Premium global themes

Regular themes adjust colors, wallpaper, corners and glass effects. A **premium global theme** customizes the whole interface:
every color, fonts, the terminal palette, status colors, corners, wallpaper, glass effects and more. The author makes one just for you,
in the style you want, with your name on it.

**To get a premium global theme, support Lattice and contact the author.** After tipping with one of the codes below, reach out by any of these and describe what you'd like:

- Leave a message in [GitHub Issues](https://github.com/ryzewang1994/Lattice_release/issues) or [Gitee Issues](https://gitee.com/ryze_king/Lattice_release/issues)
- Email **ryzewang1994@gmail.com**
- Leave your WeChat or email in the tip note, and the author will contact you
- Open the "Support Lattice" window in Lattice to see every way to reach the author (email, WeChat, phone)

## Support Lattice

Lattice is completely free. If it helps you, you can leave a tip with the codes below or give it a Star.

<table>
  <tr>
    <td align="center"><img src="docs/donate/alipay.jpg" width="240" alt="Alipay"><br>Alipay</td>
    <td align="center"><img src="docs/donate/wechat.png" width="260" alt="WeChat Pay"><br>WeChat Pay</td>
  </tr>
</table>
