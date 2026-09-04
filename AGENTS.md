# As Told Website — Agent Instructions

## Scope

This repository contains only the static support website for `getastold.com`.
The founder approved creating `ashrayastudio/getastold` on GitHub Pages and
redirecting `getastold.app` to the primary domain on September 3, 2026.
The separate iOS repositories and their active owners are outside this scope.

Read `/Users/hermes/AGENTS.md`, this file, and the current As Told website
section in `/Users/hermes/Developer/personal-digital-products-ops/docs/ACTIVE-HANDOFF.md`
before mutation or recovery. The central handoff records current exact
execution authority, tests, external before/after state and remaining work.
Do not recover from chat memory or historical plans.

## Public identity and content

- The public product name is `As Told`. No public Ashraya, Ashraya Studio,
  Ashraya-branded domain, or legacy contact may appear in website text,
  metadata, markup, attributes, resources or links.
- GitHub owner/repository identity is technical infrastructure only. Do not
  turn it into a public operator, brand, seller or copyright claim.
- The only approved support mailbox is `appportfolio.contact@gmail.com`, with
  exact subject `As Told support`; no alias, other recipient, body, cc/bcc or
  automatic attachment. Show a copyable address and sensitive-content warning.
- The founder confirmed send/receive, monitoring the inbox and deleting
  resolved conversations within 90 days unless legally required longer.
  This is founder-reported process evidence, not an agent-observed mail test.
- Apply D-016, D-027 and the D-039/D-040 controller rule. Only `privacy.html`
  may contain the exact approved sentence `The data controller is Kalpesh Patel.`
  once, in a paragraph. No name in other copy, attributes or metadata.
- This package covers website hosting and voluntary support email only.
  Do not imply it is the full app policy or add unverified app features,
  family/collaboration behavior, pricing, release availability, App Store
  links, legal-compliance promises, analytics, forms, ads or third-party assets.
- Preserve the dependency-free static architecture, existing route map and
  responsive keyboard-accessible controls. Only `docs/` is published; its exact
  file allowlist is `index.html`, `privacy.html`, `CNAME`, `.nojekyll`. Never
  publish repository instructions, validators or README. No other-host migration.

## Validation

Before any candidate freeze run `python3 -B validate_site.py`,
`python3 -B validate_site.py --self-test`, `git diff --check`, scoped secret
checks and exact diff review. Verify new HTML routes are registered and every
link points only to the approved contact, local route or provider privacy notice.
Use OS Chrome for rendered checks. Confirm strict HTTPS, matching published
body hashes, exact Pages commit and .app path/query redirects before claiming
live completion. Source, Git publication, DNS and HTTPS are separate gates.

## Git and external operations

Codex uses the `gh` CLI and HTTPS Git with the
macOS-keyring-backed credential helper for `https://github.com/ashrayastudio/getastold.git`, expected account
`ashrayastudio`. Revalidate root/origin/ref/index/worktree/account and exact
remote parent for each operation. Never retrieve or print a token or raw
author email. Hermes is a bounded backup only under the portfolio runbook.
A sandbox denial requires narrow escalation, not an operator/credential change.

Each external mutation requires current PASS gates and an exact founder-backed
envelope. No force, reset, clean, stash, amend, unrelated branch/repo/settings,
account/Apple/DSA, app release, or automatic rollback. Preserve unrelated work.
Never store credentials, private account/domain contact details or mail contents.

Domain setup is limited to `getastold.com` and `getastold.app`; verify control
in Porkbun and freeze exact records/forwarding before changes. Preserve every
MX/TXT/verification record and unrelated host. Do not enable APIs, weaken
security, change nameservers, buy services or add wildcard DNS by assumption.
Before-state, action, after-state and recovery notes belong in the private
central handoff, never account-sensitive values in this public repository.
