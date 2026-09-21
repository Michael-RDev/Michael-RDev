# Profile assets

All README images are stored here so the profile does not depend on a third-party image service.

| Original asset | Source |
| --- | --- |
| `logos/lockheed-martin.svg` | [Lockheed Martin logo on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Lockheed_Martin_logo_(2011%E2%80%932022).svg), matching the star and wordmark in the supplied reference |
| `logos/scc-soft-computer.svg` | [SCC Soft Computer's official website SVG](https://www.softcomputer.com/wp-content/uploads/2024/07/logo-scc.svg) |

Retrieved September 21, 2026. The source SVGs are preserved unchanged. Logos belong to their respective owners; Wikimedia labels the Lockheed Martin artwork as a public-domain text logo.

The four SVGs in `experience/` embed the original vector artwork alongside the roles supplied in the reference. These variants use blue logos (`#79b8ff` on dark backgrounds, `#2463a6` on light backgrounds), centered captions, and transparent backgrounds. They contain no external images, fonts, or scripts. The README selects a variant using GitHub-supported `<picture>` elements.

To change a role, update the `<desc>` and caption text in both theme variants and the corresponding image's `alt` text in the main README.
