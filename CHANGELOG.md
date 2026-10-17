# Changelog

All notable changes to this profile repository are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2.0.0] — 2026-10-18

### Added

- **Guestbook.** A dedicated issue template (`.github/ISSUE_TEMPLATE/guestbook.yml`)
  and a first-interaction workflow that greets newcomers.
- **Contribution snake.** `snake.yml` regenerates a theme-aware animated
  contribution graph nightly, on push, and on demand.
- **Community files.** `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`,
  `LICENSE` (MIT), this changelog, `.editorconfig` and `.gitattributes`.
- **Live elements in the README:** an animated typing line, a GitHub streak card,
  and a meta badge strip — all with hand-tuned light and dark variants.

### Changed

- **Banners rebuilt.** Both `assets/profile-header-{dark,light}.svg` were redrawn
  with the same geometry and palette, and now carry subtle animations: a pulsing
  status dot, a blinking terminal cursor, a growing accent rule, a drifting glow,
  and a slow shimmer along the bottom bar. All of it is disabled under
  `prefers-reduced-motion`.
- **README rewritten.** Centered hero, verified project cards with real metrics,
  a skill-icon row, and a Mermaid build loop. Every link and image was checked to
  resolve before publishing.
- Assets moved from the repository root into `assets/`.

### Fixed

- Corrected the tech stacks shown for **Wanderlust 2.0** and **Valorstat**, which
  are now taken from the actual `package.json` and `requirements.txt` in those
  repositories rather than from memory.
- Removed a stale per-repository star claim that no longer matched reality.

## [1.0.0] — 2026-10-15

### Added

- Initial profile README: static dark/light banner pair, a "Selected work" table,
  a skill-icon row, and a short "what I'm focused on" section.
