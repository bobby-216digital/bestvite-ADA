# Engagement context: Bestvite a11y remediation

- Branch: `216-a11y` (already checked out, tracks `origin/216-a11y`, clean)
- Repo: bobby-216digital/bestvite-ADA (git host: GitHub)
- Stack: Shopify theme, based on Dawn 14.0.0 (see config/settings_schema.json theme_info)
  - No package.json/build tooling found at repo root; standard Shopify theme structure (layout/, sections/, snippets/, templates/, config/, locales/, assets/)
  - Docs: Shopify Dawn theme repo (github.com/Shopify/dawn) + Shopify theme accessibility guidance (Shopify Polaris/theme a11y docs) — use as source of truth for idiomatic ARIA/focus patterns in Liquid/JS
- Pass(es) in scope: Powermapper-scan-driven only (per user request)
- Powermapper report: `/Users/kylehouston/Documents/PowerMapper Scans/Bestvite.schkd/report/map.ACC.htm`
  (most recent Bestvite scan folder, Aug 27 2026; also PDF exports exist in the scans folder but the .htm report is authoritative/parseable)
- Environment for verification: live preview theme
  - URL: https://mwk48yd9aah4miq4-40380661920.shopifypreview.com/
  - Treat as read-only preview for smoke-testing fixes in a browser; no local dev server confirmed. Do not mutate live/admin data.
- No other non-obvious human-provided context yet (brand/design constraints, known false positives, CMS-admin-only changes) — none surfaced so far.
