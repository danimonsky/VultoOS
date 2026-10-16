# Changelog

All notable changes to Vulto OS will be documented in this file.

This project follows the [Keep a Changelog](https://keepachangelog.com/en/2.0.0/) format.

## [Unreleased]

### Added
- Established the initial Arch Linux-based Vulto OS project.
- Added an initial x86_64 package list for the live system.
- Added KDE Plasma desktop environment components.
- Added SDDM display manager configuration.
- Added a dedicated live-session user named `vulto`.
- Configured automatic login for the live desktop session.
- Added NetworkManager for network connectivity.
- Added Google Chrome to the planned live environment.
- Integrated Calamares installer configuration.
- Added initial Calamares branding for Vulto OS.
- Added a desktop shortcut to launch the graphical installer.
- Added a Polkit rule to authorize launching Calamares in the live session.
- Configured initial locale, timezone, user, and hostname settings for the installer.
- Added initial support for BIOS Syslinux and UEFI systemd-boot live boot modes.
- Added project documentation, including README and contribution guidelines.
- Selected the MIT License for original project code and files, subject to third-party license terms.

### Changed
- Replaced the generic project identity with Vulto OS branding.
- Configured the local package repository for staging required packages.
- Updated the live networking configuration to use NetworkManager instead of the enabled systemd-networkd and iwd services.

### Fixed
- Added exclusions to the Calamares unpack configuration to prevent selected live-session settings from being copied into the installed system.

### Planned
- Build the first bootable ISO.
- Test booting in a virtual machine.
- Verify the live KDE Plasma session and network connectivity.
- Validate Calamares partitioning and installation.
- Verify the installed system boots correctly.
- Review bootloader installation for UEFI and legacy BIOS.
- Finalize build instructions and release documentation.
- Develop future Daily, Dev, Gamer, and Ultimate editions.

---

Vulto OS is under active development. Items listed as added or changed describe initial configuration work and do not necessarily mean that the feature has been verified in a completed ISO.
