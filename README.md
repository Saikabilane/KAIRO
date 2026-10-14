# KAIRO'25 — Event Website

KAIRO'25 is a multi-page event website built with HTML, CSS and JavaScript. Its pages present event information and navigation for an ECE-related event, including sign-in/sign-up pages, event details and paper-presentation information.

## Features
- Landing page with responsive navigation and animated visual elements.
- Event and event-listing pages.
- Paper-presentation information page.
- Sign-in and sign-up interfaces.
- Shared visual assets, logos and page-transition behavior.

## Project structure
- `index.html` — main landing page.
- `home.css` — landing page styles.
- `event.html`, `eventsPage.html`, `paperPresentation.html` — event and presentation pages.
- `SignIn.html`, `SignUp.html` and matching CSS files — account interface pages.
- `dash.html`, `dash.css` — dashboard page and styles.
- `page-transition.js` — page transition behavior.
- Image files in the root directory — logos, backgrounds and event imagery.

## Run locally
Clone the repository and open `index.html` in a browser, or serve the folder using a local static web server. The site loads some fonts and icons from external CDNs, so an internet connection may be needed for the full appearance.

## Deployment notes
This repository is primarily a static front end. Do not treat a sign-in form as secure authentication unless it is connected to a properly implemented backend. Before publishing, review all links, replace outdated event details as appropriate, and ensure you have permission to use included logos and photographs.

## License
No license file is currently included. Contact the repository owner for reuse permission.
