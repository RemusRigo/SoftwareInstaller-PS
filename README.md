# Software Installer

A PowerShell GIU script to install software via the winget package manager.

## 

## Authors

* [@remusrigo](https://github.com/RemusRigo)
* [@remusrigo](https://sourceforge.net/u/remusrigo/profile)

## 

## Installation

Just right click on "Software Installer.ps1 and select "Run with PowerShell" or run the "Software Installer.bat"

Files:

* Software Installer.bat: start the script
* Software Installer.ps1: main PowerShell script
* Software.csv: software database in csv format
* Software.xlsx: software database in Excel format
* Utilities\\InstallChocolatey.ps1: PowerShell script to install Chocolatey Package Manager
* Res\\\*.png: PNG Icons



## Roadmap

2025-07-30: Reorganized source code (grouped GUI components / functions /  methods )

2025-07-29: Rewrote the function to check if App is installed

2025-07-28: added Download button

2025-06-03: added image for the Refresh Button

2025-05-15: added presets (custom CSV lists)

2025-05-15: added Context Menu for ListView Right-Click on the Category column

2025-05-15: added tooltips

2025-05-15: added procedure to convert from Excel to CSV

2025-05-15: added label to display greeting and total of items loaded

2025-05-08: added category

2025-05-08: added settings for winget / scoop / Chocolatey (install and update only)

2025-04-11: replace local DB with csv file

2025-03-30: create local DB

2025-03-16: Project started

