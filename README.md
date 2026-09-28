## Basit Munir

Senior full-stack engineer and team lead, 14+ years. I work on the seam between
systems that were never designed to talk to each other — data platforms, POS
and ERP integration, and the reconciliation problems that show up when two
sources disagree about the same fact.

Mostly **Laravel/PHP**, **Node.js/TypeScript** and **Python**, over
**PostgreSQL**, **MySQL**, **MongoDB** and **Redis**, on **AWS**.

**What I've been doing**

- Identity and property-data workflows for a US data platform: skip tracing,
  third-party data APIs, and a service layer with a synchronous lookup path
  and a queued batch path sharing one set of resolution rules.
- Real-time inventory, pricing and order sync between Shopify and a
  third-party POS across 230+ Canadian retail locations, with POS, kiosk and
  web sales reconciled into one dataset.
- Leading a distributed team: review standards, CI checks, mentoring.

**A note on what's public here**

Most of my work over the last several years has been under NDA and lives in
private client repositories, so it isn't on this profile and won't be. What I
publish is written from scratch on my own time. If you want to see how I
actually build, start with the pinned repo below — it's small, it runs with one
command, and the reasoning is written down in `NOTES.md` rather than implied.

📌 **[identity-resolver](https://github.com/bst-engr/identity-resolver)** —
identity resolution over messy multi-source records. Deterministic and fuzzy
matching with explainable confidence scoring, per-field provenance, and a batch
worker sharing the resolver with the live API. FastAPI · PostgreSQL ·
TypeScript · Docker.

📫 basitmunir.pk@gmail.com
