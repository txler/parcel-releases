# Parcel for Windows

A desktop order tracker for Target and Pokémon Center orders, with Gmail and iCloud inbox syncing, tracking, an arrival calendar, and address labels.

## Download and install

[Download Parcel Setup.exe](https://github.com/txler/parcel-releases/releases/latest/download/Parcel%20Setup.exe)

1. If you already use Parcel, choose **Quit Parcel** from its tray menu or **Stop Parcel** from the Start menu.
2. Open the downloaded **Parcel Setup.exe** and install for your Windows user.
3. Open **Parcel** from your desktop or Start menu. No Python or Node installation is required.
4. New users connect their own inboxes. Existing users keep their saved workspace.

Version 1.12.0 introduces the built-in updater. Older versions need this one manual installation. Afterward, Parcel automatically checks for new app versions while running. Follow its update prompt to download and restart, or use **Check for app updates** from the tray menu. Save edits and finish syncing before restarting.

## Your saved data

Orders, inbox connections, address labels, and preferences remain in your private Windows-user workspace. App downloads contain no connected inboxes, saved orders, addresses, app passwords, or release signing keys. This repository distributes the app and signed update metadata.

App-update signatures are verified by the built-in updater. Windows Authenticode publisher certification is not configured for this beta.
