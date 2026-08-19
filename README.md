# Braid Social

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Braid Social, Inc. is an a16z / Initialized Capital portfolio company (seed $6.8M, August 2023) founded by Matthew Cahill and Chris Piro. It launched as a creator-economy direct-to-fan platform on `braid.ai` / `braid.social`, and now ships **Braid Teams** at [trybraid.io](https://www.trybraid.io/) (mirrored at braidsocial.com) — an AI-powered employee-engagement copilot that runs inside Slack: icebreakers, games, polls, events, reminders, leaderboards and engagement reporting.

**There is no public Braid API.** No developer portal, API reference, OpenAPI/AsyncAPI/GraphQL spec, SDK, CLI, MCP server, agent card or GitHub organization was found on any Braid host (probed 2026-08-13). The only machine surface is the private application backend at `core.trybraid.io`, which answers `{"status": "ok"}` at its root and returns HTTP 404 for every spec, docs and `/.well-known/` path. `app.trybraid.io` is a single-page app whose catch-all returns HTTP 200 with the same HTML shell for every path — those 200s are not documents.

The original domains are gone: `braid.ai` redirects to an atom.com domain-for-sale listing and `braid.social` has no DNS. Braid Teams itself is paused — the homepage reads "Currently not accepting new users" and the Slack install endpoint returns HTTP 500. See `lifecycle/braid-social-lifecycle.yml` for the full evidence table.

Backed by: a16z, Initialized Capital
