# PJSoft Desktop Groups

Launch your everyday application sets with one click and automatically restore their window layouts.

Desktop Groups is a free Windows utility for people who regularly open the same applications and arrange their windows in the same positions. It can organize applications, documents, manuals, shortcuts, and web links into named desktop groups.

## Download

[Download the latest version](https://github.com/petrjones/DesktopGroups/releases/latest)

## Main features

- Create named and color-coded desktop groups.
- Launch an entire group of applications with one click.
- Drag application tiles in Edit mode to change and save their launch order.
- Freely resize desktop group panels; tiles automatically reflow to fit the available width.
- Keep the group header and controls visible while only the content area scrolls.
- Temporarily hide selected groups from the Windows desktop without deleting their settings.
- Save separate window layouts for different monitor counts and select the matching variant automatically.
- Safely offer the nearest saved layout when the current monitor setup has no exact variant.
- Save and restore window positions, sizes, monitors, and maximized states.
- Clearly distinguish minimized and non-minimized windows while saving a layout.
- Work with one or multiple monitors and Windows virtual desktops.
- Safely close all recognized windows in a group while allowing applications to prompt for unsaved changes.
- Export, import, and restore the complete configuration.
- Automatically keep the previous configuration and up to ten timestamped backups.
- Keep applications, PDF manuals, documents, shortcuts, and web links together.
- Optionally show groups automatically after signing in to Windows.
- Choose from 256 group colors.
- Czech, English, and Spanish user interface.
- Microsoft PowerToys is not required.

## What's new in 1.3.0

This release includes all improvements developed since the last public GitHub release, version 1.1.0.

- Added freely resizable desktop group panels with automatic tile reflow.
- Long group names wrap safely and remain separated from the header controls.
- When a panel is short, only its content scrolls; the group name and controls stay visible.
- Added separate saved layouts for different monitor counts, such as one, two, or three monitors.
- Desktop Groups automatically selects the matching layout when the monitor setup changes.
- If no exact layout exists, the application offers the nearest available layout without deleting the other variants.
- Added **Export settings**, **Import settings**, and **Restore previous configuration** commands.
- Added automatic `groups.json.bak` creation and a timestamped history of up to ten backups.
- Existing groups and layouts are migrated automatically and remain available after updating.
- Introduced the refreshed PJSoft visual design and the new Desktop Groups application icon.

## Quick start

1. Install Desktop Groups.
2. Click **+ Group** and enter a name.
3. Enable **Edit** mode and add applications, documents, shortcuts, or web addresses.
4. Drag tiles to set the order used by **Launch all**.
5. Open the applications and arrange their windows as required.
6. Click **Save window layout**. A separate variant is stored for the current number of monitors.
7. Next time, click **Launch all**. Desktop Groups starts the applications and restores the appropriate saved layout.
8. Use **Close all** to safely request that recognized windows close. Applications with unsaved documents can still ask you to save changes.
9. Use the **Data** menu to export, import, or restore your configuration.

## System requirements

- Windows 10 or Windows 11
- 64-bit system
- No administrator privileges required
- No Microsoft PowerToys dependency

## Updates and configuration

New installer versions update the existing installation instead of creating additional copies. Saved groups, launch order, visibility settings, panel sizes, and window-layout variants are preserved during an update.

The configuration is stored in `groups.json`. Before relevant changes, Desktop Groups keeps `groups.json.bak` and up to ten timestamped files in the `Backups` folder. The **Data** menu can transfer the complete configuration to another computer.

## Languages

- Czech
- English
- Spanish

## License and support

Desktop Groups is freeware. It contains no advertisements, bundled offers, artificial limitations, or paid features.

Voluntary contributions are optional, unlock nothing, and have no effect on application functionality.

## Publisher

PJSoft
