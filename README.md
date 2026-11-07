# Lantern quest

Niki Durzynski | CSC4370 | Project 1

A short story site for the Quest Explorer track and Adventure Pack. Find a lantern at the market, repair it at the cottage, and carry it to the lighthouse.

## Open the site

Open `index.html` in a browser. Keep all files in the same folder. No installation or server is needed.

## Files

- `index.html`: story introduction and start link.
- `map.html`: world map and lighthouse ending.
- `market.html`: find the lantern, mission 1.
- `cottage.html`: repair the lantern, mission 2.
- `about.html`: project information and keyboard instructions.
- `styles.css`: shared layout, colors, focus styles, and motion.
- `README.md`: setup and implementation notes.
- `QA-notes.md`: checks and testing limits.

## How it works

The site uses HTML and CSS only, with no JavaScript, database, or saved progress. Links remain open, so the story does not enforce mission order.

The map uses CSS Grid. Navigation uses Flexbox and wraps when needed. At widths of 550px or less, the map changes from two columns to one. The link to `map.html#signal` reveals the ending with CSS `:target`.

Three short animations run once per load: lantern glow, cloud movement, and the market checkpoint border. Links have a color transition, and hovering over a lantern rotates it slightly. Reduced-motion settings disable animations and transitions. Keyboard users have a skip link and visible focus outlines.
