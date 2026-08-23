# frcc-audit

Public WCAG 2.1 AA audit results for [frontrange.edu](https://frontrange.edu) (Front Range Community College).

**You are looking at a data + site repository, not source code.** Contents are published automatically by a GitHub Actions workflow in the [audit tooling repo](https://github.com/ThirstyHead/audit-frontrange.edu) on a weekly schedule.

- **🌐 [Report site](https://thirstyhead.com/frcc-audit/)** — rendered results + trend (GitHub Pages, served from `docs/`)
- **`reports/`** — raw axe-core report JSON, one file per run (`axe-<UTC timestamp>.json`)
- **`docs/latest.json` / `docs/history.json`** — machine-readable latest run and full time series

Data is produced with [axe-core](https://github.com/dequelabs/axe-core) against the WCAG 2.1 A/AA rule set. Automated tooling detects only a subset of accessibility failures and does not replace manual or assistive-technology testing.