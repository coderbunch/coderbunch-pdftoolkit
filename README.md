# Coderbunch PDF Toolkit - Release Distribution

Official production release binaries and documentation for [Coderbunch PDF Toolkit](https://coderbunch.com).

## 📥 Downloads

Get the latest release from the **[Releases](https://github.com/coderbunch/coderbunch-pdftoolkit/releases/latest)** page:

- **Windows Installer**: [`Coderbunch-PDF-Toolkit-Setup-1.0.0.exe`](https://github.com/coderbunch/coderbunch-pdftoolkit/releases/download/v1.0.0/Coderbunch-PDF-Toolkit-Setup-1.0.0.exe)
- **Windows Portable**: [`Coderbunch-PDF-Toolkit-1.0.0.exe`](https://github.com/coderbunch/coderbunch-pdftoolkit/releases/download/v1.0.0/Coderbunch-PDF-Toolkit-1.0.0.exe)

---

## 🛠️ Installer Return Codes

The Windows installer is compiled with standard NSIS (Nullsoft Scriptable Install System). It supports unattended/silent installations via the `/S` flag.

The installer returns the following standard exit codes:

| Return Code | Status | Description |
|---|---|---|
| `0` | **Success** | The application was successfully installed or updated. |
| `1` | **Cancelled** | Installation was cancelled or aborted by the user. |
| `2` | **Script Error** | Installation aborted due to an unexpected system error or permission denial. |
| `1602` | **User Cancelled** | Windows Installer / MSI bridge user cancellation. |
| `1618` | **In Progress** | Another installation is currently in progress. |
| `112` | **Disk Full** | Insufficient hard disk storage space to complete the installation. |

For enterprise deployment support, visit [coderbunch.com](https://coderbunch.com).

---

### ✨ Features
- 100% Free & Offline Desktop PDF Suite
- Multi-File Merge, Split, and Organize
- Visual e-Sign Studio & 🔐 USB Token (DSC) Cryptographic Digital Signing
- Watermarks, Running Page Numbers, and Images ↔ PDF Conversion
- Zero Cloud Uploads • 100% Local Privacy

Website: [coderbunch.com](https://coderbunch.com)
