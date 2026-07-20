<p align="center">
  <img src="assets/paper-plane-logo.png" width="88" alt="Mail paper-plane logo" />
</p>

<h1 align="center">MailManager</h1>

<p align="center">
  Official Windows desktop distribution for Mail.
</p>

<p align="center">
  <a href="https://www.aillive.xyz/mail/"><strong>Website</strong></a>
  ·
  <a href="https://github.com/amine123max/Mail">Mail Project</a>
  ·
  <a href="README.zh-CN.md">简体中文</a>
  ·
  <a href="https://github.com/amine123max/MailManager/releases/latest">Latest Release</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/amine123max/MailManager?style=flat-square" alt="Latest release" />
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows 10 and 11" />
  <img src="https://img.shields.io/badge/Rust-Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white" alt="Rust and Tauri" />
  <img src="https://img.shields.io/badge/license-MIT-166534?style=flat-square" alt="MIT License" />
</p>

MailManager provides the official Windows builds of Aillive Mail. The application runs in an independent desktop window, supports signed-in and guest workspaces, and connects securely to the Mail service over HTTPS.

## Download

| Package | Recommended use | Download |
| --- | --- | --- |
| NSIS installer | Standard installation | [AilliveMail_x64-setup.exe](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail_x64-setup.exe) |
| MSI installer | Managed Windows deployment | [AilliveMail_x64_zh-CN.msi](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail_x64_zh-CN.msi) |
| Portable executable | Run without installation | [AilliveMail.exe](https://github.com/amine123max/MailManager/releases/latest/download/AilliveMail.exe) |

## Requirements

- Windows 10 or Windows 11, 64-bit
- Microsoft Edge WebView2 Runtime
- Network access to [www.aillive.xyz](https://www.aillive.xyz/mail/)

## Verify a Download

Published hashes are listed in [SHA256SUMS.txt](SHA256SUMS.txt). Verify a file with PowerShell:

```powershell
Get-FileHash .\AilliveMail_x64-setup.exe -Algorithm SHA256
```

## Security

Download packages only from this repository's [Releases](https://github.com/amine123max/MailManager/releases). Current packages are not code-signed, so Windows SmartScreen may display an unknown-publisher warning; verify the SHA-256 hash before running them.

## License
Thanks to the [LINUX DO](https://linux.do/) open-source community for providing a platform for discussion and knowledge sharing.
