# Kitty Config

A minimal [Kitty](https://sw.kovidgoyal.net/kitty/) terminal configuration with a custom Carbonfox-inspired, blue-grey color scheme.

## Features

- **Theme** — Carbonfox-inspired palette tuned for a muted, blue-grey look: custom cursor, tab bar, border, mark, and ANSI colors.
- **Typography** — FiraCode Nerd Font at 11pt, with dedicated bold, italic, and bold-italic faces.
- **Layout** — Zero window padding, margins, and borders so TUI apps fill the screen; the tab bar auto-hides when only one tab is open.
- **Keybindings** — Vim-style `Ctrl+H/J/K/L` window navigation and `Ctrl+W` word delete.

## Installation

```sh
git clone git@github.com:0XAiI/Kitty_Config.git ~/.config/kitty
```

## Layout

| File                 | Description                                                            |
| -------------------- | ---------------------------------------------------------------------- |
| `kitty.conf`         | Main configuration — fonts, keybindings, window layout, theme include  |
| `current-theme.conf` | Colorscheme — palette, cursor, tab bar, borders, marks, and ANSI colors|

## Reload

Changes apply automatically on save. To reload manually:

- `Ctrl+Shift+F5` inside a Kitty window, or
- `kill -SIGUSR1 $(pidof kitty)`