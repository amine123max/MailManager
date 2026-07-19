<p align="center">
  <img src="assets/paper-plane-logo.png" width="88" alt="Mail 纸飞机图标" />
</p>

<h1 align="center">MailManager</h1>

<p align="center">
  Mail 官方 Windows 桌面端发布仓库。
</p>

<p align="center">
  <a href="https://www.aillive.xyz/mail/"><strong>官方网站</strong></a>
  ·
  <a href="https://github.com/amine123max/Mail">Mail 项目</a>
  ·
  <a href="README.md">English</a>
  ·
  <a href="https://github.com/amine123max/MailManager/releases/latest">最新版本</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/amine123max/MailManager?style=flat-square" alt="最新版本" />
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows 10 与 11" />
  <img src="https://img.shields.io/badge/Rust-Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white" alt="Rust 与 Tauri" />
  <img src="https://img.shields.io/badge/license-MIT-166534?style=flat-square" alt="MIT 开源协议" />
</p>

MailManager 用于发布 Aillive Mail 的官方 Windows 桌面版本。应用以独立桌面窗口运行，支持登录用户与访客工作区，并通过 HTTPS 安全连接 Mail 服务。

## 下载

| 文件 | 适用场景 | 下载 |
| --- | --- | --- |
| NSIS 安装程序 | 常规安装，推荐使用 | [AilliveMail_x64-setup.exe](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail_x64-setup.exe) |
| MSI 安装程序 | Windows 管理部署 | [AilliveMail_x64_zh-CN.msi](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail_x64_zh-CN.msi) |
| 便携版 | 无需安装直接运行 | [AilliveMail.exe](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail.exe) |

## 系统要求

- 64 位 Windows 10 或 Windows 11
- Microsoft Edge WebView2 Runtime
- 能够访问 [www.aillive.xyz](https://www.aillive.xyz/mail/)

## 文件校验

发布文件的哈希值见 [SHA256SUMS.txt](SHA256SUMS.txt)。可使用 PowerShell 校验：

```powershell
Get-FileHash .\AilliveMail_x64-setup.exe -Algorithm SHA256
```

## 安全说明

请仅从本仓库的 [Releases](https://github.com/amine123max/MailManager/releases) 下载。当前安装包尚未进行代码签名，Windows SmartScreen 可能提示未知发布者；运行前请核对 SHA-256 哈希值。

## 开源协议

项目使用 [MIT License](LICENSE) 发布。
