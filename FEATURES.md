# Built-in features for quiet-web-os

Purpose: privacy-conscious browsing

1. **organize a personal routine** — run quiet-web-os-workspace. It creates ~/Documents/quiet-web-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run quiet-web-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/quiet-web-os-session-plans/.
3. **check routine readiness** — run quiet-web-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/quiet-web-os-workspace features/quiet-web-os-plan features/quiet-web-os-check "$HOME/.local/bin/"
