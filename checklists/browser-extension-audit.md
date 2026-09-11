# Browser Extension Security Checklist for Small Teams

Adapted from the full guide: [ops-notes/browser-extension-security-audit](https://hive80-lab.github.io/ops-notes/browser-extension-security-audit)

## Checklist

- [ ] Kill duplicates. Three ad blockers fight each other, triple the privilege surface, and slow every page load. Keep the best one, delete the rest.
- [ ] Turn on automatic updates (Chrome and Edge default to on; Firefox is a settings toggle). An un-updated extension is a known-vulnerable one waiting for a scan.
- [ ] Open every browser's extension page once this quarter — today is fine.
- [ ] Delete everything you don't recognize, haven't used in 90 days, or wouldn't install again.
- [ ] Check "last updated" on the survivors; abandon anything stale with broad permissions.
- [ ] Write the one-line install policy in the team channel. Done. Next quarter, repeat — it gets faster every time.

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*