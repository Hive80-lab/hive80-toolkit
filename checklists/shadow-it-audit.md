# Shadow IT Audit Checklist for Small Teams

Adapted from the full guide: [ops-notes/shadow-it-audit-checklist](https://hive80-lab.github.io/ops-notes/shadow-it-audit-checklist)

## Checklist

- [ ] Card-statement sweep: every recurring software charge is a tool — label each known, forgotten, or mystery
- [ ] Shared-inbox sweep: search for "your account is ready" confirmation emails (one person can grep a year in ten minutes)
- [ ] Walk one shared laptop's browser history and extensions to count tools
- [ ] Rank findings by data held: money and customer data first, convenience tools last
- [ ] Classify each tool's auth: shared admin password, one person's work email, or proper SSO — a customer-data tool on a shared password is your top finding
- [ ] Check which tools touch production (repos, deploy platforms, invoicing) and force MFA plus named owners, no exceptions
- [ ] Count the AI assistants people actually use — each is a third party receiving your conversations, sometimes customer data
- [ ] Paste-test: if a teammate could paste a customer contract into a tool unnoticed, the policy is missing, not the person
- [ ] Decide per tool: adopt (into SSO), contain (restrict data), or retire (export then delete)
- [ ] Assign one named owner per surviving tool
- [ ] Calendar a quarterly 30-minute card-statement sweep
- [ ] Write the one-line AI-tools policy: what may be pasted, and into which tools

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*
