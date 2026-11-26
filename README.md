# Zimlo for Windows

Record conversations, transcribe audio, and keep your notes and meeting screenshots together. Use your Zimlo account across Windows, Mac, and iPhone.

[Download Zimlo for Windows](https://github.com/jaywoofter/Zimlo-Releases/releases/download/windows-v1.0.1/Zimlo-Setup-1.0.1-x64.exe)

Version 1.0.1 · Windows x64 installer for Intel and AMD PCs. Microsoft Foundry Local transcription requires Windows 11 24H2 or later. An ARM64 installer is not included in this release.

## Install

1. Download and run **Zimlo-Setup-1.0.1-x64.exe**.
2. Follow the installer, then open Zimlo from your desktop or Start menu. Installation is for your Windows account.
3. If Windows reports a missing Microsoft C++ runtime, install the [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe) and reopen Zimlo.

The installer is currently unsigned, so Windows may display an unrecognized-publisher warning. Download only from this repository or the links on [zimlo.io](https://zimlo.io/download/).

## Automatic updates

Installed Zimlo checks for new versions after launch and every six hours, and downloads updates automatically. When an update is ready, choose **Settings → General → Restart to update**. Installation waits until recording, transcription, sync, and other work are finished. You can also choose **Check for updates** at any time.

Closing Zimlo normally does not install an update. A failed check or download leaves your current version available and can be retried.

If you previously downloaded a portable ZIP, run the installer once to enable updates. Finish active work and close the old app first. The installer uses your existing library and settings in `%APPDATA%\Zimlo`; preserve that folder. Use the new desktop or Start menu shortcut afterward, and remove any separate old portable application folder when you have verified your library.

## Get started

- **Free local transcription:** In **Settings → Transcription**, prepare Microsoft Foundry. The model downloads once, then transcription runs on your PC after recording.
- **Zimlo account:** Open **Settings → Account & sync** to sign in or create and verify an account. Use the same Zimlo account on your devices to access its plan and shared allowance.
- **Zimlo Live:** Open **Settings → Zimlo Live** and choose a plan. Stripe handles payment in your browser. Return to Zimlo and refresh your allowance afterward.
- **Library sync:** Connect the same Google Drive account and Zimlo account used on your other devices. Audio transfer is optional. Library sync and the Live subscription are separate features.

| Zimlo Live plan | Monthly price (USD) | Shared monthly transcription allowance |
| --- | --- | --- |
| Starter | $10 | 10 hours |
| Plus | $30 | 40 hours |
| Pro | $50 | 80 hours |

The allowance belongs to your Zimlo account and is shared across devices. Existing Apple subscriptions remain managed through Apple. New Windows subscriptions use Stripe; **Manage Stripe subscription** opens your billing portal.

This repository contains public installers and update files. Application source and publisher credentials remain private.
