<div align="center">

<img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/banner.png?v=2" alt="InBrief — incident communication, without lock-in" width="100%">

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
| 📡 **Monitoring** | HTTP, TCP, DNS and ping checks, plus heartbeats for cron jobs and pipelines, grouped into the services your customers recognise. |
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
| [**MCP**](https://inbrief.sh/docs/developers/mcp) | Connect an assistant to your account by URL |

The full REST contract is published as [OpenAPI](https://inbrief.sh/docs/developers/openapi.json),
and the site ships an [llms.txt](https://inbrief.sh/llms.txt) so coding agents can read it directly.

## Badges, widgets & feeds

Public, unauthenticated, cached for five minutes — no API key anywhere, because
it is all public information by design. Badges and the widget are drawn by
InBrief in your colours and served from our side, so the README, the docs site
and the app footer all say what the status page says.

**Named badges** come in three variants — signal, compact and uptime — in light,
dark or your own palette, and in all four languages. These follow your GitHub
theme:

<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/signal-operational-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/signal-operational-light.svg" width="301" height="72" alt="Signal badge: Northwind, everything is working, 99.98% uptime, live status"></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-operational-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-operational-light.svg" width="191" height="40" alt="Compact badge: everything is working"></picture>
&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/uptime-operational-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/uptime-operational-light.svg" width="371" height="40" alt="Uptime badge: everything is working, 99.98% uptime, live status"></picture>

<br>

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-degraded-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-degraded-light.svg" width="260" height="40" alt="Compact badge: some services are running slowly"></picture>
&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-outage-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-outage-light.svg" width="242" height="40" alt="Compact badge: some services are unavailable"></picture>
&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-maintenance-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/compact-maintenance-light.svg" width="274" height="40" alt="Compact badge: scheduled maintenance in progress"></picture>

<br>

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/signal-operational-ar-dark.svg"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/badges/signal-operational-ar-light.svg" width="413" height="72" alt="The signal badge in Arabic, laid out right to left"></picture>

<sub>Every state has its own colour and glyph, and the wording is the status page's own.</sub>

</div>

**The website widget.** A card that floats in a corner of your own site and
expands into the latest update, or a bar across the bottom of every page. Nine
placements, styled from the console, with nothing to redeploy at your end. Show
it only when something is wrong, or always; a visitor can dismiss it for that
page view.

**Feeds and calendars.** `/feed.xml` is the incident ledger as RSS 2.0 — filter
it by service and by language (`?service=api&lang=ar`) — alongside Atom and a
maintenance calendar, all generated with copy buttons in **Branding → Embed**.

[Badges and widgets in the docs →](https://inbrief.sh/docs/product/badges-and-widgets)

<br>

---

## Repositories

Most of our work is private; this page is the front door. The public
repositories here are the ones useful on their own.

<br>

<div align="center">
<sub>

[inbrief.sh](https://inbrief.sh) · [Docs](https://inbrief.sh/docs) · [LinkedIn](https://www.linkedin.com/company/inbriefsh) · [Facebook](https://www.facebook.com/inbriefsh) · [support@inbrief.sh](mailto:support@inbrief.sh)

</sub>
</div>
