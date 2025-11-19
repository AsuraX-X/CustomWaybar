# Waybar Configurations

This repository contains custom Waybar configurations for a top and bottom bar setup.

## Top Waybar

The top waybar configuration (`Top Waybar/config.jsonc` and `Top Waybar/style.css`) can be used as a standard waybar setup. It includes modules for workspaces, clock, network, battery, and more.

### Weather Module

The top waybar includes a custom weather module that requires [wttrbar](https://github.com/bjesus/wttrbar) to be installed. Install it to enable weather information in the bar.

## Bottom Waybar

The bottom waybar configuration (`Bottom Waybar/config-bottom.jsonc` and `Bottom Waybar/style-bottom.css`) is designed to show media controls and lyrics. It includes mpris modules for media control and a custom lyrics module.

### Lyrics Module

The bottom waybar includes a custom lyrics module that requires [waybar-lyric](https://github.com/Nadim147c/waybar-lyric) to be installed. Install it to enable lyrics display in the bar.

### Installation

To use the bottom waybar:

1. Copy or move `config-bottom.jsonc` and `style-bottom.css` to your Waybar configuration directory (e.g., `~/.config/waybar/` or a location of your choice).
2. Run Waybar with the bottom configuration using:
   ```
   waybar -c path/to/config-bottom.jsonc -s path/to/style-bottom.css
   ```

You can automate this with a bash script or systemd service if desired.