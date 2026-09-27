<p align="center"><img src="assets/banner.svg" alt="Mohandes AI" width="100%"></p>

<p align="center"><b>Applied AI for technical teams in MENA — starting with water treatment</b></p>

<p align="center" dir="rtl" lang="ar">ذكاء اصطناعي تطبيقي للفرق الفنية في المنطقة العربية، بدءًا من معالجة المياه</p>

<p align="center"><b>Status:</b> Live &nbsp;·&nbsp; <b>Built by</b> <a href="https://github.com/Mohanad1st">Mohannad Hesham</a></p>

> Case study only: the source is private because it runs a live product. Walkthrough on request.

## The problem

Engineers and technicians at water treatment plants need fast, reliable maintenance answers, but verified technical documentation in Arabic is hard to reach, and every hour of troubleshooting costs the plant. Mohandes AI is the product home for Dr. Water, an assistant for plant maintenance, with access granted per person rather than open to anyone. (Dr. Water OS, the plant operations platform, is a separate product with its own case study.)

## What it does

- A bilingual product site with full right-to-left switching
- The Dr. Water assistant, with chat history per session
- Access to the assistant by request, not open sign-up
- Star ratings on answers, reviewed by the team
- An admin back office for access requests, users and analytics

## See it

**[Visit the Mohandes AI site](https://mohandes-ai.com)**

How the work flows:

```mermaid
flowchart TD
  accTitle: How access to Dr. Water works
  accDescr: A person requests access, the team approves, the person asks questions, rates answers, and the team reviews the ratings.
  A[Request access] --> B{Team approves}
  B --> C[Ask Dr. Water]
  C --> D[Rate the answer]
  D --> E[Team reviews ratings]
```

## Built with

React · TypeScript · Tailwind CSS · PostgreSQL with auth and serverless functions · transactional email

## Built responsibly

- Role-based back office with separate viewer, moderator and admin levels
- The assistant is gated: people request access and are approved
- A feedback loop on every answer, reviewed by staff

## What it deliberately doesn't do

- The assistant does not replace a qualified engineer's sign-off on plant work.

## More from Mohandes AI

- [Dr. Water OS](https://github.com/Mohanad1st/dr-water-os-showcase) — Daily operations for water treatment plants, in one bilingual system

---

<sub>© 2026 Mohannad Hesham. Showcase text and images only — no source code is published or licensed here. See all my work on <a href="https://github.com/Mohanad1st">my GitHub profile</a> · <a href="https://www.linkedin.com/in/mohannadhesham/">LinkedIn</a>.</sub>
