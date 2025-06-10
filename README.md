# Windows Maintenance Tool 🚀

![Version](https://img.shields.io/badge/version-v2.9.3-brightgreen)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)

A powerful Windows maintenance toolkit in a single Batch script.

## 📸 Screenshot
![d8753738c59affb607ea5d821a1f1c83](https://github.com/user-attachments/assets/6ce253bb-5670-4070-94e3-95c3f9281867)


## ✅ Features
- Run SFC, DISM, CHKDSK, Windows Update repair...
- Auto-detect active network adapters
- Set DNS (Google, Cloudflare, Custom)
- Generate system, network, driver reports
- Clean temp files and optionally browser cache

## 📥 Installation
1. Download `.bat` and run **as Administrator**.
2. Auto-elevation is built in — script restarts itself if needed.
3. Choose your action from the menu.

## 📝 Outputs
Report files saved to your Desktop:
- System_Info_*.txt  
- Network_Info_*.txt  
- Driver_List_*.txt

## 🧪 Common Issues & FAQ
**Q: Script didn't restart as Admin?**  
A: Ensure UAC is enabled and `.bat` is right-clicked → Run as administrator.

**Q: "Clear Browser Cache" crashes?**  
A: Still under testing — feel free to submit an issue with browser and Windows version.

## 🤝 Contributing
PRs, issues and suggestions are welcome—see the [CONTRIBUTING.md]() for details.

## 📜 License
MIT License — see `LICENSE` file.

## 📎 Related Projects
- [macOS Service Script (MSS)](...)
https://github.com/ios12checker/MSS-Mac-Service-Script
