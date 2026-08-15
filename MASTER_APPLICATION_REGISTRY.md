# Master Application Registry

Central source of truth for applications and major project repositories owned under the `CreigT` GitHub account.

**Registry established:** August 14, 2026  
**Owner:** CreigT / CREIGNIFICENT LLC  
**GitHub inventory:** 41 repositories — 22 public, 19 private

> Statuses: **FOUNDATION → LIVE → DEPLOYMENT READY → ACTIVE DEVELOPMENT → LOCAL / HYBRID → DORMANT → SUPERSEDED**

## Status Definitions

- **FOUNDATION** — private shared development foundation used to create and govern isolated applications; it is not itself treated as one public application deployment.
- **LIVE** — confirmed deployed and accessible through a production hosting platform.
- **DEPLOYMENT READY** — application is substantially built and has a credible deployment path, but production launch or final validation remains.
- **ACTIVE DEVELOPMENT** — meaningful current project that still requires engineering or integration work.
- **LOCAL / HYBRID** — intentionally operates partly or primarily on the user's local machine.
- **DORMANT** — preserved project or experiment that is not a current priority.
- **SUPERSEDED** — older, duplicate, placeholder, or replaced repository that should not be used for current development or deployment.

---

# FOUNDATION

| Foundation | Repository | Visibility | Created | Purpose | Current State | Next Action |
|---|---|---|---|---|---|---|
| HybridSecure AI Systems Foundation | `-hybridsecure-ai-systems` | Private | Aug 14, 2026 | Secure AI application foundation for isolated, production-ready business applications with AI decision controls, security guardrails, audit logging, human approval, deployment standards, and reusable shared services. | Full verified foundation published to `main`. Foundation guardrails, application isolation standard, AI gateway security, security policy, `.env.example`, Docker support, tests, and shared modules are present. | Keep private; add/maintain CI and security checks; use only shared foundation modules for future apps. |

## Applications Built Through HybridSecure

| App # | Application | Repository / Boundary | Status | Purpose | Isolation / Placement | Next Action |
|---|---|---|---|---|---|---|
| 1 | HybridSecure Business Intake | Root application in `-hybridsecure-ai-systems` | ACTIVE DEVELOPMENT / PROTECTED | Public landing page and secure inquiry workflow with Firebase verification, deterministic risk rules, real configured Ollama structured analysis, human review, and redacted audit logging. | Protected root application. Its routes, UI, tests, configuration, data conventions and deployment behavior must remain intact. | Verify full regression suite and production infrastructure before deployment. |
| 2 | SecureQuote Lite | `applications/securequote_lite/` inside `-hybridsecure-ai-systems` | ACTIVE DEVELOPMENT / PROTECTED | Secure review-first quoting workflow with structured intake, AI-assisted analysis, policy checks, human approval, and auditability. | Correctly isolated under its own application directory with its own business, security, tests, web UI and workflow files. | Complete production integrations and deployment validation without changing App #1. |

### HybridSecure Standing Rules

- The foundation stays private.
- Every application is standalone and isolated from every other application.
- Shared capabilities live only in explicit foundation/shared modules.
- One application may not overwrite, refactor, rename, move, or depend unsafely on another application's code, routes, data, configuration, secrets, tests or runtime behavior.
- Existing applications are protected by default.
- A foundation change must remain backward-compatible and be verified against all applications before release.
- AI output is untrusted; deterministic policy checks and explicit human authorization remain required for sensitive actions.
- Do not mark an application LIVE until an actual production deployment and production URL are verified.

---

# LIVE

| Application | Repository | Visibility | Created | Purpose | Platform / URL | Next Action |
|---|---|---|---|---|---|---|
| Missing Money Method | `money-missing-method-` | Public | Aug 10, 2026 | Helps people locate official unclaimed-property resources without requiring login or collecting claim data. | Vercel — https://money-missing-method.vercel.app | Maintain production app; monitor analytics and links. |
| JoyDrop | `joydrop` | Public | Jul 11, 2026 | Permission-first AI birthday automation, contribution collection, reviewed AI surprise, and Birthday Bridge memory page. | Vercel — https://joydrop-iota.vercel.app | Maintain production configuration and integrations. |
| AEDSHIELDAI | `AEDSHIELDAI-` | Private | May 16, 2026 | AED maintenance and management application. | Vercel — https://aedshieldai.vercel.app | Verify production behavior and document current operating status. |

## Other Web / Portfolio Deployments Requiring Verification

| Project | Repository | Visibility | Created | Current State | Next Action |
|---|---|---|---|---|---|
| Tc Creig Portfolio | `tccreig.github.io` | Public | Jun 2, 2026 | GitHub Pages-enabled portfolio. | Verify canonical public URL and decide whether it remains official. |
| Creignificent Automation | `creignificent-automation` | Public | Mar 18, 2026 | GitHub Pages capability present; business automation portfolio repository. | Verify whether Pages deployment should remain public-facing. |

---

# DEPLOYMENT READY

