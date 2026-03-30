# C三NETEX Brand

Official brand assets and guidelines for C三NETEX (Cenetex Inc.).

## Name

**C三NETEX** — the first E is replaced by 三 (sān), the Chinese character for "three." The name is always rendered in uppercase.

- Full: **C三NETEX**
- Fallback (plain ASCII): **CENETEX**
- Legal: **Cenetex Inc.**
- Never: "cenetex", "Cenetex", "CeNetEx", or any other casing

## Logo

The mark is the character 三 rendered as three horizontal black bars on a white field. It functions as both a standalone symbol and the E in C三NETEX.

| File | Format | Use |
|------|--------|-----|
| `logos/cenetex-mark.svg` | SVG | Primary — paper white bg, dark bars |
| `logos/cenetex-mark-dark.svg` | SVG | Dark backgrounds — slate 950 bg, paper white bars |
| `logos/cenetex-mark-transparent.svg` | SVG | Overlays — no background, dark bars |
| `logos/cenetex-mark.jpg` | JPG | Profile pictures, favicons, raster contexts |

### Usage

- Minimum clear space: the height of one bar on all sides
- On dark backgrounds: invert to white bars on transparent
- Never rotate, distort, or add effects to the mark

## Colors

Both modes are derived from the mark's two real colors. Vermillion is the accent — from the seal stamp (朱印) tradition in East Asian calligraphy. Three ink strokes, one red seal.

### Brand Anchors

| Name | Hex | Source |
|------|-----|--------|
| Paper | `#f8f7f5` | Mark background — warm off-white |
| Ink | `#090808` | Mark strokes — warm near-black |
| Vermillion | `#c53d2f` | Accent — seal stamp red, for 三 highlight and interactive elements |

### Light Mode (default)

| Token | Hex | Use |
|-------|-----|-----|
| `--cx-bg` | `#f8f7f5` | Page background (= Paper) |
| `--cx-surface` | `#ffffff` | Cards, elevated elements |
| `--cx-border` | `#e8e6e3` | Subtle borders |
| `--cx-border-strong` | `#d4d1cc` | Emphasized borders |
| `--cx-text` | `#090808` | Primary text (= Ink) |
| `--cx-text-secondary` | `#52504d` | Secondary text |
| `--cx-text-muted` | `#8a8783` | Tertiary/muted text |
| `--cx-code-bg` | `#f0efed` | Code block backgrounds |

### Dark Mode

| Token | Hex | Use |
|-------|-----|-----|
| `--cx-bg` | `#090808` | Page background (= Ink) |
| `--cx-surface` | `#141313` | Cards, elevated elements |
| `--cx-border` | `#242222` | Subtle borders |
| `--cx-border-strong` | `#363333` | Emphasized borders |
| `--cx-text` | `#f8f7f5` | Primary text (= Paper) |
| `--cx-text-secondary` | `#b5b2ae` | Secondary text |
| `--cx-text-muted` | `#7a7774` | Tertiary/muted text |
| `--cx-code-bg` | `#1a1818` | Code block backgrounds |

### Principle

Dark mode is Ink on Paper inverted. Light mode is Paper on Ink inverted. The two modes are mirrors, not separate palettes. No navy, no slate, no Tailwind generics. Every color is a tint of Paper or Ink.

## Typography

| Role | Font | Weight | Tracking |
|------|------|--------|----------|
| Headings | Inter | 700-800 | -0.02em to -0.03em |
| Body | Inter | 400 | normal |
| Code | JetBrains Mono / Fira Code | 400 | normal |
| UI Labels | Inter | 500-600 | 0.05em (uppercase) |

## Voice

- **Direct.** Say what it does, then stop. Every sentence earns its place.
- **Honest.** Name the limits alongside the strengths. Trust is built by what you admit.
- **Specific.** Show the work. Code, numbers, outcomes. Concrete over abstract.
- **Present.** Write about what is, not what could be. If it ships today, say so. If it doesn't, say that too.

## Digital Presence

| Property | URL |
|----------|-----|
| Main site | [cenetex.com](https://cenetex.com) |
| Lab blog | [lab.cenetex.com](https://lab.cenetex.com) |
| GitHub | [github.com/cenetex](https://github.com/cenetex) |

## License

Brand assets are provided for reference and authorized use only. Contact hello@cenetex.com for usage permissions.
