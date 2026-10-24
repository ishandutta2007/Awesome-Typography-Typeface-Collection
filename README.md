# Awesome-Typography-Typeface-Collection

## Top Typography & Typeface Collection Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on SIL Open Font License Libraries, Variable Font Axes & Self-Hosted Font Distribution*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Typography & Typeface Collections**. These tools provide the raw material of visual design — typefaces — as curated libraries, foundry catalogs, or self-hosted distributions, with a spectrum running from commercial font empires to open-source libraries where every glyph is licensed for any use, including commercial products and logos.

**Examples** include Google Fonts, Font Library, Fontsource, The League of Moveable Type, and SIL Fonts (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, permissive licensing, and variable font delivery — ideal for designers who need professional typography without per-desktop or per-pageview licensing fees, and developers who want fonts as installable dependencies rather than CDN links.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Adobe Fonts** — **The Creative Cloud type library.** Includes fonts from major foundries and **The League of Moveable Type** (the first open-source foundry, with League Gothic, Raleway, Orbitron, and others available under Creative Commons licenses) . **Included with Creative Cloud subscriptions**. **Best for Adobe subscribers** wanting licensed commercial fonts without separate purchasing, though the fonts are tied to the subscription and not self-hostable outside Adobe's terms.

- **Monotype Fonts** — Enterprise font licensing platform with a vast catalog of commercial typefaces. **Subscription-based** with brand compliance controls. **Best for large organizations** needing licensed commercial fonts with governance, not for open-source-first workflows.

## Open-Source GitHub Projects

- **Google Fonts** — **The largest open-source font library.** **1,500+ font families** and **443+ independent type designers and foundries** from 51+ countries . **All fonts are open source and free for commercial use**, with the **SIL Open Font License (OFL)** being the most common, alongside Apache and Ubuntu Font License . **Variable fonts** are widely supported, letting you adjust weight axes (e.g., Space Grotesk's 300–700 range) in a single file . **The reputation has shifted**: once considered a novelty library, it now includes excellent UI choices — **Inter, Roboto Flex, DM Sans, Plus Jakarta Sans, Nunito Sans, IBM Plex Sans** . **Web delivery** uses WOFF 2.0 compression and automatic format selection for performance . **Self-hosting** is supported via the GitHub repository or **Fontsource** npm packages . **Best for essentially any project** needing a free, high-quality, commercially usable typeface — the default starting point for open-source typography.

- **Font Library (formerly Open Font Library)** — **The community-curated libre font archive.** **6,000+ fonts from 250+ contributors**, hosted as a sister project to Openclipart . **Licensed under CC0 and SIL Open Font License**, intended for downloading, remixing, and sharing freely . **Active since 2006**, with a 2024 rebrand to "Free Fonts Forever" and adoption of Nostr for communications . **The honest caveat**: the project has acknowledged challenges with AI-generated submissions and is rewriting its codebase — it's a community archive, not a polished commercial catalog . **Best for discovering libre fonts outside the Google Fonts mainstream**, especially niche or experimental work.

- **Fontsource** — **The NPM-based self-hosted font delivery standard.** **Packages open-source fonts as installable npm modules** — `npm install @fontsource/space-grotesk` — so fonts are bundled into your build rather than fetched from a third-party CDN . **Solves the privacy and performance issues** of Google Fonts CDN requests: fonts are served from your own domain, reducing external requests and avoiding CDN tracking . **Includes full metadata**: weights, axes, OpenType features, and license details for each family . **Best for JavaScript/TypeScript projects** where build-time font embedding fits the bundler workflow and self-hosting is a requirement.

- **The League of Moveable Type** — **The original open-source foundry.** **The first free and open-source type foundry**, curated by a group of typographers pushing libre typography into professional territory . **Available on Google Fonts and Adobe Fonts** (under Creative Commons), with families including **League Gothic, Raleway, Orbitron, Linden Hill, Sniglet, and Sorts Mill Goudy** . **Best for designers wanting a curated, professionally-minded libre collection** rather than a sprawling catalog, with the credibility of the original open-source foundry movement.

- **SIL Fonts** — **The specialist libre font repository for under-resourced scripts.** From **SIL Global** (Summer Institute of Linguistics), providing fonts for **Ethiopic, Arabic, Devanagari, Hebrew, Greek, Cyrillic, Khmer, Myanmar, Tai Viet, and many more** — scripts that mainstream libraries often neglect . **All under the SIL Open Font License**, with Graphite and OpenType support . **Notable families**: **Charis SIL, Doulos SIL, Gentium, Andika, Awami Nastaliq, Padauk** . **Best for multilingual typography** where broad script coverage matters more than display aesthetics — the reference for underserved language support.

### Additional Strong Open-Source Options

- **Space Grotesk** — Proportional sans-serif variant based on Space Mono, retaining idiosyncratic details while optimizing readability at non-display sizes. Variable weight axis 300–700, with OpenType features including tabular figures, fractions, and stylistic alternates . **Best for UI and editorial typography** needing personality without sacrificing legibility.
- **Inter** — **The default UI typeface for modern software.** Designed specifically for screen interfaces with a tall x-height and open letterforms that stay readable at 12–14px. Used by Figma, Linear, and most developer tools . **Best for product UIs** when you want a clean, defensible default.
- **Geist** — Vercel's open-source typeface (2023), slightly more distinctive than Inter, with proportional (Geist) and monospace (Geist Mono) variants. **Best for developer tools and SaaS products** wanting a modern feel.
- **Cyreal Foundry (Lora)** — Open-source serif family for text, with variable axes and Cyrillic support. **Best for editorial and long-form reading** where a warm serif is appropriate .

**Frameworks for building custom systems**: Combine **Google Fonts** for the broadest open-source catalog with variable font support, **Fontsource** for self-hosted npm-based delivery in JavaScript builds, **The League of Moveable Type** for a curated professional libre collection, **SIL Fonts** for multilingual and under-resourced script coverage, and **Inter or Geist** for UI-specific defaults — to build a typography stack tailored to your need for catalog breadth versus curation, self-hosting versus CDN convenience, and script coverage requirements.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Typography collections differ significantly in licensing, script coverage, and delivery model. **Google Fonts is the broadest open-source library** with 1,500+ families and commercial-use permission, but **its CDN requests raise privacy and compliance concerns** — Fontsource solves this by packaging fonts for self-hosting . **Font Library is a community archive, not a polished commercial catalog** — quality varies and the project is actively rewriting its codebase . **The League of Moveable Type is curated and professionally-minded** but smaller than Google Fonts . **SIL Fonts is the reference for under-resourced scripts** but not a display typography source . **Variable fonts** reduce HTTP requests and file size while offering fine-grained weight control, but not all fonts offer variable axes . **System font stacks** (`-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto`) offer zero loading overhead and platform-native feel, at the cost of brand distinctiveness — a legitimate choice for internal tools .
- Self-hosted open-source solutions require proper WOFF2 serving, CORS headers for cross-origin font files, and awareness that font licensing (even OFL) may require attribution or restrict resale of the fonts themselves.

---

**Made for designers and developers choosing typefaces that match their licensing needs, script coverage, and delivery constraints.**
Let's make typography and typeface collections more open, commercially usable, and script-inclusive.
