# Zimlo for Windows

Record conversations, transcribe audio, and keep your notes and meeting screenshots together.

[Download Zimlo 0.1.2 for Windows x64](https://github.com/jaywoofter/Zimlo-Releases/releases/download/windows-v0.1.2/Zimlo-Windows-x64-0.1.2.zip)

This download is for Intel and AMD PCs. Use Windows 11 24H2 or later for Microsoft Foundry Local transcription. An ARM64 release is not included here.

## Install

1. Download the ZIP and choose **Extract All**.
2. Keep the extracted folder together and open **Zimlo.exe**. You can move the whole folder to a permanent location and create a shortcut to the EXE.
3. If Windows reports a missing Microsoft C++ runtime, install the [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe) and reopen Zimlo.

This early Windows build is unsigned. Windows may show a security prompt. Use the download linked from Zimlo's official website and this repository.

## Get started

- **Free local transcription:** In **Settings > Transcription**, prepare Microsoft Foundry. The model downloads once, then transcription runs on your PC after recording.
- **Zimlo account:** Open **Settings > Account & sync** to sign in or create and verify an account. Use your existing Zimlo account to retain its plan and allowance.
- **Zimlo Live:** Open **Settings > Zimlo Live** and choose a plan. Stripe handles payment in your browser. Return to Zimlo and select **Refresh allowance** afterward.
- **Library sync:** Connect the same Google Drive account and Zimlo account used on your other device. Audio transfer is optional. Library sync and the Live subscription are separate features.

| Zimlo Live plan | Monthly price (USD) | Shared monthly transcription allowance |
| --- | --- | --- |
| Starter | $10 | 10 hours |
| Plus | $30 | 40 hours |
| Pro | $50 | 80 hours |

The allowance belongs to your Zimlo account and is shared across devices. Existing Apple subscriptions remain managed through Apple. New Windows subscriptions use Stripe; **Manage Stripe subscription** opens your billing portal.

## Update an existing installation

Updates are manual in this release. Finish recording, transcription, and sync, then close Zimlo. Extract the new ZIP into a new folder and replace the old application folder with the complete new folder. Keep the EXE, DLLs, and `resources` folder together.

Your library and settings are stored separately in `%APPDATA%\Zimlo`. Preserve that folder when updating. The application does not install updates automatically.

See the [0.1.2 release notes](https://github.com/jaywoofter/Zimlo-Releases/releases/tag/windows-v0.1.2) for verification and current limitations.
