## RengeOS 2026.03.06

- **Notes**: We will have KDE Edition coming soon, so stay tuned!

- **Change**:
+ Adding the ``fastfetch-git``, ``zenity`` packages and keybind(Mod+Alt+W) allows changing the wallpaper on NiriWM-Edition.
+ Fixed the issue where ``ros-reborn`` automatically saves as kernel-name.preset.pacsave(pacman-saved backup) from an unselected kernel during installation.
+ The ``ros-reborn-system-ota`` update now lets you choose between the latest version of NiriWM and Minimal Edition to download.
+ The repository [ROS-Reborn-System-OTA](https://github.com/RengeOS/ROS-Reborn-System-OTA) will be replaced with the repositories corresponding to the current editions on RengeOS for ``ros-reborn-system-ota`` (e.g., Minimal and NiriWM Edition).
+ Update packages between the two Edition(NiriWM and Minimal) to the latest version today (2026.03.06).

### Minimal Edition

- **Information**:
+ Built-in WM, DE: No, only TTY
+ Built-in Audio (pipewire,pulseaudio): No, needs to install the packages manually
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19
+ Linux Stratix Pulse LTS: 6.12.71

### Niri WM Edition

- **Information**:
+ Built-in WM, DE: NiriWM
+ Built-in Audio: Pipewire
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19
+ Linux Stratix Pulse LTS: 6.12.71