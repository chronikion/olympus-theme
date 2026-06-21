# Olympus Theme

Olympus is a **Hermes Agent** inspired dark mode theme with golden highlights and green mid tones. It's easy to read, beloved daily driver that I use every day in every interface.

---

## OpenCode

### Palette

| Role       | Hex       | Description          |
|------------|-----------|----------------------|
| Background | transparent | Inherits terminal (Konsole 20% opacity) |
| Panel      | `#131316` | Dark grey midground  |
| Element    | `#19191D` | Elevated surfaces    |
| Foreground | `#0A9628` | Green mid tones      |
| Muted      | `#E7AD00` | Faded gold/amber     |
| Primary    | `#4DD0E1` | Cyan interactive     |
| Accent     | `#FFBF00` | Golden highlights    |

### Install

```bash
mkdir -p ~/.config/opencode/themes
cp olympus.json ~/.config/opencode/themes/
```

Set theme in `~/.config/opencode/tui.json`:

```json
{
  "theme": "olympus"
}
```

Or select at runtime with `/theme` in the OpenCode TUI.

---

## Konsole

### Files

- `Hermes Agent.colorscheme` — base scheme
- `HermesAgentWarm.colorscheme` — warm variant  
- `Hermes.profile` — profile with font and cursor config

### Install

```bash
cp "Hermes Agent.colorscheme" HermesAgentWarm.colorscheme Hermes.profile ~/.local/share/konsole/
```

Then select **Hermes** profile in Konsole → Settings → Manage Profiles.
