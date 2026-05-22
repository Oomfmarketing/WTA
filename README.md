# Book Turku — Trends Dashboard (public snapshot)

Public, shareable snapshot of Bookturku.fi sales analytics. Single static HTML, no backend.

- **Data window:** 2024-04 → 2026-05 (snapshot 2026-05-21)
- **Source:** Bokún REST API, Book Turku channel
- **Bookings:** 423 confirmed / 32 755 € BM / 956 PAX
- **Live URL:** https://oomfmarketing.github.io/bookturku-trends/ *(after Pages is enabled)*

This is a one-off snapshot. The fully-automated 4 h-refresh version lives in `oomfmarketing/bookturku-trends` (separate repo with fetcher + GH Actions).

## Update the snapshot

Replace `index.html` with a freshly built version from the [bookturku-dashboard scaffold](../bookturku-dashboard/), then `git push`.

## Notes

- Bruttomyynti (BM) is gross booking value through the channel, **not** FAS-liikevaihto.
- No PII — aggregates only.
- Vendor- and product-level figures are included by explicit CEO approval (2026-05-22).
