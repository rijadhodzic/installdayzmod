# Overview
This Bash script automates the process of downloading and installing a DayZ mod from the Steam Workshop onto a DayZ server. It ensures proper mod linking, key file handling, and verification for a seamless installation experience.

# Features
- Automated Mod Download: Fetches and installs mods using SteamCMD.
- Symbolic Linking: Creates a link to the downloaded mod for easy management.
- Key File Handling: Copies required key files to the appropriate directory.
- User-Friendly Prompts: Guides the user through the installation process.
- Error Handling: Detects missing dependencies and invalid input.

# Requirements
Ensure you have the following installed:
- SteamCMD
- curl
- A DayZ server with the appropriate directories set up

# Installation
`git clone https://github.com/yourusername/dayz-mod-installer.git`

`cd dayz-mod-installer`

Make the script executable:
`chmod +x install_dayz_mod.sh`

# Usage
Run the script:
`./install_dayz_mod.sh`

# Steps:
The script will check for SteamCMD and curl.

It will ask for your Steam username (saved for future use).

You need to enter the Steam Workshop URL of the mod you want to install.

The script extracts the Mod ID, downloads it, and links it to the server.

If the mod includes keys, they will be copied automatically.

If everything is successful, the mod is ready to use!

# Example
To install a mod from Steam Workshop, use a URL like:

`https://steamcommunity.com/sharedfiles/filedetails/?id=123456789`

# Troubleshooting
- SteamCMD not found: Ensure SteamCMD is installed and accessible in your PATH.
- Invalid Mod ID: Make sure the provided Steam Workshop URL is correct.
- Key files missing: Not all mods include key files. Check manually if needed.

#License
This script is open-source and available for modification and redistribution.

#Author

**fx0 - www.dayzbalkan.com**

# Contributions
Feel free to fork this repository and submit pull requests to improve functionality!
