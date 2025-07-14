# 🛠️ HDPlayerDumper Tool — Description
HDPlayerDumper is a lightweight, portable PowerShell-based utility that captures a full memory dump of the HD-Player.exe process (used by Android emulators like BlueStacks or MSI App Player). It is designed for cheat detection, reverse engineering, and forensic analysis.

# 🔍 What It Does
Detects if HD-Player.exe is running.

Uses procdump.exe (Microsoft Sysinternals) to create a .dmp file containing the entire memory of the process.

Saves the dump to a local dumps\ folder inside the tool's directory.

Works fully offline and without any installation.

# 🚀 Key Features

✅ Fully Portable	No install, no registry usage — works from USB or any folder
🧠 Forensics Ready	Dump can be analyzed in tools like WinDbg or strings.exe
🔐 Anti-Cheat Utility	Useful for inspecting injected DLLs, suspicious memory patterns
🔄 Automatically Timestamped	Each dump is named using current date & time
🖥️ Works on Any Windows PC	Supports Windows 10/11 (64-bit), no admin install needed
