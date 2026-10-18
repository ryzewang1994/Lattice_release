# Lattice

**中文** | [English](#english)

Lattice 是一个 Windows 原生文件管理器，用 C++ 和 Win32 / Direct2D 从头写成：单个 exe、启动快、占用小，**完全免费、没有广告**。

这个仓库是 Lattice 的发布仓，只放安装包和更新清单。

## 下载

到 [GitHub Releases](https://github.com/ryzewang1994/Lattice_release/releases/latest) 或 [Gitee 发行版](https://gitee.com/ryze_king/Lattice_release/releases)（国内更快）下载最新的 **LatticeSetup.exe**，运行即可安装或原地升级。

每个版本的附件里还有一份 `update.json`（版本号、体积、SHA-256），发布说明末尾也写着安装包的 SHA-256，可以自行核对。
程序里"设置 → 系统 → 检查更新"可以选 GitHub 或 Gitee 作为更新来源。

系统要求：Windows 10 / 11（x64）。

## 能做什么

- **多标签 + 多栏**：标签页、标签组、一键清理；最多四栏并排，拖动文件在栏之间复制移动。
- **快**：主页秒开，全盘索引搜索（有管理员权限时直读 NTFS 文件表），地址栏即搜即达。
- **终端内置**：ConPTY + libvterm 的真终端（cmd / PowerShell / Git Bash / WSL），
  底部面板或整页终端；目录和文件列表双向跟随；分屏、广播输入、快捷命令、灰字补全、输出高亮、会话录制与回放。
- **SSH / SFTP**：保存的服务器一点就连，密钥 / ssh-agent 登录、跳板机、端口转发；远程目录和终端 `cd` 双向跟随。
- **网络位置与网盘**：SMB、FTP、SFTP、WebDAV、S3 兼容对象存储；手机、相机（MTP）。
- **自己的传输引擎**：复制、移动、删除、压缩、解压都有进度和动画，大文件自动分卷越过 FAT32 的 4GB 限制。
- **检测占用**：右键文件 →"检测占用"，看清是哪个程序、哪条进程链锁住了文件，并按推荐方式一键解锁。
- **磁盘空间分析**：矩形树图看清谁占了空间。
- **预览**：图片、视频、音乐、PDF、Markdown、代码、压缩包内部，侧边栏直接看；图片画廊、音乐播放器、书架。
- **右键菜单与自定义命令**：重新设计的右键菜单，自己加常用命令。
- **主题**：浅色 / 深色 / 跟随系统，内置主题包，主题编辑器自己调配色、壁纸和玻璃质感。
- **U 盘便携版**、多语言（简体中文 / English / Español）、自动检查更新。

每个版本改了什么，见各版本的发布说明。

## 高阶全局主题

普通主题可以调整配色、壁纸、圆角和玻璃质感。**高阶全局主题**能定制整个界面：所有颜色、字体、终端配色、状态色、
圆角、壁纸、玻璃质感……由作者按你想要的风格单独制作，主题里写着你的名字。

**高阶全局主题支持 Lattice 可联系作者获取**：扫下面的码打赏后，通过以下任一方式联系作者，说说你想要的样子：

- 在 [GitHub Issues](https://github.com/ryzewang1994/Lattice_release/issues) 或 [Gitee Issues](https://gitee.com/ryze_king/Lattice_release/issues) 留言
- 发邮件到 **ryzewang1994@gmail.com**
- 打赏时在备注里留下你的微信或邮箱，作者会主动联系你
- 在 Lattice 里打开"支持 Lattice"窗口，能看到全部联系方式（邮箱、微信、电话）

## 支持 Lattice

Lattice 完全免费。如果它帮到了你，欢迎扫码打赏，或者点个 Star。

<table>
  <tr>
    <td align="center"><img src="docs/donate/alipay.jpg" width="240" alt="支付宝打赏码"><br>支付宝</td>
    <td align="center"><img src="docs/donate/wechat.png" width="260" alt="微信打赏码"><br>微信支付</td>
  </tr>
</table>

---

<a id="english"></a>

# Lattice (English)

[中文](#lattice) | **English**

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