| Application | Repository | Visibility | Created | Purpose | Readiness / Dependency | Next Action |
|---|---|---|---|---|---|---|
| ContentForge AI Pro | `contentforge-ai-pro` | Private | Jul 4, 2026 | Netlify creator studio that turns source URLs into platform-optimized social content using server-side xAI/Grok. | Netlify configuration exists; requires production xAI/environment configuration. | Validate environment variables and deploy to Netlify. |
| PQC Migration Agent | `pqc-migration-agent` | Public | Jul 1, 2026 | Scans PDF, DOCX, and TXT files for legacy and post-quantum cryptography migration signals. | FastAPI/Vercel path, tests, CI, security documentation and scanning are present. | Run final CI/security validation, then deploy. |
| CouponForge AI | `Creig-Ai-Operator` | Private | Jul 10, 2026 | Grocery coupon assistant using live coupon sources, Gemini extraction, Firestore, shopping optimization, and clipping workflows. | Docker deployment path exists; external integrations require validation. | Validate live store/Gemini/Firestore flows, then choose hosting platform. |
| CryptoMentions News Feed | `cryptomentions-news-feed` | Private | May 19, 2026 | Lightweight HTML/CSS/JavaScript crypto-news feed. | Small static application with straightforward deployment path. | Review live data source and deploy or retire. |
| CryptoMentions Tracker | `Cryptomentionss` | Public | Apr 4, 2026 | More developed CryptoMentions tracking project. | Candidate pending final deployment review. | Audit current files and choose canonical CryptoMentions product. |
| AI Agent Researcher | `AI-agent-researcher` | Public | Apr 7, 2026 | Gemini-powered autonomous research agent. | Candidate pending integration/deployment verification. | Audit credentials, safety controls and deployment path. |

---

# ACTIVE DEVELOPMENT

| Application / Project | Repository | Visibility | Created | Purpose | Current State | Next Action |
|---|---|---|---|---|---|---|
| ContractShield AI | `ContractShield-AI` | Public | Jun 25, 2026 | AI contract-review application for small businesses. | Strong application; dependency security remediation is underway. | Close remaining dependency findings and rerun CI/security checks before production. |
| AI ShadowGuard | `ai-shadowguard` | Public | Jun 28, 2026 | B2B Shadow AI governance SaaS with tenant controls, MFA-sensitive actions, browser guardrails and compliance workflows. | Substantial SaaS; production infrastructure still required. | Validate Clerk, Prisma/PostgreSQL, MFA, tenant isolation and production secrets. |
| GHOSTMODEAI | `GHOSTMODEAI` | Private | May 27, 2026 | AI idea-recovery and self-reflection platform for forgotten projects, goals and digital opportunities. | Large substantial repository requiring deployment-readiness review. | Perform focused architecture, secrets, integrations and deployment audit. |
| AI Industry Report | `AI-industry-report` | Public | May 28, 2026 | Automated AI industry/news reporting system. | Meaningful project; external data/integrations require verification. | Verify feeds/APIs and production schedule before deployment. |
| Creignificent Automation | `creignificent-automation` | Public | Mar 18, 2026 | Business automation for proposals, leads, follow-up, reporting and operations. | Active business/portfolio repository with security documentation. | Continue moving production workflows into isolated applications. |
| AI Agent Lab | `ai-agent-lab` | Public | Apr 3, 2026 | Defensive cybersecurity AI research assistant and lab. | CI, tests, security policy and dependency/secret monitoring added. | Expand authorized defensive tests and maintain CI. |
| Cybersecurity Journey | `Cybersecurity-journey` | Public | Mar 29, 2026 | Cybersecurity labs, notes, research and learning portfolio. | Strong portfolio repository. | Maintain as evidence of continuing cybersecurity practice. |
| Hustle Apparel Store | `HustleApparel-store` | Public | May 3, 2026 | AI-built apparel/e-commerce storefront. | Commerce behavior and production integrations need validation. | Verify checkout, inventory and deployment before public launch. |
| CryptoMentions AI Center | `cryptomentions-ai-center` | Public | Jun 7, 2026 | CryptoMentions AI/static center. | Needs deployment and canonical-product review. | Compare against other CryptoMentions repositories. |
| LEADFORGE v3 | `LEADFORGEv3` | Private | May 20, 2026 | AI-powered lead intelligence / fresh lead operating system. | Very small/prototype repository. | Decide whether to rebuild through current secure application standards or preserve as history. |

---

# LOCAL / HYBRID

| Application | Repository | Visibility | Created | Purpose | Current State | Next Action |
|---|---|---|---|---|---|---|
| LocalMechAI | `LocalMechAI` | Public | Jul 3, 2026 | Local-first Windows health/diagnostics agent with AI-assisted explanations and human-approved repairs. | Active; CI, tests, security policy and local-agent architecture present. | Keep repair agent local-first; deploy only appropriate dashboard components. |

---

# DORMANT

