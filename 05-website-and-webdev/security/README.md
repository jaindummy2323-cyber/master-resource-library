# Web Security

> Open-source security tools for web applications — vulnerability scanning, WAF, rate limiting, secrets management, OWASP compliance, and hardening. Everything needed to secure a production website.

---

## Vulnerability Scanning & Penetration Testing

| Repository | Stars | Description |
|---|---|---|
| [OWASP ZAP](https://github.com/zaproxy/zaproxy) | 13k+ | World's most popular web app security scanner. Active/passive scanning, API testing, CI/CD integration. |
| [Nuclei](https://github.com/projectdiscovery/nuclei) | 21k+ | Fast vulnerability scanner with YAML templates. 8000+ community templates, CI/CD ready. |
| [Nikto](https://github.com/sullo/nikto) | 8k+ | Web server scanner. Tests for 7000+ dangerous files, outdated versions, misconfigurations. |
| [SQLMap](https://github.com/sqlmapproject/sqlmap) | 32k+ | Automatic SQL injection detection and exploitation. Database takeover tool. |
| [Wapiti](https://github.com/wapiti-scanner/wapiti) | 4k+ | Web vulnerability scanner. XSS, SQL injection, file disclosure, command execution detection. |
| [Trivy](https://github.com/aquasecurity/trivy) | 24k+ | All-in-one security scanner. Containers, filesystems, Git repos, Kubernetes, IaC, SBOM. |
| [Snyk CLI](https://github.com/snyk/cli) | 5k+ | Find and fix vulnerabilities in dependencies, containers, IaC. CI/CD integration. |
| [Grype](https://github.com/anchore/grype) | 9k+ | Vulnerability scanner for container images and filesystems. Fast, accurate, SBOM-aware. |

---

## Web Application Firewall (WAF)

| Repository | Stars | Description |
|---|---|---|
| [ModSecurity](https://github.com/SpiderLabs/ModSecurity) | 8k+ | Industry-standard open-source WAF engine. OWASP Core Rule Set, Apache/Nginx/IIS. |
| [Coraza](https://github.com/corazawaf/coraza) | 2k+ | Enterprise-grade WAF in Go. ModSecurity-compatible, OWASP CRS, Caddy/Traefik plugins. |
| [SafeLine](https://github.com/chaitin/SafeLine) | 15k+ | Web application firewall. Semantic analysis engine, one-click deployment, Docker-based. |
| [NAXSI](https://github.com/nbs-system/naxsi) | 5k+ | Nginx WAF module. Whitelist-based, low-maintenance, high-performance filtering. |
| [lua-resty-waf](https://github.com/p0pr0ck5/lua-resty-waf) | 2k+ | High-performance WAF for OpenResty/Nginx. Lua-based rules, flexible configuration. |

---

## Rate Limiting & DDoS Protection

| Repository | Stars | Description |
|---|---|---|
| [express-rate-limit](https://github.com/express-rate-limit/express-rate-limit) | 3k+ | Basic rate limiting for Express. Memory/Redis store, custom key generators. |
| [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) | 3k+ | Flexible rate limiter for Node.js. Redis, Memcached, MongoDB, cluster support. |
| [Fail2Ban](https://github.com/fail2ban/fail2ban) | 12k+ | Intrusion prevention. Bans IPs with too many failed attempts. SSH, web, mail protection. |
| [CrowdSec](https://github.com/crowdsecurity/crowdsec) | 9k+ | Collaborative security engine. Behavior detection, crowd-sourced IP blocklists, bouncers. |
| [GoGuardian](https://github.com/shaj13/go-guardian) | 600+ | Go authentication middleware. Rate limiting, token caching, LDAP, basic/bearer/certificate. |

---

## Secrets Management

| Repository | Stars | Description |
|---|---|---|
| [Vault (HashiCorp)](https://github.com/hashicorp/vault) | 31k+ | Industry standard secrets management. Dynamic secrets, encryption, access control. |
| [Infisical](https://github.com/Infisical/infisical) | 16k+ | Open-source secrets management platform. ENV sync, rotation, audit logs, SDK for all languages. |
| [Doppler](https://github.com/DopplerHQ/cli) | 500+ | Universal secrets manager CLI. Sync env vars across platforms, teams, environments. |
| [SOPS](https://github.com/getsops/sops) | 17k+ | Encrypted file editor. AWS KMS, GCP KMS, Azure Key Vault, PGP encryption for secrets. |
| [detect-secrets](https://github.com/Yelp/detect-secrets) | 4k+ | Prevent secrets from entering your codebase. Pre-commit hooks, baseline scanning. |
| [GitLeaks](https://github.com/gitleaks/gitleaks) | 18k+ | Detect hardcoded secrets in Git repos. Pre-commit hooks, CI/CD scanning, custom rules. |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | 16k+ | Find and verify leaked credentials. 800+ detectors, Git history scanning. |

---

## HTTPS, SSL/TLS & Certificates

| Repository | Stars | Description |
|---|---|---|
| [Certbot (Let's Encrypt)](https://github.com/certbot/certbot) | 31k+ | Free SSL/TLS certificates. Automatic issuance and renewal for any web server. |
| [mkcert](https://github.com/FiloSottile/mkcert) | 50k+ | Zero-config local HTTPS. Trusted development certificates, no configuration needed. |
| [Caddy](https://github.com/caddyserver/caddy) | 60k+ | Web server with automatic HTTPS. Let's Encrypt integration, zero-config TLS. |
| [step-ca](https://github.com/smallstep/certificates) | 7k+ | Private certificate authority. Internal TLS, mTLS, ACME server, short-lived certificates. |
| [ssl-proxy](https://github.com/suyashkumar/ssl-proxy) | 600+ | Single-command HTTPS reverse proxy with auto Let's Encrypt certificates. |

---

## Authentication Security & CSRF/XSS Protection

| Repository | Stars | Description |
|---|---|---|
| [Helmet.js](https://github.com/helmetjs/helmet) | 10k+ | Express security headers middleware. CSP, HSTS, X-Frame-Options, 15+ headers. |
| [csurf](https://github.com/expressjs/csurf) | 2k+ | CSRF token middleware for Express. Double-submit cookie pattern. |
| [DOMPurify](https://github.com/cure53/DOMPurify) | 14k+ | XSS sanitizer for HTML, MathML, SVG. Trusted by millions of sites. |
| [sanitize-html](https://github.com/apostrophecms/sanitize-html) | 4k+ | Clean HTML input. Whitelist tags/attributes, remove scripts, configurable. |
| [hpp](https://github.com/analog-nico/hpp) | 700+ | HTTP Parameter Pollution protection middleware for Express. |
| [cors](https://github.com/expressjs/cors) | 6k+ | CORS middleware for Express/Connect. Configurable origins, methods, headers. |
| [csp-evaluator](https://github.com/nicedoc/nicedoc.io) | — | Content Security Policy evaluator. Test and validate CSP headers. |

---

## Dependency & Supply Chain Security

| Repository | Stars | Description |
|---|---|---|
| [Socket.dev](https://github.com/nicedoc/nicedoc.io) | — | Detect supply chain attacks in npm packages before they happen. |
| [npm-audit](https://docs.npmjs.com/cli/v8/commands/npm-audit) | — | Built-in npm vulnerability auditing. Check dependencies for known vulnerabilities. |
| [Renovate](https://github.com/renovatebot/renovate) | 18k+ | Automated dependency updates. Multi-platform, security patches, custom schedules. |
| [Dependabot](https://github.com/dependabot/dependabot-core) | 4k+ | GitHub's automated security updates. PRs for vulnerable dependencies. |
| [Lockfile-lint](https://github.com/lirantal/lockfile-lint) | 800+ | Lint lockfiles for security policies. Detect tampered packages, unauthorized registries. |

---

## Security Headers & Hardening

| Repository | Stars | Description |
|---|---|---|
| [Security Headers](https://github.com/nicedoc/nicedoc.io) | — | Test your site's HTTP security headers. Grade A+ to F rating. |
| [Observatory (Mozilla)](https://github.com/mozilla/http-observatory) | 2k+ | HTTP security scanner. Tests headers, cookies, redirects, third-party content. |
| [HSTS Preload](https://github.com/nicedoc/nicedoc.io) | — | Submit your domain to browser HSTS preload lists. Force HTTPS everywhere. |
| [Report-URI](https://github.com/nicedoc/nicedoc.io) | — | Collect CSP violation reports, HPKP, Expect-CT. Monitor security header effectiveness. |

---

## Bot Detection & CAPTCHA

| Repository | Stars | Description |
|---|---|---|
| [hCaptcha](https://github.com/nicedoc/nicedoc.io) | — | Privacy-focused CAPTCHA alternative to reCAPTCHA. GDPR-compliant. |
| [Friendly Captcha](https://github.com/nicedoc/nicedoc.io) | — | Proof-of-work CAPTCHA. No user interaction needed, privacy-first. |
| [Turnstile (Cloudflare)](https://github.com/nicedoc/nicedoc.io) | — | Smart CAPTCHA alternative. Invisible, privacy-preserving, free tier. |
| [BotD](https://github.com/nicedoc/nicedoc.io) | 2k+ | Bot detection library. Browser fingerprinting, automation detection. |

---

## Security Monitoring & Logging

| Repository | Stars | Description |
|---|---|---|
| [Wazuh](https://github.com/wazuh/wazuh) | 11k+ | Security monitoring platform. Intrusion detection, compliance, vulnerability assessment. |
| [OSSEC](https://github.com/ossec/ossec-hids) | 4k+ | Host-based intrusion detection. Log analysis, file integrity, rootkit detection. |
| [Suricata](https://github.com/OISF/suricata) | 5k+ | Network threat detection engine. IDS/IPS, protocol analysis, file extraction. |
| [Velociraptor](https://github.com/Velocidex/velociraptor) | 3k+ | Endpoint visibility and forensics. Hunt, monitor, collect artifacts at scale. |

---

## Why These Are Top-Tier

- **OWASP ZAP** — Industry standard, used by enterprises and pentesters worldwide
- **Nuclei** — Fastest growing scanner, 21k+ stars, massive template library
- **Infisical** — Modern secrets management, replaces .env files with proper infrastructure
- **Helmet.js** — One-line security headers for any Express/Node.js app
- **CrowdSec** — Community-powered threat intelligence, modern Fail2Ban replacement
- **Trivy** — All-in-one scanner that covers containers, code, and infrastructure

---

## Security Checklist for Production Websites

| Layer | Tools |
|---|---|
| Headers & HTTPS | Helmet.js + Caddy (auto-TLS) + HSTS Preload |
| Input sanitization | DOMPurify + sanitize-html + Zod validation |
| Rate limiting | rate-limiter-flexible + CrowdSec |
| Secrets | Infisical or Vault + GitLeaks (pre-commit) |
| Dependencies | Renovate + npm audit + Trivy |
| WAF | SafeLine or Coraza |
| Monitoring | Wazuh + CrowdSec |
| Scanning | Nuclei + OWASP ZAP (CI/CD) |
