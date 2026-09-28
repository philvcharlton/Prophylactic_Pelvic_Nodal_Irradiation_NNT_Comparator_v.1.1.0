# Prophylactic Pelvic Nodal Irradiation – NNT Comparator

Standalone package version 1.3.0, build 2026.09.28.

## Immediate offline use

Open `index.html` directly in a modern browser. All calculations, trial summaries, toxicity data, QOL results, styling and references required for the NNT Comparator are contained locally. No internet connection, server, account or installation is required.

## Installable offline web app

To enable installation and automatic offline caching, serve this folder over HTTPS or a local web server. Upload the folder unchanged, with `index.html` at its root. The included manifest, service worker and icons support installation on current Chrome, Edge, Android and iOS/iPadOS browsers. Direct `file://` opening works as a standalone comparator but browsers do not permit service-worker installation from local files.

## Privacy and data handling

The NNT Comparator runs entirely in the browser. It has no backend, database, analytics, login, cookies or patient-data transmission. Custom values remain in the current browser page and are not saved.

## Package contents

- `index.html` — standalone NNT Comparator
- `USER_GUIDE.html` — beginner and advanced use instructions
- `METHODOLOGY_AND_REFERENCES.html` — equations, interpretation and evidence sources
- `validation.html` — automated known-answer tests
- `CLINICAL_DISCLAIMER.html` — intended-use and safety limitations
- `manifest.webmanifest`, `service-worker.js`, `icons/` — installable offline support
- `RELEASE_NOTES.md` — version history

## Validation before deployment

Open `validation.html` and confirm that every test reports PASS. Do not alter trial constants or calculation code without updating and rerunning the validation cases.
