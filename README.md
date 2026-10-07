# Microsoft Activaiton ToolKit 🚀

A lightweight, one-click Windows executable tool designed to automatically request Administrator privileges and run the PowerShell activation script seamlessly with a custom icon.

---

## ✨ Features
- **Auto-Elevation:** Automatically prompts for UAC (Administrator) permissions upon launch.
- **Custom Branding:** Built with a clean custom `.ico` file.
- **Instant Execution:** No need to manually open PowerShell or type commands; just a simple double-click.

---

## 📥 How to Use
1. Go to the **Releases** section on the right side of this repository.
2. Download the latest `activate.exe` file.
3. Double-click the downloaded `.exe` file.
4. Allow Administrator permissions when prompted, and the script will run automatically.

---

## 🛠️ How It Was Made
- **Script Used:** PowerShell (`irm https://get.activated.win | iex`)
- **Compilation Tool:** PS2EXE (GUI/CLI) with the `-RequireAdmin` and `-Icon` parameters.

---

## ⚠️ Disclaimer
This tool is provided for personal utility and educational purposes only. Use it at your own discretion.
