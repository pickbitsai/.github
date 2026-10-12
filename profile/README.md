# PickBits.AI

**Personalized software you own.**

PickBits builds software to order for one business, for a one-time cost. The business owns what we build, and it changes when the owner asks. It's for people who are tired of paying every month for features they never use, redesigns they didn't ask for, and requests that never ship. Work directly with [Mark Pickering](https://pickbits.ai/about), based in Phoenix, Arizona, and working remotely anywhere.

---

## Services

**[pickbits.ai](https://pickbits.ai)** · [Book a free 30-minute call](https://pickbits.ai/book/?type=consulting)

**The PickBits Challenge:** add up what your business pays in a year for the software you'd replace, and halve it. The one-time build should come in under that number, and then the software is yours. Builds run from $500 to $5,000, billed mostly on time and materials. If part of it runs in the cloud, you pay what the cloud costs. Software that runs offline on a PC or phone has no ongoing cost. [More on the Challenge →](https://pickbits.ai/#challenge)

### Personalized software and AI tools for small businesses

| | |
|---|---|
| **AI phone receptionist** | Answers your business line, handles common questions, takes customer details and books appointments using your services, prices and availability. |
| **Mobile invoicing app** | Enter a job once on site to get a service record and a separate customer invoice. Works on your phone, even without internet. |
| **Online booking system** | Customers pick a time and confirm. The available times account for your calendar and planned work. |
| **Social media management** | You supply the ideas and material. Mark prepares the posts, articles and short videos, gets your approval and publishes on an agreed schedule. |
| **AI search optimization** | Checks whether AI assistants can find and accurately describe your business, then fixes the gaps in your pages and business details. |
| **Task and calendar management** | Keeps your tasks and calendar in step, suggests changes when plans shift, and updates the schedule after you approve. |
| **Training and onboarding materials** | Guides, lessons and quizzes built from your processes, for new hires, refreshers or a course of your own. |
| **Custom websites and apps** | Sites that help customers request a quote, book or order, plus customer portals, staff dashboards and back-office tools. |

Your problem doesn't have to fit a row. [Tell Mark where the work gets stuck →](https://pickbits.ai)

### Own it: open-source tools for the apps you rent

These are the free starting points we build from. Run one yourself under Apache-2.0, or [have PickBits set it up, make it yours and run it for you](https://pickbits.ai/own-it/).

| Instead of | Use |
|---|---|
| Dropbox | [pickbits-file-share](https://github.com/pickbitsai/pickbits-file-share): team files in your own AWS account, with expiring links, two-factor sign-in and e-signature |
| Mailchimp | [pickbits-newsletter](https://github.com/pickbitsai/pickbits-newsletter): your list in files you own, sent from your own mailbox, with no tracking |
| Shopify or Wix | [pickbits-catalog-site](https://github.com/pickbitsai/pickbits-catalog-site): a bilingual catalog with option pricing and reserve-for-pickup |
| Calendly | [pickbits-booking](https://github.com/pickbitsai/pickbits-booking): your hours and buffers, with busy times from your calendar and invites from your own mailbox |
| Jobber | [pickbits-field-invoices](https://github.com/pickbitsai/pickbits-field-invoices): offline-first customers, visits and numbered invoices on your phone |
| Re-keying paper | [pickbits-paper-to-records](https://github.com/pickbitsai/pickbits-paper-to-records): photos of tickets, invoices or receipts turned into validated CSV by your own AI |

### Help for people who build with AI

- **[DIY Rescue](https://pickbits.ai/work-with-mark)**: for when you built it yourself with AI or a free tool and got stuck. You get a written review, a call to walk through it, and 90 days of questions answered.
- **[Hands-on fixes and builds](https://pickbits.ai/work-with-mark)**: Mark fixes an existing project or builds a new one, with an estimate before work starts.
- **[Agentic workflow consulting](https://pickbits.ai/ai-consulting-arizona/)**: Mark audits, builds and embeds agentic workflows in your team's real tools and data, then trains the team to run them.
- **Training and 1:1 coaching**: live workshops on agentic development, MCP, security, evals and cost control, or focused sessions on your own codebase.

See [the case studies](https://pickbits.ai/case-studies/) for real builds in production.

---

## Avalanche: open-source ops for a company run by one person and AI agents

PickBits runs on Avalanche. These four modules are open source. Each one is a ServiceNow-shaped module sized for a small company. Every module has:

- a CLI and a local browser desk that call the same library
- an append-only event journal that records which person or agent made each change
- zero runtime dependencies, built-in SQLite, Node 22.13+, Apache-2.0
- no telemetry and no hosted service
- a five-minute demo: `npm ci && npm run demo`

| Module | The question it answers |
|---|---|
| **[avalanche-service-catalog](https://github.com/pickbitsai/avalanche-service-catalog)** | *How do my team and my AI agents request a ticket, a change or a new initiative in one place?* Dynamic forms validate each request before it's recorded, a producer fulfils it by running a command, and the ledger keeps the actor, outcome and reference. |
| **[avalanche-estate-map](https://github.com/pickbitsai/avalanche-estate-map)** | *What's actually running, who owns it, and where has it drifted?* Typed configuration items and relationships, checked against live listeners and scheduled tasks. Sync defaults to a dry run. |
| **[avalanche-assets-and-spend](https://github.com/pickbitsai/avalanche-assets-and-spend)** | *What do we own, what does it cost each month, and what does each service really cost?* An asset register, a spend ledger, AI-usage import and an estimated total cost per service. |
| **[avalanche-roadmap](https://github.com/pickbitsai/avalanche-roadmap)** | *How do I keep a real roadmap without an enterprise portfolio tool?* Demand intake with value, effort and risk scoring, recorded decisions, initiatives, goals and a five-quarter roadmap. |

---

## More from PickBits

- **[CyberHawk](https://pickbits.ai/cyberhawk/)**: CVE intelligence for the AI and vibe-coder stack, with a weekly digest ([cyberhawk-feed](https://github.com/pickbitsai/cyberhawk-feed)).
- **[ACVE](https://agentcve.org/)**: a public registry of AI agent configurations known to be vulnerable or to have caused harm.
- **[pickbits-dependency-audit](https://github.com/pickbitsai/pickbits-dependency-audit)**: a local, report-only dependency vulnerability audit built on OSV.
- **[enView](https://github.com/pickbitsai/enView)**: a `.env` scanner and drift detector for many projects. It never exposes the secrets.
- **[company-os](https://github.com/pickbitsai/company-os)**: a local ops dashboard for running many projects with AI agents.
- **[session-index](https://github.com/pickbitsai/session-index)**: a local-first tracker for Codex and Claude Code sessions.
- **[work-forge](https://github.com/pickbitsai/work-forge)**: a qualifications repository and job feed for any coding agent.
- **[weaver](https://github.com/pickbitsai/weaver)** and **[backlot](https://github.com/pickbitsai/backlot)**: a long-form narrative pipeline, and the engine that turns its releases into episodic video.

[PickBits University](https://pickbits.academy/) has the courses, [PickBits Daily](https://pickbits.ai/pickbits-daily/) is the daily AI brief, and [PickBits Studio](https://pickbits.studio/) makes the games.

---

[Substack](https://pickbitsai.substack.com) · [YouTube](https://www.youtube.com/@PickBitsAI) · [X](https://x.com/pickbitsai) · [LinkedIn](https://www.linkedin.com/in/mrpickering) · [pickbits.ai](https://pickbits.ai)
