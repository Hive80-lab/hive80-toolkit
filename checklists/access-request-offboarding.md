# Access Request & Offboarding Checklist for Small Teams

Adapted from the full guide: [ops-notes/access-request-offboarding-checklist](https://hive80-lab.github.io/ops-notes/access-request-offboarding-checklist)

## Checklist

- [ ] System: the exact name, not "the cloud thing."
- [ ] Person + role: who, and what they do for the company.
- [ ] Access level: viewer / editor / admin. Default to the lowest that works.
- [ ] Duration: permanent, or ends on a date (contractors always get dates).
- [ ] Approver: one named human. Forwarded DMs don't count.
- [ ] Reason in one sentence: if nobody can write it, access doesn't get granted.
- [ ] Every system you run gets a 3-5 line grant recipe: where the admin panel lives, the exact permission set for each level, and what the invite email should say.
- [ ] Mark which systems support SSO or deprovisioning APIs — those go first in the offboarding list below because they're the ones people forget.
- [ ] Shared credentials get an owner and a rotation date. A password in a group chat is not a credential policy, it's a countdown.
- [ ] Rotate shared credentials: anything the person knew or could have known, including WiFi passwords and API tokens tied to their account.
- [ ] Remove external access: vendor portals, client admin panels, social accounts, the domain registrar. Contractors accumulate these silently.
- [ ] Recover hardware & note the date. The date matters: "revoked the same day" is the sentence you want to be able to write.
- [ ] Admin-for-everyone: the default grant level of busy teams. Cost shows up later as an unexplained change nobody can attribute.
- [ ] The growing spreadsheet nobody updates: if the inventory isn't the same doc the requests land in, it's already stale. One doc, one place, newest on top.

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*