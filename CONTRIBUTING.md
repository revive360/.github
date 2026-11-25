# Contributing: bring work you can stand behind

English, português, español. Use yours. You can show up with code, docs, tests or a useful bug report. Tell us what you tried and ask when you get stuck.

The crew meets in [Revive360 Discussions](https://github.com/orgs/revive360/discussions), sourced from `.github`. App ideas, help and demos go there. Concrete bugs, formal app reviews and membership requests use issues. Vulnerability details go through [private reporting](SECURITY.md).

## Before you open the PR

Read the eleven [house rules](profile/README.md#rules), [GOVERNANCE](GOVERNANCE.md) and [Code of Conduct](CODE_OF_CONDUCT.md). Then bring four things:

- **What changed and why.** Name the problem and the result. For a new app, show what it adds or does better than the existing options. Renaming the template isn't a new app.
- **A change we can review.** Keep one purpose in the diff. Split unrelated work. A huge untested dump comes back for another pass; there is no magic line-count cutoff.
- **Evidence.** For console-affecting app code, it must already run on a real Xbox 360. Give the model/setup, source commit, artifact hash and log, photo, video or another record. For docs or tooling that does not run on the console, say what you checked and why console execution does not apply. A build or emulator run alone is not a console record.
- **An author who can answer.** Use AI if it helps. Read the result, understand the code and check its origin. If the reviewer asks how it works, answer it yourself. “The AI did it” doesn't close the question.

If an item is missing, the reviewer names it and returns the PR for changes. Review is based on technical reasons and these checks, not a debate about personal taste. Disagreement is fine. Personal attacks aren't.

## Credit the work. Sign yours.

Identify every new dependency or copied piece: source, license and notices. Follow the receiving project's license. Keep secrets and private configuration out of code, logs and screenshots.

Sign every contribution commit with `git commit -s`. The `Signed-off-by: Name <email>` trailer certifies the [Developer Certificate of Origin 1.1](https://developercertificate.org/); it is distinct from cryptographic signing. Use your contribution identity, preserve prior sign-offs and retain them when squashing/merging. DCO checks every PR commit.

## From contribution to responsibility

Keep showing quality, technical understanding, trust and follow-through. Roles come by invitation from the responsible maintainer or org owner within their authority. There is no “X PRs buys a role” formula and no automatic promotion. A maintainer decides for the project; org owners decide for the org. To contest a decision, use the evidence-based route in [GOVERNANCE](GOVERNANCE.md).

## Release and review requirements

No release without real-console evidence for the exact source and artifact hash. Project releases must be built in CI with hashes and signature/attestation. Nobody reviews their own app except founder Pedro, including at the maximum level, with the exception recorded. External reviews are FIFO with a 14-day target; security response is 48 hours. Community entries have no badge. [Full review policy](REVIEW.md).

No piracy, games, keys, leaked SDK material, exploits or DRM/paywall bypass. Console preparation remains outside the org. Report provenance concerns privately through [SECURITY](SECURITY.md); do not attach suspected material.
