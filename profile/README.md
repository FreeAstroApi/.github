<div align="center">
  <h1>FreeAstroAPI</h1>
  <p><strong>Free Astrology APIs and open-source starter kits for commercial apps, websites, and client tools.</strong></p>
  <p>
    <a href="https://www.freeastroapi.com">Website</a>
    ·
    <a href="https://www.freeastroapi.com/docs">Documentation</a>
    ·
    <a href="https://www.freeastroapi.com/guide">Guides</a>
    ·
    <a href="https://stats.uptimerobot.com/0E0KFhq8CR">Status</a>
    ·
    <a href="mailto:contact@freeastroapi.com">Contact</a>
  </p>
</div>

---

## Build Astrology Products Faster

FreeAstroAPI provides hosted astrology calculation endpoints, visual chart rendering (both for vedic and western charts, and deployable starter projects for teams building astrology products.

Use the API to add natal charts, compatibility, transits, horoscopes, Vedic Kundli tools, Chinese astrology, moon data, city search, and SVG chart generation without maintaining your own ephemeris infrastructure.

## What You Can Build

- Western natal chart apps, reports, and visual wheels
- SVG chart renderers for natal, transit, synastry, and composite charts
- Vedic Kundli calculators with divisional charts, dasha, yogas, panchang, and matching
- WordPress astrology blocks and site integrations
- Daily horoscope, transit timeline, moon phase, and city autocomplete tools
- Commercial astrology apps that keep API keys server-side

## Open-Source Starters

| Repository | What it is | Stack |
| --- | --- | --- |
| [open-chart](https://github.com/FreeAstroApi/open-chart) | Production-ready natal chart and interpretation app powered by FreeAstroAPI | Next.js, TypeScript, Tailwind |
| [Kundli-birth-chart-free](https://github.com/FreeAstroApi/Kundli-birth-chart-free) | Free AstroSage-style Vedic Kundli chart calculator and client tool | Next.js, TypeScript, Tailwind |
| [wordpress-Astrology-plugin](https://github.com/FreeAstroApi/wordpress-Astrology-plugin) | WordPress plugin with astrology blocks, settings, and FreeAstroAPI proxy routes | PHP, WordPress |

## API Quickstart

Base URL:

```text
https://api.freeastroapi.com
```

Example request:

```bash
curl -X POST "https://api.freeastroapi.com/api/v1/natal/calculate" \
  -H "Content-Type: application/json" \
  -H "x-api-key: YOUR_KEY" \
  -d '{"year":1990,"month":5,"day":15,"hour":14,"minute":30,"city":"New York"}'
```

Get started in the docs:

- [Authentication](https://www.freeastroapi.com/docs/auth)
- [Endpoints overview](https://www.freeastroapi.com/docs)
- [Western natal chart](https://www.freeastroapi.com/docs/western/natal)
- [Vedic chart](https://www.freeastroapi.com/docs/vedic/chart)
- [City search](https://www.freeastroapi.com/docs/geo/search)
- [Starter kits](https://www.freeastroapi.com/docs/utilities/starter-kits)
--[LLM file](https://www.freeastroapi.com/docs/utilities/starter-kits](http://freeastroapi.com/llms.txt)

## API Coverage

| Area | Examples |
| --- | --- |
| Western astrology | Natal charts, insights, transits, solar returns, synastry, astrocartography, horoscopes |
| Western visual charts | Natal SVG, transit bi-wheel, synastry bi-wheel, composite chart rendering |
| Vedic astrology | Basic chart, full calculate, Vimshottari dasha, yogas, planetary strength, panchang, match by birth |
| Chinese astrology | BaZi, BaZi synastry, current pillars, flow timing, dictionary endpoints |
| Utilities | City search, timezone handling, moon phase, moon timeline, hosted MCP, AstroFont |

## Integration Principles

- Keep API keys on the server, never in browser bundles.
- Use starter kits as production foundations, not just demos.
- Validate request and response contracts in your app.
- Respect rate limits and add retry/backoff behavior for production traffic.
- Keep visitor birth data handling explicit and privacy-aware.

## Useful Links

- Website: [freeastroapi.com](https://www.freeastroapi.com)
- Documentation: [freeastroapi.com/docs](https://www.freeastroapi.com/docs)
- Pricing: [freeastroapi.com/pricing](https://www.freeastroapi.com/pricing)
- Contact: [contact@freeastroapi.com](mailto:contact@freeastroapi.com)
