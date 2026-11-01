# Vera Dark

A dark theme for Mono and Vera's console, with the colors of Vera's classic interface: its
blue-gray grays, blue accent, and the green, amber and red it uses for success, warnings and
errors.

## Installing

In Vera's console, run `AddTheme cvrnz/vera-dark-theme`, then pick `vera-dark` with `Themes`.

For Mono, clone it into its themes folder:

```sh
git clone https://github.com/cvrnz/vera-dark-theme.git \
  "$HOME/Library/Application Support/dev.mono.app/themes/vera-dark-theme"
```

On Linux the folder is `~/.config/dev.mono.app/themes`. Then pick `vera-dark` with the
`Themes` command. To update it, `git pull` in that folder and reopen `Themes`.

## Colors

| Key | Color | Used for | From classic |
|-----|-------|----------|--------------|
| `bg` | `#161719` | Background | Cards (`surface`) |
| `dark` | `#0d0e10` | Side panels, popups | Window frame (`background`) |
| `raised` | `#262729` | Cursor line, selected tab | Hover and selected fill (`default`) |
| `selection` | `#323335` | Selected text | Segmented control (`segment`) |
| `fg` | `#f1f2f4` | Text | `foreground` |
| `dim` | `#8f9299` | Comments, muted text | `muted` |
| `purple` | `#8b5cf6` | Keywords | Event color |
| `green` | `#11c965` | Strings, added lines | `success` |
| `yellow` | `#f7b750` | Types | `warning` |
| `orange` | `#f97316` | Numbers, constants | Event color |
| `blue` | `#3279d7` | Functions, the accent | `accent` |
| `cyan` | `#14b8a6` | Operators, regular expressions | Event color |
| `red` | `#e94646` | Errors, deleted lines, keys | `danger` |

Classic's colors are oklch values over a dark gray; the hex values here are those colors with
the see-through fills laid over the card color.
