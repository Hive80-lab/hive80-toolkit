# Contractor Security Onboarding Checklist for Small Teams

Adapted from the full guide: [ops-notes/contractor-security-onboarding-checklist](https://hive80-lab.github.io/ops-notes/contractor-security-onboarding-checklist)

## Checklist

- [ ] Put the end date in the plan before work starts — write it where the access lives, next to the grant
- [ ] One internal owner approves every grant and runs the final revocation
- [ ] One identity email, MFA-backed, owned by the contractor but linked to your recovery
- [ ] Least-privileged seats only: guest, not member; read-only viewers where the tool supports it
- [ ] Shared vault for shared secrets — never a shared password
- [ ] Mark every contractor account at creation: role note, engagement name, end date
- [ ] Split the tool inventory into grant, share, and never
- [ ] Repo access follows the branch model, not the org model (fork or scoped project)
- [ ] Chat access is a channel list, not the org chart — single-channel guest in the project channel
- [ ] Production is a milestone: local sandbox, staging, production read, production write — each step a date
- [ ] Credentials through the vault, nothing through chat DMs
- [ ] Issue per-purpose secrets where the system allows (contractor deploy key, contractor database user)
- [ ] Grant log five lines: secret name, contractor, issued, expiry, vault location
- [ ] Rotate on the calendar for long engagements, not on suspicion
- [ ] One security clause in every agreement, in plain sentences
- [ ] Data return and deletion, written down and confirmed at the end (working files, local copies, personal drives)
- [ ] Re-verify identity channels on day one (one video call)
- [ ] One laptop policy sentence: current OS updates, screen lock, disk encryption
- [ ] Route sensitive work through your VPN or gateway
- [ ] Never grant access from your own session — use the contractor's own onboarding invite
- [ ] Keep grant log with the contract, one folder per engagement
- [ ] Calendar a mid-engagement review for engagements over six weeks

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*
