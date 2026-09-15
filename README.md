<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/coordant-light.svg">
    <img src="brand/coordant-dark.svg" alt="Coordant" width="360">
  </picture>
</p>

<p align="center">Your agents. One workspace.</p>
<p align="center"><a href="https://github.com/null-x-0/coordant-releases/releases/latest"><strong>Download Coordant →</strong></a> · <a href="https://github.com/null-x-0/coordant-releases/releases">Release notes</a> · <a href="https://github.com/null-x-0/coordant-releases/issues">Report an issue</a></p>

Coordant brings your coding agents, terminals, and project tools into a desktop workspace.

- Work with Codex, Grok, OpenCode, Cursor, and Claude Code using your own CLI accounts.
- Switch between chat and terminal views of the same conversation.
- Arrange sessions side by side and coordinate work across agents.
- Keep browser previews, Git tools, schedules, and usage close to your work.
- Answer agent questions in Chat, track session tokens and reference costs, and use the coffee button to keep work running while the screen is locked.
- Choose among nineteen palettes, including Coordant Dark, Coordant Light, and Obsidian, and set your preferred time zone and regional format in Settings → Appearance.

## Install

Download the installer for your computer from the [latest release](https://github.com/null-x-0/coordant-releases/releases/latest).

- **macOS 13 or later:** choose the **mac-arm64.dmg** for Apple silicon or **mac-x64.dmg** for Intel. Open the DMG and drag **Coordant** into **Applications**. Find your chip under Apple menu → About This Mac.
- **Windows x64:** open **win-x64.exe** and follow the installer. Install Git for Windows to use project cloning, Git review, and providers that require Git Bash.
- **Linux x64:** use **linux-x86_64.AppImage**, mark it executable, and open it; or install **linux-amd64.deb** with your package manager. The AppImage needs FUSE support. Git is required for Git features.

Open Settings and choose **Install CLI** for the provider you want to use, then sign in to your account. Existing CLI installations are detected automatically. Open a project or start a No project chat. Some CLIs require a one-time workspace trust confirmation in Terminal.

Coordant uses your own provider accounts. A GitHub account is not required to download the app or receive updates.

### First launch on macOS

This early release is signed with Coordant's release identity but is not Apple-notarized. If macOS blocks it, first attempt to open the app, then use **System Settings → Privacy & Security → Open Anyway**. [Apple's instructions](https://support.apple.com/guide/mac-help/mh40616/mac) explain this approval. Keep macOS security protections enabled.

### Clone a GitHub repository

Choose **Clone from GitHub**. Coordant detects local GitHub CLI sign-ins and supported Git credential connections. Choose a connection, then search its accessible repositories, including shared and organization repositories. Use **Load more repositories** for additional results. You can also enter a repository URL or SSH address directly. Selecting a connection does not switch your global GitHub account.

## Updates

Coordant checks for new releases when it opens and periodically while running. Use **Settings → Updates**, or click the version number at the bottom left, to check manually. Choose **Download update**, then **Restart to update** when ready. Coordant asks you to finish active work and closes idle sessions automatically before restarting. Your projects and conversation history stay in place.

Linux AppImage installations use the in-app updater. Debian installations update through their package workflow.

## About this repository

This repository contains official installers, release notes, and public branding. Application development and source history are maintained separately.
