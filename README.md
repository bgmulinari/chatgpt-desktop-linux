# ChatGPT Desktop Linux RPM

This repository builds the `chatgpt-desktop` RPM from the latest [`ilysenko/codex-desktop-linux`](https://github.com/ilysenko/codex-desktop-linux) source and upstream ChatGPT Desktop DMG.

The daily workflow excludes the bundled update manager, replaces the single `latest` release, and publishes a signed DNF repository through GitHub Pages.

```bash
# Add the repository
sudo curl -fsSL https://bgmulinari.github.io/chatgpt-desktop-linux/chatgpt-desktop.repo -o /etc/yum.repos.d/chatgpt-desktop.repo

# Install
sudo dnf install chatgpt-desktop
```
