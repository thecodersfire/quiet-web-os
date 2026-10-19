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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **GIMP** (org.gimp.GIMP) — edit raster graphics and textures.
14. **Krita** (org.kde.krita) — paint digital illustrations.
15. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
2. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
3. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
4. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
7. **Ark** (org.kde.ark) — open and create common project archive files.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
12. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
13. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for privacy-conscious browsing. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
2. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
3. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
4. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
5. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
6. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
7. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
8. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
9. **Merkuro** (org.kde.merkuro) — Organize calendars, contacts, and tasks.
10. **KClock** (org.kde.kclock) — Use alarms, timers, and a stopwatch.
11. **LibreOffice** (org.libreoffice.LibreOffice) — Write reports, manage tables, and prepare presentations.
12. **Document Scanner** (org.gnome.SimpleScan) — Scan and save paperwork as image or PDF files.
13. **Evolution** (org.gnome.Evolution) — Manage email, calendar, contacts, and tasks.
14. **Contacts** (org.gnome.Contacts) — Keep a local address book.
15. **Calendar** (org.gnome.Calendar) — Plan events, appointments, and work sessions.
