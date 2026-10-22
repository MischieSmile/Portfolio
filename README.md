# Personal portfolio

A responsive, one-page static portfolio. No backend, package installation, or build step.

## Preview

Serve this directory with any static server, for example `npx --yes serve .`.

## Content

- `index.html`: introduction, About, Projects, Experience, and social/contact destinations.
- `styles.css`: dark palette, responsive layout, project entries, and reduced-motion rules.
- `script.js`: English/Turkish content and the name's scroll animation.

Content reflects Baha Taşkın’s supplied biography, project repositories, and CVs. Both languages are maintained in `script.js`; English fallback content also lives in `index.html`. Project descriptions remain fully visible, with no expandable cards. Google Fonts loads Manrope; local sans-serif fonts are used if unavailable.

The initial language uses a saved preference first, then the Europe/Istanbul browser timezone or a Turkish primary browser language, otherwise English. This is an approximate region hint, not IP geolocation. The manual language selection is stored locally when storage is available.

There is no header or footer. The large centered name eases up and left on scroll, staying fixed in the corner throughout the page. The movement follows scrolling in either direction with time-based damping. Reduced-motion users get direct scroll-linked movement without trailing, entrance, or ambient animation. The language switch is the only control in the top right.

On wide screens the content has a separate column to the right of the pinned name. On narrower screens a subtle background fade protects the name as content scrolls beneath it.

## GitHub Pages

Publish the repository root from the chosen branch through GitHub Pages. Relative asset paths also support a project repository URL. Add the custom domain later through the repository Pages settings. No deployment has been configured yet.
