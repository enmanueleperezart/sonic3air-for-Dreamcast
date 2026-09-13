# Dreamcast port status

## Milestone 1 — completed in this tree

- Added `PLATFORM_DREAMCAST` detection from KallistiOS's `__DREAMCAST__` define.
- Classified Dreamcast as a console platform.
- Disabled the desktop OpenGL master switch for Dreamcast.
- Selected the existing software renderer as the initial graphics path.
- Added a KallistiOS-oriented build directory at `Oxygen/sonic3air/build/_dreamcast`.
- Added an experimental Makefile that targets the SH-4 KOS toolchain.
- Removed PC-only Discord/OpenGL/ImGui/network/download sources from the first build set.

## Milestone 2 — next

1. Build against an actual KallistiOS + kos-ports environment.
2. Fix the first compiler errors, one subsystem at a time.
3. Get an ELF that boots in Flycast.
4. Fix SDL2 video/input/audio on KOS.
5. Measure RAM use against the Dreamcast's 16 MB main RAM.
6. Add disc/romdisk packaging and generate a self-bootable image.
