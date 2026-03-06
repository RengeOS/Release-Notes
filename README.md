## RengeOS 2026.03.06

- **Notes**: We'll have KDE Edition coming soon, so stay tuned!

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

## RengeOS 2026.03.02

- **Notes**: Currently, the ``ros-reborn-system-ota`` tool only retrieves airootfs and the kernel of the latest minimal version of **RengeOS**, so in the next release we will be able to choose between the Minimal Edition and NiriWM Edition and the documentation will gradually be improved.

- **Change**:
+ We've added a NiriWM Edition for **RengeOS**, yay!
+ Fixed the ``ros-reborn`` tool that couldn't create kernel presets.
+ The ``Recovery Mode`` partition size requirement has been increased from **7GB** to **10GB** to avoid memory shortage errors when containing airootfs in NiriWM Edition.

### Minimal Edition

- **Information**:
+ Built-in WM, DE: No, only TTY
+ Built-in Audio (pipewire,pulseaudio): No, needs to install the packages manually
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19 (Mainline)
+ Linux Stratix Pulse LTS: 6.12.71 (Latest LTS)

### Niri WM Edition

- **Information**:
+ Built-in WM, DE: NiriWM
+ Built-in Audio: Pipewire
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19 (Mainline)
+ Linux Stratix Pulse LTS: 6.12.71 (Latest LTS)

## RengeOS 2026.02.15
### Minimal Edition

- **Notes**: This version helps stabilize the system and encourages users to reinstall their system.

- **Change**:
+ Migrating all linux-renge to linux-stratix-pulse to fix some bugs and add some patches to improve performance.
+ Remove initramfs(fallback) as it is unnecessary to create and consumes extra memory.
+ linux-renge-bore(Deprecated) -> linux-stratix-pulse
+ linux-renge-lts(Deprecated) -> linux-stratix-pulse-lts

- **Information**:
+ Built-in WM, DE: No, only TTY
+ Built-in Audio (pipewire,pulseaudio): No, needs to install the packages manually
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19 (Mainline)
+ Linux Stratix Pulse LTS: 6.12.71 (Latest LTS)

### Niri WM Edition (Not yet available)

## RengeOS 2026.02.12
### Minimal Edition

- **Changes**:
+ Officially launched for the first time.
+ It's stable and ready for the community to use.

- **Information**:
+ Built-in WM, DE: No, only TTY
+ Built-in Audio (pipewire,pulseaudio): No, needs to install the packages manually
+ Supported Chipset: Intel, AMD, NVIDIA needs to install the packages manually
+ Supported Filesystems: XFS, Bcachefs
+ Linux Renge BORE: 6.18.8
+ Linux Renge LTS: 6.12.65

### Niri WM Edition (Not yet available)
