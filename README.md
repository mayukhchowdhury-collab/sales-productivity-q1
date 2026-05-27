# Sales Productivity Time Study · Q1 2026

Live: https://mayukhchowdhury-collab.github.io/sales-productivity-q1/

Q1 2026 fact pack measuring how Moloco Ads sales reps spent their time across
calendar, Gong, Slack, and inferred internal-tool channels. Sales-org cohort
of 124 reps (Department = "Ads Sales"); ≥15 Q1 calendar events for inclusion.

## How it's generated

```bash
cd ~/sales-productivity
python3 scripts/build_factpack_html.py    # writes ./web/factpack_q1.html
cp ~/sales-productivity/web/factpack_q1.html ~/git/sales-productivity-q1/index.html
cd ~/git/sales-productivity-q1
git add . && git commit -m "Refresh Q1 fact pack" && git push
```

Single self-contained HTML — no build pipeline, no JS dependencies beyond
Google Fonts CDN. Per-rep data embedded inline for client-side filtering.

## Contact

Prepared by Mayukh Chowdhury · GTM Revenue & Analytics
