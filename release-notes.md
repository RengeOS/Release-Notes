## RengeOS 2026.03.20

- **Notes**: This update primarily focuses on nvidia support and bug fixes due to the wide compatibility between different machines. I plan to add other filesystems support and KDE Edition later, as well as research plans to create an immutable system.

- **Change**:
+ Migrate the website from ``https://rengeos.github.io/rengeos-docs/`` to ``https://rengeos.github.io/``
+ ``ros-installer`` and ``ros-reborn`` have been updated to support installation for nvidia graphics cards. Thanks to **@phantasmwolf** for testing it!
+ Critical bugs related to ``bcachefs`` and ``binutils`` have been fixed.
+ Replace ``fastfetch-git`` with ``fastfetch`` and ``hyprlax-git`` with ``hyprlax`` in NiriWM Edition.
+ Update the kernel version for ``linux-stratix-pulse`` (6.19-1 -> 6.19.6-1) and ``linux-stratix-pulse-lts`` (6.12.71-1 -> 6.12.76-1)
+ Update packages between the two Edition(NiriWM and Minimal) to the latest version today (2026.03.06).

### Minimal Edition

- **Information**:
+ Built-in WM, DE: No, only TTY
+ Built-in Audio (pipewire,pulseaudio): No, needs to install the packages manually
+ Supported Chipset: Intel, AMD
+ Supported Graphics Cards:  Intel, AMD, NVIDIA
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19.6
+ Linux Stratix Pulse LTS: 6.12.76

### Niri WM Edition

- **Information**:
+ Built-in WM, DE: NiriWM
+ Built-in Audio: Pipewire
+ Supported Chipset: Intel, AMD
+ Supported Graphics Cards:  Intel, AMD, NVIDIA
+ Supported Filesystems: XFS, Bcachefs
+ Linux Stratix Pulse: 6.19.6
+ Linux Stratix Pulse LTS: 6.12.76