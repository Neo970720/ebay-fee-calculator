# eBay Fee & Profit Calculator (2026 rates)

Free, single-page eBay fee calculator. No sign-up, no tracking scripts, no external requests.

**Live:** https://neo970720.github.io/ebay-fee-calculator/

## What it does

- 2026 US final value fee for 13 eBay categories (most 13.6% up to $7,500 per item, 2.35% above),
  with the separate No Store / Basic+ rate cards.
- Per-order fee, insertion fee, international fee, promoted listings charged on the taxed total,
  sales tax on the fee base.
- Profit after cost of goods, prep, label and ad rate — plus the list price to hit a target margin.
- Athletic shoes at $150+ (8%, no per-order fee) and jewelry as a whole-sale cliff, not a slice.

Checked against the companion workbook `eBay True Profit OS`:
a $59.99 item, $9.30 shipping, no tax, 5% ad rate, $38.49 cost →
$9.42 final value fee + $0.40 per-order + $3.46 ad = **$13.28 fees**, **$17.52 profit** (25.3% margin).

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole calculator (inline CSS + JS, no dependencies) |
| `robots.txt`, `sitemap.xml` | Crawling and discovery |
| `_headers` | Security headers (GitHub Pages honours this only with certain setups; harmless otherwise) |
| `.nojekyll` | Serve files as-is |
| `google0054193d5bc33842.html` | Google Search Console ownership verification |
| `bbff316b926c598b2876860aea94b967.txt` | IndexNow key |

Built by [Sheetwright](https://sheetwrightstudio.gumroad.com). Not affiliated with eBay Inc. Rates read
from eBay's published fee pages on 20 November 2026.
