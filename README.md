# karabiner
My Karabiner config for HHKB Hybird-Type S 
- Remap using [HHB Remapping Tool](https://happyhackingkb.com/download/) 
   - [Wide mod](https://colemakmods.github.io/ergonomic-mods/wide.html) 
   - Move `backtick` next to `Esc` 
- Navigation layer (TODO)
- Window layer 
## Setup
```bash
ln -s ~/Documents/karabiner ~/.config
```
https://karabiner-elements.pqrs.org/docs/manual/misc/configuration-file-path/#about-symbolic-link (allow full disk access for Karabiner)

## Custom shortcuts
### Better Snap Tool
- Under Shortcuts panel
  - For `maximise`: add shortcut `Option + Command + f`
  - For `center on next monitor`: add shortcut `Shift + Option + Command + n`
  - For `left half`: add `Shift + Option + Command + <-`
  - For `right half`: add `Shift + Option + Command + ->`
### Vscode
- For `View: Two Columns Editor Layout` : add shortcut `Option + Command + u`
### Intellij IDEA
- Override `Search everywhere` shortcut
  - Disable default `Double-Shift` 
    - Open Settings > Advanced Settings 
    - Here, in search box type "Disable double modifier key shortcuts" 
  - Add shortcut  `Command + \`
- For `Split right` : add shortcut `Option + Shift + Command + y` 
- For `Split and move right`: add shortcut `Option + Shift + Command + t`