# The First 30 Minutes of an Incident

Adapted from the full guide: [ops-notes/first-30-minutes-incident-response](https://hive80-lab.github.io/ops-notes/first-30-minutes-incident-response)

## Checklist

- [ ] Declare severity (3 levels, one owner, timestamp written down) — more than 5 levels never gets used
- [ ] Contain before diagnosing: containment beats eradication for speed
- [ ] Name in advance which machines get pulled off the network, who is authorized to pull them, and the one shared drive or cloud folder to freeze first
- [ ] Do not act on an unverified guess — a wrong "it is ransomware" call can push you to destroy your only good backups
- [ ] Do not reboot or reimage machines you will need evidence from; preserve logs first
- [ ] Send the one-line "what to do right now" staff message (have the template pre-written)
- [ ] Hold customer-facing comms until you have facts — but have the template ready
- [ ] Start the incident log: time, action, owner, evidence path
- [ ] One response channel; keep the rest of the business running normally
- [ ] Verify backups exist AND are offline or immutable before trusting them
- [ ] Rotate exposed credentials only after you understand the scope
- [ ] At the 30-minute mark: decide — keep handling, or engage outside help

Printable versions + full kits: [Hive80 Lab on Gumroad](https://hive80lab.gumroad.com) — free incident quick-start, paid kits from $9.

*Templates, not legal or regulatory advice.*
