# 🛡️ GS

> Batch script to **import security policy** via LGPO (Local Group Policy Object) using `GSecurity.inf`.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⚙️ **LGPO Import** | Imports `GSecurity.inf` security template |
| 🔒 **Auto-Elevation** | UAC elevation via fsutil/vbs fallback |
| 📋 **Local Policy** | Applies security settings to local machine |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **LGPO** | [Microsoft Security Compliance Toolkit](https://www.microsoft.com/en-us/download/details.aspx?id=55319) — `lgpo.exe` in PATH |
| **Privileges** | Administrator |

---

## 🚀 Usage

```cmd
:: Run Setup.bat as Administrator
Setup.bat
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
