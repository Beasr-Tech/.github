<div align="center">

<img src="https://beasr.world/assets/images/png/logo-beasr_green_gold_neg_master.webp" alt="Beasr" width="480" />

<br /><br />

**Full-stack platform for the UK home-moving market.**<br />
AI-assisted marketplace, membership system, partner ecosystem, and community.

<br />

[![Site](https://img.shields.io/website?url=https%3A%2F%2Fbeasr.world&style=flat-square&label=beasr.world)](https://beasr.world)
[![SSL](https://img.shields.io/badge/SSL-A+-4ade80?style=flat-square&logo=letsencrypt&logoColor=white)](https://www.ssllabs.com/ssltest/analyze.html?d=beasr.world)
[![Security Headers](https://img.shields.io/badge/Security_Headers-scan-4ade80?style=flat-square&logo=shield&logoColor=white)](https://securityheaders.com/?q=beasr.world)
[![Hardenize](https://img.shields.io/badge/Hardenize-report-4ade80?style=flat-square&logo=shield&logoColor=white)](https://www.hardenize.com/report/beasr.world)
[![PageSpeed](https://img.shields.io/badge/PageSpeed-test-4285f4?style=flat-square&logo=pagespeedinsights&logoColor=white)](https://pagespeed.web.dev/analysis?url=https%3A%2F%2Fbeasr.world)

</div>

---

## Architecture

Greenfield monorepo. No frameworks on the frontend. No ORMs on the backend. Everything is built from base classes and composed upward.

| Layer | Stack |
|:------|:------|
| **Frontend** | Vanilla JavaScript, custom DOM abstraction, CSS design system with token architecture |
| **Backend** | Node.js, Express 5, PostgreSQL, Redis, session management, rate limiting |
| **AI** | Multi-agent system with intent detection, prompt construction, and conversation management |
| **Billing** | Stripe integration for subscription lifecycle, trials, and partner payouts |
| **Build** | Vite 7 with custom plugin pipeline, asset processing, code analysis |
| **Desktop** | Electron shell wrapping the web frontend |
| **Ops** | Health monitoring, log aggregation, deployment automation, database migrations |

<br />

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-22+-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-5-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-Billing-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-Desktop-47848F?style=flat-square&logo=electron&logoColor=white)

</div>

---

## Structure

The codebase is organised as a monorepo with isolated, single-responsibility modules.

```
beasr-code/
  beasr-web/           Web application (frontend + backend)
  beasr-dashboard/     Internal operations dashboard
  beasr-shared/        Cross-module constants, utilities, logging
  beasr-vite-plugins/  Custom build pipeline plugins
  beasr-deploy/        Deployment configuration and automation
  beasr-server/        Server infrastructure
  beasr-health/        Uptime and health monitoring
  beasr-logs/          Centralised log management
  beasr-sync/          Data synchronisation
  beasr-scripts/       Tooling and maintenance scripts
  beasr-assets/        Static assets and media
```

Frontend code follows strict architectural rules: base class inheritance for all managers and API clients, a centralised DOM factory instead of raw DOM access, barrel exports for cross-module boundaries, and a CSS token system with no hardcoded values. Backend follows the same discipline: base classes for repositories, controllers, AI agents, and HTTP clients. Every class extends a base. Every module exposes through an index.

---

## Product Verticals

**Calm Move Membership.** Subscription service for UK home movers. Freemium tier with premium access to AI concierge, curated marketplace, and savings tracking with a money-back guarantee.

**Partner Ecosystem.** Estate agent plugins, influencer referral system, and vendor self-onboarding. Revenue share model over 18 months. Automated compliance, KYC, and payout workflows.

**Chinwag.** Location-based community where movers share local knowledge. AI moderation. Feeds back into the recommendation engine.

**Marketplace.** Aggregated products across furniture, utilities, insurance, and home essentials. Affiliate network integration with direct deal pipeline.

---

## Security Posture

- HTTPS everywhere with TLS 1.3
- Rate limiting and session hardening on all endpoints
- GDPR, PECR, and Consumer Rights Act 2015 compliance
- Stripe-managed payment tokenisation (no card data touches our servers)
- Content Security Policy headers enforced
- Automated security scanning in CI

Verify independently:

| Check | Link |
|:------|:-----|
| SSL/TLS grade | [SSL Labs](https://www.ssllabs.com/ssltest/analyze.html?d=beasr.world) |
| Security headers | [securityheaders.com](https://securityheaders.com/?q=beasr.world) |
| Full posture report | [Hardenize](https://www.hardenize.com/report/beasr.world) |
| Performance audit | [PageSpeed Insights](https://pagespeed.web.dev/analysis?url=https%3A%2F%2Fbeasr.world) |

---

## Team

<div align="center">

<table>
<tr>
<td align="center" width="340">

[![Varietyz](https://github-readme-stats.vercel.app/api?username=Varietyz&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=4ade80&icon_color=4ade80&text_color=c9d1d9&hide_title=true&hide_rank=true&card_width=300)](https://github.com/Varietyz)

**Jay** / [@Varietyz](https://github.com/Varietyz)<br />
System Architecture, AI Governance, R&D

</td>
<td align="center" width="340">

[![8hours-ltd](https://github-readme-stats.vercel.app/api?username=8hours-ltd&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=4ade80&icon_color=4ade80&text_color=c9d1d9&hide_title=true&hide_rank=true&card_width=300)](https://github.com/8hours-ltd)

**Aidan** / [@8hours-ltd](https://github.com/8hours-ltd)<br />
Infrastructure, Product Design, Growth

</td>
</tr>
</table>

</div>

---

<div align="center">

[![Facebook](https://img.shields.io/badge/Facebook-Beasr--World-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/people/Beasr-World/61586313443277/)
[![TikTok](https://img.shields.io/badge/TikTok-@beasrworld0-000000?style=flat-square&logo=tiktok&logoColor=white)](https://www.tiktok.com/@beasrworld0)
[![YouTube](https://img.shields.io/badge/YouTube-BeasrTech-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@BeasrTech)
[![Instagram](https://img.shields.io/badge/Instagram-b3as.rman-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/b3as.rman/)

<br />

<sub>Beasr Tech Ltd. United Kingdom.</sub>

</div>
