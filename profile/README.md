<div align="center">

<img src="https://inbrief.sh/logo.png" alt="" width="76" height="76">

# InBrief

### Incident communication, without lock-in.

Hosted status pages that keep your customers informed while you keep control of
the account, the domain and the history. Monitors that notice, incidents you
publish, subscribers you notify — and an API to drive all three from your own systems.

[**Website**](https://inbrief.sh) · [**Docs**](https://inbrief.sh/docs) · [**Live demo**](https://demo.inbrief.sh) · [**Developer quickstart**](https://inbrief.sh/docs/developers/quickstart) · [**Pricing**](https://inbrief.sh/#ib-pricing)

<a href="https://demo.inbrief.sh"><img src="https://raw.githubusercontent.com/InBrief-Inc/.github/main/profile/status-page.png" alt="An InBrief status page: an ongoing incident above fourteen days of service health" width="880"></a>

<sub>Our demonstration page, kept in an incident on purpose · <a href="https://demo.inbrief.sh">demo.inbrief.sh</a></sub>

</div>

---

## What we build

**Status pages** — Your brand, your domain, your history window. A separate
outage page for when your own site cannot answer, and an embeddable badge for
READMEs and dashboards.

**Monitoring** — Website, port, DNS and cron-job checks, grouped into the
services your customers recognise, with private database and connection-pool
diagnostics kept off the public page.

**Incidents** — Publish, update and resolve. Schedule maintenance ahead of time,
write the postmortem afterwards. Manual and monitor-detected incidents go
through the same flow.

**Subscribers** — Email, Discord, Microsoft Teams, Telegram and browser push.
Write the update once; every channel and every published language gets it.

**Your team** — Slack and WhatsApp alerts for responders, owner/admin/member/viewer
roles, and an exportable audit log of who changed what.

## Built to be driven by code

| | |
| --- | --- |
| [Public Status API](https://inbrief.sh/docs/developers/public-status-api) | Current health and the incident ledger as cached JSON |
| [Incident API](https://inbrief.sh/docs/developers/incident-api) | Open, update and resolve incidents from your own systems |
| [Event API](https://inbrief.sh/docs/developers/event-api) | Batch application outcomes into the private operational view |
| [Webhooks](https://inbrief.sh/docs/developers/webhooks) | Signed deliveries with documented retry behaviour |
| [Badges & feeds](https://inbrief.sh/docs/developers/badges-and-feeds) | SVG badges, JSON status, RSS and Atom — no key required |
| [MCP](https://inbrief.sh/docs/developers/mcp) | Model Context Protocol connection, in preview |

The full REST contract is published as [OpenAPI](https://inbrief.sh/docs/developers/openapi.json),
and the site ships an [llms.txt](https://inbrief.sh/llms.txt) for coding agents.

## A few things worth knowing

- **Four languages, properly.** English, Arabic, French and Spanish — including
  right-to-left layout, not a translated theme.
- **Pay for what you switch on.** Capabilities are priced individually rather
  than bundled into tiers. There is a free page.
- **Cloud today.** On-premises and hybrid deployments are on the roadmap and
  will open when their support boundaries are ready.
- **Running in production.** [status.sakneen.com](https://status.sakneen.com)
  is a customer page, not a mock-up.

Built with TypeScript, Next.js, NestJS and MongoDB.

## Repositories

Most of our work is private — this page is the front door. The public
repositories here are the ones that are useful on their own.

---

<div align="center">
<sub>

[inbrief.sh](https://inbrief.sh) · [LinkedIn](https://www.linkedin.com/company/inbriefsh) · [Facebook](https://www.facebook.com/inbriefsh) · [support@inbrief.sh](mailto:support@inbrief.sh)

</sub>
</div>
