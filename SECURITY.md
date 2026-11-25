# Security and provenance reports

For a vulnerability in an app, use that project's Security tab and **Report a vulnerability** if available. For an organization-wide issue, use this repository's private vulnerability reporting. Describe affected revisions, impact and a minimal reproduction without credentials, keys, personal data or suspected leaked material. Reports in Portuguese, Spanish or English are welcome.

If private reporting is unavailable, use [org issues](https://github.com/revive360/.github/issues) only to request a private channel, with no sensitive details. Never post exploits or secrets publicly. Security reports at **every level** receive an initial response within **48 hours**; this is not a fix deadline. Severe issues trigger immediate revocation and suspension of unsafe downloads. No bounty is offered. See [review scope and lifecycle](REVIEW.md).

We review the report, agree on remediation and coordinate public disclosure with the affected owner. Each project states its supported versions; until it does, report against its latest source and identify the exact revision. Provenance concerns block redistribution of the affected material pending review.

XBDM is an unauthenticated development interface. Keep it on a trusted local network. The devkit is a client; it ships no console monitor, unlock payload, keys or Microsoft SDK.

## Account compromise

Suspend releases and revoke affected badges immediately. Remove compromised accounts' access and automation tokens; revoke exposed provider credentials and rotate signing/deployment credentials. Preserve private evidence and inspect organization audit log, memberships, GitHub Apps, deploy keys, workflows, tags and release assets since the last trusted state. Recover owner access through GitHub recovery; rebuild on a fresh hosted runner from known-good source and pinned inputs, verify hashes/attestations and retest the exact binary on a real console. Publish a reviewed, safe incident notice before restoring trust and minimal access with 2FA. Keep owner recovery codes offline; do not promote an untrusted person to fill an owner slot.

2FA, reviewed PRs, no force pushes, DCO, secret scanning/push protection, dependency alerts and minimal Actions permissions are mandatory. Third-party Actions use full commit SHAs. Public forks run without secrets on disposable hosted runners; **no self-hosted runners in public repositories**. [SETUP.md](SETUP.md) gives configuration steps.

No hidden collection: explicit opt-in is required and login/tokens remain on the console, outside logs and org services. Reviewed external coverage is only the recorded version/hash/date; new/replaced binaries are not covered. Community listings are unverified but receive the same security response priority.

`CONTACT_DECEMBER_2026_TODO`: replace temporary GitHub routes only after the owner confirms the org email/domain in December.
