# macOS Tahoe Rice - Cinnamon
A clean, performance-focused macOS clone for Cinnamon.

### Hardware
- **CPU:** Intel i5-9400
- **GPU:** Intel UHD 630
- **RAM:** 8GB DDR4

### Visuals
- **GTK Theme:** MacTahoe-Dark
- **Cursor:** MacTahoe-cursors
- **Icons:** MacTahoe-Dark (Custom icons in custom-icons)
- **Dock:** Plank (Locked config)
- **Terminal:** Blackbox
- **Shell:** Zsh (Powerlevel10k)

### Config

#### 1. Custom Icons
The icons in the `custom-icons` folder have been manually processed with ImageMagick (`-trim -resize 110%`) to ensure they are not too big or small on plank.
* **To Install:** Copy the `custom-icons` folder to `~/.icons/`.
* **To Apply:** Use a Menu Editor (like MenuLibre) to manually set your app icons to these images via the app's properties.

* #### 2. Plank Dock Configuration
To get the exact look:
* Copy the `settings` file to `~/.config/plank/dock1/`.
* Copy the WhiteSur-Dark folder to ~/.local/share/plank/themes/ and apply in preferences.
* (You should use plank-reloaded since plank isn't getting updates anymore.)
* 
#### 3. Terminal & Shell
* Copy `.zshrc` and `.p10k.zsh` to your `$HOME` directory.
