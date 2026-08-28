# Oligarchy

An [Omarchy](https://omarchy.org/) theme. Ink-black, champagne gold, racing green, oxblood.

> Elite capital. Public code.

![Oligarchy](backgrounds/5-public-code.webp)

## Install

```bash
omarchy theme install https://github.com/acrogenesis/omarchy-oligarchy-theme.git
```

That clones the repo into `~/.config/omarchy/themes/oligarchy` and applies it.

To switch to it later:

```bash
omarchy theme set oligarchy
```

Cycle wallpapers with `omarchy theme bg next`, or open the picker with `omarchy theme bg-switcher`.

## Update

```bash
omarchy theme update
```

## Remove

```bash
omarchy theme remove oligarchy
```

## GTK apps

Omarchy themes GTK apps by switching them to Adwaita-dark and setting an icon theme — it does not pass the palette along, so Nautilus and other GTK windows stay default grey. This theme ships a `gtk.css` that repaints them in the Oligarchy palette. Point GTK at the current theme's copy once:

```bash
mkdir -p ~/.config/gtk-3.0 ~/.config/gtk-4.0
ln -sfn ~/.local/state/omarchy/current/theme/gtk.css ~/.config/gtk-3.0/gtk.css
ln -sfn ~/.local/state/omarchy/current/theme/gtk.css ~/.config/gtk-4.0/gtk.css
```

Restart the apps to pick it up. The symlinks track whichever theme is applied.

## Backgrounds

| File | |
| --- | --- |
| `0-penguin.webp` | Crowned penguin. Free as in beer. Funded as in friends. (16:9) |

Extra aspect ratios sit in `backgrounds/.responsive/0-penguin/` (`16x9.webp`, `21x9.webp`, `32x9.webp`, …) so they are not separate wallpapers in the picker. This machine’s background plugin picks the closest ratio to the monitor. Drop more files there, or under `~/.config/omarchy/backgrounds/oligarchy/.responsive/0-penguin/`.
| `1-library.webp` | Private library, green banker's lamp |
| `2-circuit.webp` | Empty night circuit after rain |
| `3-boardroom.webp` | Dark marble table, gold ring light |
| `4-figlet.webp` | `OLIGARCHY` in Omarchy's own logo font |
| `5-public-code.webp` | Elite capital. Public code. |
| `oligarchy.webp` | Centered wordmark |

Add your own without touching this repo: drop images into `~/.config/omarchy/backgrounds/oligarchy/`.

## Palette

| Role | Hex |
| --- | --- |
| Background | `#171c16` |
| Dark background | `#12160f` |
| Darker background | `#0c0f0a` |
| Lighter background | `#22281f` |
| Foreground | `#e8d9b4` |
| Accent | `#c7a668` |
| Selection | `#2c3226` |
| Muted | `#5a5440` |
| Red | `#a34b3e` |
| Green | `#5c6b4a` |
| Yellow | `#c3a176` |

Icons: `Yaru-yellow`.

## License

Theme files are MIT (see `LICENSE`). The photographic wallpapers are AI-generated images, free to use and redistribute with the theme.
