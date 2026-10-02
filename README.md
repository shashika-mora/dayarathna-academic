# dayarathna-academic

Academic curriculum documentation, systems coursework, and study records for Shashika Dayarathna, deployed at [academic.dayarathna.com](https://academic.dayarathna.com).

## Scope & Status

This repository documents undergraduate studies in the Department of Computer Science & Engineering at the University of Moratuwa, Sri Lanka.

- **Current Status**: Active undergraduate coursework (Class of 2027). Core modules in systems architecture, operating systems, algorithms, and databases.
- **Academic Integrity**: This repository indexes open-source lab implementations (e.g. `WCSS-nano-processor/nano-processor`) and conceptual notes. Confidential exams, grading keys, and proprietary university materials are excluded.

## Architecture

- **Stack**: Pure semantic HTML5, pure CSS3, and vanilla ES6+ JavaScript.
- **Visual System**: Celestial space aesthetic matching `dayarathna.com`, dark palette (`#070a10`), neon lime accents (`#c7f44a`), typography (`DM Sans`, `IBM Plex Mono`, `Instrument Serif`), and HTML5 Canvas starfield.
- **Dependencies**: Zero runtime dependencies, zero build steps.
- **Hosting**: Firebase Hosting targeting site `shashika-dev-academic` under project `shashika-dev`.

## Edit Workflow

1. To update coursework milestones or curriculum details, edit `index.html`.
2. Static assets (schematics, lab diagrams) belong in `public/`.
3. Preview locally with any static HTTP server (`python -m http.server 8080`).

## Deployment

Deploy strictly to the dedicated academic hosting site:

```sh
npx firebase-tools deploy --only hosting:academic --project shashika-dev
```

## Maintainer

Maintained by Shashika Dayarathna. Main portfolio: [https://dayarathna.com](https://dayarathna.com).
