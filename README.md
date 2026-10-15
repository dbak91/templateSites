# templateSites

Three independent, client-demo-friendly website concepts. Each template is a small static site built with plain HTML and CSS, so it is easy to inspect, customize, and host without a build step or extra dependencies.

## Templates

| Template | Intended audience | Style |
| --- | --- | --- |
| [01 — Alder & Row](templates/01-alder-row/) | A boutique architecture or workplace-design studio | Editorial, calm, and image-led, with a warm neutral palette and oversized typography. |
| [02 — Clearview](templates/02-clearview/) | A residential and commercial window-cleaning service | Direct, bright, and practical, with high-contrast calls to action and clear service information. |
| [03 — Good Day Coffee](templates/03-good-day-coffee/) | An independent neighborhood coffee shop | Playful and energetic, with bold color, rounded details, and a menu-focused layout. |

These are sample concepts, not real businesses. Replace names, copy, contact details, service areas, prices, and calls to action with client-approved content before publishing.

## Preview and review

Open any template's `index.html` directly in a browser. No install or build command is needed. Review one concept at a time in its own folder; each has a separate stylesheet and does not depend on the other templates.

The repository root `index.html` is a landing page linking to all three demos. A GitHub Actions workflow deploys the root and template folders to GitHub Pages whenever changes are pushed to `main`, and can also be started manually from the Actions tab. For the first deployment, set the repository's **Settings → Pages → Build and deployment → Source** to **GitHub Actions**.

## Replacing the image placeholders

The visual panels are intentionally self-contained CSS placeholders—there are no downloaded or externally hosted images, and therefore no third-party image licenses or source attributions to manage. In each stylesheet, find the `IMAGE PLACEHOLDER` rule and replace its gradient or pattern with a `background-image: url(...)` pointing to a client-approved image. Keep the accompanying HTML placeholder label or replace the visual panel with an `<img>` that has meaningful `alt` text. Use images the client owns or has permission to use, and record the source and license with the project.

## Folder structure

```text
templates/
  01-alder-row/
    index.html
    styles.css
  02-clearview/
    index.html
    styles.css
  03-good-day-coffee/
    index.html
    styles.css
```
