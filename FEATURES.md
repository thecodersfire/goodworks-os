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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for nonprofit administration:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
3. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
6. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
7. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
8. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
2. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
3. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
4. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
7. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
8. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
9. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
10. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
13. **GNOME Maps** (org.gnome.Maps) — look up places and plan routes.
14. **GNOME Weather** (org.gnome.Weather) — check local weather conditions.
15. **GNOME Boxes** (org.gnome.Boxes) — test workflows in virtual machines.

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
