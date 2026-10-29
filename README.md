# Aura Dark for Logseq

Deep purple dark theme for Logseq, ported from the VS Code theme
[Aura Dark](https://github.com/vinaycodes-io/aura-dark-theme) by Vinay.

<!-- TODO: screenshot (required by the Logseq marketplace) -->

## Features

- Aura Dark palette for the whole UI: sidebars, header, menus, command palette, page content
- Works with both Logseq UI variable sets (`--ls-*` and the newer `--lx-*` / shadcn tokens)
- Code blocks colored like Aura Dark in VS Code (CodeMirror and highlight.js)
- Bundled **Hack Nerd Font Mono**: used for code blocks and inline code, and as an icon fallback everywhere, so Nerd Font glyphs render without installing the font

## Install

**Marketplace:** Logseq → Plugins → Marketplace → Themes → search "Aura Dark" → Install, then pick it under Settings → Themes (`t i`).

**Manual (development):**

1. Settings → Advanced → enable Developer mode
2. Plugins → Load unpacked plugin → select this folder
3. Select "Aura Dark" with `t i`

## Color system

| Color | Hex | Role in Logseq |
|---|:---:|---|
| Purple | `#C792EA` | Accent, links, page refs, headings |
| Periwinkle | `#82AAFF` | Block refs, functions |
| Mint Teal | `#7FDBCA` | Tags, properties |
| Sage Green | `#C3E88D` | Inline code, strings |
| Warm Gold | `#FFCB6B` | Bold text, types |
| Amber | `#FFD580` | Highlights, warnings |
| Slate | `#6B7A99` | Quotes, comments, muted text |

## Credits

- Original theme: [vinaycodes-io/aura-dark-theme](https://github.com/vinaycodes-io/aura-dark-theme) (MIT)
- Font: [Hack](https://github.com/source-foundry/Hack) patched by [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts), see `fonts/LICENSE.md`

## License

MIT, see `LICENSE`.
