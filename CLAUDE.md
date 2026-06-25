# Parth Prajapati — Portfolio Site · Project Context

Context for Claude Code. The site is a **single self-contained `index.html`**
(all HTML/CSS/JS inline, no build step, no dependencies, no framework).

## Who this is for
- **Name:** Parth Prajapati
- **Title:** Analytics Engineer (5+ years experience)
- **Domain:** Supply chain analytics, AI & automation, applied AI, operations research
- **Location:** New York, NY
- **Employers:** Amazon (2024–present) and Staples (previous role)
- **Contact:** Parth45730@gmail.com · (857) 424-6009 · LinkedIn (placeholder — fill real URL)
- **Audience:** External recruiters (public portfolio, outside Amazon)

## File layout
- `index.html` — the entire website (edit this)
- `CLAUDE.md` — this context file
- `README.md` — short public readme

## Editing rules / guardrails (IMPORTANT)
1. **Confidentiality:** no Amazon-internal system names, internal URLs, logins, building
   codes, manager names, ETL job IDs, or bucket names. Keep former-employer **client names
   genericized**. Industry-standard tech names (AWS Lambda, Bedrock, Claude, Redshift, S3,
   DynamoDB, Python, FastAPI, etc.) are fine.
2. **AI-forward but honest.** Lead with AI/automation, never invent capabilities. Frame
   Staples work as analytics/automation/algorithms (not "AI agents").
3. **Keep impact metrics** ($ savings, %, scale) — strongest recruiter signal.
4. **Two-company split stays:** Amazon projects under the Amazon header (gradient dot),
   Staples projects under the Staples header (red `.staples` dot).
5. **Consistency:** the "Shipped" fact, the hero `14+` stat, and the real project count
   must agree when projects change.
6. **Placeholder to fill:** the LinkedIn `href` (`https://www.linkedin.com/in/your-handle`).

## Projects on the site
- **Amazon (6):** Migratrix (GenAI SQL migration, Bedrock+Claude) · Autonomous Inventory
  Health Agent · Real-Time Operations Control Tower · Redshift Cluster Scaling & Load
  Balancing · Intelligent Shrink Attribution Engine · Automated Business Review Intelligence.
- **Staples (8):** Fulfillment Costing & Channel-Shift Model ($2M) · Line-Haul Utilization &
  Mode-Shift Engine ($500K+) · Restock Savings Tracker ($1.5M) · Drop-Ship Transformation
  Analysis ($365K) · Fuzzy Address-Matching Model (Levenshtein) · Cost Data-Quality
  Investigation · Inventory Re-Slotting & Network Optimization ($160K) · Hidden-Cost &
  Customer Profitability Audit.

## Run locally
```bash
open index.html              # or:
python3 -m http.server 4321  # http://127.0.0.1:4321/
```

## Deploy pipeline (store → production)
**Claude Code (edit) → GitHub (store) → Vercel (deploy).** Vercel: framework = Other,
no build command, output dir = root. After setup, every change is:
```bash
git add -A && git commit -m "describe change" && git push
```
Branch/PR → preview URL; merge to `main` → production.
