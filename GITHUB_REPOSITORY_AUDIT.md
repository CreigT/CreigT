# GitHub Repository Audit — Phase 2

Date: 2026-08-14

This audit is intentionally non-destructive. No application code was changed, no repositories were deleted, and no repositories were archived during Phase 2.

## Canonical Repositories to Preserve

These are the versions that currently show the strongest evidence of being the active or more complete project and should be preserved as the primary version unless later review proves otherwise.

- `CreigT/money-missing-method-`
  - Active public application repository.
  - Contains the current production work, social preview updates, and Vercel Analytics commit.
  - Preserve as canonical.

- `CreigT/LocalMechAI`
  - Multiple substantive commits including dashboard, Netlify, safety, testing, and routing work.
  - Preserve as canonical over `localmechai-app`.

- `CreigT/ai-shadowguard`
  - Public repository with substantive SaaS foundation work and multiple commits.
  - Preserve as canonical over `AI-ShadowGuard-`.

- `CreigT/GHOSTMODEAI`
  - Much larger and more developed repository with multiple implementation and conflict-resolution commits.
  - Preserve as canonical over `GhostMode`.

- `CreigT/Cryptomentionss`
  - Non-empty public repository and the strongest current candidate among similarly named Cryptomentions repositories.
  - Preserve pending deeper content review.

- `CreigT/cryptomentions-news-feed`
  - Non-empty private repository.
  - Preserve over the empty `cryptomentions-news-feed-` repository pending deeper review.

## Duplicate / Superseded Candidates

These should NOT be deleted automatically. They are candidates for archiving after one final verification pass.

- `CreigT/money-missing-method`
  - Private repository with only the initial Vercel-created commit.
  - Superseded by `money-missing-method-`.

- `CreigT/localmechai-app`
  - Initial-commit-only private repository.
  - Superseded by the more developed `LocalMechAI`.

- `CreigT/AI-ShadowGuard-`
  - Initial-commit-only private repository.
  - Superseded by `ai-shadowguard`.

- `CreigT/GhostMode`
  - Small private predecessor repository.
  - Superseded by the substantially larger `GHOSTMODEAI`.

- `CreigT/cryptomentions-news-feed-`
  - Empty private repository.
  - Superseded candidate: `cryptomentions-news-feed`.

## Empty / Near-Empty Repositories Requiring Cleanup Review

These repositories appear empty or effectively placeholder-level and should be reviewed before deciding whether to archive them.

- `CreigT/Cryptomentionssgame`
- `CreigT/Cryptomentions-`
- `CreigT/cryptomentions-news-feed-`
- `CreigT/secure-stack-ai-v1`
- `CreigT/Cyber-Watch`
- `CreigT/AI-ShadowGuard-`
- `CreigT/VibeSpot`
- `CreigT/localmechai-app`

## Portfolio Repositories That Should Remain Active

These support the public professional portfolio and should not be part of cleanup without a separate review.

- `CreigT/CreigT` — GitHub profile repository
- `CreigT/money-missing-method-`
- `CreigT/Cybersecurity-journey`
- `CreigT/ai-agent-lab`
- `CreigT/ContractShield-AI`
- `CreigT/ai-shadowguard`
- `CreigT/creignificent-automation`
- `CreigT/pqc-migration-agent`
- `CreigT/LocalMechAI`
- `CreigT/AI-industry-report`
- `CreigT/joydrop`

## GitHub Pages / Portfolio Repositories

Two GitHub Pages-style repositories exist and both contain actual site files:

- `CreigT/tccreig.github.io`
  - Contains `index.html`, `script.js`, and `styles.css`.

- `CreigT/creig.github.io`
  - Contains a larger `index.html` and a `TcCreig portfolio` directory.

These are NOT classified as duplicates yet. They require a visual/content comparison before one is selected as the official portfolio site.

## Naming Cleanup Opportunities

Future repository naming should use one consistent style:

- lowercase or clean TitleCase
- no trailing hyphens
- no accidental duplicate spellings
- one canonical repository per application

Examples needing future cleanup decisions:

- `money-missing-method-`
- `Crypto-Vault-`
- `AEDSHIELDAI-`
- `AI-ShadowGuard-`
- `Cryptomentions-`
- `cryptomentions-news-feed-`

Renaming active production repositories should only be done after checking deployment integrations and external links.

## Phase 3 Recommendation

Phase 3 should be a controlled cleanup and professionalization pass:

1. Archive verified duplicate/placeholder repositories instead of deleting them.
2. Select one official GitHub Pages portfolio repository.
3. Upgrade README files for flagship projects.
4. Add consistent descriptions, topics, screenshots, live links, security notes, and sponsorship branding.
5. Standardize repository naming only after confirming deployment dependencies.
6. Add baseline repository hygiene where appropriate: `.gitignore`, `.env.example`, license, security notes, and CI/testing documentation.

## Safety Rule

No repository should be deleted, renamed, made public/private, or disconnected from a deployment until its role and integrations are verified.

---

**Sponsored by CREIGNIFICENT LLC.**
