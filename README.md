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

## Images and map

The demos use a mix of sample CSS artwork and externally hosted photographs. Photo credits and license links are shown beside the photos and listed below; the Manchester map is an OpenStreetMap embed with its attribution displayed by the map. External photos and the interactive map need an internet connection. Other visual panels remain replaceable CSS artwork; use client-approved images or update the gradients in each template's stylesheet. Check usage rights and any model/property releases before adapting demo assets for a client.

### Photo sources

- **Alder & Row — office interior:** Mike Peel, [WMUK office - meeting room.jpg](https://commons.wikimedia.org/wiki/File:WMUK_office_-_meeting_room.jpg), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Credit: “Mike Peel / Wikimedia Commons / CC BY-SA 4.0.”
- **Clearview — window cleaner:** François Schnell, [WindowCleaner.jpg](https://commons.wikimedia.org/wiki/File:WindowCleaner.jpg), [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/). Credit: “François Schnell / Wikimedia Commons / CC BY 2.0.”
- **Good Day Coffee — coffee:** Nathan Dumlao, [photo on Unsplash](https://unsplash.com/photos/focus-photography-of-coffee-artwork-r-KfktlyBL0), [Unsplash License](https://unsplash.com/license). Attribution is not required by the license; credit is included here.

The map in Good Day Coffee centers on Manchester, UK (53.4808, -2.2426). Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

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
