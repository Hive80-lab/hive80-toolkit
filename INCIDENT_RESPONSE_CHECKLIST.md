# The First 30 Minutes of an Incident — small-team checklist

Public reference version, maintained by [Hive80 Lab](https://hive80-lab.github.io/ops-notes/).
> The **printable one-pager** (fill-in blanks, severity table, copy-paste comms templates) is free at [hive80lab.gumroad.com/l/first-30-minutes](https://hive80lab.gumroad.com/l/first-30-minutes).

Your team has no dedicated on-call staff. Something is broken. Run this in order — do not skip to fixes before Steps 1–3.

## 0–2 min · Establish
- [ ] **Who is Incident Lead?** One name, said out loud. (Not "we'll all figure it out.")
- [ ] **Where do we talk?** One bridge/channel (Slack `#inc-YYYYMMDD`). Everything else is noise.
- [ ] Start a timestamp log. Even plain text. Times from here on are evidence.

## 2–5 min · Triage
- [ ] **Who is affected?** (all users / one tenant / internal only)
- [ ] **What is the user-visible symptom?** Say it in one sentence a customer would recognize.
- [ ] **What changed in the last 24h?** (deploys, config, DNS, certs, vendor updates) — write them down even if you "know" they're innocent.

## 5–15 min · Classify & contain
- [ ] Assign severity (3 levels is enough):
  | Sev | Meaning | Response |
  |---|---|---|
  | S1 | All users down / data at risk | All hands, page everyone, status page |
  | S2 | Major feature broken, workaround exists | On-call + one helper, status page if >30min |
  | S3 | Minor, internal, workaround | Fix in business hours |
- [ ] **Contain before you understand.** Rollback, feature-flag off, block at the edge. You are not "solving" it yet — you are stopping the bleeding.
- [ ] If S1: post status page update *now*. One line: "We are investigating an issue affecting X."

## 15–30 min · Communicate & stabilize
- [ ] Internal update every 15 min, even if it's "no change, next update 14:45."
- [ ] One person investigates; one person communicates. Never the same pair of hands.
- [ ] Do **not** restart the same service twice "to see." Note every action with its timestamp.
- [ ] Stable? Freeze: no deploys, no config changes until a written "all clear."

## After (within 48h)
- [ ] Blameless postmortem: timeline → root cause → 3 concrete fixes with owners and dates.
- [ ] The fixes that survive are process, not patches: runbook entries, dashboards, alert thresholds.

---

**Why teams fail this in practice:** no named lead (3 people "coordinating" = nobody deciding), no single channel, and skipping "what changed" because confidence is cheaper than checking. The paid [Ops Starter Kit](https://hive80lab.gumroad.com/l/ops-starter-kit) ($14) turns this checklist into a fillable IR plan with severity matrix, tabletop scenarios, and the comms templates pre-written.

## Related
- [Ops-notes: free guides for teams without an ops dept](https://hive80-lab.github.io/ops-notes/)
- [On-call rotation template](https://hive80-lab.github.io/ops-notes/on-call-rotation-schedule-template.html) · [Backup restore test checklist](https://hive80-lab.github.io/ops-notes/backup-restore-test-checklist.html)

*Template — adapt to your team; not legal or regulatory advice.*
