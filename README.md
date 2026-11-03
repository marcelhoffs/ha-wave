# Wave themes

Themes for [Home Assistant](https://www.home-assistant.io/), each with a light and a dark mode:

| Theme | Light accent | Dark accent |
| --- | --- | --- |
| **Purple wave** | `#7c5cf6` | `#a78bfa` |
| **Sapphire wave** | `#1d4ed8` | `#60a5fa` |
| **Emerald wave** | `#047857` | `#34d399` |
| **Bordeaux wave** | `#7f1d3f` | `#e092ac` |

The palettes match the Wave style of [Anchor](https://github.com/marcelhoffs/anchor).

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/hacs/integration)

## Installation

### HACS (recommended)

1. Open HACS in Home Assistant.
2. Open the menu (⋮) → **Custom repositories**.
3. Add `https://github.com/marcelhoffs/ha-wave` with category **Theme**.
4. Search for **Wave themes** and download it.
5. Make sure themes are enabled in `configuration.yaml`:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

6. Restart Home Assistant (or run the `frontend.reload_themes` action).
7. Go to your **Profile** and select one of the Wave themes. Set the mode to *Auto* to follow your device’s light/dark setting.

### Manual

Copy the files from `themes/` into the `themes` folder of your Home Assistant configuration directory, then follow steps 5–7 above.

## License

[MIT](LICENSE)
