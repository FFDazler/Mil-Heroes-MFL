# Military Heroes MFL theme

Responsive custom styling and image assets for the Military Heroes
MyFantasyLeague site. Development and testing should be performed on staging
league `31506` before anything is copied to a live league.

## GitHub Pages

In the repository settings, enable Pages using the `main` branch and `/ (root)`
as the publishing source. The public stylesheet will then be available at:

`https://ffdazler.github.io/Mil-Heroes-MFL/military-heroes.css`

The stylesheet contains an absolute GitHub Pages URL for the optimized homepage
banner, so it can be pasted into MFL's custom CSS editor without broken relative
paths.

## Files

- `military-heroes.css` — responsive MFL custom theme
- `assets/branding/military-heroes-banner.jpg` — optimized web banner
- `assets/branding/military-heroes-banner-original.png` — original source banner
- `assets/franchises/` — final 600×200 franchise artwork

## Safe rollout

1. Enable GitHub Pages and verify the banner URL opens directly.
2. Paste `military-heroes.css` into staging league `31506` only.
3. Review the homepage, rosters, standings, lineup, transactions, and live
   scoring pages on desktop and mobile.
4. Adjust the staging stylesheet until approved.
5. Back up the live league CSS before transferring the finished theme.
