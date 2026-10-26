# Forest Admin (forestadmin)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Forest Admin is an ops orchestration platform and internal tool builder that enables operations and compliance teams to manage data, workflows, and business processes through a customizable admin panel. It uses an agent-based architecture where developers deploy a REST API agent (Admin Backend) on their own infrastructure, keeping data entirely within client-controlled servers. The platform supports Node.js, Ruby on Rails, Python (Django/Flask), and PHP (Laravel/Symfony) agents with role-based access control, JWT authentication, AI-assisted workflows, and SOC 2 compliance for regulated industries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/forestadmin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/forestadmin/refs/heads/main/apis.yml)

**Naftiko:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=forestadmin-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=forestadmin-api-evangelist&utm_content=repo)

## Tags

- admin panel
- internal tools
- RBAC
- workflow automation
- CRUD
- operations
- fintech
- compliance
- low-code
- AI agents

## APIs

### Forest Admin REST API (Admin Backend)

The Forest Admin Admin Backend is a REST API deployed on the customer's own infrastructure. It translates UI calls from the Forest Admin browser interface into database queries covering CRUD operations, search and filters, pagination, sorting, smart actions, and chart rendering. Authentication uses dual JWT tokens (FOREST_ENV_SECRET and FOREST_AUTH_SECRET).

- **Documentation:** [https://docs.forestadmin.com/documentation](https://docs.forestadmin.com/documentation)
- **Node.js Agent Reference:** [https://forestadmin.github.io/agent-nodejs/](https://forestadmin.github.io/agent-nodejs/)

**Supported agents:**
- Node.js (@forestadmin/agent v1)
- Ruby on Rails (forest_liana)
- Python Django (forestadmin-agent-django)
- Python Flask (forestadmin-agent-flask)
- PHP Laravel (forestadmin/laravel-forestadmin)
- PHP Symfony (forestadmin/symfony-forestadmin)

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/forestadmin-plans-pricing.yml](plans/forestadmin-plans-pricing.yml) |
| Rate Limits | [rate-limits/forestadmin-rate-limits.yml](rate-limits/forestadmin-rate-limits.yml) |
| FinOps | [finops/forestadmin-finops.yml](finops/forestadmin-finops.yml) |

**Pricing summary:**
- **Free/Community:** Up to 10 users, core CRUD features at no cost
- **Scale:** $60/user/month ($48/user/month annual) for growing ops teams
- **Control:** Custom pricing, minimum 50 users, for enterprises and regulated sectors

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.forestadmin.com](https://www.forestadmin.com) |
| Documentation | [https://docs.forestadmin.com/documentation](https://docs.forestadmin.com/documentation) |
| GitHub Organization | [https://github.com/ForestAdmin](https://github.com/ForestAdmin) |
| LinkedIn | [https://www.linkedin.com/company/forestadmin](https://www.linkedin.com/company/forestadmin) |
| Blog | [https://www.forestadmin.com/blog](https://www.forestadmin.com/blog) |
| Pricing | [https://www.forestadmin.com/pricing](https://www.forestadmin.com/pricing) |
| Status Page | [https://status.forestadmin.com](https://status.forestadmin.com) |
| Community | [https://community.forestadmin.com](https://community.forestadmin.com) |

## Maintainers

- **Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
