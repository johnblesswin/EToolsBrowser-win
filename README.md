# ETools Browser Suite (Windows)

Official Windows distribution packages, patches, and version manifests for the **ETools Browser Suite** — engineered for SRM Institute of Science and Technology (SRMIST).

---

## 📦 Distribution Packages (v1.0.4 "Mars")

| Application | Mode | Installer (`download_url`) | Delta Patch (`patch_url`) | Description |
| :--- | :--- | :--- | :--- | :--- |
| **EEB** | **Exam Mode** | [`EEB_Setup.exe`](EEB_Setup.exe) (~186 MB) | [`EEB_patch.zip`](EEB_patch.zip) (~7.1 MB) | High-stakes locked-down examination browser with active process containment, VM detection, and clipboard protection. |
| **EPB** | **Practice Mode** | [`EPB_Setup.exe`](EPB_Setup.exe) (~186 MB) | [`EPB_patch.zip`](EPB_patch.zip) (~7.0 MB) | Academic practice and laboratory evaluation browser with educational whitelisting and self-healing shell. |

---

## 🔄 Automatic Update Manifest

The browser automatically checks for updates using [`version.json`](version.json):
* **Manifest URL:** `https://dld.srmist.edu.in/apps/ebrowsers/win/version.json`
* Existing installations receive lightweight in-place micro-patches (~7 MB) without requiring full re-installation.

---

## 🚀 Installation

### Interactive GUI Installation
Run `EEB_Setup.exe` or `EPB_Setup.exe` and click **Install**. The setup installs securely and creates desktop and Start Menu shortcuts automatically.

### Silent / Enterprise Lab Deployment
For IT administrators deploying across campus computer labs:
```cmd
:: Silent installation
EEB_Setup.exe /S

:: Silent installation with immediate launch
EEB_Setup.exe /S /LAUNCH

:: Silent uninstall
EEB_Setup.exe /uninstall /S
```

---

## 🛡️ Technical Specifications

* **Release Version:** `v1.0.4` (Mars Hardened)
* **Application Framework:** `JBW Chromium`
* **Security Engine:** `JOHN316 Shield`
* **Architecture:** 64-bit (x64)
* **Supported OS:** Windows 10 / Windows 11

---

## 📧 Support & Inquiries

For technical support or institutional deployment inquiries:  
**Directorate of Learning & Development (DLD)**  
SRM Institute of Science and Technology  
Email: [`etools.dld@srmist.edu.in`](mailto:etools.dld@srmist.edu.in)
