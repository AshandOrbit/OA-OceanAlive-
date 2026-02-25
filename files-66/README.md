# Ocean Alive – Sado Estuarine Park

**Turning conservation data into visitor experience, community income, and verified ecological outcomes.**

[![Ocean Alive](https://img.shields.io/badge/Ocean%20Alive-Natura%202000%20Award%202024-teal)](https://oceanalive.org)
[![SDGs](https://img.shields.io/badge/SDGs-4%20·%205%20·%208%20·%2012%20·%2013%20·%2014%20·%2015-gold)]()
[![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-blue)]()

---

## What This Is

A planning and verification platform for the **Sado Estuarine Park** – a community-based conservation model built on the work of [Ocean Alive](https://oceanalive.org) and 18 Guardiãs do Mar in the Sado Estuary, Portugal (Natura 2000 site PTCON0011).

**Live site:** [→ View on GitHub Pages](https://username.github.io/ocean-alive-sado/)

---

## Site Structure

| Page | Description |
|------|-------------|
| [`index.html`](index.html) | Landing page with navigation to all tools and documents |
| [`dashboard.html`](dashboard.html) | Verification dashboard – ecosystem monitoring, governance, community voice, spatial conflicts, Estuarine Park planning |
| [`grants.html`](grants.html) | Grant calendar – 30 funding opportunities with timeline, pipeline, actions, budget map |
| [`proposta.html`](proposta.html) | Collaboration proposal (Portuguese) |
| [`pdfs/`](pdfs/) | Downloadable Portuguese documents |

## Documents (Portuguese)

| Document | Contents |
|----------|----------|
| `parque_estuarino_do_sado.pdf` | Full Park concept – problem, solution, 5 experiences, Sentinela, revenue model, 3-year projections |
| `plano_de_desenvolvimento.pdf` | Feasibility – governance options, risk register, carrying capacity, gender, succession, 40+ fieldwork questions |
| `mapa_de_financiamento.pdf` | Funder map – 20+ actions, 40+ prospects, 7 categories, 11 nonprofit partnerships |
| `concursos_e_oportunidades.pdf` | Competition tracker – Hult, EcoVenture, MIT CEP, Halcyon, and 12+ more |
| `oportunidades_parcerias_jovens.pdf` | Youth partnerships – EarthEcho, Global CoLab, Bow Seat, Sea Youth Rise Up, YRE |

## Key Numbers

- **190 ha** seagrass mapped in the Sado Estuary
- **18** Guardiãs do Mar (community monitors, predominantly women)
- **4 years** continuous monitoring data
- **10** Sentinela apprenticeship tracks (Film, Ceramics, Ecology, Data, Translation, Hospitality, Engineering, Archive, Sound, Research)
- **12** revenue streams (guided experiences → data licensing → replication)
- **30** funding opportunities tracked (€4M+ pipeline)
- **7 SDGs** aligned (4, 5, 8, 12, 13, 14, 15)

## Language

All pages have a **PT 🇵🇹 / EN 🇬🇧** toggle. Portuguese documents are in `pdfs/`.

## The Model

Every visitor interaction produces three things simultaneously:

1. **Verification data** – monitoring the meadow
2. **A cultural product** – ceramic tile, film, experience
3. **Socioeconomic transformation** – paid community work

The park measures success by the number of people whose income depends on the estuary being healthy.

## Technology

Static HTML/CSS/JS. No build step. No dependencies beyond Google Fonts. Designed for GitHub Pages.

- Dashboard: React (CDN) + vanilla CSS
- Grant Calendar: React (CDN) + vanilla CSS
- Proposal: Static HTML
- PDFs: Generated with ReportLab (Python)

## Setup

```bash
# Clone and serve locally
git clone https://github.com/username/ocean-alive-sado.git
cd ocean-alive-sado

# Any static server works
python3 -m http.server 8000
# or
npx serve .
```

For GitHub Pages: Settings → Pages → Source: Deploy from branch → `main` → `/ (root)`.

## Acknowledgements

- [Ocean Alive](https://oceanalive.org) – Guardiãs do Mar programme, EU Natura 2000 Award 2024
- 18 Guardiãs do Mar and the fishing communities of the Sado Estuary
- [Project Seagrass](https://projectseagrass.org) · [ESRA](https://www.esra-europe.eu) · [EarthEcho International](https://earthecho.org)

---

*Documents presented as proposals for discussion with community and partners. February 2026.*
