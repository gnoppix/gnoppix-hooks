 gnoppix-hooks

Pacman hooks for setting up system identification files and other features of Gnoppix.

File name | Description
:--- | :---
gnoppix-hooks-runner | Fixes files like `os-release`, `lsb-release`, `issues` for Gnoppix.
gnoppix-hooks.hook | Runs `gnoppix-hooks-runner` after the `gnoppix-hooks` package is updated.
lsb-release.hook | Runs `gnoppix-hooks-runner` after package `lsb-release` has been updated.
os-release.hook | Runs `gnoppix-hooks-runner` after package `filesystem` has been updated.
gnoppix-reboot-required | Notifies user to reboot after essential system files have been updated.
gnoppix-check-reboot-required | Filters a selection of kernel targets to `gnoppix-reboot-required`.
gnoppix-reboot-required.hook | Runs `gnoppix-reboot-required` after any listed essential system files have been updated.
gnoppix-nvidia.hook | Avoids black screens after driver updates with `nvidia-drm.modeset=1` enabled.
