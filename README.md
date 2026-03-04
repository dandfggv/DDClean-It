# DDCleanIt – System Cleaner

**Version:** 1.0.0  
**Publisher:** DEXPLOSION Corp.  
**Platform:** Windows 10 / 11 (64‑bit)  
**Build Type:** Qt 6.10.2 (MinGW 64‑bit)

---

## 1. About DDCleanIt

DDCleanIt is a lightweight Windows optimization tool designed to clean temporary files, manage startup programs, inspect services, and improve system responsiveness. It uses a modern Qt‑based interface and performs safe cleaning operations that do not modify protected system files.

---

## 2. Features

### Cleaner
- Temporary files cleanup  
- Windows Update leftover cleanup  
- Crash dump cleanup  
- Log cleanup  
- Prefetch cleanup  
- Thumbnail cache cleanup  
- Browser cache/history cleanup (Chrome, Edge, Firefox)

### Startup Manager
- View startup programs  
- Enable/disable registry startup entries  
- Enable/disable Startup folder shortcuts  

### Services Viewer
- View running/stopped services  
- Display service descriptions and status  

### Settings
- Start with Windows (registry Run key)  
- Open logs folder  
- Reset app statistics and settings  

### Dashboard
- Overview of system cleaning status  
- Summary of last clean and total space freed  

---

## 3. Installation

1. Download the installer from the **Releases** page.  
2. Run `DDCleanIt_Setup.exe`.  
3. Choose the installation folder (default: `C:\Program Files\DDCleanIt`).  
4. Select optional tasks:
   - Create desktop shortcut  
   - Start with Windows  
5. Click **Install**.  
6. (Optional) Launch DDCleanIt after installation.

---

## 4. Uninstalling

1. Open **Control Panel → Programs and Features**.  
2. Select **DDCleanIt**.  
3. Click **Uninstall**.

The uninstaller removes:
- Program files  
- Logs folder  
- Temporary data  

---

## 5. Logs & Data Storage

DDCleanIt stores logs and settings in:

%AppData%\DDCleanIt\
├─ DDCleanItLogs\
└─ settings.ini

These files are safe to delete.

---

## 6. Known Limitations

- DDCleanIt does **not** modify or delete files in:
  - `C:\Windows`
  - `C:\Windows\System32`
  - Protected OS directories

- Deep cleaning of system components is intentionally restricted for safety and stability.

---

## 7. Support

For issues, suggestions, or feature requests, contact:

**DEXPLOSION Corp.**  
Support Email: *(Dandusnehith9@gmail.com)*

---

## 8. License

This software is provided **“as‑is”** without warranty of any kind.  
You may distribute the installer freely.

---

## 9. Releases

You can go to the **Releases** section of this repository to download the latest installer.

---

## Thank You

Thank you for using DDCleanIt!

