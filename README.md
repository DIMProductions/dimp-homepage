サーラだ。
**dimp-homepage 用の README（英語版）を“企業サイトとして最適化した完成版”出す。
これを `dimp-homepage/README.md` にそのまま貼ればいい。**

---

# ✅ **DIMProductions – Homepage Repository (README.md)**

```markdown
# DIMProductions – Official Website

This repository hosts the **official corporate website of DIMProductions**, served via GitHub Pages and published at:

**https://dim.productions**

The site provides product overviews, brand information, and entry points to all public projects under the DIMProductions umbrella.

---

## 📌 Purpose

This repository contains the **static website files** for the company's main domain.  
It is *not* a product code repository — each product has its own dedicated repo.

`dimp-homepage` is responsible for:

- The main landing page
- Navigation to DIMProductions products and sub-sites
- Brand assets (logo, typography, style)
- Company-level SEO / OpenGraph metadata
- Domain-level routing (Cloudflare + GitHub Pages)

---

## 📂 Structure

```

dimp-homepage/
│
├── index.html        # Main corporate page
├── assets/           # Shared fonts, images, icons, styles
│     ├── fonts/
│     └── pic/
│
└── pianovirtuoso18/  # Product subpage (legacy link)

```

> **Note:** Product directories inside this repo are being migrated  
> to independent repositories under the DIMProductions organization.

---

## 🌐 Deployment

DIMProductions uses **GitHub Pages + Cloudflare**:

- Domain: `dim.productions`
- DNS: CNAME flattening enabled  
- Hosting: GitHub Pages (organization-level)

No build pipeline.  
The site deploys automatically on every push to `main`.

---

## 🧩 Product Repositories

Active product repos live in the main organization:

- **Piano Virtuoso 18** — https://pv18.dim.productions  
- **ΔPhase Tuner** — (to be published)
- **Perceptual Sonic Grimoire (PSG)** — (research / docs repo)
- Other DSP, plugins, and tools (coming soon)

Each product will eventually have:

- Its own homepage (under a subdomain)
- Its own documentation
- Its own independent repository

---

## 📬 Contact

For business inquiries:

**info@dim.productions**

---

## 📄 License

This repository contains **company website assets**.  
All rights reserved © DIMProductions.  
Do not reuse branding, logos, or proprietary graphics without permission.
```
