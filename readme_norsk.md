Clean Connect Launcher
🚀 A modern and user-friendly Windows launcher designed for all FiveM servers. The launcher provides players with quick access, maintenance, troubleshooting, and automatic client updates, compatible with any FiveM server regardless of the roleplay community or configuration.
🧩 Features
✅ Deletion of FiveM cache and crash logs (disabled by default, can be enabled via settings)
✅ Display of server status (FiveM/Cfx platform)
✅ Displays system status and performance info (CPU, RAM, etc.)
✅ Simple GUI built with Windows Forms
✅ Automatic ping and latency display for the selected server
✅ Multi-server support for users playing on more than one FiveM server
✅ F3 button to switch servers when multiple servers are added
✅ F3 button to switch servers when multiple servers are added
🎮 Grafikkinnstillinger
✅ Programmet lar deg enkelt konfigurere grafikk- og lydinnstillinger for FiveM/GTA V direkte fra launcheren:
Førstegangsoppsett

Under første oppstart vil du se en "Graphics"-knapp
Klikk for å velge mellom forhåndsdefinerte presets:
Lav ✅ - Optimal for svake maskiner
Medium ✅ - Balanse mellom ytelse og kvalitet
Høy ✅ - For maskiner med god ytelse
Ultra ✅ - Max kvalitet (kun for kraftige maskiner)



Etter oppsett

Åpne innstillinger via hovedvinduet
Klikk "Graphics"-knappen
Velg ønsket preset og bekreft

Viktig merknad
⚠️ For at endringene skal aktiveres fullt ut:

Start GTA V i historiemodus etter endring
Åpne innstillinger i FiveM og trykk "OK" for å bekrefte

Hva endres?
Programmet oppdaterer følgende i gta5_settings.xml:

Skjermoppløsning og vindusmodus ✅
Skyggekvalitet ✅
Teksturdetaljer ✅
Vann- og gresseffekter ✅
Anti-aliasing ✅
Lydinnstillinger (inkl. mikrofon) ✅

🖼️  
For streamere
🎥 Bruk "Medium" eller "Høy"-preset for:

Stabil ytelse under streaming ✅
God bildekvalitet for seerne ✅
Balansert ressursbruk ✅
Anbefalte innstillinger:
Deaktiver dybdeskarphet (DoF) for bedre lesbarhet ✅
Bruk FXAA istedenfor TXAA for mindre "ghosting" ✅



Hardware-anbefalinger



Grafikkortklasse
Anbefalt preset



Integrert grafikk
Lav ✅


GTX 1060/RX 580
Medium ✅


RTX 2060/RX 5700
Høy ✅


RTX 3070+
Ultra ✅


📥 Download
Find the latest version here:  👉 GitHub ReleasesInstaller file: CleanConnectLauncher_setup.exe
📦 Installation
✅ Multi-language support (🇳🇴 Norwegian / 🇬🇧 English)
✅ Automatic and manual update checks via GitHub Releases
✅ Optional initial setup (select server, port, and language)
Download the .exe file from the releases pageRun the installer file, which will automatically install .NET 8 if it is not already present on your systemOn first launch, you’ll be prompted to select server and languageThe launcher automatically starts the server after setup
⚙️ Technology
.NET Framework / .NET 8 - Windows Forms (WinForms) - C# - GitHub API for version checking
🔁 Updates
On startup, the launcher automatically checks for new versions. You can also manually click "Check for updates" in the settings.Updates are fetched directly from this GitHub page, and the installer starts automatically.
🗃️ Folder Structure and Cache Cleanup
The following folders can be cleared via the launcher:
FiveM\FiveM.app\data\server-cache-priv
FiveM\FiveM.app\data\game-storage
FiveM\FiveM.app\data\nui-storage (designed to preserve user login data, so you don’t need to re-authenticate with your Cfx account in FiveM after clearing)
FiveM\FiveM.app\data\server-cache
FiveM\FiveM.app\crashes
FiveM\FiveM.app\data\cache
GTA5 settings file (gta5_settings.xml)
🛠️ Troubleshooting
Suggestions for troubleshooting:
Ensure FiveM is properly installed.
Use launcher settings to clear cache, crashes, and other FiveM files.
If the problem persists, restart your PC and try again.
Reinstall FiveM with user backup (if you were logged in with a Cfx account, no re-authentication is required as the launcher ensures your data is restored correctly after reinstallation).
Install / Reinstall FiveM:
Status: Ready to install
🛠️ Planned Improvements
🛠️ Suggestions for improvements are welcome! Please share your ideas via an issue.
💬 Contact and Contributions
This is an open-source project. Have suggestions, improvements.
Create an issueOr submit a pull request
If you would like support for additional languages, please contact me via an issue and specify which language you would like to see added.
📸 Screenshots
Below are some screenshots of the Clean Connect Launcher in action:





© 2025 – Developed with ❤️ for the FiveM community by Nightbox RP.
