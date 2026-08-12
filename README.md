# Portfolio Website

Legacy static personal portfolio based on UIdeck's **Unfold** Bootstrap template. The repository contains a customized `index.html` page plus the template's original CSS, JavaScript, font/icon, carousel, popup, image, and Bootstrap assets.

## Ownership and structure

- `index.html` — customized portfolio content and the page entry point.
- `assets/css/style.css` — UIdeck Unfold template stylesheet; its upstream attribution header is preserved.
- `assets/css/bootstrap.min.css`, `LineIcons.css`, `magnific-popup.css`, and related files — third-party/template assets.
- `assets/js/main.js` — UIdeck Unfold template behavior; upstream attribution is preserved.
- `assets/js/vendor/` plus Bootstrap, jQuery, Popper, Magnific Popup, Parallax, Slick, Waypoints, and CounterUp files — third-party/vendor code.
- `assets/images/` — portfolio and template imagery.
- `CNAME`, `robots.txt`, `_config.yml`, and `.nojekyll` — static-hosting/discovery configuration.

The vendor/template files are intentionally not rewritten with project-specific comments. Their own headers and licenses describe their ownership. Project-specific maintenance should focus on the customized HTML/content and any new authored code added outside those vendor files.

## Running locally

No package manager or build step is required. Serve the repository root with any static HTTP server and open `index.html` through that server.

For example:

```bash
python -m http.server 8080
```

## Maintenance notes

This is a legacy template-based portfolio. Keep relative asset paths stable unless all linked HTML/CSS/JavaScript references are migrated together. If replacing template functionality with newly authored code, place that ownership boundary clearly in the repository instead of modifying minified/vendor files in place.

Repository README rewriting workflows, generated repository reports, machine-profile files, and operating-system metadata are not part of the site and should not be committed.

## Status

The repository remains a functional historical portfolio/template snapshot. Its customized `index.html` still needs a dedicated authored-markup documentation pass before the repository is considered fully normalized under the account-wide cleanup standard.
