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
