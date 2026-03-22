# Dil Automator For Mac 🚀

Your unified macOS automation control center. Turn all your daily routine workflows (opening native mac apps, chrome websites with delays, and auto-login autofills) into a single click or schedule them to run automatically!

## Download & Install 📥

**[Download the App](https://github.com/dilali-pk/Mac-AutoLogin-Automator/releases/latest)**

1. Go to the [Releases](https://github.com/dilali-pk/Mac-AutoLogin-Automator/releases) page.
2. Download the `Dil_Automator.zip` file.
3. Extract the ZIP file.
4. **Double-click on `install.command`** inside the folder. *(If it asks for permission, right-click -> Open)*.
5. The script will automatically fix the "App is damaged" macOS error, move it to your `/Applications` folder, and launch it!

## Features ✨

- **Tab Navigation**: Beautiful, native-feeling macOS UI with Dashboard, Presets, and Settings.
- **Custom Presets**: Create specific routines (e.g., "Morning Work", "Gaming", "Coding") and run them with one click.
- **Smart Delays**: Add independent delays for App launching, Page loading, and Tab switching.
- **Auto-Fill & Logins**: Automatically triggers your saved browser passwords/credentials.
- **Scheduling**: Set the Automator to run automatically at a specific time of day.
- **Optimized & Fast**: Built for Apple Silicon (`arm64`) with an incredibly small footprint and fast execution speed.

## System Requirements 💻
- **OS:** macOS (Apple Silicon / M-series chips recommended)
- No internet connection required for local app launches.

---

## Troubleshooting 🛠

**Error: "Dil Automator is damaged and can't be opened. You should move it to the Trash."**
This happens because the app isn't signed with an expensive Apple Developer certificate, so macOS Gatekeeper blocks it for being downloaded from the internet.

**How to fix:**
1. Open the **Terminal** app on your Mac.
2. Type the following command and hit Enter:
   ```bash
   xattr -cr "/Applications/Dil Automator.app"
   ```
   *(Note: If you didn't move it to Applications yet, change the path to where your app is located, e.g., `~/Downloads/Dil Automator.app`)*
3. Now open the app normally. It will work!

---

## 👨‍💻 About the Developer

**Dilshad Ali**  
*Passionate Software Engineer & Automation Enthusiast*

Dilshad is dedicated to building smart, efficient, and user-friendly tools that save time and eliminate repetitive daily tasks. With a strong engineering background, his focus is on crafting elegant solutions and scripts that simplify complex workflows for everyone. 

- 🐙 **GitHub:** [@dilali-pk](https://github.com/dilali-pk)
- 💡 If you found this tool helpful, feel free to **Star** the repository!

**Platform Built For:** macOS
