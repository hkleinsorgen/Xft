# Xft
Xft font binding for VisualWorks

## Packages

Choose the branch matching the version of VisualWorks.
If the version of VisualWorks is newer than the most recent branch, then loading Xft might not work or crash due to the deep integration into VisualWorks.

Make sure that VW does not load outdated Xft parcels from the `contributed` directory of VW.

### Xft

A binding for the X FreeType interface library for enumerating and rendering fonts.
Also includes XftFont, a screen font implementation.

### Xft-Integration

Replaces the old XFonts handled by the VM with XftFonts.
Requires a restart once the package is loaded.

### Xft-DesktopIntegration

Gathers font information from the desktop configuration. 
The default text attributes will be reset according to the default font of the desktop.

### Xft-Development

Settings and tweaks for the IDE

### Xft-Performance

Patch: Minimize library/primitive calls when drawing strings with composite fonts
