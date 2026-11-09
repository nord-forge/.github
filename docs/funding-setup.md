# Set up funding for nord-forge

Status: [GitHub Sponsors for nord-forge](https://github.com/sponsors/nord-forge) is public and enabled in the shared funding file. Ko-fi is deferred; Buy Me a Coffee is not configured. Updated on 9 November 2026.

Use the public name **nord-forge** across the services you choose. Claim a matching handle where available, and record the actual public URL rather than assuming a handle is yours. One shared account per service can receive support for the organization's projects.

## Choose the services

| Service | Suggested role | Start here |
| --- | --- | --- |
| GitHub Sponsors | Sponsorship from people who discover the projects on GitHub. Organization enrollment can involve an invitation or waitlist and approval. | [GitHub Sponsors](https://github.com/sponsors) · [organization setup](https://docs.github.com/en/sponsors/receiving-sponsorships-through-github-sponsors/setting-up-github-sponsors-for-your-organization) |
| Buy Me a Coffee | A simple page for one-time support, with optional memberships. | [Buy Me a Coffee](https://www.buymeacoffee.com/) · [service guide](https://help.buymeacoffee.com/en/articles/10182730-what-is-buy-me-a-coffee-and-how-does-it-work) |
| Ko-fi | An alternative tip page connecting to PayPal or Stripe. | [Ko-fi](https://ko-fi.com/) · [payments guide](https://help.ko-fi.com/hc/en-us/articles/24482435253661-What-payment-methods-are-available-on-Ko-fi) |

A practical starting combination is GitHub Sponsors plus one tip service. The funding file supports all three if you prefer. Review each service's current fees and payout availability during registration: [GitHub fees](https://docs.github.com/en/sponsors/getting-started-with-github-sponsors/about-github-sponsors), [Buy Me a Coffee fees](https://help.buymeacoffee.com/en/articles/8105744-how-to-calculate-charges-on-your-payment), [Ko-fi payments and fees](https://help.ko-fi.com/hc/en-us/articles/24482435253661-What-payment-methods-are-available-on-Ko-fi). Payment-processing charges can apply separately.

## Account-owner steps

Complete registration, contact information, payout details, tax information, identity checks and service terms directly on the chosen service. Keep those details out of this public repository and chat.

For GitHub Sponsors, open Get sponsored and select **nord-forge**. Follow the organization invitation/waitlist flow shown for the account. Choose direct payouts or a fiscal host during enrollment, then complete the organization profile and required application steps. Receiving sponsorships depends on GitHub approving the account.

For Buy Me a Coffee or Ko-fi, create a creator page named **nord-forge**, claim an available handle and connect the required payout account. Finish any checks shown by the platform. Start with one-time support; memberships are optional.

## Ready-to-use profile text

Short bio:

> Small open-source tools for everyday software work.

Introduction:

> nord-forge builds and maintains practical open-source tools, including Fonn. Your support helps fund maintenance, bug fixes, documentation and time to improve these projects. Whether you contribute code, report an issue or leave a tip, thank you for helping keep the work moving.

Thank-you message:

> Thanks for supporting nord-forge! Your contribution helps me maintain and improve these open-source projects.

An optional simple tier structure: a $5 one-time tip, a $5 monthly Supporter tier and a $15 monthly Sustainer tier. These are draft suggestions; choose the amounts and currency supported by the service. Keep the descriptions focused on supporting maintenance. Add specific rewards only when you want to commit to providing them.

## Activate the shared Sponsor button

1. Confirm that each chosen public page belongs to you and is ready to receive support. A reserved handle or an unfinished application is not enough.
2. In [`.github/FUNDING.yml`](../.github/FUNDING.yml), uncomment only the ready providers. Replace each external-provider placeholder with the actual claimed username. For GitHub Sponsors, enable `github: [nord-forge]` after its listing is live.
3. Commit the funding file through a pull request and merge it into this repository's default branch. Keep this repository named **.github** and public.
4. Check the Sponsor button on Fonn and other nord-forge repositories. An existing repository-specific funding file overrides the shared default; review any override before changing it. Do not add duplicate funding files to every project.

GitHub supports these provider keys directly: `github`, `buy_me_a_coffee` and `ko_fi`. No custom redirect or widget is required. Each service independently receives its payments; the shared file only displays the links.
