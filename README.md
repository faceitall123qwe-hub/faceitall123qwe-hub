# Hi, I'm Tim 👋

**Aspiring Cloud / DevOps engineer** who builds and ships real projects end to end — from the
Postgres schema and the API to the infrastructure code and the CI pipeline that deploys it.

- ☁️ Working toward **AWS Solutions Architect Associate (SAA-C03)**, **Terraform** and **CKA**
- 🛠️ I like systems that fail safe: dry-run by default, idempotent operations, least-privilege IAM, documented threat models
- 🇵🇱 Based in Poland · English / Polish / Russian

---

## ⭐ Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [serwis](https://github.com/faceitall123qwe-hub/serwis) · [live demo](https://serwis-pi.vercel.app)
Full-stack platform for a mobile PC repair business: public site, repair tickets driven by a
**pure state machine**, admin panel, customer tracking, Telegram + e-mail notifications,
GDPR-minded data handling.

`Next.js 16` `TypeScript` `Postgres` `Drizzle` `Vercel`

</td>
<td width="50%" valign="top">

### [serwis-infra](https://github.com/faceitall123qwe-hub/serwis-infra)
The same app on **AWS as Terraform modules**: VPC across 2 AZs, ECS Fargate behind an ALB,
RDS Postgres, EventBridge cron, GitHub **OIDC** deploys (no static keys), alarms and budgets.
CI runs fmt, validate, tflint and Checkov.

`Terraform` `AWS` `ECS` `RDS` `GitHub Actions`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [signal-copier](https://github.com/faceitall123qwe-hub/signal-copier)
Async Telegram → Bybit trade copier: regex fast-path + LLM fallback parser, risk-to-stop
sizing, trade state machine, `/panic` kill-switch. **Runs without any API keys** against an
in-memory exchange; 31 tests.

`Python` `asyncio` `pydantic v2` `Telethon` `Bybit API`

</td>
<td width="50%" valign="top">

### [taroluna](https://github.com/faceitall123qwe-hub/taroluna)
Cross-platform tarot app for iOS and Android: 78 cards, 9 spreads, 4 languages, freemium with
in-app purchases. Quota enforced server-side in Postgres; security review included.

`React Native` `Expo` `TypeScript` `Supabase` `RevenueCat`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [second-brain-bot](https://github.com/faceitall123qwe-hub/second-brain-bot)
Telegram bot that turns voice notes, text and photos into structured Notion entries, with
human approval before any write — and a **documented threat model**.

`Python` `Telegram` `Whisper` `LLM` `Notion API`

</td>
<td width="50%" valign="top">

### [autosafe-expert](https://github.com/faceitall123qwe-hub/autosafe-expert)
Bilingual (PL / UA) static website and ad materials for an independent car-inspection
business.

`Astro` `Tailwind CSS`

</td>
</tr>
</table>

## 🧰 Toolbox

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**Languages & frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
