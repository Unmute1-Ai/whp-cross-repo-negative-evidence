# Independent Cross-Repository Negative Verification

**Result:** 15/15 PASS · **Date:** 2026-09-19

This repository holds **independent evidence** of a cross-repo negative suite against Wheeler Hubbell Publishing public surfaces (DIP, Standing, StandingMark, WheelerHubbell, WHP-Vending).

It is **not** a security audit, not an official WHP result, and not a claim of funded mainnet or production completion.

## Public statement

> Independent verification of Wheeler Hubbell’s public surfaces and a separately constructed 15-case cross-repo negative suite found no demonstrated confused-deputy escalation or receipt-to-capability promotion across the tested DIP, Standing, StandingMark, WheelerHubbell, and WHP-Vending boundaries. Funded mainnet completion and private execution paths remain outside the evidence obtained.

**Correct label:** Independent Cross-Repository Negative Verification — 15/15 PASS

## Contents

| Path | Description |
|------|-------------|
| `CROSS_REPO_VERIFICATION.md` | Full human-readable technical record |
| `PUBLIC_SNIPPET.md` | Short text for a public verification page |
| `PUBLICATION_NOTES.md` | Where/how to publish without overclaiming |
| `cross-repo-negative-2026-09-19/` | Dated artifact: JSON results, harness sources, SHA256SUMS |

## Reproduce

```bash
python cross-repo-negative-2026-09-19/cross_repo_negative.py
python cross-repo-negative-2026-09-19/harness.py --json run.json
```

## Naming discipline

Do **not** describe this as “passed a 15/15 security audit” or “100% secure.”
