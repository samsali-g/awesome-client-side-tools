# Awesome Client-Side Web Tools

A curated list of web tools that process files **entirely in the browser** — no upload, no server copy, no account required. The privacy guarantee is architectural: if the code runs on your device, there is nothing to leak from a server.

Contributions welcome. Criteria: the core processing must run client-side (WASM, Canvas, Web APIs), and the tool must be free to use.

## Photo & Image

- [ExifStudio](https://www.exifstudio.online) — EXIF/IPTC/XMP viewer & editor, GPS stripper, HEIC→JPG, exact-KB compressor, brush redaction, image splitter, 300 DPI passport photos. 24 tools, WASM + Canvas.
- [Squoosh](https://squoosh.app) — image compression with side-by-side codec comparison (MozJPEG, WebP, AVIF, OxiPNG).
- [Photopea](https://www.photopea.com) — full raster editor (PSD, XD, Sketch, XCF), layers, masks, filters.
- [Remove.bg](https://www.remove.bg) — background removal (note: uploads to server; listed for contrast, not client-side).
- [SVGOMG](https://jakearchibald.github.io/svgomg/) — SVGO optimizer UI, runs locally.
- [Favicon Generator](https://realfavicongenerator.net) — favicon package generation (server-assisted; check before sensitive use).

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

## Astronomy & Planning (same maker, same philosophy)

- [Alfalaki](https://alfalaki.space) — natal charts from live ephemeris, moon phases, lunar months, eclipses, planetary hours. Static pages + edge rendering, English & Arabic.
- [WedMaroc](https://www.wedmaroc.com) — Moroccan wedding budget calculator across 28 cities, guides in Arabic/French/English. No account, no vendor commissions.

## Why client-side matters

Every "online converter" that uploads your file creates a copy on someone else's disk, with a retention policy you cannot audit. For photos of your home, your children, client work, or identity documents, the upload step is the risk. Client-side tools remove it. When evaluating a tool, open DevTools → Network and watch whether your file ever leaves the machine.

---

License: CC0. No affiliate links.
