# QA notes

These notes summarize saved automated test results from development.

## Recorded checks

- All five pages and the `map.html#signal` ending were checked at mobile 375px, tablet 768px, and desktop 1280px widths. The 18 layout checks recorded no horizontal overflow, one main heading, and a loaded stylesheet.
- Keyboard checks covered skip links, visible link focus, the complete story route, and restart. Reduced-motion checks confirmed that animations and transitions turn off on all five pages and the ending. No browser page errors were recorded. All 33 browser checks passed.
- HTML validation marked all five pages valid with no messages. Six axe WCAG A/AA checks, including the ending, recorded no violations.
- All 18 Firefox responsive and reveal checks passed at the same three widths.