# Authentication & Authorization

> The best open-source authentication libraries, identity providers, and authorization tools for web applications.

---

## Auth Libraries (Drop-in for Your App)

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Auth.js (NextAuth.js)](https://github.com/nextauthjs/next-auth) | 25k+ | Authentication for Next.js and other frameworks. | Most popular Next.js auth. 50+ OAuth providers. JWT + database sessions. |
| [Better Auth](https://github.com/better-auth/better-auth) | 8k+ | Comprehensive, framework-agnostic authentication library. | Modern alternative to Auth.js. TypeScript-first. Plugin system. |
| [Lucia](https://github.com/lucia-auth/lucia) | 10k+ | Simple session-based authentication library. | Lightweight. Framework-agnostic. No magic — you understand the code. |
| [Passport.js](https://github.com/jaredhanson/passport) | 23k+ | Simple, unobtrusive authentication for Node.js. | 500+ strategies. Express middleware. Battle-tested since 2011. |
| [Clerk](https://github.com/clerk/javascript) | 4k+ | Complete user management and authentication. | Drop-in components. User profiles, organizations, MFA. |

## Self-Hosted Identity Providers

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Keycloak](https://github.com/keycloak/keycloak) | 24k+ | Open-source identity and access management. | Enterprise standard. SSO, LDAP, SAML, OpenID Connect. Red Hat backed. |
| [Authentik](https://github.com/goauthentik/authentik) | 14k+ | Modern identity provider with focus on flexibility. | Beautiful UI. LDAP, SAML, OAuth2, proxy auth. Docker deploy. |
| [ZITADEL](https://github.com/zitadel/zitadel) | 9k+ | Identity management platform. Cloud-native. | Built-in multi-tenancy. OIDC/OAuth2/SAML. Audit logs. |
| [Logto](https://github.com/logto-io/logto) | 9k+ | Auth infrastructure for modern apps. | Beautiful sign-in experience. Multi-tenant. SDKs for all frameworks. |
| [Ory](https://github.com/ory/kratos) | 11k+ | Cloud-native identity and access management. | Headless identity server. MFA, social login, account recovery. |
| [Casdoor](https://github.com/casdoor/casdoor) | 10k+ | UI-first Identity and Access Management platform. | Web UI for managing users. OAuth 2.0, OIDC, SAML, LDAP. |
| [SuperTokens](https://github.com/supertokens/supertokens-core) | 13k+ | Open-source alternative to Auth0. | Self-hosted. Pre-built auth UI. Session management. |
| [FusionAuth](https://github.com/FusionAuth/fusionauth-issues) | 2k+ | Full-featured identity platform. | Single-tenant. CIAM focused. Passwordless, MFA, consent management. |

## OAuth & JWT Tools

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [jose](https://github.com/panva/jose) | 6k+ | JavaScript module for JSON Object Signing and Encryption. | Best JWT library for JS/TS. Works in Node, Deno, Bun, browsers. |
| [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 18k+ | JWT implementation for Node.js. | Most popular JWT library. Simple API. By Auth0. |
| [PyJWT](https://github.com/jpadilla/pyjwt) | 5k+ | JSON Web Token implementation in Python. | Python standard for JWTs. Simple and reliable. |

## Authorization Frameworks

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Casbin](https://github.com/casbin/casbin) | 18k+ | Authorization library supporting ACL, RBAC, ABAC. | Multi-language (Go, JS, Python, Java). Flexible policy models. |
| [CASL](https://github.com/stalniy/casl) | 6k+ | Isomorphic authorization for JavaScript apps. | Works on frontend and backend. Integrates with Prisma, Mongoose. |
| [Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa) | 10k+ | General-purpose policy engine. | CNCF graduated. Policy-as-code. Used by Netflix, Pinterest. |
| [Cerbos](https://github.com/cerbos/cerbos) | 3k+ | Scalable authorization as a service. | YAML policy definitions. Language-agnostic. API-first. |

## Passwordless & Passkeys

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [SimpleWebAuthn](https://github.com/MasterKale/SimpleWebAuthn) | 2k+ | WebAuthn/FIDO2 library for browsers and Node.js. | Best WebAuthn library. Passkeys support. TypeScript. |
| [Hanko](https://github.com/teamhanko/hanko) | 7k+ | Passkey-first authentication platform. | Passwordless by default. Passkeys, WebAuthn, FIDO2. Self-hosted. |

---

## Selection Criteria Applied
- Every repo above has 2,000+ GitHub stars
- All are actively maintained (commits within 2025-2026)
- Production-ready with clear documentation
- Support standard protocols (OAuth2, OIDC, SAML, JWT)
- Permissive or open-source licenses

## How to Choose
- **Next.js app?** -> Auth.js (most popular) or Better Auth (modern, plugin-based)
- **Lightweight, understand your auth?** -> Lucia (session-based, no magic)
- **Enterprise SSO/LDAP?** -> Keycloak (Red Hat) or Authentik (modern alternative)
- **Auth0 replacement (self-hosted)?** -> SuperTokens or Logto
- **Passkeys/passwordless?** -> Hanko (passkey-first) or SimpleWebAuthn (library)
- **Authorization (RBAC/ABAC)?** -> Casbin (multi-language) or CASL (JavaScript)
- **Policy engine?** -> Open Policy Agent (CNCF standard)
