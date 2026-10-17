# Contributing

This repository is my GitHub **profile**: a README, two hand-drawn SVG banners, and
the small bits of automation that keep it honest. There is no app to build and no
test suite to run — but there are three genuinely useful ways to contribute.

## 1. Sign the guestbook

The friendliest and most useful option. Open a
[new guestbook issue](https://github.com/Aayush-shrma/Aayush-shrma/issues/new?template=guestbook.yml),
say hi, and tell me what you're building. No agenda required.

## 2. Fix or improve the README

Typos, a broken link, a clearer sentence, better alt text for an image — all
welcome. Please keep the design system intact so the page stays coherent:

- **Palette:** `#5eead4` → `#60a5fa` → `#a78bfa` on a `#0b1020` base.
- **Theme parity:** anything added must work in **both** dark and light mode, via
  `<picture>` + `prefers-color-scheme`.
- **Accessibility:** every `<img>` needs a meaningful `alt`. No "image" or "banner".
- **Honesty:** don't add a metric, title, or claim that isn't true.

## 3. Suggest a better banner

The banners live in `assets/`. Both `profile-header-dark.svg` and
`profile-header-light.svg` must stay in sync (same geometry, different palette) and
must remain self-contained — **no external fonts, images, or scripts**, because
GitHub renders them as isolated images. Animations should stay subtle and must be
disabled under `prefers-reduced-motion`.

## Pull request checklist

- [ ] Renders correctly in **both** GitHub themes (dark and light).
- [ ] Every link and image resolves.
- [ ] Every image has meaningful alt text.
- [ ] No secrets, tokens, or personal data in the diff.

## Ground rules

Be kind, be patient, be specific. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
