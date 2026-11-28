# Security policy

This policy applies to every repository under
[`siafuDB`](https://github.com/siafuDB) (the SiafuDB graph database), unless a repository ships its own
`SECURITY.md` with different terms. It follows the canonical Nyuchi
Africa policy at
[`nyuchi/.github`](https://github.com/nyuchi/.github/blob/main/SECURITY.md).

## Reporting a vulnerability

**Do not** open a public issue, pull request or discussion for a
suspected vulnerability. Public disclosure before a fix is available
puts users at risk.

Use either private channel.

1. **GitHub private vulnerability reporting.** On the affected
   repository, open the **Security** tab and choose **Report a
   vulnerability**. Only that repository's maintainers see the report.
   It is available on public repositories.
2. **Email.** Send a report to **<security@nyuchi.com>**. Use email for a
   private repository, or when you are not sure which repository is
   affected. Say in your first message if you want to encrypt the report
   and we will arrange a secure channel.

## What to include

- A descriptive title.
- The repository, package, version and commit SHA affected, and the URL
  if it is a live deployment.
- What the vulnerability is and its impact.
- Steps to reproduce, ideally a minimal proof of concept.
- Whether you want to be credited in the advisory.

Never include real personal data, credentials or tokens in a report. If
you came across some, tell us what kind and where, and do not copy it.

## Our commitments

When you report in good faith we will:

- acknowledge receipt within **3 business days**;
- give an initial assessment within **10 business days**;
- keep you informed about remediation progress;
- coordinate disclosure with you, and credit you in the advisory unless
  you ask us not to.

Our default target is a fix and a GitHub Security Advisory within **90
days** of confirming a vulnerability, sooner for critical issues.

## Scope

In scope:

- Every repository under [`siafuDB`](https://github.com/siafuDB), unless it is
  archived or marked experimental in its README.
- Packages, container images and releases those repositories publish.
- Production services for SiafuDB, such as `siafudb.org` and its subdomains.

Out of scope:

- Vulnerabilities in third-party dependencies. Report them upstream, and
  tell us if one has a concrete impact on one of our projects.
- Issues on github.com or hosting providers. Report them to the vendor.
- Social engineering, physical attacks, and denial of service by resource
  exhaustion alone.
- Reports from automated scanners with no demonstrated impact.

## Safe harbor

We will not start or support legal action over good-faith research
against in-scope assets, provided you avoid privacy violations, data
destruction and service disruption, only touch accounts you own or have
permission to use, take no more data than needed to show the issue and
delete it once we acknowledge the report, and report privately and give
us a reasonable window to fix before any public disclosure. This policy
does not authorize activity that would violate applicable law.
