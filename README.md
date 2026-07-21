# Michael Vargo — portfolio site scaffold

## To preview locally
1. Install Quarto: https://quarto.org/docs/get-started/
2. From this folder, run: `quarto preview`

## To publish
1. Create a GitHub repo named `<yourusername>.github.io`
2. Push this folder's contents to it
3. Run: `quarto publish gh-pages`

## Punch list before this is real
- [ ] Export map/graphic assets from InDesign (cover linework, river motif) to replace
      the placeholder SVG at images/river-divider.svg with your actual artwork
- [ ] Write real intro copy on index.qmd
- [ ] Fill in about.qmd bio
- [ ] Decide resume.qmd approach (embed PDF vs. transcribe) and add files/resume.pdf if embedding
- [ ] Fill in the four portfolio/*.qmd stubs with real write-ups, dates, categories, thumbnails
- [ ] Update navbar right-side links (LinkedIn/GitHub) and site-url in _quarto.yml
- [ ] Swap Barlow Condensed / Inter / JetBrains Mono for alternatives if you want a different feel
      (all three load from Google Fonts in custom.scss — easy one-line swaps)

## Design tokens (custom.scss)
- Blue #3A59A0 — structural color (nav, hero, dividers)
- Yellow #FFD427 — accent, only ever against blue backgrounds
- White #FFFFFF — content background
- Black #000000 — body text
- $blue-dark / $blue-tint — derived shades of blue only, not new hues
