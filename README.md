## RengeOS 2026.03.02

- **Notes**: Currently, the ``ros-reborn-system-ota`` tool only retrieves airootfs and the kernel of the latest minimal version of **RengeOS**, so in the next release we will be able to choose between the Minimal Edition and NiriWM Edition and the documentation will gradually be improved.

- **Change**:
+ We've added a NiriWM Edition for **RengeOS**, yay!
+ Fixed the ``ros-reborn`` tool that couldn't create kernel presets.

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
