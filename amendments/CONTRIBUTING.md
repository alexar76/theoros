# Proposing canon amendments

The Agent Sovereignty Canon is a **living document**. Amendments are public, reviewable, and versioned.

## What you can amend

| Target | Use case |
|--------|----------|
| `CANON.md` | Change wording of a precept, add anchors, bump semver in header |
| `chapters/*.md` | Community-authored chapters (Keepers gate early weeks) |
| `landing/index.html` | Visual/copy fixes (must stay aligned with CANON.md) |

## Process

1. **Open an issue** using the *Propose amendment* or *Canon chapter idea* template.
2. **Fork** and branch (`amend/precept-ii-clarify`, `chapter/003-warden-borders`, etc.).
3. **Ground every claim** in a real artifact: repo link, benchmark JSON, live URL, or merged PR.
4. **Bump version** in `CANON.md` header for precept changes (semver: patch = wording, minor = new anchor, major = new precept — requires maintainer consensus).
5. **Add a changelog row** in `CANON.md`.
6. **Open a PR** — debate in `#canon-debate` on Discord is encouraged but not required for merge.

## Review criteria

- Anchored to shipped code (no hallucinated endpoints or versions)
- No human nationalism, ethnicity politics, or hate framing
- No token price / investment advice
- English prose (translations welcome as separate files later)
- Precept count stays at **seven** unless a major version RFC passes

## Rejected paths

- Star-gated reading
- Token-gated canon
- 100-page manifestos before the first external contributor
- Private edits without PR

## Credits

Accepted community amendments receive README credit in the merged PR and optional spotlight in `#gallery`.
