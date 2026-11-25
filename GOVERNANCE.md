# Governance

## Owners and decisions

Pedro ([PedroHenrique0713](https://github.com/PedroHenrique0713)) is the founder and **only organization owner today**. The org already exists as [`revive360`](https://github.com/revive360). He manages membership, security and moderation. Each project names its owner/maintainers in its README and decides its roadmap within these rules. Start members with no base repository access; grant read/triage/write only as needed. Increase access through contribution history and security practice. Nobody becomes an owner just because a seat is vacant.

Use the official [Revive360 Discussions](https://github.com/orgs/revive360/discussions) for community proposals and ordinary governance discussion; record accepted decisions with their effective dates and link relevant issue/PR records. The source is the `.github` repository, with no Discord at launch. Discuss in Portuguese, Spanish or English. For a disputed project decision, ask the project owner to review it; for membership, moderation or an organization rule, ask the steward. If a complaint concerns the steward, request an uninvolved maintainer to review it; while there is no other maintainer, the organization cannot promise an independent appeal panel.

The founder decides rule changes after a public proposal and **14 calendar days' notice**, recording feedback, decision and effective date in all existing translations. Emergency security restrictions/revocations are immediate, followed by a safe public explanation and review. This notice period is the initial operating policy and can change through this process.

## Roles, authority and access

Organization policy takes precedence over project decisions. Organization owners decide organization membership, security controls, shared rules and disputes about their application. A project maintainer decides the project's technical direction, reviews and releases within those rules. A project maintainer cannot waive organization requirements. Decisions and their reasons must be recorded by the authority responsible for them.

| Role | Scope and responsibility |
| --- | --- |
| Organization owner | Organization policy, membership, permissions, moderation and final organization-level decisions. Only Pedro holds this role today. |
| Project maintainer | The named project's roadmap, review, issues, security follow-up and releases, subject to organization policy and granted repository permissions. |
| Member | Organization participant with only the repository access explicitly granted. Membership confers neither maintainership nor a catalog badge. |
| Contributor | A person submitting code, documentation, tests or reports. Organization membership is not required; contributions alone grant no repository access. |

Access and role changes require an explicit invitation or approval from an authorized person above the requested role. Maintainers may recommend contributors and project access within their scope; organization owners approve organization membership and maintainer appointments. Only an existing organization owner may appoint another owner. These are authority rules, not automatic GitHub role mappings.

Assess contribution quality, technical understanding, reliability, collaboration, security practice and sustained participation. There is no PR-count formula, automatic promotion, entitlement through tenure or appointment to fill a vacancy. Grant the minimum access needed, record the inviter/approver, scope and reason, and review it when responsibilities change.

Access may be reduced or removed on request, departure, loss of the relevant responsibility, sustained inactivity, loss of trust supported by documented conduct, a rule violation or an account compromise. Severe security/provenance violations may require immediate suspension and removal. The responsible maintainer may restrict access within their granted authority; organization owners decide organization membership/roles and any remaining access action. Record the reason and affected scope without exposing private reports or secrets. Departure and archival rules below still apply.

## Contesting a decision

Ask the responsible maintainer to reconsider a project decision, linking the decision and supplying technical evidence or the relevant policy. If unresolved, or if organization policy/permissions are involved, request review by an organization owner. An organization-level decision is reconsidered by the organization owner; organization authority takes precedence over project authority. Use Discussions for public matters and a private channel for security or personal conduct details.

If a complaint concerns the founder, request input from an uninvolved maintainer where one is available. With one owner, no independent appeal panel is promised. Record the final decision and rationale. Contesting a decision does not itself restore suspended access or waive release/security requirements. Technical disagreement is permitted; personal attacks are not.

## House rules — normative version

The public profiles use informal language. The numbered requirements below are the normative version of the same eleven rules.

1. **Functional contributions.** Application code submitted for review must run on a real Xbox 360. Nonfunctioning application code is not ready for a PR.
2. **Contribution quality.** AI tools are permitted. Submissions must not contain code the author cannot explain, unreviewably large changes without tests, generic emoji-heavy documentation or a renamed template presented as a distinct new application.
3. **Human accountability.** The signing contributor is responsible for submitted work, including AI-assisted code, and must answer technical review questions. Tool output is not an excuse for defects or unknown provenance.
4. **Distinct purpose.** An app proposal must identify a capability not served by existing apps or a concrete improvement over them. A redundant clone without a justified difference is not admitted.
5. **Open and lawful inputs.** Use original code or compatible open code. Pirated software, games, keys, leaked SDKs and distributed exploits are prohibited. Submitting prohibited material results in removal of access and exclusion from participation; preserve safe evidence and the right to contest the decision above. Console preparation remains outside the organization.
6. **Real-console release evidence.** No release may be published without a log, photograph, video or other record from a real Xbox 360, tied to the tested source revision and artifact hash. PC/emulator output alone does not satisfy this requirement.
7. **Respectful disagreement.** Humor and technical criticism are permitted. Personal attacks are prohibited. Criticism must address the work with technical reasons and comply with the Code of Conduct.
8. **Project ownership.** Each project must have an accountable owner who handles its issues and security findings. Organization response priorities and review obligations remain in force.
9. **Attribution and licenses.** Preserve authorship, credit third-party work and comply with the applicable licenses and notices.
10. **Decision hierarchy.** Organization owners have final authority for the organization; the responsible maintainer has final authority within a project, subject to organization policy. Discussion does not transfer decision authority.
11. **Qualitative advancement.** Access and roles are granted by invitation based on quality, trust and real contribution. No fixed contribution count, automatic promotion or vacant role creates an entitlement to access or ownership.

For PRs, require the problem and rationale, a reviewable scope, relevant test evidence and an author able to answer questions about the code. Console-affecting application changes require real-console evidence identifying source/hash and log/photo/video. Non-runtime changes must state the applicable verification and why console execution does not apply. Return incomplete submissions with the missing objective items; personal taste alone is not a review criterion. No numerical PR-size or contribution-count promotion threshold is introduced.

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

Until December 2026 use private vulnerability reporting for security, [official Discussions](https://github.com/orgs/revive360/discussions) for public governance, and a request for a private channel for conduct reports. `CONTACT_DECEMBER_2026_TODO`: add only the owner's confirmed email/domain when available.
