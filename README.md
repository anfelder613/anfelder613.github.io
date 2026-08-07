# anfelder613.github.io

Portfolio index for the Data Analytics & Visualization capstone — a single page linking four
university analytics dashboards.

**Live:** https://anfelder613.github.io/

## The projects

| # | Project | Data | Hosting |
|---|---|---|---|
| 01 | [Institutional Data Dashboard](https://github.com/anfelder613/university-dashboard) | Synthetic | Local (Streamlit) |
| 02 | [PhD Completions Dashboard](https://github.com/anfelder613/yu-enrollment-dashboard) | IPEDS Completions | [Live](https://anfelder613.github.io/yu-enrollment-dashboard/) |
| 03 | [Institutional Resources Dashboard](https://github.com/anfelder613/yu-institutional-resources-dashboard) | IPEDS Finance | [Live](https://anfelder613.github.io/yu-institutional-resources-dashboard/) |
| 04 | [Peer Tuition Dashboard](https://github.com/anfelder613/yu-tuition-dashboard) | IPEDS Cost | Local (Streamlit + Postgres) |

Projects 02 and 03 are static React builds, so they deploy to GitHub Pages directly.
Projects 01 and 04 are Streamlit apps needing a live Python process — 04 additionally queries
PostgreSQL — so neither can run on Pages. Each repo's README covers how to run it locally.

## Editing

Single self-contained `index.html` — no build step, no dependencies. Push to `main` and
GitHub Pages redeploys automatically.
