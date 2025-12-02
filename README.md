# NekoFastflagsSaver

NekoFastflagsSaver is an application for editing fast variables in Roblox Windows client in real-time without limitations.

🔗 **GitHub Repository:** https://github.com/rycoxdesu/NekoExternaLC

## ⚡ Main Features

This application allows you to:

- **Edit Fast Variables Real-time** - Modify Roblox fast variables while the game is running
- **Auto-Detect Roblox Instances** - Automatically detects all active Roblox instances
- **Apply to All Instances** - Changes are applied to all Roblox instances simultaneously
- **Desktop App with GUI** - Modern and easy-to-use interface

## 🎯 Features

- ✅ Edit fast variables in real-time without restarting Roblox
- ✅ Automatically detects all running Roblox instances
- ✅ Applies changes to both existing and new instances
- ✅ Supports various types of fast variables (boolean, integer, string, log)
- ✅ No limitations when editing fast variables
- ✅ Desktop App with modern GUI (Electron)
- ✅ Easy-to-use interface

## ⚠️ Important Warning

**False Positive Detection**: This application may be flagged by some antivirus software as a false positive. This happens because the application uses Windows memory manipulation APIs (`ReadProcessMemory`/`WriteProcessMemory`) to modify Roblox client memory for game configuration purposes.

**Why it's flagged:**
- Uses legitimate Windows APIs commonly used by game modding tools
- Heuristic detection may flag memory manipulation as potentially suspicious
- This is a **false positive** - the application is safe and open source

**What this application does NOT do:**
- ❌ Does NOT download or install malware
- ❌ Does NOT steal data or credentials
- ❌ Does NOT modify system files
- ❌ Does NOT perform any malicious activities

**What this application does:**
- ✅ Only modifies Roblox client memory for game configuration
- ✅ Only targets `RobloxPlayerBeta.exe` process
- ✅ Uses legitimate Windows APIs
- ✅ Source code is publicly available on GitHub

If your antivirus flags this application, you can safely add it to exclusions. See [SECURITY.md](SECURITY.md) for more information.

## 📝 Notes

- Application only works with Roblox Windows client
- Fast variable changes are temporary (will reset when Roblox is closed)

---

## 🔗 Links

- **GitHub Repository:** https://github.com/rycoxdesu/NekoExternaLC
- **Issues & Support:** https://github.com/rycoxdesu/NekoExternaLC/issues
- **Security Information:** [SECURITY.md](SECURITY.md)

---

**Copyright © 2025 Neko's Circle. All rights reserved.**

**Open Source Project** - This project is open source and available on GitHub.

**License:** This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
