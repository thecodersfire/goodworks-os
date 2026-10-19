# Built-in features for goodworks-os

Purpose: nonprofit administration

1. **organize work and records** — run goodworks-os-workspace. It creates ~/Documents/goodworks-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run goodworks-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/goodworks-os-session-plans/.
3. **check records and task readiness** — run goodworks-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/goodworks-os-workspace features/goodworks-os-plan features/goodworks-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for nonprofit administration:

1. **GNOME Calendar** — org.gnome.Calendar
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