| Project | Repository | Visibility | Created | Purpose / History | Recommendation |
|---|---|---|---|---|---|
| CleanHub Pro | `CleanHub-Pro` | Public | Sep 27, 2025 | Janitorial operations, scheduling and team-management platform. | Preserve; revisit only if it supports current facilities/cleaning operations. |
| Crypto Vault | `Crypto-Vault-` | Public | Feb 28, 2026 | Solana / DeFi personal-finance dashboard concept. | Preserve; no current priority. |
| AstrumX | `AstrumX` | Private | Oct 12, 2023 | Finance technology concept. | Preserve as historical concept. |
| Holly Jolly Video Generator | `Holly-Jolly-Video-Generator` | Public | Oct 25, 2025 | AI festive/video-generation experiment. | Archive after final verification if no reuse is planned. |
| ICFGM Church Website Rebuild | `icfgm-church-website-rebuild` | Public | May 10, 2026 | Church website redesign project. | Preserve if client/history value exists; otherwise archive. |
| GitHub Desktop Tutorial | `desktop-tutorial` | Private | Oct 12, 2023 | GitHub Desktop learning repository. | Archive as training history. |
| Knowledge Power | `knowledge-power` | Private | Feb 18, 2024 | Early GitHub learning repository. | Archive as training history. |

---

# SUPERSEDED / EMPTY / PLACEHOLDER

| Repository | Visibility | Created | Classification | Canonical / Recommended Direction |
|---|---|---|---|---|
| `GhostMode` | Private | May 23, 2026 | Superseded predecessor | Use `GHOSTMODEAI`. |
| `AI-ShadowGuard-` | Private | Jun 28, 2026 | Superseded predecessor | Use public `ai-shadowguard`. |
| `localmechai-app` | Private | Jul 3, 2026 | Superseded predecessor | Use public `LocalMechAI`. |
| `money-missing-method` | Private | Aug 11, 2026 | Duplicate / older alternate repository | Use public `money-missing-method-` for production. |
| `cryptomentions-news-feed-` | Private | May 16, 2026 | Empty / duplicate predecessor | Review against `cryptomentions-news-feed`; likely archive. |
| `Cryptomentions-` | Public | Apr 4, 2026 | Empty / old version | Compare with `Cryptomentionss`; likely archive. |
| `Cryptomentionssgame` | Private | Oct 23, 2023 | Empty old template | Archive. |
| `secure-stack-ai-v1` | Private | May 18, 2026 | Empty placeholder for security-event explainer | Archive unless intentionally revived. |
| `Cyber-Watch` | Private | Jun 19, 2026 | Empty repository / concept | Archive unless intentionally rebuilt. |
| `VibeSpot` | Private | Jun 30, 2026 | Empty / unfinished repository | Archive unless intentionally revived. |

---

# PORTFOLIO / SUPPORT REPOSITORIES

| Repository | Visibility | Created | Role | Status |
|---|---|---|---|---|
| `CreigT` | Public | Oct 23, 2023 | GitHub profile, portfolio navigation, repository audit and this registry. | ACTIVE SUPPORT |
| `creig.github.io` | Public | Jun 3, 2026 | More developed alternate professional portfolio site. | ACTIVE REVIEW — stronger codebase than older portfolio; canonical choice still pending. |

---

# Portfolio Summary

| Measure | Current Position |
|---|---:|
| Total GitHub repositories | 41 |
| Public repositories | 22 |
| Private repositories | 19 |
| HybridSecure foundations | 1 |
| HybridSecure protected applications | 2 |
| Confirmed major live Vercel applications | 3 |
| Strong deployment-ready / near-ready candidates | 6+ |
| Active major AI / cybersecurity / business systems | 10+ |
| Local / hybrid applications | 1 |
| Dormant historical projects | 7 |
| Superseded / empty / placeholder repositories | 10 |

## Immediate Priority Order

1. **Protect and maintain foundation:** HybridSecure AI Systems Foundation and both protected applications.
2. **Maintain LIVE:** Missing Money Method, JoyDrop, AEDSHIELDAI.
3. **Deploy next:** PQC Migration Agent or ContentForge AI Pro after final verification.
4. **Complete remediation:** ContractShield AI.
5. **Productionize:** AI ShadowGuard.
6. **Audit for revival/deployment:** GHOSTMODEAI and CouponForge AI.
7. **Consolidate CryptoMentions:** identify one canonical repository/product and retire duplicates.
8. **Archive verified obsolete repositories:** archive rather than delete.
9. **Update this registry whenever an application's status, URL, repository, visibility, foundation relationship, or deployment changes.**

## Registry Rule for Every New Application

Every new application should receive a registry entry containing:

- Application name
- GitHub repository
- Foundation relationship, if any
- Public/private visibility
- Creation date
- One-sentence purpose
- Technology stack
- Current status
- Live URL, if deployed
- Hosting/deployment platform
- Security/testing status
- Required external credentials or dependencies
- Application boundary and isolation namespace, when built through HybridSecure
- Next action
- Canonical/superseded relationship, when applicable

This registry should remain the **single source of truth** for the application portfolio.

---

**Sponsored by CREIGNIFICENT LLC.**
