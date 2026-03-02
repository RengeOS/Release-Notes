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
