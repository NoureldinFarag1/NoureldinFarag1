# Noureldin Farag

**Backend / Full-stack Software Engineer** · Giza / Cairo, Egypt  
.NET (ASP.NET Core) & Laravel · Clean Architecture · systems that stay correct under real load

I build production backends for messy business domains: inventory & orders, ticketing & check-in, support workflows, multi-brand POS, RBAC, refunds, and audit trails.  
I care about **data integrity**, **optimistic concurrency**, **explicit domain rules**, and code that another engineer can trust in production.

[![Available for hire](https://img.shields.io/badge/Available%20for%20hire-2ea44f?style=for-the-badge)](mailto:noureldinfarag@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/noureldin-farag-042240245)
[![Email](https://img.shields.io/badge/Email-noureldinfarag%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noureldinfarag@gmail.com)

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)

---

## What I work on

| Area | Tools & ideas I use in practice |
| --- | --- |
| **.NET backends** | ASP.NET Core, EF Core, MediatR / CQRS, FluentValidation, JWT Identity, xUnit |
| **Laravel / PHP** | Laravel 12, Blade + Vite, Socialite, queues/mail, feature tests |
| **Architecture** | Clean Architecture, domain state machines, append-only ledgers & audit logs |
| **Hard problems** | Stock allocation, concurrent check-in, RBAC, multi-brand isolation, refunds |
| **Ops-minded** | Docker / Compose, Swagger, health checks, no secrets in git |

Open to **backend** and **full-stack** roles in **Cairo / Giza** (on-site, hybrid, or remote).

---

## Featured projects

### 1. [Fulfillment Inventory & Orders API](https://github.com/NoureldinFarag1/FullfilmentInventoryManagementPlatform)
**.NET 10 · Clean Architecture · CQRS · SQL Server**

Inventory and order backend with an append-only stock-movement ledger, order lifecycle (allocate / restore stock), role policies (`CanManageCatalog`, `CanAdjustStock`, …), optimistic concurrency, JWT auth, Swagger, and xUnit coverage across domain + application layers.

*Best fit for: .NET / backend roles that care about correctness under concurrency.*

### 2. [After Eight - Event Booking & Ticketing](https://github.com/NoureldinFarag1/after-eight-booking-website)
**Laravel 12 · Full-stack product · QR check-in**

Event ticketing with fee-inclusive ticket types, Admin / Operator / User journeys, QR validation, invitations, refunds, Google OAuth, email notifications, and feature tests (including concurrent scan / locking). Built with a teammate — real collaboration history, not a solo tutorial.

*Best fit for: Laravel / full-stack product roles.*

### 3. [Customer Support API](https://github.com/NoureldinFarag1/CustomerSupport)
**.NET · CQRS · Domain state machine · Docker Compose**

Support-desk API with an explicit request state machine, domain events, customer messages vs internal notes, append-only audit trail, `409` on claim races, JWT roles (Customer / Agent / Manager), integration tests, and SQL Server via Docker Compose.

*Best fit for: interviews, small enough to walk through end-to-end in 10 minutes.*

### Also (private)
**Local Hub POS** - Laravel multi-brand POS: brand-owner isolation, inventory variants, sales/refunds/COD, Spatie permissions, thermal printing. Happy to walk through architecture.

---

## How I usually ship

- Prefer **explicit domain rules** over “just update the row”
- Treat concurrency and audit as first-class, not afterthoughts
- Document setup, roles, and API surfaces so another engineer can run the project cold
- Keep secrets out of the repo (user-secrets / env)

---

## Contact

- Email: [noureldinfarag@gmail.com](mailto:noureldinfarag@gmail.com)
- LinkedIn: [linkedin.com/in/noureldin-farag-042240245](https://www.linkedin.com/in/noureldin-farag-042240245)
- GitHub: [github.com/NoureldinFarag1](https://github.com/NoureldinFarag1)

*Based in Giza / Cairo · open to backend & full-stack opportunities.*
