# So Much to Tell You | Brand palette & logo rules

## Status

Locked at the user's request on 2026-11-10, build `1110-BrandRefresh`.

The approved visual reference is the book-spine bookmark with orange trim and rising paragraph stripes. The brand should remain empowering, welcoming, mature, and readable.

## Four core palette colors

| Color | Hex | Role |
| --- | --- | --- |
| Deep green | `#172734` | Sidebar, dark surfaces, prominent dark text |
| White | `#FFFFFF` | Wordmark, clean reading surfaces, contrast |
| Light cream | `#FBF1E3` | Main site background, warm neutral surfaces |
| Signature orange | `#F47721` | Top navigation bar, high-visibility accents, action buttons |

The book-spine illustration includes a brighter orange edge `#F6A51B` as an **orange-family logo highlight**, not a fifth general-purpose UI color. Do not introduce brown as a UI surface color. Subtle greys, shadows, borders, and accessible interaction states are allowed as neutrals.

## Contrast and accessibility

- Orange `#F47721` has adequate contrast against deep green `#172734` for normal-sized text, but **not** against white.
- Place **green text** on orange bars and orange primary buttons. Avoid white text on signature orange.
- White or cream on deep green is preferred for dark navigation.
- Avoid relying on color alone to identify selected items and important events.

## Logo files

- `assets/logo.svg`: horizontal logo with the book spine and full white wordmark for deep-green backgrounds.
- `assets/book-spine-mark.svg`: reusable symbol/icon, visually matched to the approved screenshot.

The logo combines a side-on book spine, an angular bookmark/chapter notch, two white rising paragraph lines, and an orange ribbon. Keep enough clear space around the mark for small displays. Do not stretch or recolor it to brown. The horizontal wordmark uses live SVG text in this design prototype; outline its type in the final production logo kit.

## Deployment and safety

The Cloudflare Workers preview is an **interactive public design demo** with fictional examples and browser-local text, not a private family app yet. No photo/video uploads or accounts are implemented. The production app must use authenticated storage and privacy controls before real personal content is collected.
