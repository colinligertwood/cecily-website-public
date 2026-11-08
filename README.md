# Cecily website

The website for the Cecily apps, Cecily Budget, Cecily Cards and Cecily Tasks, served at [cecily.app](https://cecily.app). The apps' code is on GitHub: [Budget](https://github.com/colinligertwood/cecily-budget-public), [Cards](https://github.com/colinligertwood/cecily-cards-public), [Tasks](https://github.com/colinligertwood/cecily-tasks-public) and [CecilyKit](https://github.com/colinligertwood/cecily-kit-public), the package they share.

| Page | File |
| --- | --- |
| Front page | `index.html` |
| Cecily Budget | `budget.html` |
| Cecily Cards | `cards.html` |
| Cecily Tasks | `tasks.html` |
| News and releases | `news.html` |
| Privacy | `privacy.html` |

## How it's built

Plain HTML and CSS, with no build step and no scripts beyond CSS animation. Open `index.html` in a browser to see it.

- Each page is one file: its styles in a `<style>` block and the wordmark as inline SVG. The app icons are images in `icons/`, drawn as the system draws them.
- Headings use Silom, then `fonts/ChicagoFLF.woff`, then Geneva; body text uses Geneva, then Verdana.
- The front page's monitor flips between a Budget, a Cards and a Tasks screen every five seconds, in CSS. Visitors who ask their system for reduced motion see the Budget screen, still.
- The layout is drawn for 1440 pixels wide. Below 1380 pixels, rows side by side stack, and the margins narrow at 900 and 640 pixels, down to a phone.

## Rights

The site's words, pages and artwork, and the Cecily name, mark, wordmark and icons, belong to Colin Ligertwood, with all rights reserved: see `NOTICE`. ChicagoFLF is in the public domain: see `fonts/README.ChicagoFLF.txt`.
