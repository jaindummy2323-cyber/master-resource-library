# Media & Storage

> Open-source tools for file storage, image/video processing, CDN, streaming, and asset management — the infrastructure layer for handling media at scale.

---

## Object Storage (S3-compatible)

| Repository | Stars | Description |
|---|---|---|
| [MinIO](https://github.com/minio/minio) | 49k+ | High-performance S3-compatible object storage. Self-hosted, distributed, Kubernetes-native. |
| [SeaweedFS](https://github.com/seaweedfs/seaweedfs) | 23k+ | Fast distributed storage. S3 API, FUSE mount, tiered storage, billions of files. |
| [Garage](https://github.com/nicedoc/nicedoc.io) | 4k+ | Lightweight S3-compatible storage. Geo-distributed, self-hosted, minimal resources. |
| [Ceph](https://github.com/ceph/ceph) | 14k+ | Enterprise distributed storage. Object, block, file. Petabyte-scale, self-healing. |

---

## Image Processing & Optimization

| Repository | Stars | Description |
|---|---|---|
| [Sharp](https://github.com/lovell/sharp) | 29k+ | High-performance Node.js image processing. Resize, crop, convert, compress. libvips-based. |
| [Imgproxy](https://github.com/imgproxy/imgproxy) | 9k+ | Fast image processing server. On-the-fly resize, crop, watermark, format conversion. |
| [Thumbor](https://github.com/thumbor/thumbor) | 10k+ | Smart image service. Crop, resize, filters, face detection, CDN-ready. Python-based. |
| [Imagor](https://github.com/cshum/imagor) | 3k+ | Fast image processing in Go. Thumbor-compatible URL, filters, S3/GCS storage. |
| [Squoosh](https://github.com/nicedoc/nicedoc.io) | 22k+ | Google's image compression tool. Multiple codecs (AVIF, WebP, MozJPEG), web app + CLI. |
| [next/image](https://github.com/vercel/next.js) | 127k+ | Next.js built-in image optimization. Lazy loading, responsive, format conversion, CDN. |
| [Unpic](https://github.com/ascorbic/unpic-img) | 1k+ | Universal image component. Works with any CDN/CMS, responsive, lazy load, all frameworks. |

---

## Video Processing & Streaming

| Repository | Stars | Description |
|---|---|---|
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) | 46k+ | Universal media toolkit. Transcode, stream, filter, mux/demux any format. |
| [ffmpeg.wasm](https://github.com/nicedoc/nicedoc.io) | 14k+ | FFmpeg in the browser via WebAssembly. Client-side video processing, no server needed. |
| [Remotion](https://github.com/remotion-dev/remotion) | 21k+ | Make videos programmatically with React. Render MP4/GIF, data-driven, server-side. |
| [Video.js](https://github.com/videojs/video.js) | 38k+ | Web video player. HLS, DASH, ads, analytics, plugins, accessibility, custom skins. |
| [Plyr](https://github.com/sampotts/plyr) | 27k+ | Simple HTML5 media player. Video, audio, YouTube, Vimeo. Accessible, customizable. |
| [HLS.js](https://github.com/nicedoc/nicedoc.io) | 15k+ | HTTP Live Streaming client. Adaptive bitrate, buffer management, EME DRM. |
| [Shaka Player](https://github.com/nicedoc/nicedoc.io) | 7k+ | Google's media player. DASH, HLS, DRM, offline, accessibility, live streaming. |

---

## File Upload Infrastructure

| Repository | Stars | Description |
|---|---|---|
| [Uppy](https://github.com/transloadit/uppy) | 29k+ | Modular file uploader. Drag-and-drop, webcam, URL, resumable (tus), cloud sources. |
| [tus](https://github.com/tus/tus-node-server) | 900+ | Open resumable upload protocol. Resume interrupted uploads, any file size. |
| [FilePond](https://github.com/pqina/filepond) | 15k+ | File upload library. Image preview, validation, progress, transform, all frameworks. |
| [Filebrowser](https://github.com/filebrowser/filebrowser) | 26k+ | Web file manager. Upload, download, share, edit. Self-hosted, Docker, auth. |
| [Minio Client (mc)](https://github.com/minio/mc) | 3k+ | CLI for S3-compatible storage. Sync, mirror, cp, rm, admin operations. |

---

## CDN & Edge Delivery

| Repository | Stars | Description |
|---|---|---|
| [Varnish Cache](https://github.com/varnishcache/varnish-cache) | 4k+ | HTTP accelerator. Cache frontend, load balancing, edge logic, ESI support. |
| [Nginx (caching)](https://github.com/nicedoc/nicedoc.io) | — | Reverse proxy with caching. Static file serving, gzip, brotli, HTTP/2, SSL. |
| [Caddy (file server)](https://github.com/caddyserver/caddy) | 60k+ | Web server with auto-HTTPS. Static file serving, reverse proxy, caching, compression. |
| [KeyCDN (self-hosted)](https://github.com/nicedoc/nicedoc.io) | — | Pull-zone CDN concepts. Origin shield, cache purge, geo-distribution strategies. |
| [BunnyCDN (client)](https://github.com/nicedoc/nicedoc.io) | — | CDN API integration. Storage zones, pull zones, purge, stream (video CDN). |

---

## Digital Asset Management (DAM)

| Repository | Stars | Description |
|---|---|---|
| [Pimcore](https://github.com/pimcore/pimcore) | 3k+ | Enterprise DAM + PIM. Asset management, metadata, versions, workflows. |
| [ResourceSpace](https://github.com/nicedoc/nicedoc.io) | 100+ | Open-source DAM. Collections, metadata, search, API, watermarking, sharing. |
| [Damster](https://github.com/nicedoc/nicedoc.io) | — | Lightweight digital asset management for teams. Tags, collections, previews. |
| [Directus Files](https://github.com/directus/directus) | 28k+ | File management built into Directus. Thumbnails, transforms, access control, S3. |

---

## Audio Processing

| Repository | Stars | Description |
|---|---|---|
| [Howler.js](https://github.com/goldfire/howler.js) | 24k+ | Audio library for the web. Sprite sheets, spatial audio, fade, cross-browser. |
| [Tone.js](https://github.com/Tonejs/Tone.js) | 14k+ | Web Audio framework. Synthesizers, effects, sequencing, transport, instruments. |
| [Peaks.js](https://github.com/nicedoc/nicedoc.io) | 3k+ | BBC's audio waveform viewer. Zoom, segments, points, custom rendering. |
| [WaveSurfer.js](https://github.com/nicedoc/nicedoc.io) | 9k+ | Audio waveform visualization. Playback, regions, spectrogram, plugins. |

---

## PDF Generation & Processing

| Repository | Stars | Description |
|---|---|---|
| [pdf-lib](https://github.com/Hopding/pdf-lib) | 7k+ | Create and modify PDFs in JavaScript. No native dependencies, browser + Node.js. |
| [Puppeteer (PDF)](https://github.com/nicedoc/nicedoc.io) | 89k+ | Generate PDFs from HTML. Chrome rendering, CSS support, headers/footers. |
| [React PDF](https://github.com/diegomura/react-pdf) | 15k+ | Create PDFs with React components. Styled primitives, flexbox layout, streaming. |
| [Gotenberg](https://github.com/gotenberg/gotenberg) | 8k+ | Docker PDF generation API. HTML-to-PDF, Chromium + LibreOffice, merge, convert. |
| [PDFKit](https://github.com/foliojs/pdfkit) | 10k+ | JavaScript PDF generation library. Vector graphics, text, images, annotations. |

---

## Why These Are Top-Tier

- **MinIO** — 49k+ stars, the gold standard for self-hosted S3 storage
- **Sharp** — 29k+ stars, fastest image processing for Node.js, production standard
- **Uppy** — 29k+ stars, best file upload experience with resumable support
- **FFmpeg** — Universal media tool, powers 90% of video infrastructure
- **Remotion** — Programmatic video creation, unique capability for dynamic content
- **Video.js** — 38k+ stars, most deployed web video player

---

## Implementation Guide

| Use Case | Recommended Stack |
|---|---|
| Image optimization | Sharp + imgproxy + next/image |
| File uploads | Uppy + tus + MinIO (S3) |
| Video hosting | FFmpeg + HLS.js + Video.js |
| Programmatic video | Remotion (React-based) |
| PDF generation | React PDF or Gotenberg |
| Audio player | Howler.js + WaveSurfer.js |
| Self-hosted storage | MinIO + Filebrowser |
| CDN caching | Caddy + Varnish + BunnyCDN |
