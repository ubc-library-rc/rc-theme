# rc-theme
This fork of the [just-the-docs](https://github.com/just-the-docs/just-the-docs) (JTD) Jekyll theme is used by most UBC Library worskhop websites. The theme has local customizations (navbar content, link color, logo, readme). The customizations and this readme file could be over-written when the fork is synced with the upstream JTD repository. Make a copy of the repository before syncing in case you need to restore files later.

The last sync with the JTD repository was on 2025-03-21.

## UBC Research Commons customizations

- `_sass/color_schemes/rc.scss` file added, changes default link color to blue. This custom color scheme is referenced by the `color_scheme: rc` line in a workshop repository's `_config.yml` file.
- `_includes/components/footer_rc.html` file added, produces custom "View in Github" link in page footer. Referenced in `_layouts/default.html`.
- `_includes/nav_footer_custom.html` file modified, produces license block and logo at bottom of left-hand navigation pane. Content included automatically.
- `assets/images/rc-logo.png` file added, generic UBC Library logo. Referenced by `_includes/nav_footer_custom.html`
- `_sass/custom/custom.scss` file modified, contains RC-related css changes. Content included automatically.
- `_layouts/default.html` file modified, line added to reference `components/footer_rc.html` (line 35).
