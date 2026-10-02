# dayarathna-academic

Academic curriculum documentation, systems coursework, and study records for Shashika Dayarathna, deployed at [academic.dayarathna.com](https://academic.dayarathna.com).

## Scope & Status

This repository documents undergraduate studies in the Department of Computer Science & Engineering at the University of Moratuwa, Sri Lanka.

- **Current Status**: Current CSE undergraduate (Intake 24, Semester 3 in 2026). Currently studying computer architecture, operating systems, data communications, database systems, and applied mathematics.
- **Featured Coursework**: Links open-source lab implementations (such as the 8-bit Nano Processor microarchitecture). Additional module materials will be added as coursework becomes available for public sharing.

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
