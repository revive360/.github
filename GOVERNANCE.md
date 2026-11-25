# Governance

## Owners and decisions

Pedro ([PedroHenrique0713](https://github.com/PedroHenrique0713)) is the founder and **only organization owner today**. The org already exists as [`revive360`](https://github.com/revive360). He manages membership, security and moderation. Each project names its owner/maintainers in its README and decides its roadmap within these rules. Start members with no base repository access; grant read/triage/write only as needed. Increase access through contribution history and security practice. Nobody becomes an owner just because a seat is vacant.

Use a public issue for ordinary decisions and record the outcome. Discuss in Portuguese, Spanish or English. For a disputed project decision, ask the project owner to review it; for membership, moderation or an organization rule, ask the steward. If a complaint concerns the steward, request an uninvolved maintainer to review it; while there is no other maintainer, the organization cannot promise an independent appeal panel.

The founder decides rule changes after a public proposal and **14 calendar days' notice**, recording feedback, decision and effective date in all existing translations. Emergency security restrictions/revocations are immediate, followed by a safe public explanation and review. This notice period is the initial operating policy and can change through this process.

## Joining and admitting a project

The [three levels and review limits](REVIEW.md) govern catalog admission. **Revive360 Project** requires a repo inside the org; **Reviewed · vX.Y.Z** covers only a specific external version/hash/date; **Community list** is unverified discovery with no badge. Membership is not a seal. The org takes operational responsibility only for its repos and the external versions reviewed within the published scope. A member's unlisted repo belongs solely to its author. Software is as is under its license; unauthorized name/badge use is misuse, contradicted by the catalog.

Contributors can participate without joining. Use a membership request to describe what you want to maintain. The steward grants membership and the minimum required access after agreement on the rules.

An app proposal must identify an accountable owner, a useful application, its open license, source repository, all external code and licenses, and a plan for testing on real hardware. The owner of an existing project must expressly agree to join. Review provenance and license compatibility before importing code or transferring a repository. The steward records acceptance or the reason for rejection in the proposal. Do not advertise a third party's project as a member before acceptance.

## Licenses and authorship

There is no organization-wide software license. Each project chooses an open license and preserves copyright and dependency notices. MIT and GPL projects may coexist. Do not copy GPL code into an MIT-only project without meeting the GPL; linking and redistribution also require review. A change of license requires the relevant rights holders' permission. Membership and repository transfers do not transfer copyright.

Only code made by members, or open libraries with compatible licenses, belongs here. Imported work must identify its source and license. Do not claim an upstream library as our own.

## Red lines

No piracy, games, keys, leaked Microsoft SDKs or exploit distribution. BadUpdate/RGH are external prerequisites managed by users. Do not host unlocking payloads, SDK binaries or copyrighted game assets. A provenance doubt blocks import or packaging until resolved; a label claiming an open license alone does not resolve contradictory evidence. Remove violating material from distribution and review the concern before continuing.

Apps using third-party services must not bypass DRM/paywalls; service terms risk belongs to the author. Every org app README must carry the Xbox Live ban/damage warning and privacy notice in [APP_README_TEMPLATE.md](APP_README_TEMPLATE.md). No collection without opt-in; login/tokens stay on the console.

## AI and releases

AI is permitted as a tool. The human signing off is responsible for correctness, provenance, security and licenses, including generated code. Do not upload confidential material to an AI service. AI use does not replace review or testing.

Every release must be tested on a real console. Record console model/setup, source revision, build inputs, artifact hash, checks and outcome in the release evidence. A successful build alone is not a console test.

Require reviewed PRs, DCO sign-off on contributions and CI-built releases with hashes and signature/attestation. Nobody reviews their own app **except founder Pedro**, including at the maximum level. Record the exception; all evidence requirements remain. See [SETUP.md](SETUP.md).

## Leaving, transfer and inactivity

A member or project owner can leave by informing the steward. Remove access promptly, preserve attribution and licenses, and agree whether to transfer the repository back, keep it with a new consenting owner, or archive it with a link to its new home. Existing open licenses remain in force; leaving does not revoke users' existing rights. Do not assign maintainership to someone without their agreement. Mark an ownerless project unmaintained and archive it if no owner accepts it; do not imply it is still supported.

The author may take the project back to their account. Revoke its Project status on transfer; external Reviewed status needs a separate exact-version review. Keep catalog history and a redirect. After **12 months without maintenance activity**, notify the owner and archive unless an active maintenance plan is recorded. Violations may cause immediate suspension/revocation and archival after preserving safe evidence.

## Money and contact

The org currently **receives no donations and splits no donations**. Individual authors' arrangements are theirs and cannot be presented as the org's pool.

Until December 2026 use private vulnerability reporting for security, issues/Discussions for public governance, and a request for a private channel for conduct reports. `CONTACT_DECEMBER_2026_TODO`: add only the owner's confirmed email/domain when available.
