<p align="center">
  <a href="https://ziad-said-portfolio.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-ziad--said-c2723f?style=flat-square&logo=vercel&logoColor=ebe5d3&labelColor=2a1d12" /></a>
  <a href="mailto:ziadsaidahmed2005@gmail.com"><img src="https://img.shields.io/badge/EMAIL-ziadsaidahmed2005-c2723f?style=flat-square&logo=gmail&logoColor=ebe5d3&labelColor=2a1d12" /></a>
  <a href="https://www.linkedin.com/in/ziadsaid/"><img src="https://img.shields.io/badge/LINKEDIN-ziadsaid-c2723f?style=flat-square&logo=linkedin&logoColor=ebe5d3&labelColor=2a1d12" /></a>
  <a href="https://wa.me/201010695751"><img src="https://img.shields.io/badge/WHATSAPP-chat-1a7f37?style=flat-square&logo=whatsapp&logoColor=ebe5d3&labelColor=2a1d12" /></a>
</p>

<p align="center"><sub><kbd>📍 Egypt / Remote</kbd> &nbsp; <kbd>⏵ Full-stack @ Eduncy</kbd> &nbsp; <kbd>✦ Building with intent</kbd></sub></p>

<br/>

> _I don't always have a solution, but I know how to find one._

<br/>

I build and maintain **SaaS products** — messaging platforms, CRM systems, billing. Most of my work sits where a feature meets real load: the thing that worked fine for ten users and falls apart at ten thousand.

Some of what that's looked like: a bulk send that delivered all **1,953** messages but recorded itself as failed, because an edge proxy cut the connection at 60 seconds — rebuilt as an async job with progress callbacks. A report endpoint stuck at **~25s** for the largest tenant, traced to a `uuid`-to-`varchar` cast that silently disabled an index, brought down to **~10ms**. Delivery counters that tracked whether an API had *accepted* a request rather than whether it *succeeded*, so a batch where everything failed still read as fully delivered — replaced with values derived at read time.

I spend a lot of time in **Datadog** working out what production is actually doing, and I care about the boring parts that stop things breaking: idempotency keys so a double-click can't charge a customer twice, fallbacks for data created before a change shipped, migrations that don't need a migration.

I use **AI** heavily and treat its output as a hypothesis, not an answer. It's fastest at exploring unfamiliar code and at attacking my own designs before I commit to them — but tests are what tell me it was right.

<br/>

## <samp>「 ⏵ &nbsp;CURRENTLY &nbsp;」</samp>

<table>
<tr>
<td width="180" valign="top">
<img src="https://img.shields.io/badge/-EDUNCY-c2723f?style=for-the-badge&labelColor=2a1d12" /><br/>
<sub><code>full-stack · Dec 2025 →</code></sub>
</td>
<td valign="top">
Started as an intern, full-time within two months. Two products, across a distributed system of Node services talking over <strong>NATS</strong> and HTTP.
</td>
</tr>
<tr>
<td valign="top">
<img src="https://img.shields.io/badge/-FLOVOO-8a7a6b?style=flat-square&labelColor=2a1d12" /><br/>
<sub><code>2026 →</code></sub>
</td>
<td valign="top">
Customer messaging platform. Bulk campaigns, real-time chat, the full <strong>Stripe</strong> subscription lifecycle (upgrades, downgrades, add-ons, usage limits, saved cards, invoices, 12 webhook handlers), and integrations with <strong>WhatsApp</strong> and <strong>Meta</strong> channels.
</td>
</tr>
<tr>
<td valign="top">
<img src="https://img.shields.io/badge/-EDUNCY_CRM-8a7a6b?style=flat-square&labelColor=2a1d12" /><br/>
<sub><code>Dec 2025 — Apr 2026</code></sub>
</td>
<td valign="top">
CRM &amp; operations platform for study-abroad agencies. Stabilised it through a rewrite from a tRPC/Prisma monolith into separate NestJS/Sequelize services — chasing down the regressions the split introduced across frontend and backend.
</td>
</tr>
</table>

<br/>

## <samp>「 ✦ &nbsp;THE STACK &nbsp;」</samp>

