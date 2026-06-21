# Hermes Agent — OpenCode Theme

A **Hermes Agent** inspired custom theme for the [OpenCode](https://opencode.ai) TUI, adapted from the Konsole color scheme of the same name.

## Palette

| Role    | Hex       | Description          |
|---------|-----------|----------------------|
| Background | `#141416` | Very dark grey       |
| Panel      | `#131316` | Dark grey midground   |
| Element    | `#19191D` | Elevated surfaces     |
| Foreground | `#0A9628` | Terminal green        |
| Muted      | `#E7AD00` | Faded gold/amber      |
| Bright     | `#FFF8DC` | Cornsilk highlights   |
| Primary    | `#4DD0E1` | Cyan interactive      |
| Accent     | `#FFBF00` | Yellow highlights     |
| Error      | `#EF5350` | Red                   |

## Installation

```bash
mkdir -p ~/.config/opencode/themes
cp hermes-agent.json ~/.config/opencode/themes/
```

Then set it in `~/.config/opencode/tui.json`:

```json
{
  "theme": "hermes-agent"
}
```

Or select it at runtime with `/theme` in the OpenCode TUI.

## Credits

Based on the Hermes Agent color scheme for Konsole by @chronikion.
