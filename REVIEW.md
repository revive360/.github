# Review levels and evidence

The [catalog](https://github.com/revive360/catalog) is the source of truth. Membership, a copied badge and a repository name confer no status. Every badge links to the app's record. Check its repository, version, SHA-256, date and state: a cached/copied image is not a cryptographic certificate.

| Level | Scope and release | Lifetime |
| --- | --- | --- |
| **Revive360 Project** | Repository inside `revive360`; organization rules, security, review and signed/attested CI releases. Dark compact mascot badge with a neon-green outline plus an exclusive circular Project medal, strongest level. | Continuous while compliant; revocable. |
| **Reviewed · vX.Y.Z** | Repository stays with its author. Only the recorded version, source and artifact hash were reviewed on the recorded date. Author builds; org checks the hash and its correspondence to the checked source. | New versions return to the manual queue; badge says **current version not reviewed**. No org update channel. |
| **Community list** | Discovery only, below both reviewed sections; no badge, verification or recommendation. | May be removed at any time. |

Every Community entry displays: **Not verified by Revive360; not a recommendation; use at your own risk.** / **Não verificado pela Revive360, não é recomendação, use por sua conta e risco.** / **No verificado por Revive360; no es una recomendación; úsalo bajo tu responsabilidad.**

External reviews deliberately require more manual work and have lower priority than Project releases. Authors submit a new request for every version, including replaced assets under the same tag. A source/binary hash change invalidates the current-version claim even when the version string is unchanged. Preserve the old review as historical evidence, never approval of the replacement. Reviewed apps have a separate section beneath Projects.

## Reviewer and checklist

Nobody reviews their own app, **except founder Pedro (`PedroHenrique0713`)**, who may review every project, including his own, at the highest level. Record this exception; do not claim independent review. DCO, CI evidence and console testing still apply.

Record owner, reviewer, decision/date, source commit, version, download URL, SHA-256 and evidence:

- [ ] Open license; declared dependency sources, compatible licenses and preserved notices.
- [ ] No leaked Microsoft SDK or material with unresolved provenance.
- [ ] Binary built from checked source and inputs. For external builds, independently download/hash the author's artifact and inspect the source/build linkage; request a reproduction if the linkage is unclear. Matching a hash alone does not establish that linkage.
- [ ] Tested on a **real console**: person, date, model/setup, source commit, exact binary hash, behavior, normal exit and results. PC/emulator does not satisfy this.
- [ ] No hidden collection; any telemetry is documented, opt-in before collection and disableable. Login credentials/tokens stay on the console, never org services or logs.
- [ ] No DRM/paywall bypass, piracy, games, keys or distributed exploits. Third-party service terms risk belongs to the author.
- [ ] README risk/privacy notice present; release origin/hash verified; review and DCO requirements met.

This is **not a complete security audit**: it does not cover every code path, dependency/history, future version, console model, service availability or terms enforcement, or guarantee freedom from malware, defects, bans or damage. Software is **as is** under its license; no badge adds a warranty. The org's operational responsibility covers its repositories and the external versions it reviewed, within this scope; no disclaimer overrides applicable law. A member's unlisted repo is solely the author's work.

## Priority and lifecycle

1. Security at **any level**: initial response within **48 hours** of receipt, not a promised fix deadline. Severe issue: immediate revocation, suspend unsafe downloads, retain a public tombstone with a safe reason. Remove/flag Community entries rather than issuing a badge.
2. Project release: automatic CI build/hash/attestation flow after reviewed source and exact-artifact console evidence pass. Automation never invents hardware validation.
3. First/renewed external review: FIFO by submission time, target **14 calendar days**, not guaranteed approval. Log received date, version/hash and outcome; security interrupts the queue. Record missing evidence and request it without silently leapfrogging.
4. Community entry: best effort, when capacity permits.

For external reviews record `author_confirmed_on` and `expires_on`. Initial operating default: request confirmation at least every **90 days**, allow **14 days** to respond, expire at the recorded deadline if no confirmation arrives. These periods implement the owner's disappearance rule and may change through governance. Expired reviews retain history, show **Expired**, and require a fresh human decision to return. Contact renewal never approves a new version. Revocation overrides expiry; expiry overrides current-version status. Projects have no expiry date but may be revoked/archived.

On new releases/replaced assets, immediately update external status to **current version not reviewed**, retain the reviewed version/hash/date and enqueue the new request. Authors must report changes; maintainers check upstream releases manually at least weekly until a read-only monitor exists. The generator only uses recorded data/date: it cannot discover upstream changes or disappearance. Regenerate/publish changes promptly. Copied/cached badges cannot override the catalog record.

Unauthorized name/badge use is misuse: link to the catalog record or its absence, request correction and record the decision. Preserve revocation history so stale claims can be refuted.

## Temporary contact

Security: affected repo **Security and quality → Report a vulnerability**, or [org private reporting](https://github.com/revive360/.github/security/advisories/new). Public questions: [official Revive360 Discussions](https://github.com/orgs/revive360/discussions), sourced from `.github`. Formal review requests retain their catalog issue records. If private reporting is not enabled, request a private channel without sensitive details.
