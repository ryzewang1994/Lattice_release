# Lattice 发布包

Lattice（梭哈）是一个 Windows 文件管理器。这个仓库**只放安装包**，不含源代码。

## 下载

到 [Releases](https://github.com/ryzewang1994/Lattice_release/releases/latest) 下载最新的 **LatticeSetup.exe**，运行即可安装或原地升级。

每个版本的附件里还有一份 `update.json`（版本号、体积、SHA-256），和自建更新服务器上的清单是同一个文件；发布说明末尾也写着安装包的 SHA-256，可以自行核对。

## 在程序里使用这个发布源

设置 → 系统 → 检查更新 → 选择 **GitHub**。程序会从这里读取最新版本，下载后按 SHA-256 校验再安装。

## 系统要求

Windows 10 / 11（x64）。
