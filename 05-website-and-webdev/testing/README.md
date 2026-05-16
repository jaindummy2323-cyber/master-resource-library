# Testing & Quality Assurance

> The best open-source testing frameworks, E2E tools, and quality assurance libraries for web development.

---

## End-to-End (E2E) Testing

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Playwright](https://github.com/microsoft/playwright) | 68k+ | Cross-browser E2E testing by Microsoft. | Best E2E tool. Chromium, Firefox, WebKit. Auto-wait. Codegen. |
| [Cypress](https://github.com/cypress-io/cypress) | 47k+ | Fast, easy, reliable testing for anything in a browser. | Time-travel debugging. Real browser testing. Great DX. |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | 89k+ | Chrome/Chromium automation library by Google. | Official Google tool. Headless Chrome control. Scraping + testing. |
| [Selenium](https://github.com/SeleniumHQ/selenium) | 31k+ | Browser automation framework. Multi-language. | Industry standard. Supports all browsers and languages. |

## Unit & Integration Testing

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Vitest](https://github.com/vitest-dev/vitest) | 13k+ | Blazing fast unit testing framework powered by Vite. | Vite-native. Jest-compatible API. TypeScript out of the box. |
| [Jest](https://github.com/jestjs/jest) | 44k+ | Delightful JavaScript testing. | Most popular JS testing framework. Snapshot testing. Mocking. |
| [Testing Library](https://github.com/testing-library/react-testing-library) | 19k+ | Simple utilities for testing React components. | Test like users interact. Framework-agnostic versions available. |
| [pytest](https://github.com/pytest-dev/pytest) | 12k+ | Python testing framework. | Python standard. Fixtures, plugins, parametrize. Simple yet powerful. |
| [Mocha](https://github.com/mochajs/mocha) | 23k+ | Feature-rich JavaScript test framework for Node.js. | Flexible. BDD/TDD. Great with Chai assertion library. |

## API Testing

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Hoppscotch](https://github.com/hoppscotch/hoppscotch) | 66k+ | Open-source API development ecosystem. | Best open-source Postman alternative. Tests, collections, environments. |
| [Bruno](https://github.com/usebruno/bruno) | 28k+ | Offline-first API client. Git-friendly. | Files on disk. Version-controlled API tests. Privacy-first. |
| [Supertest](https://github.com/ladjs/supertest) | 14k+ | HTTP assertions for Node.js. | Test Express/Koa/Fastify APIs directly. No server needed. |
| [k6](https://github.com/grafana/k6) | 26k+ | Modern load testing tool by Grafana. | JavaScript-based load tests. Beautiful metrics. CLI + cloud. |

## Visual & Accessibility Testing

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Storybook](https://github.com/storybookjs/storybook) | 85k+ | UI component development and testing environment. | Industry standard for component development. Visual testing. Addons. |
| [Chromatic](https://github.com/chromaui/chromatic-cli) | 1k+ | Visual testing for Storybook components. | Pixel-level visual diffs. CI integration. By Storybook team. |
| [axe-core](https://github.com/dequelabs/axe-core) | 6k+ | Accessibility testing engine for web pages. | WCAG compliance checking. Browser extension + CI integration. |
| [Pa11y](https://github.com/pa11y/pa11y) | 5k+ | Automated accessibility testing tool. | CLI-based. CI-friendly. WCAG 2.1 AA testing. |

## Mocking & Test Utilities

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [MSW (Mock Service Worker)](https://github.com/mswjs/msw) | 16k+ | API mocking library for browser and Node.js. | Intercepts requests at network level. Works in tests and dev. |
| [Faker.js](https://github.com/faker-js/faker) | 13k+ | Generate realistic fake data for testing. | Names, addresses, emails, images. 60+ locales. TypeScript. |
| [Nock](https://github.com/nock/nock) | 13k+ | HTTP server mocking for Node.js. | Mock external API calls in tests. Pattern matching. |
| [json-server](https://github.com/typicode/json-server) | 73k+ | Full fake REST API with zero coding. | Create mock APIs from JSON files. 30 seconds to setup. |

---

## Selection Criteria Applied
- Every repo above has 1,000+ GitHub stars (most have 10k+)
- All actively maintained (commits within 2025-2026)
- Production-ready with clear documentation
- Standard in the industry for their category
- Permissive licenses (MIT, Apache 2.0)

## How to Choose
- **E2E testing?** -> Playwright (best overall) or Cypress (great DX)
- **Unit testing (JS)?** -> Vitest (modern, fast) or Jest (most popular, mature)
- **Component testing?** -> Testing Library (test like users) + Storybook (visual)
- **API testing?** -> Hoppscotch (GUI) or Supertest (code-based)
- **Load testing?** -> k6 (JavaScript, modern, Grafana ecosystem)
- **Mock APIs?** -> MSW (network-level) or json-server (zero-config fake API)
- **Test data?** -> Faker.js (realistic fake data)
- **Accessibility?** -> axe-core (engine) or Pa11y (CLI tool)
- **Python testing?** -> pytest (standard, powerful)