<table>
<tr>
<td valign="top" width="120"><sub><code>frontend</code></sub></td>
<td>
<img src="https://img.shields.io/badge/-Next.js-000?style=flat-square&logo=next.js&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-React-20232a?style=flat-square&logo=react&logoColor=61dafb&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Tailwind-0b1120?style=flat-square&logo=tailwindcss&logoColor=38bdf8&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-TanStack_Query-ff4154?style=flat-square&logo=reactquery&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Zod-3068b7?style=flat-square&logo=zod&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Ant_Design-0170fe?style=flat-square&logo=antdesign&logoColor=white&labelColor=2a1d12" />
</td>
</tr>
<tr>
<td valign="top"><sub><code>backend</code></sub></td>
<td>
<img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-NestJS-e0234e?style=flat-square&logo=nestjs&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Express-000?style=flat-square&logo=express&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-NATS-27aae1?style=flat-square&logo=nats.io&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Stripe-635bff?style=flat-square&logo=stripe&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-JWT-000?style=flat-square&logo=jsonwebtokens&logoColor=white&labelColor=2a1d12" />
</td>
</tr>
<tr>
<td valign="top"><sub><code>databases</code></sub></td>
<td>
<img src="https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Redis-dc382d?style=flat-square&logo=redis&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Sequelize-52b0e7?style=flat-square&logo=sequelize&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-TypeORM-fe0902?style=flat-square&logo=typeorm&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white&labelColor=2a1d12" />
</td>
</tr>
<tr>
<td valign="top"><sub><code>devops</code></sub></td>
<td>
<img src="https://img.shields.io/badge/-Docker-2496ed?style=flat-square&logo=docker&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-AWS_S3-232f3e?style=flat-square&logo=amazons3&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Datadog-632ca6?style=flat-square&logo=datadog&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Vercel-000?style=flat-square&logo=vercel&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Git-f05032?style=flat-square&logo=git&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Postman-ff6c37?style=flat-square&logo=postman&logoColor=white&labelColor=2a1d12" />
</td>
</tr>
<tr>
<td valign="top"><sub><code>ai in flow</code></sub></td>
<td>
<img src="https://img.shields.io/badge/-Claude-d97757?style=flat-square&logo=anthropic&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Claude_Code-d97757?style=flat-square&logo=anthropic&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Cursor-000?style=flat-square&logo=cursor&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-Copilot-1f6feb?style=flat-square&logo=githubcopilot&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/-ChatGPT-10a37f?style=flat-square&logo=openai&logoColor=white&labelColor=2a1d12" />
</td>
</tr>
</table>

<br/>

## <samp>「 ⌬ &nbsp;A FEW THINGS I'VE SHIPPED &nbsp;」</samp>

<table>
<tr>
<td width="33%" valign="top">

#### [Portfolio](https://github.com/ziadsaid2/Ziad-Portfolio) &nbsp;·&nbsp; [live ↗](https://ziad-said-portfolio.vercel.app)
Interactive portfolio with a working terminal — eight commands, a boot screen, a lens cursor, a 3D scene and d3 visuals.

<sub>
<img src="https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/Spline-c2723f?style=flat-square&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/d3-f9a03c?style=flat-square&logo=d3.js&logoColor=white&labelColor=2a1d12" />
</sub>

</td>
<td width="33%" valign="top">

#### [mohamed-shop](https://github.com/ziadsaid2/mohamed-shop)
Storefront for a car-parts and car-wash business — catalogue, services, search, admin area, and SEO done properly.

<sub>
<img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/Supabase-3ecf8e?style=flat-square&logo=supabase&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/Cloudflare-f38020?style=flat-square&logo=cloudflare&logoColor=white&labelColor=2a1d12" />
</sub>

</td>
<td width="33%" valign="top">

#### [restaurant-project](https://github.com/ziadsaid2/restaurant-project)
Full-stack restaurant management — admin dashboard, menu, cart, table reservations, real-time notifications.

<sub>
<img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/NestJS-e0234e?style=flat-square&logo=nestjs&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white&labelColor=2a1d12" />
</sub>

</td>
</tr>
</table>

<br/>

## <samp>「 ⏷ &nbsp;EDUCATION &nbsp;」</samp>

<table>
<tr>
<td width="180" valign="top">
<img src="https://img.shields.io/badge/-B.SC.-c2723f?style=for-the-badge&labelColor=2a1d12" /><br/>
<sub><code>Sep 2024 — Jun 2028</code></sub>
</td>
<td valign="top">
<strong>Alexandria University</strong> — Faculty of Science, Software &amp; Multimedia (SIM).

<br/><br/>

<sub><strong>Recent learning:</strong></sub><br/>
<img src="https://img.shields.io/badge/Node.js_Diploma-AMIT_2025-c2723f?style=flat-square&logo=node.js&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/AI_for_Backend-Udemy_2026-c2723f?style=flat-square&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/Git_&_GitHub-Almdrasa_2026-c2723f?style=flat-square&logo=git&logoColor=white&labelColor=2a1d12" />
<img src="https://img.shields.io/badge/Responsive_Web-freeCodeCamp_2025-c2723f?style=flat-square&labelColor=2a1d12" />
</td>
</tr>
</table>

<br/>

## <samp>「 ⏵ &nbsp;GET IN TOUCH &nbsp;」</samp>

<p>
  <a href="https://ziad-said-portfolio.vercel.app"><img height="40" src="https://img.shields.io/badge/-Portfolio-c2723f?style=for-the-badge&logo=vercel&logoColor=ebe5d3&labelColor=2a1d12" /></a>
  <a href="mailto:ziadsaidahmed2005@gmail.com"><img height="40" src="https://img.shields.io/badge/-ziadsaidahmed2005@gmail.com-c2723f?style=for-the-badge&logo=gmail&logoColor=ebe5d3&labelColor=2a1d12" /></a>
  <a href="https://www.linkedin.com/in/ziadsaid/"><img height="40" src="https://img.shields.io/badge/-LinkedIn-c2723f?style=for-the-badge&logo=linkedin&logoColor=ebe5d3&labelColor=2a1d12" /></a>
</p>
