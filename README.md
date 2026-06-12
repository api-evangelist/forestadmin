# Forest Admin (forestadmin)

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
