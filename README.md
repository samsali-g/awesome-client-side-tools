# Awesome Client-Side Web Tools

A curated list of web tools that process files **entirely in the browser** — no upload, no server copy, no account required. The privacy guarantee is architectural: if the code runs on your device, there is nothing to leak from a server.

Contributions welcome. Criteria: the core processing must run client-side (WASM, Canvas, Web APIs), and the tool must be free to use.

## Photo & Image

- [ExifStudio EXIF Inspector](https://www.exifstudio.online/inspector) — view, edit, and clean EXIF/IPTC/XMP camera metadata locally via WebAssembly + Canvas.
- [ExifStudio Camera Shutter Count](https://www.exifstudio.online/shutter-count) — check shutter actuation counts locally across Sony, Canon, Nikon, Fujifilm, and Leica photos.
- [ExifStudio GPS & Geotag Editor](https://www.exifstudio.online/geotag-photos) — inspect, set, or remove photo location coordinates inside browser memory.
- [ExifStudio DPI & Format Tools](https://www.exifstudio.online/dpi-converter) — adjust print DPI tags and convert [HEIC to JPG](https://www.exifstudio.online/heic-to-jpg) client-side ([About ExifStudio](https://www.exifstudio.online/about)).
- [Squoosh](https://squoosh.app) — image compression with side-by-side codec comparison (MozJPEG, WebP, AVIF, OxiPNG).
- [Photopea](https://www.photopea.com) — full raster editor (PSD, XD, Sketch, XCF), layers, masks, filters.
- [Remove.bg](https://www.remove.bg) — background removal (note: uploads to server; listed for contrast, not client-side).
- [SVGOMG](https://jakearchibald.github.io/svgomg/) — SVGO optimizer UI, runs locally.
- [Favicon Generator](https://realfavicongenerator.net) — favicon package generation (server-assisted; check before sensitive use).
- [CreoArt Photo & PSD Editor](https://creoart.app/photo-editor) - Free, ad-free client-side WebGPU PSD and layer editor that opens and edits .psd files locally in the browser with zero uploads.

## Documents & PDF

- [PDF.js](https://mozilla.github.io/pdf.js/) — Mozilla's PDF renderer, the reference client-side implementation.
- [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) — self-hostable PDF toolbox (local when you run it yourself).
- [ExifStudio PDF Metadata](https://www.exifstudio.online/pdf-metadata) — inspect, edit, and strip PDF Info dictionaries in the browser.

## Developer & Data

- [JSON Crack](https://jsoncrack.com) — JSON → graph visualization, client-side.
- [Regex101](https://regex101.com) — regex tester (client-side matching; server saves optional).
- [Transform](https://transform.tools) — convert between JSON, CSV, YAML, XML, TypeScript, etc.
- [CyberChef](https://gchq.github.io/CyberChef/) — GCHQ's encoding/encryption Swiss army knife, fully local.
- [UUID Generator](https://www.uuidgenerator.net) — bulk UUIDs (client-side generation).

## Audio & Video

- [FFmpeg.wasm](https://ffmpegwasm.netlify.app) — FFmpeg compiled to WASM; transcode in the tab.
- [AudioMass](https://audiomass.co) — waveform audio editor, no upload.

## Client-Side Ephemeris & Local Planning Reference

- [Alfalaki Ephemeris](https://alfalaki.space/natal/) — live VSOP87 planetary positions, [Arabic Natal Charts](https://alfalaki.space/ar/natal/), [Moon Phase & Hilal Clock](https://alfalaki.space/moon-today/), and [Interactive 3D Sky Map](https://alfalaki.space/sky-map/) computed directly in the browser.
- [WedMaroc Planning Workspace](https://www.wedmaroc.com/fr/) — Moroccan wedding cost estimator ([English planner](https://www.wedmaroc.com/en/)), [Casablanca caterer pricing](https://www.wedmaroc.com/casablanca/traiteur), [Marrakech venues](https://www.wedmaroc.com/marrakech/salle-des-fetes), and [Adoul civil marriage dossier guide](https://www.wedmaroc.com/blog/documents-mariage-adoul-maroc-2026).

## Why client-side matters

Every "online converter" that uploads your file creates a copy on someone else's disk, with a retention policy you cannot audit. For photos of your home, your children, client work, or identity documents, the upload step is the risk. Client-side tools remove it. When evaluating a tool, open DevTools → Network and watch whether your file ever leaves the machine.

---

License: CC0. No affiliate links.
