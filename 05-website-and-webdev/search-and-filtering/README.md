# Search & Filtering

> Open-source search engines, full-text search libraries, faceted filtering, autocomplete, and search UI components for building powerful discovery experiences.

---

## Search Engines (Self-hosted)

| Repository | Stars | Description |
|---|---|---|
| [Meilisearch](https://github.com/meilisearch/meilisearch) | 48k+ | Lightning-fast search. Typo tolerance, faceting, filtering, geo, vector/hybrid search, SDKs for all languages. |
| [Typesense](https://github.com/typesense/typesense) | 21k+ | Fast, typo-tolerant search. Faceting, geo, vector search, curation, synonyms, API-first. |
| [Zinc](https://github.com/zincsearch/zincsearch) | 17k+ | Lightweight Elasticsearch alternative. Full-text search, low resource usage, simple API. |
| [Manticore Search](https://github.com/manticoresoftware/manticoresearch) | 9k+ | Database for search. Full-text, columnar storage, auto-schema, SQL-compatible. |
| [Sonic](https://github.com/valeriansaliou/sonic) | 20k+ | Fast, lightweight search backend. Sub-millisecond queries, autocomplete, suggest. |
| [Tantivy](https://github.com/quickwit-oss/tantivy) | 12k+ | Full-text search library in Rust. Lucene-inspired, fast, BM25, phrase queries. |
| [Quickwit](https://github.com/quickwit-oss/quickwit) | 8k+ | Cloud-native search engine. Sub-second search on petabytes, S3-native, Kafka ingest. |

---

## Client-side / Edge Search

| Repository | Stars | Description |
|---|---|---|
| [Orama](https://github.com/askorama/orama) | 10k+ | Full-text + vector + hybrid search in browser/edge. TypeScript, facets, AI answers. |
| [FlexSearch](https://github.com/nicedoc/nicedoc.io) | 12k+ | Fastest in-memory full-text search. Zero dependencies, phonetic matching, web workers. |
| [Fuse.js](https://github.com/krisk/Fuse) | 18k+ | Lightweight fuzzy search. No dependencies, weighted scoring, configurable threshold. |
| [Lunr.js](https://github.com/olivernn/lunr.js) | 9k+ | Client-side full-text search. Pre-built index, no server needed, small bundle. |
| [MiniSearch](https://github.com/lucaong/minisearch) | 4k+ | Tiny full-text search engine. Prefix search, fuzzy match, auto-suggest, 7kb gzipped. |
| [Pagefind](https://github.com/CloudCannon/pagefind) | 4k+ | Static site search. Indexes at build time, 6kb JS, works with any SSG. |

---

## Search UI Components

| Repository | Stars | Description |
|---|---|---|
| [InstantSearch.js](https://github.com/algolia/instantsearch) | 4k+ | UI library for search. React, Vue, Angular. Facets, pagination, infinite scroll, autocomplete. |
| [React InstantSearch](https://github.com/algolia/instantsearch) | 4k+ | React widgets for search. Hits, refinements, pagination, range sliders, stats. |
| [Autocomplete.js](https://github.com/algolia/autocomplete) | 3k+ | Fast, accessible autocomplete. Multi-source, keyboard navigation, templates, plugins. |
| [cmdk](https://github.com/pacocoursey/cmdk) | 10k+ | Command palette component for React. Fast, accessible, composable, used by Vercel/Linear. |
| [kbar](https://github.com/timc1/kbar) | 5k+ | Command palette for React apps. Keyboard shortcuts, actions, nested menus. |
| [Downshift](https://github.com/downshift-js/downshift) | 12k+ | Primitives for building autocomplete/combobox/select. Accessible, flexible, headless. |

---

## Faceted Filtering & Data Tables

| Repository | Stars | Description |
|---|---|---|
| [TanStack Table](https://github.com/TanStack/table) | 25k+ | Headless table library. Sorting, filtering, pagination, grouping, virtualization. All frameworks. |
| [AG Grid](https://github.com/nicedoc/nicedoc.io) | 13k+ | Enterprise data grid. Filtering, grouping, pivoting, charting. Community edition free. |
| [Mantine DataTable](https://github.com/nicedoc/nicedoc.io) | 1k+ | Data table component for Mantine. Sorting, filtering, pagination, row selection. |
| [shadcn/ui Data Table](https://github.com/nicedoc/nicedoc.io) | — | TanStack Table + shadcn/ui. Column visibility, filtering, sorting, pagination. |
| [Refine](https://github.com/refinedev/refine) | 29k+ | React framework for data-intensive apps. Built-in filtering, CRUD, any UI/API. |

---

## Elasticsearch Alternatives & Wrappers

| Repository | Stars | Description |
|---|---|---|
| [OpenSearch](https://github.com/opensearch-project/OpenSearch) | 10k+ | AWS fork of Elasticsearch. Full-text, analytics, observability, security, dashboards. |
| [ElasticSearch (client)](https://github.com/elastic/elasticsearch-js) | 5k+ | Official Node.js client for Elasticsearch. Bulk, scroll, suggest, aggregations. |
| [Searchkit](https://github.com/searchkit/searchkit) | 5k+ | Search UI for Elasticsearch/OpenSearch. InstantSearch-compatible, GraphQL, React. |
| [AppBase.io](https://github.com/nicedoc/nicedoc.io) | 2k+ | Hosted Elasticsearch with search UI builder. ReactiveSearch components, analytics. |

---

## Specialized Search

| Repository | Stars | Description |
|---|---|---|
| [Atlas (MongoDB)](https://github.com/nicedoc/nicedoc.io) | — | MongoDB Atlas Search. Full-text, autocomplete, facets, embedded in your database. |
| [pg_trgm + GIN (Postgres)](https://github.com/nicedoc/nicedoc.io) | — | PostgreSQL trigram similarity search. Fuzzy matching, GIN/GiST indexes, built-in. |
| [ParadeDB](https://github.com/paradedb/paradedb) | 6k+ | Postgres for search and analytics. BM25 full-text, hybrid search, columnar storage. |
| [ZincObserve](https://github.com/nicedoc/nicedoc.io) | 12k+ | Log search and observability. Petabyte-scale, S3 storage, 10x less resource usage. |

---

## Why These Are Top-Tier

- **Meilisearch** — 48k+ stars, best DX, instant results, typo-tolerant out of the box
- **Typesense** — Enterprise-ready, vector search built-in, great Algolia alternative
- **Orama** — Runs entirely in browser/edge, no server needed, AI-powered answers
- **cmdk** — Used by Vercel, Linear, Raycast — the modern command palette standard
- **TanStack Table** — 25k+ stars, headless, works with any UI, any framework
- **Pagefind** — Perfect for static sites, zero config, tiny bundle

---

## Implementation Guide

| Use Case | Recommended Stack |
|---|---|
| SaaS product search | Meilisearch or Typesense (self-hosted) |
| Documentation search | Pagefind (static) or Orama (edge) |
| E-commerce catalog | Typesense + InstantSearch.js (facets) |
| Command palette | cmdk or kbar |
| Blog/content search | Fuse.js (small) or MiniSearch (medium) |
| Enterprise full-text | OpenSearch or ParadeDB (Postgres-native) |
| AI-powered search | Meilisearch vector + Orama AI answers |
| Autocomplete/suggest | Autocomplete.js + Meilisearch |
