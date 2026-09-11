# MFA Rollout Checklist for Small Teams

Adapted from the full guide: [ops-notes/mfa-rollout-checklist-small-business](https://hive80-lab.github.io/ops-notes/mfa-rollout-checklist-small-business)

## Checklist

- [ ] One backup admin per critical app: the person who can reset MFA for someone else must not be the person most likely to lose their own phone the same week.
- [ ] Then enforce the rest in one batch. Keep "allow existing sessions" on if the app offers it, so nobody gets logged out mid-task on day one.
- [ ] Enforcing before recovery codes exist. This is the one that turns a Tuesday into a payroll outage. The recovery layer is section 2 for a reason.
- [ ] "Optional" forever. The users who most need MFA are the ones most likely to skip an optional setting. Set the enforcement date when you announce the rollout.
- [ ] Recovery before enforcement: break-glass admins, per-person recovery codes, and a written lost-phone path exist before the first "enforced" toggle.
- [ ] Pilot on volunteers so the broken integrations surface on five people instead of forty.
- [ ] Authenticator over SMS, hardware keys for admins, exceptions with expiry dates — and nothing stays "optional."

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*