# Revive360

**New, open software for a twenty-year-old console.** We build real apps for today's Xbox 360, from scratch and in the open, using the existing homebrew ecosystem.

[Português](README.pt-BR.md) · [Español](README.es.md)

## Catalog and three levels

- **Revive360 Project** — repository inside [revive360](https://github.com/revive360), organization rules/security, reviewed PRs and signed/attested CI releases; continuous status while compliant. Green mascot badge, strongest level.
- **Reviewed · vX.Y.Z** — external author's repository, only that reviewed version/hash/date. New or replaced binaries return to a lower-priority manual FIFO queue (target 14 days); **current version not reviewed** until accepted. Author builds, org verifies the hash and source linkage; no org update channel. If the author disappears, the badge expires.
- **Community list** — discovery without a badge: **Not verified by Revive360; not a recommendation; use at your own risk.** Entries may be removed at any time.

The [catalog](https://github.com/revive360/catalog) is authoritative; badge images link to app records and can be valid, current-version-not-reviewed, expired or revoked. Membership is not a badge. The org takes operational responsibility for its repos and the external versions reviewed within the documented scope; an unlisted member repo is solely the author's. Unauthorized name/badge use is misuse. Review is not a complete audit; software is **as is**, with no badge warranty.

**Tube360** — native YouTube app, MIT, owner [Pedro](https://github.com/PedroHenrique0713). Its [actual repository](https://github.com/PedroHenrique0713/tube360) remains with the author. The local catalog's Project record is explicitly a **demonstration of a future org-hosted state**, not a transfer or live certification. No other real app is listed.

Security at every level receives a response in **48 hours**, with immediate revocation if severe. Project releases follow the automatic CI flow after review and exact-binary console testing; external reviews target **14 days** FIFO; Community admission is best effort. Nobody reviews their own app **except founder Pedro**, including at the highest level. Read the [checklist and limits](../REVIEW.md).

## Rules

1. Only open code written by members, or open libraries with compatible licenses.
2. No piracy, games, keys, leaked Microsoft SDKs or distributed exploits. BadUpdate/RGH are prerequisites managed by users, outside this organization.
3. Each project has an owner and its own license. MIT, GPL and other open licenses can coexist; moving code between projects must respect its license.
4. Every release is tested on a real console.
5. AI tools are allowed. Whoever signs off on the code is responsible for it.
6. The community works in Portuguese, Spanish and English. Use whichever you speak; translation help is welcome.

## Build something or join

Open an **App proposal** or **Join Revive360** issue in this repository. Describe the app, the person responsible, the proposed license and the sources of its dependencies. Existing projects join only with their owner's agreement. Contributing does not require membership. Read [CONTRIBUTING](../CONTRIBUTING.md), [GOVERNANCE](../GOVERNANCE.md) and the [Code of Conduct](../CODE_OF_CONDUCT.md).

## Built on an existing ecosystem

Thank you to [xenosworks](https://github.com/xenosworks): [xsdk](https://github.com/xenosworks/xsdk), [vulkan4xenon](https://github.com/xenosworks/vulkan4xenon) and [SDL-xenon](https://github.com/xenosworks/SDL-xenon), and to [Free60/libxenon](https://github.com/Free60Project/libxenon). Their work makes this possible. Revive360 complements these projects; it does not replace or claim their work.

## People, risk and contact

Only founder Pedro is an owner today. Members start with minimum access and grow through contribution history; no automatic owner promotion. DCO sign-off is mandatory. Rule changes are decided by the founder with 14 days' public notice; urgent security restrictions are immediate. Projects may return to their authors; archive after 12 months without maintenance or for violations. The org currently receives/splits no donations.

**Homebrew risks Xbox Live account/console bans, data loss and console damage; use at your own risk.** No collection without opt-in; login/tokens stay on the console. Third-party terms risk belongs to the author; DRM/paywall bypass is forbidden.

Until December use private vulnerability reporting for security and org issues/Discussions for public contact. `CONTACT_DECEMBER_2026_TODO`: add the confirmed org email/domain later.

Xbox and Xbox 360 are trademarks of Microsoft. Revive360 is independent and is not affiliated with or endorsed by Microsoft, Google or the projects credited above.
