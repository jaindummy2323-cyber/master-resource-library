# Performance & Caching

> Open-source tools for making websites blazing fast — caching layers, CDN, edge computing, bundle optimization, lazy loading, and performance monitoring.

---

## Caching (In-Memory & Distributed)

| Repository | Stars | Description |
|---|---|---|
| [Redis](https://github.com/redis/redis) | 67k+ | In-memory data store. Caching, pub/sub, streams, Lua scripting, clustering. Industry standard. |
| [Valkey](https://github.com/valkey-io/valkey) | 17k+ | Redis fork (Linux Foundation). Drop-in replacement, open governance, community-driven. |
| [Dragonfly](https://github.com/dragonflydb/dragonfly) | 26k+ | Modern Redis alternative. 25x throughput, multi-threaded, compatible API, less memory. |
| [KeyDB](https://github.com/nicedoc/nicedoc.io) | 8k+ | Multi-threaded Redis fork. Active replication, flash storage, MVCC. |
| [Memcached](https://github.com/memcached/memcached) | 14k+ | Distributed memory caching. Simple, fast, scales horizontally, proven at scale. |
| [node-cache](https://github.com/nicedoc/nicedoc.io) | 2k+ | Simple in-memory cache for Node.js. TTL, key-value, statistics, no dependencies. |
| [unstorage](https://github.com/unjs/unstorage) | 2k+ | Universal storage layer. Memory, Redis, Cloudflare KV, S3, filesystem — one API. |

---

## HTTP Caching & Reverse Proxy

| Repository | Stars | Description |
|---|---|---|
| [Varnish Cache](https://github.com/varnishcache/varnish-cache) | 4k+ | HTTP accelerator. Cache frontend, VCL scripting, ESI, grace mode, health checks. |
| [Nginx](https://github.com/nginx/nginx) | 25k+ | Web server + reverse proxy. Caching, load balancing, gzip, brotli, HTTP/2, HTTP/3. |
| [Caddy](https://github.com/caddyserver/caddy) | 60k+ | Auto-HTTPS web server. Reverse proxy, caching, compression, rate limiting, minimal config. |
| [Traefik](https://github.com/traefik/traefik) | 51k+ | Cloud-native edge router. Auto service discovery, Let's Encrypt, middleware, metrics. |
| [Souin](https://github.com/nicedoc/nicedoc.io) | 1k+ | HTTP cache middleware. Caddy/Traefik/Nginx plugins, distributed cache, Vary support. |

---

## Edge Computing & Workers

| Repository | Stars | Description |
|---|---|---|
| [Cloudflare Workers (Wrangler)](https://github.com/cloudflare/workers-sdk) | 3k+ | Edge compute runtime. V8 isolates, KV storage, D1 database, R2 storage, AI. |
| [Deno Deploy](https://github.com/denoland/deno) | 98k+ | Serverless edge runtime. TypeScript-first, globally distributed, web standard APIs. |
| [Vercel Edge Runtime](https://github.com/nicedoc/nicedoc.io) | 1k+ | Edge functions runtime. Lightweight, web APIs, streaming, middleware. |
| [Hono](https://github.com/honojs/hono) | 21k+ | Ultra-fast web framework for edge. Works on Cloudflare Workers, Deno, Bun, Node.js. |
| [Nitro](https://github.com/unjs/nitro) | 6k+ | Universal server engine. Edge-ready, auto-deploys to 15+ platforms, file-based routing. |

---

## Bundle Optimization

| Repository | Stars | Description |
|---|---|---|
| [Vite](https://github.com/vitejs/vite) | 69k+ | Next-gen build tool. Instant HMR, optimized builds, code splitting, tree shaking. |
| [esbuild](https://github.com/evanw/esbuild) | 38k+ | Extremely fast bundler. 100x faster than webpack, tree shaking, minification, Go-based. |
| [Turbopack](https://github.com/vercel/turborepo) | 26k+ | Incremental bundler. Rust-based, successor to Webpack, used by Next.js. |
| [Rollup](https://github.com/rollup/rollup) | 25k+ | ES module bundler. Tree shaking, code splitting, plugin ecosystem, library builds. |
| [SWC](https://github.com/nicedoc/nicedoc.io) | 31k+ | Rust-based compiler. 20x faster than Babel, minification, bundling, TypeScript. |
| [Biome](https://github.com/biomejs/biome) | 16k+ | Fast formatter + linter. Rust-based, replaces ESLint + Prettier, 200x faster. |

---

## Image & Asset Optimization

| Repository | Stars | Description |
|---|---|---|
| [Sharp](https://github.com/lovell/sharp) | 29k+ | High-performance image processing. Resize, convert, compress, watermark. libvips-based. |
| [SVGO](https://github.com/nicedoc/nicedoc.io) | 21k+ | SVG optimizer. Remove metadata, minify paths, clean attributes, plugins. |
| [imagemin](https://github.com/nicedoc/nicedoc.io) | 6k+ | Image minification. MozJPEG, pngquant, gifsicle, svgo, WebP conversion. |
| [Squoosh](https://github.com/nicedoc/nicedoc.io) | 22k+ | Image compression in browser/CLI. AVIF, WebP, MozJPEG, OxiPNG codecs. |
| [next/image](https://github.com/vercel/next.js) | 127k+ | Automatic image optimization. Lazy loading, responsive, AVIF/WebP, CDN. |
| [Partytown](https://github.com/nicedoc/nicedoc.io) | 13k+ | Move third-party scripts to web workers. Unblock main thread, keep analytics/ads. |

---

## Lazy Loading & Code Splitting

| Repository | Stars | Description |
|---|---|---|
| [React.lazy + Suspense](https://github.com/nicedoc/nicedoc.io) | — | Built-in React code splitting. Dynamic imports, loading boundaries, streaming SSR. |
| [@loadable/component](https://github.com/nicedoc/nicedoc.io) | 8k+ | React code splitting library. SSR support, prefetching, library splitting. |
| [lozad.js](https://github.com/nicedoc/nicedoc.io) | 8k+ | Lazy loading library. Images, iframes, ads, videos. IntersectionObserver-based, 1kb. |
| [vanilla-lazyload](https://github.com/nicedoc/nicedoc.io) | 8k+ | Lightweight lazy load. Images, videos, iframes. SEO-friendly, responsive, IntersectionObserver. |
| [next/dynamic](https://github.com/vercel/next.js) | 127k+ | Next.js dynamic imports. Client-only components, loading states, SSR skip. |

---

## Performance Monitoring & Metrics

| Repository | Stars | Description |
|---|---|---|
| [web-vitals](https://github.com/nicedoc/nicedoc.io) | 8k+ | Google's Core Web Vitals library. LCP, FID, CLS, INP, TTFB measurement. |
| [Lighthouse](https://github.com/nicedoc/nicedoc.io) | 28k+ | Google's web performance auditing. Performance, accessibility, SEO, PWA scoring. |
| [Unlighthouse](https://github.com/nicedoc/nicedoc.io) | 4k+ | Scan entire site with Lighthouse. Concurrent, sitemap-based, beautiful reports. |
| [SpeedCurve](https://github.com/nicedoc/nicedoc.io) | — | Synthetic + real user monitoring. Film strips, competitive benchmarking, budgets. |
| [Perfume.js](https://github.com/nicedoc/nicedoc.io) | 3k+ | Web performance monitoring. First paint, FID, CLS, navigation timing, custom metrics. |
| [Bundle Analyzer](https://github.com/nicedoc/nicedoc.io) | 13k+ | Visualize bundle contents. Tree map, find bloat, identify duplicate dependencies. |
| [Size Limit](https://github.com/nicedoc/nicedoc.io) | 6k+ | Performance budget tool. Track JS size, loading time, CI integration, GitHub Actions. |

---

## Service Workers & PWA

| Repository | Stars | Description |
|---|---|---|
| [Workbox](https://github.com/nicedoc/nicedoc.io) | 12k+ | Google's service worker toolkit. Precaching, runtime caching, offline, strategies. |
| [Serwist](https://github.com/nicedoc/nicedoc.io) | 2k+ | Next-gen Workbox fork. TypeScript-first, framework integrations, modern API. |
| [next-pwa](https://github.com/nicedoc/nicedoc.io) | 6k+ | PWA plugin for Next.js. Offline support, service worker, push notifications. |
| [vite-plugin-pwa](https://github.com/nicedoc/nicedoc.io) | 3k+ | PWA for Vite apps. Auto-generate service worker, manifest, offline page. |

---

## Database Query Optimization

| Repository | Stars | Description |
|---|---|---|
| [DataLoader](https://github.com/nicedoc/nicedoc.io) | 13k+ | Batch and cache database requests. N+1 prevention, per-request caching, any data source. |
| [Prisma Accelerate](https://github.com/nicedoc/nicedoc.io) | — | Connection pooling + global caching for Prisma. Edge-ready, query caching. |
| [pgBouncer](https://github.com/nicedoc/nicedoc.io) | 3k+ | PostgreSQL connection pooler. Reduce DB connections, transaction/session pooling. |
| [Redis caching patterns](https://github.com/nicedoc/nicedoc.io) | — | Cache-aside, write-through, write-behind, read-through patterns with Redis. |

---

## Why These Are Top-Tier

- **Redis** — 67k+ stars, universal caching standard, powers everything at scale
- **Vite** — 69k+ stars, fastest build tool, instant HMR, optimal production bundles
- **Caddy** — 60k+ stars, auto-HTTPS + reverse proxy + caching in one binary
- **Dragonfly** — 25x Redis throughput, drop-in replacement, revolutionary performance
- **esbuild** — 100x faster than webpack, makes builds trivial
- **Workbox** — Google's PWA toolkit, offline-first with minimal effort

---

## Performance Stack for $20k-$50k Sites

| Layer | Tools |
|---|---|
| Build optimization | Vite + esbuild + SWC |
| Image delivery | Sharp + imgproxy + next/image (AVIF/WebP) |
| Caching layer | Redis/Dragonfly + HTTP cache (Caddy/Varnish) |
| Edge computing | Hono + Cloudflare Workers + Nitro |
| Bundle monitoring | Size Limit + Bundle Analyzer (CI) |
| Core Web Vitals | web-vitals + Lighthouse CI |
| Third-party scripts | Partytown (offload to worker) |
| Offline/PWA | Workbox + vite-plugin-pwa |
| DB performance | DataLoader + pgBouncer + Redis cache |
