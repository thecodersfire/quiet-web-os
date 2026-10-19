# Built-in features for quiet-web-os

Purpose: privacy-conscious browsing

1. **organize a personal routine** — run quiet-web-os-workspace. It creates ~/Documents/quiet-web-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run quiet-web-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/quiet-web-os-session-plans/.
3. **check routine readiness** — run quiet-web-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/quiet-web-os-workspace features/quiet-web-os-plan features/quiet-web-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for privacy-conscious browsing:

1. **VSCodium** — com.vscodium.codium
2. **GNOME Builder** — org.gnome.Builder
3. **Wireshark** — org.wireshark.Wireshark

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for privacy-conscious browsing:

1. **Thonny** — write and debug Python code (org.thonny.Thonny)
2. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
3. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
4. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
