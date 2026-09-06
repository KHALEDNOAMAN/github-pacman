# GitHub Pac-Man - Customization Guide

## Themes
| Theme | Colors | Best For |
|-------|--------|----------|
| Classic | Yellow/Blue | Original arcade feel |
| Dark | Cyan/Purple | Dark mode profiles |
| Neon | Green/Pink | Cyberpunk aesthetic |
| Minimal | Gray/White | Clean profiles |

## Configuration
```yaml
pacman:
  speed: 2
  ghost_count: 4
  dot_style: round
  trail: true
  loop: true
```

## How It Works
1. Reads your GitHub contribution graph
2. Converts green squares into maze walls
3. Animates Pac-Man eating through your contributions
4. Generates SVG output via GitHub Actions