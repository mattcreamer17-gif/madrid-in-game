# Madrid in Game landing page

Bespoke landing page prepared for the Madrid in Game team ahead of eMerge Americas 2026 (booth 1045). The page mirrors the madridingame.es visual system (pure black background, hot-pink / electric-blue / mint neon geometry, Lato display, Inter body) so the prospect reads it as native to their own brand, with Eduba's content inside.

Content is Spanish-primary with an EN toggle in the top strip; both languages are rendered inline and switched via a small JS snippet that flips the `lang` attribute on the document root. The page carries:

- H1 and pitch body verbatim from `fit-analysis.md` section 7
- Meta description equal to the section 5 hook
- Start IN Up metrics, a Correlation One / Pacific Life + Colgate-Palmolive case card, and an ICM paper block with real anchors
- A single primary CTA to Matt Creamer (`[CAL_LINK]` placeholder for Calendly) with a `mailto:` fallback
- Eduba branding only in the footer (per disclosure rules)

## Intended URL path: /for/madrid-in-game

## Files

- `index.html` — single-page bilingual landing page (ES primary, EN toggle)
- `styles.css` — companion stylesheet, no build step
- `logo.svg` — Madrid in Game white wordmark (copied from Brand Pack assets)

## Notes before publishing

1. Replace `[CAL_LINK]` in the CTA with Matt Creamer's Calendly URL.
2. Verify booth number on arrival; the brief lists 1045 and the eMerge exhibitor portal shows 1078. The page currently uses 1045.
3. The `Madrid_in_game` proprietary OTF display face used on the live site is not shipped here. Lato 900 carries the display role, as the live site itself does for most section headings.
