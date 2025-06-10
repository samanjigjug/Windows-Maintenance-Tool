
# 🖥️ Windows Maintenance Tool

![Version](https://img.shields.io/badge/version-v2.9.4-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)

A powerful, all-in-one Windows maintenance toolkit built entirely in Batch. Designed for power users, sysadmins, and curious tinkerers.

---

## 📸 Screenshot
![8bd720f29d619c518a010b9ba5bc20d3](https://github.com/user-attachments/assets/8440e020-f679-4af5-8f8b-cb5c03dfa667)


---

## ✅ Features

- Run essential repair tools: `SFC`, `DISM`, `CHKDSK`
- Windows Update Fix Utility (new in v2.9.4)
- Auto-detect active network adapters
- Configure DNS (Google, Cloudflare, or custom)
- Clean temp files, Windows logs, and browser cache (optional)
- Generate and save detailed reports:
  - System Info
  - Network Configuration
  - Driver List
- Easy-to-use menu interface with colorful output

---

## ⚙️ Installation

1. Download the `.bat` file.
2. **Right-click → Run as Administrator** (auto-elevation supported).
3. Follow the interactive menu.

> ⚠️ Script output may appear in your system language (e.g. Danish). This is normal.

---

## 📝 Output Files

Saved to your Desktop for easy access:

- `System_Info_YYYY-MM-DD.txt`
- `Network_Info_YYYY-MM-DD.txt`
- `Driver_List_YYYY-MM-DD.txt`

---

## 🧪 Troubleshooting & FAQ

**Q: The script didn’t restart as Admin?**  
A: Make sure UAC is enabled. Right-click the file and select **Run as Administrator**.

**Q: Windows messages show in Danish/German/etc.?**  
A: The script uses native Windows tools. Output language follows your OS install language.

**Q: Browser cache clear crashes?**  
A: This feature is in beta. Report issues with your browser and OS version.

---

## ✍️ Changelog (v2.9.4)

- ➕ Added `choice23`: Reset Windows Update Services tool
- 🚀 Services included: `wuauserv`, `cryptsvc`, `appidsvc`, `bits`
- ♻️ Utility returns to main menu on completion
- 🧼 Small text polish, output clarity improvements

---

## 🤝 Contributing

Pull requests, issues, and feedback are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📜 License

Licensed under the MIT License. See [`LICENSE`](LICENSE) for full details.

---

## 🔗 Related Projects

- [🍎 MSS – Mac Service Script](https://github.com/ios12checker/MSS-Mac-Service-Script)
