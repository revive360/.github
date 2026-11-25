# Owner's publication checklist

Prepared locally; nothing here creates an organization or publishes a repository.

1. Create the GitHub organization `revive360` with display name **Revive360**. Use no Xbox trademark in organization or repository names.
2. Create public, empty `.github` and `devkit` repositories, then push each local `main` branch. Public `.github` is necessary for organization default community files and `profile/README.md`.
3. Enable Issues in `.github` for proposals and membership. Verify bug, app proposal and join templates appear in a project with no overrides. GitHub normally creates its default `bug`, `enhancement`, `documentation` labels; create those if missing. Do not add other projects to the profile without their owners agreeing.
4. Enable private vulnerability reporting on both repositories and confirm the reporting route in SECURITY.md works. Configure a private conduct-reporting route with Pedro before announcing the community; the current fallback is the contact route on his public GitHub profile. Do not invent an email address.
5. Require 2FA for members, give the base member role read access, and grant write access through project teams. Require pull requests for `main`; avoid requiring another person's approval while there is only one maintainer. Add reviewers as maintainers join.
6. Review owner contact routes and all three languages. Set project descriptions and topics; the devkit is development infrastructure, while Tube360 is the only app currently listed. Tube360 stays in its existing repository unless its owner later chooses a transfer.
7. Build artifacts remain unreleased until tested on a real console. Preserve the test record and third-party notices with every release.

After creating the remote repositories, the owner can run separately in each local repository:

```sh
git remote add origin https://github.com/revive360/.github.git
git push -u origin main
```

Use `https://github.com/revive360/devkit.git` in the devkit repository. These commands were not run during preparation.
