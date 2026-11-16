# Nicolas Cantarelli

Software developer and technical project lead — full-stack web, e-commerce platforms, and native macOS apps. I take digital products from requirements and UX through implementation, integrations, testing, and deployment.

Currently a Shopify developer at [Inflection Growth](https://inflection-growth.com), a growth team for Shopify and Shopify Plus brands including Gopuff, AeroPress, Dyper, Kappa, Singer and Viking.

Co-founded and ran [Lumios Digital](https://dribbble.com/lumiosdigital) (2023–2026), a small studio that shipped 50+ production sites and products for international clients — most of the repos here are that work. Remote from San Juan, Argentina.

[nicocantarelli.com](https://nicocantarelli.com) · [necantarelli@gmail.com](mailto:necantarelli@gmail.com) · [LinkedIn](https://linkedin.com/in/nicolascantarelli)

## Apps

**[Concordia: Discount Control](https://github.com/nicocantarelli/concordia-app)** · [useconcordia.com](https://useconcordia.com)
My own Shopify app for stores that run a lot of discounts: an inventory of every code, automatic and app discount, guardrails that flag conflicts before they reach checkout, bulk changes with undo, and sale campaigns across markets and currencies. Embedded app with Polaris web components, a theme app extension for storefront sale prices, and Cloudflare Workers.

**[Baudie Gifts & Deals](https://github.com/nicocantarelli/baudie-discounts)**
Custom Shopify app with no server. One discount Function runs two deals: upsell products at their deal price whenever the cart holds a regular product, in every currency, and gift-with-purchase spend tiers that block discount codes while a promo runs. A checkout rule blocks payment for a gift that isn't free, and the app's own admin pages manage the gifts and the deal prices. Tests cover every rule.

**[Baudie Checkout Upsell](https://github.com/nicocantarelli/baudie-checkout-upsell)**
Checkout UI extension in Preact with the Storefront GraphQL API, offering Baudie's upsells inside checkout.

**Timglas** · [timglas.app](https://timglas.app)
Native macOS time tracker in Swift, SwiftUI and AppKit.

## Websites

**[Baudie](https://github.com/nicocantarelli/baudie-shopify-theme)** · [baudie.com](https://baudie.com)
Custom Shopify theme whose cart drawer runs the upsells and adds the free gifts, sharing one metafield contract with Baudie Gifts & Deals and Baudie Checkout Upsell.

**[Walkfully](https://github.com/nicocantarelli/walkfully)** · [walkfully.com](https://walkfully.com)
Shopify OS 2.0 theme built on theme blocks, Section Rendering API partials, and custom web components.

**[Nirup Island](https://github.com/nicocantarelli/nirup-island)** · [nirupisland.com](https://nirupisland.com)
WordPress theme for a private-island resort: nine custom post types, booking-engine integration, bilingual EN/ID.

**[Harbour Bay Downtown](https://github.com/nicocantarelli/harbourbaydowntown)** · [harbourbaydowntown.com](https://harbourbaydowntown.com)
WordPress block theme with a Vite pipeline, Customizer-driven content, and a WP-CLI venue importer.

**[Tashola](https://github.com/nicocantarelli/tashola)** · [tashola.com](https://tashola.com)
Fashion-boutique Shopify theme: mega menu, AJAX cart drawer, faceted catalogue. Built and iterated since late 2024.

## Stack

TypeScript · React / Next.js · React Router · Vite · Node.js (NestJS · PostgreSQL · Prisma) · Swift / SwiftUI / AppKit · Shopify (Liquid · Admin GraphQL API · App Bridge · Polaris · Checkout UI Extensions · Functions · Theme app extensions) · Cloudflare Workers · WordPress / PHP · GraphQL · Playwright

Agentic development workflow: Claude Code and Codex CLI wired into every repo through project instructions, skills, agents, and hooks.
