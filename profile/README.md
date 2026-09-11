<div align="center">

<img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/banner.png" alt="InBrief — incident communication, without lock-in" width="100%">

<br><br>

[![Website](https://img.shields.io/badge/Website-inbrief.sh-1b87c5?style=for-the-badge&logoColor=white)](https://inbrief.sh)
[![Docs](https://img.shields.io/badge/Docs-Read_the_guides-22b573?style=for-the-badge&logoColor=white)](https://inbrief.sh/docs)
[![REST API](https://img.shields.io/badge/REST_API-OpenAPI-1b7a4f?style=for-the-badge&logo=openapiinitiative&logoColor=white)](https://inbrief.sh/docs/developers/openapi.json)
[![Live demo](https://img.shields.io/badge/Live_demo-demo.inbrief.sh-0d1117?style=for-the-badge&logoColor=white)](https://demo.inbrief.sh)

**Hosted status pages that keep your customers informed — while you keep the account, the domain and the history.**

Monitors that notice. Incidents you publish. Subscribers you notify.<br>
An API to drive all three from your own systems.

<br>

<a href="https://demo.inbrief.sh"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/status-page.png" alt="An InBrief status page: an ongoing incident above fourteen days of service health" width="900"></a>

<sub>Our demonstration page — kept in an incident on purpose, so you can see how one reads · <a href="https://demo.inbrief.sh">demo.inbrief.sh</a></sub>

</div>

<br>

---

## Why teams move to InBrief

### 💸 &nbsp;Pay for what you switch on — no tiers

Tiered pricing makes you buy a bundle to reach one thing inside it. The custom
domain sits in the tier above yours, so you move up a plan and pay for four
capabilities you will never open in order to get the one you came for.

Here every capability carries its own price. You assemble the set you want, the
builder shows the running total as you add and remove, and that total is what
checkout charges. Named plans still exist for people who would rather not
assemble anything — they are a preselected set of the same capabilities at a
discount, never a different product.

**Free · $0** &nbsp;·&nbsp; **Start · $10/mo** &nbsp;·&nbsp; **Pro · $20/mo** &nbsp;·&nbsp; [**or build your own →**](https://inbrief.sh/build)

### 🌍 &nbsp;Write the incident once, publish it in every language

Choose the languages your page publishes in and InBrief prepares the
translations automatically — you review them before anything goes out. Visitors
pick their own with a toggle, and the choice sticks for the rest of the incident.

Arabic is a first-class language here, not a translation target bolted on: the
page renders **right-to-left with Arabic-Indic digits**, because a right-to-left
page that lays out left-to-right reads as broken to the people it is for.

<div align="center">
<a href="https://demo.inbrief.sh/?lang=ar"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/status-page-arabic.png" alt="The same status page in Arabic, laid out right to left with Arabic-Indic numerals" width="860"></a>
<br><sub>The same page, same incident, <code>?lang=ar</code> — layout mirrored, digits localised</sub>
</div>

### 🛟 &nbsp;A status page that survives the outage it is reporting

A status page served from the infrastructure it reports on is the one page
guaranteed to be down exactly when it matters. Outage continuity puts the
customer-facing page somewhere else entirely — so when your own systems are
unreachable, visitors still get a page, carrying the message you want them to
read instead of a connection error.

### 🏛 &nbsp;Run it where your compliance team needs it

| | Deployment | Status |
| :-- | :-- | :-- |
| **01** | **Cloud** — nothing to install; we run the product, delivery and upgrades | **Available, self-serve** |
| **02** | **On-premises** — the whole product inside your own perimeter | *Coming soon* |
| **03** | **Hybrid** — manage incidents in InBrief Cloud, keep operational event history where you choose | *Coming soon* |

Private deployment options are published now and open when their support
boundaries are ready. [See the deployment models →](https://inbrief.sh/#ib-deployment)

<br>

---

## The platform

| | |
| :-- | :-- |
| 📊 **Status pages** | Your brand, your logo, your accent, your history window. Run more than one page from a single account. |
| 🌐 **Custom domains** | Point a DNS record at InBrief; the certificate is issued and renewed for you. |
| 📡 **Monitoring** | Website, port, DNS and cron-job checks, grouped into the services your customers recognise. |
| 🗄 **Database health** | Private connection and pool diagnostics — visible to you, never on the public page. |
| 🚨 **Incidents** | Publish, update and resolve. Schedule maintenance ahead of time; write the postmortem afterwards. |
| 📬 **Subscribers** | Email, Discord, Microsoft Teams, Telegram and browser push — one update reaches every channel. |
| 💬 **Team alerts** | Monitor and certificate alerts into the Slack channel your responders actually watch. |
| 📈 **Analytics** | Page loads, visitor-days and subscription conversion, per public page. |
| 👥 **Roles & audit** | Owner, admin, member and viewer permissions, with an exportable log of who changed what. |

## Built to be driven by code

| | |
| :-- | :-- |
| [**Public Status API**](https://inbrief.sh/docs/developers/public-status-api) | Current service health and the incident ledger as cached JSON |
| [**Incident API**](https://inbrief.sh/docs/developers/incident-api) | Open, update and resolve incidents from your own systems |
| [**Event API**](https://inbrief.sh/docs/developers/event-api) | Batch application outcomes into the private operational view |
| [**Webhooks**](https://inbrief.sh/docs/developers/webhooks) | Signed deliveries, documented event types and retry behaviour |
| [**Badges & feeds**](https://inbrief.sh/docs/developers/badges-and-feeds) | SVG badges, JSON status, RSS and Atom — public, no key required |
| [**MCP**](https://inbrief.sh/docs/developers/mcp) | Model Context Protocol connection, in preview |

The full REST contract is published as [OpenAPI](https://inbrief.sh/docs/developers/openapi.json),
and the site ships an [llms.txt](https://inbrief.sh/llms.txt) so coding agents can read it directly.

<div align="center">
<br>

**Not a picture — this badge is live, served by InBrief as you read it:**

<a href="https://demo.inbrief.sh"><img src="https://demo.inbrief.sh/badge.svg" alt="Live status of the InBrief demonstration page"></a>

<sub>It reports our <a href="https://demo.inbrief.sh">demonstration page</a>, which is held in an incident on purpose — so it says <code>degraded</code> by design.<br>Drop <code>/badge.svg</code> from any InBrief page into a README or a dashboard.</sub>

</div>

<br>

---

## In production

[**status.sakneen.com**](https://status.sakneen.com) is a customer page carrying
real incidents — not a mock-up.

Built with TypeScript, Next.js, NestJS and MongoDB.

## Repositories

Most of our work is private; this page is the front door. The public
repositories here are the ones useful on their own.

<br>

<div align="center">
<sub>

[inbrief.sh](https://inbrief.sh) · [Docs](https://inbrief.sh/docs) · [LinkedIn](https://www.linkedin.com/company/inbriefsh) · [Facebook](https://www.facebook.com/inbriefsh) · [support@inbrief.sh](mailto:support@inbrief.sh)

</sub>
</div>
