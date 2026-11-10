<div align="center">

# Hey, I'm Tejas Rana 👋

### Senior Software Engineer · Platform & Identity Engineering

I build identity, integration and AI-agent platforms that run on AWS for 10,000+ enterprise users.

[![Website](https://img.shields.io/badge/tejasrana.in-ff5722?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://tejasrana.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tejasrana3898/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@tejasrana.in)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/tony_3898)

![Profile views](https://komarev.com/ghpvc/?username=Tony3898&color=blueviolet&style=flat-square&label=Profile+views)

</div>

---

## 🧑‍💻 About me

- 📍 Mumbai, India · **6+ years** building distributed systems and multi-tenant SaaS
- 🏢 Senior Software Engineer at **[Freespace](https://www.afreespace.com)** · I lead a team of 4 engineers and have mentored 4 interns
- 🔐 I own the **identity, MCP, integration and notification** platforms at a 99% uptime SLA
- 🤖 Now building **Model Context Protocol (MCP)** servers that give AI agents secure, multi-tenant access to real data
- 💬 Ask me about **OAuth 2.1, SSO, SCIM, serverless on AWS, micro-frontends and MySQL deadlocks**

## ⚡ Impact in numbers

| | |
|---|---|
| 🚀 **16x faster TTFB** | Portal time to first byte from 800ms to 50ms with CloudFront Function routing and edge caching |
| 🔑 **5,000 concurrent users** | k6 load test of the OAuth 2.1 platform. Fixed 1,666 MySQL deadlocks found on the way |
| 🛡️ **100/100** | HTTPS Observatory score, at no added cost |
| ⏱️ **35% faster auth** | Moved login from an EC2 MVC app to serverless SAML/OIDC. It now handles every customer login |
| 🧪 **811 tests** | Automated coverage for the Microsoft Places two-way sync |

## 🛠️ Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,java,spring,python&perline=12" alt="Languages" />
  <br/>
  <img src="https://skillicons.dev/icons?i=react,express,vite,webpack,tailwind,materialui&perline=12" alt="Frameworks" />
  <br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,jenkins,githubactions,git,cloudflare&perline=12" alt="Cloud and DevOps" />
  <br/>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,dynamodb,redis&perline=12" alt="Databases" />
</p>

**Cloud:** Lambda · Step Functions · SQS · SNS · S3 · DynamoDB · API Gateway · CloudFront · CDK · CloudFormation  
**Identity & security:** OAuth 2.1 · PKCE · OIDC · SAML · SCIM · MFA · RBAC · CSP · CORS  
**Architecture:** Microservices · Event-driven systems · Micro-frontends (Module Federation, Single-SPA) · Multi-tenant SaaS  
**Quality:** JUnit · Jest · k6 · SonarQube · CI coverage gates  
**AI engineering:** MCP servers · Claude Code · Cursor

## 🌟 What I've built

<details open>
<summary><b>🔐 OAuth 2.1 Identity Platform</b> · Java 17, Spring Boot, Lambda, Redis, MySQL</summary>

- Auth-code flow with PKCE (S256) for web and Flutter mobile, including MDM managed browsers
- Refresh-token rotation with replay detection, race-safe single-use codes and CSRF protection
- Per-device sessions with revoke-on-deactivate across SCIM, admin and delete flows
- Email one-time-code MFA (Redis Lua, fail-closed) and Cloudflare Turnstile through one Spring AOP annotation
</details>

<details>
<summary><b>🤖 Model Context Protocol (MCP) Platform</b> · Java, Spring Boot, Node.js, TypeScript</summary>

- Multi-tenant MCP server in daily production use. It gives AI agents workspace occupancy analysis tools
- The tenant comes from token claims, so one deployment serves every tenant
- Authorization server for machine clients with Dynamic Client Registration (RFC 7591) and RFC 9728 metadata
</details>

<details>
<summary><b>📣 Distributed Notification Service</b> · Node.js, SQS, SNS, Lambda, Redis</summary>

- Platform-wide service for 10,000+ users over email, in-app and push
- SQS fanout, idempotent processing, preference routing, DLQ isolation and at-least-once delivery
- Per-event, per-channel opt-out and one-click unsubscribe
</details>

<details>
<summary><b>🛂 Access Control & Audit Platform</b> · Spring Security, MongoDB, JaVers</summary>

- RBAC with custom roles, Spring pre-authorization, cached permission lookups and SSO group-to-role mapping
- Platform-wide audit trail: schema-validated SQS intake with versioned entity history in MongoDB
</details>

<details>
<summary><b>🔗 Integrations Platform</b> · Microsoft Places, Serraview, Workday, SCIM, Slack, Teams</summary>

- Two-way Microsoft Places sync with self-resuming Lambda runs (~6,400 creates, no manual re-runs)
- One config-driven pipeline for Serraview, SFTP and Workday. Workday shipped with no integration-specific code
- SCIM 2.0 provisioning for Okta and Azure AD, a Slack booking app and a multi-tenant Microsoft Teams app
</details>

<details>
<summary><b>🧩 Micro-frontend Portal</b> · React, Module Federation, Single-SPA</summary>

- Independent deployments, shared React libraries and white-label branding for web and mobile
- Per-tenant subdomains with Route 53 and CloudFront across US and UK regions
</details>

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Tony3898&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tony3898&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Tony3898&hide_border=true&theme=transparent" alt="GitHub streak" />
</p>

---

<div align="center">

**I like to share what I learn, work on open source and learn from other engineers. Feel free to reach out.**

> *"Build with empathy, scale with clarity, and never stop learning."*

</div>
