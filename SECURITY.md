# security

report vulnerabilities privately. never in public issues, pull requests or discussions.

- github: security tab -> report a vulnerability
- email: security@octra.org

include the repo, commit or release, impact, and steps to reproduce.

## review

every submission goes through octra's automated security pipeline, which has been running since 2026-07-24 and has reviewed every public repository. every finding it has recorded is timestamped. only genuinely new findings are considered. a report that overlaps an earlier record is not eligible.

we aim to acknowledge within 3 business days and to fix within 90 days. we allow public disclosure only when an issue is fixed. disclosing earlier forfeits any reward.

## rewards

| severity | reward |
|---|---|
| critical | up to 1,000,000 oct |
| high | up to 250,000 oct |
| medium | up to 50,000 oct |
| low | up to 5,000 oct |

reviewers set severity and likelihood at their discretion. a finding that is unlikely to occur will not be rewarded. awarded oct may be vested. submissions may require a working proof of concept or a reproduction on devnet.

## scope

`lite_node` and `webcli`.

## rules

- devnet: test with your own wallets.
- mainnet: read only.
- no denial of service, spam or load testing on shared networks.
- no social engineering.
- no extortion.
