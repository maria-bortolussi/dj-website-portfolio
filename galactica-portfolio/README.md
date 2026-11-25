# Galáctica web projects

Frontend source excerpts from my WordPress projects and a Cloudflare Worker for audio uploads.

| Project | Source | What it demonstrates |
| --- | --- | --- |
| [Galáctica Live Radio](projects/live-radio/wordpress-content.html) | Production WordPress page | Live audio UI, station visuals and player integrations |
| [DJ Tracklist Creator](projects/tracklist-creator/wordpress-content.html) | Production WordPress page | A publishing workflow for DJ tracklists |
| [Portal G](projects/portal-g/wordpress-content.html) | Staging WordPress page | A prototype for presenting charts |
| [Orbital UI Lab](projects/orbital-lab/wordpress-content.html) | Staging WordPress page | An experimental interface for the live radio experience |
| [Orbital Uploader](projects/orbital-uploader/worker.js) | Cloudflare Worker source | Uploading lossless audio to private R2 storage |

[Live radio](https://noebortolussi.com/live-radio) · [Tracklist Creator](https://noebortolussi.com/tracklist-creator)

The WordPress files are page-content snapshots. They depend on the original site's theme, plugins, assets and endpoints. The uploader requires a private R2 binding named `ORBITAL_STORAGE` and a Worker secret named `UPLOAD_PASSWORD`. Review each project's dependencies before deploying it.
