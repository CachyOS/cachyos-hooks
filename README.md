# cachyos-hooks

Pacman hooks for setting up system identification files and other features of CachyOS.

File name | Description
:--- | :---
cachyos-branding | Fixes files like `os-release`, `lsb-release`, `issues` for CachyOS.
cachyos-branding.hook | Runs `cachyos-branding` script after the `cachyos-hooks` package is updated.
cachyos-nvidia.hook | Avoids black screens after driver updates with `nvidia-drm.modeset=1` enabled.
cachyos-plymouth-initramfs.hook | Replaces plymouth script to update initrd with ``update-initramfs``
cachyos-reboot-required | Notifies user to reboot after essential system files have been updated.
cachyos-reboot-required.hook | Runs `cachyos-reboot-required` after any listed essential system files have been updated.
lsb-release.hook | Runs `cachyos-branding` script after package `lsb-release` has been updated.
os-release.hook | Runs `cachyos-branding` scirpt after package `filesystem` has been updated.
update-initramfs | Helper script for autodetecting and using installed initramfs generator
