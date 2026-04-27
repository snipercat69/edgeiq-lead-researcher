# 🎯 EdgeIQ Lead Researcher

**Company lead enrichment — company name, domain, or LinkedIn URL to enriched data.**

Company size, industry, tech stack (Wappalyzer-style fingerprinting), recent news, social links, and contact enrichment from a single input.

[![Project Stage](https://img.shields.io/badge/Stage-Beta-blue)](https://edgeiqlabs.com)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-orange)](LICENSE)

---

## What It Does

Takes a company name, LinkedIn URL, or domain as input and returns enriched lead data: company size, industry classification, technology stack (HTTP header/JS fingerprinting), recent news and press, social links, and contact enrichment.

---

## Key Features

- **Multi-format input** — company name, LinkedIn URL, or domain
- **Tech stack detection** — Wappalyzer-style fingerprinting via HTTP headers and JS
- **News/press lookup** — recent articles about the company
- **Social link discovery** — LinkedIn, Twitter, Facebook, GitHub
- **Contact enrichment** — email patterns and organizational structure
- **JSON/CSV export** — structured data for CRM integration

---

## Prerequisites

- Python 3.8+
- `requests`, `beautifulsoup4`, `lxml`

---

## Installation

```bash
git clone https://github.com/snipercat69/edgeiq-lead-researcher.git
cd edgeiq-lead-researcher
pip install -r requirements.txt
```

---

## Quick Start

```bash
# Research a company by name
python3 lead_researcher.py "Acme Corp"

# Research by domain
python3 lead_researcher.py "acme.com"

# Research from LinkedIn URL
python3 lead_researcher.py "https://www.linkedin.com/company/acme-corp"

# JSON output
python3 lead_researcher.py "acme.com" --format json

# CSV export
python3 lead_researcher.py "acme.com" --format csv --output acme_leads.csv
```

---

## Pricing

| Tier | Price | Features |
|------|-------|----------|
| **Free** | $0 | 3 lookups/month, basic enrichment |
| **Lifetime** | $39 one-time | Unlimited lookups, news/social/contact enrichment, CSV export |
| **Monthly** | $7/mo | All Lifetime features, billed monthly |

---

## Integration with EdgeIQ Tools

- **[EdgeIQ Client Dashboard](https://github.com/snipercat69/edgeiq-client-dashboard)** — feed enriched leads into client management
- **[EdgeIQ Alerting System](https://github.com/snipercat69/edgeiq-alerting-system)** — alert on new lead findings

---

## Support

Open an issue at: https://github.com/snipercat69/edgeiq-lead-researcher/issues

---

*Part of EdgeIQ Labs — [edgeiqlabs.com](https://edgeiqlabs.com)*
