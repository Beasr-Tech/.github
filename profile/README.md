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

## What Beasr is

Beasr is a platform for people moving home in the UK. It combines a membership service, an AI concierge, a curated marketplace, a partner ecosystem, and a location-based community into one product. The goal is to make the process of moving house simpler, cheaper, and less stressful by putting the tools, the deals, and the local knowledge in one place.

The platform is built and run by a small team in the United Kingdom. Everything is built from the ground up: no third-party frontend framework, no ORM, no off-the-shelf page builders. The architecture is constraint-driven. Quality is enforced structurally, not by discipline alone.

---

## Product

**Calm Move Membership.** A subscription service for UK home movers. Freemium tier with premium access to an AI concierge, curated marketplace, and savings tracking with a money-back guarantee. The membership covers the full journey from first viewing to settled.

**AI Concierge.** Five conversational agents with distinct expertise: property guidance, lifestyle and marketplace, community moderation, navigation, and general assistance. Each agent handles its own domain and hands off to the right specialist when a question crosses boundaries.

**Marketplace.** Aggregated products across furniture, utilities, insurance, and home essentials. Affiliate network integration with a direct deal pipeline. Members get access to curated discounts and tracked savings.

**Partner Ecosystem.** Estate agent plugins, influencer referral system, and vendor self-onboarding. Revenue share model. Automated compliance and payout workflows.

**Chinwag.** A location-based community where movers share local knowledge: schools, parking, broadband, noise, neighbours. AI-moderated. Feeds back into the recommendation engine so the platform gets smarter the more people use it.

---

## How we build

The codebase is a single monorepo. The frontend is vanilla JavaScript with a custom DOM abstraction and a CSS token system. The backend is Node.js and Express with PostgreSQL and Redis. The AI layer is built on Anthropic's Claude. The desktop client is Electron. Deployment runs on DigitalOcean with automated backups, health monitoring, and Discord notifications.

Every change goes through an automated validation pipeline before it can be pushed. The pipeline checks code formatting, lint rules, type safety, dead code, architectural compliance, and structural conventions. There is no bypass. A check either passes or it blocks. The team treats this as a feature, not overhead: catching violations at authoring time is cheaper than catching them in production.

The architecture is designed so that the right thing is the only available path. Limits are constants that validators read. Styles come from tokens that stylelint enforces. Classes extend bases that the pipeline checks. The system is shaped so that drift is structurally impossible rather than merely discouraged.

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-20_LTS-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-5-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-Billing-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-Desktop-47848F?style=flat-square&logo=electron&logoColor=white)

</div>

---

## Security posture

- HTTPS everywhere with TLS 1.3
- Rate limiting and session hardening on all endpoints
- GDPR, PECR, and Consumer Rights Act 2015 compliance
- Stripe-managed payment tokenisation (no card data touches our servers)
- Content Security Policy headers enforced at build time and runtime
- Continuous health monitoring with automated alerting

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
