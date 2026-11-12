# Awesome-CSAT-Customer-Feedback-Management

## Top CSAT & Customer Feedback Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Survey Collection, Sentiment Analysis & Closed-Loop Feedback Action*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CSAT & Customer Feedback Management**. These tools help teams capture customer sentiment through NPS, CSAT, and CES surveys, analyze feedback at scale, and route insights to the right teams—closing the loop between what customers say and what organizations actually fix.

**Examples** include Qualtrics, Medallia, SurveyMonkey, Delighted, Typeform, InMoment, AskNicely, Retently, Survicate, and Formbricks (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted feedback collection, open-source survey platforms, and community-driven sentiment analysis—ideal for organizations seeking data sovereignty and predictable costs over per-response SaaS pricing. The open-source CX space has matured significantly; Formbricks now positions itself as a direct alternative to Qualtrics and Medallia for technical teams [citation:13].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Qualtrics CustomerXM](https://www.qualtrics.com/)** | Enterprise experience management platform covering surveys, analytics, and closed-loop action. Positioned for large organizations with dedicated CX programs. | Quote-only (enterprise contract; typically six-figure annual) | No free tier; demo via sales |
| **[Medallia](https://www.medallia.com/)** | Enterprise feedback management and experience analytics. Widely deployed in hospitality, retail, and financial services for large-scale CSAT/NPS programs. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[SurveyMonkey](https://www.surveymonkey.com/)** | Widely used survey platform with CSAT/NPS templates, analytics, and integrations. | Team Advantage: ~$25/user/month (annual) | **Free**: 10 questions per survey, 25 responses/month, 7-day data retention [citation:4] |
| **[Delighted](https://delighted.com/)** | NPS and CSAT feedback platform focused on simplicity. Sends surveys via email, SMS, link, or in-app, with Slack and CRM integrations. | Quote-only; free plan available | **Free**: 100 responses/month |
| **[Typeform](https://www.typeform.com/)** | Form and survey builder known for conversational, one-question-at-a-time UX. Popular for brand-sensitive feedback collection. | Basic: ~$25/month (annual) | **Free**: 10 responses/month |
| **[InMoment](https://inmoment.com/)** | Enterprise experience intelligence platform combining surveys, text analytics, and action planning. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[AskNicely](https://www.asknicely.com/)** | NPS-focused feedback platform for frontline teams. Emphasizes real-time coaching and team accountability. | Quote-only (per-seat or response-based) | No free tier; demo via sales |
| **[Retently](https://www.retently.com/)** | NPS and CSAT platform with automated campaigns and integrations. Positioned for mid-market B2B teams. | Quote-only (tiered by contacts) | Free trial available |
| **[Survicate](https://survicate.com/)** | Survey platform with in-app, website, and email feedback collection. Includes NPS, CSAT, and CES templates. | Quote-only (tiered by responses) | Free plan available with limited responses |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Formbricks](https://github.com/formbricks/formbricks)** | [![Stars](https://img.shields.io/github/stars/formbricks/formbricks?style=social&color=white)](https://github.com/formbricks/formbricks/stargazers) | **The leading open-source experience management platform and direct alternative to Qualtrics, Medallia, Typeform, and SurveyMonkey.** Self-hosted, AGPLv3, unlimited responses with no per-response fees [citation:7]. Supports link surveys, website surveys, and in-app surveys with precise targeting based on attributes, events, and segments [citation:1][citation:7]. 20+ question types including NPS, CSAT, CES, matrix, and ranking [citation:7]. Built-in analytics with CSV/JSON export, webhooks, and integrations with Slack, Notion, Google Sheets, Airtable, and Zapier [citation:7]. The Formbricks 5.0 release added **feedback unification** (ingest Trustpilot, App Store reviews via API), **AI enrichment** (sentiment analysis, topic labeling via embeddings), and **Formbricks Hub**—a scalable Go backend for feedback enrichment, free under Apache 2.0 [citation:13]. Self-host on Railway for ~$5–15/month infrastructure cost [citation:7]. |
| **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)** | [![Stars](https://img.shields.io/github/stars/LimeSurvey/LimeSurvey?style=social&color=white)](https://github.com/LimeSurvey/LimeSurvey/stargazers) | **Mature open-source survey platform** (~2,770 stars) positioned as a free alternative to SurveyMonkey, Typeform, Qualtrics, and Google Forms [citation:2]. Supports 30+ question types, 80+ languages, conditional branching, and assessments. The **free tier is genuinely functional**: 1 administrator, 25 responses/month, 10 MB upload storage, full survey tool [citation:4]. Paid cloud plans scale to 50,000 responses/year. Self-hosted version available with no response caps. |
| **[Astuto](https://github.com/astuto/astuto)** | [![Stars](https://img.shields.io/github/stars/astuto/astuto?style=social&color=white)](https://github.com/astuto/astuto/stargazers) | Open-source, self-hosted customer feedback tool for collecting, managing, and prioritizing user feedback. Positioned as a UserVoice/Fider alternative. Free to self-host; paid cloud subscription available [citation:6]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Fider](https://github.com/getfider/fider)** | [![Stars](https://img.shields.io/github/stars/getfider/fider?style=social&color=white)](https://github.com/getfider/fider/stargazers) | Open-source customer feedback platform with voting boards, roadmaps, and changelogs. Cross-platform, lightning-fast, and free for self-hosting. Positioned as a UserVoice alternative [citation:6]. |
| **[Quackback](https://github.com/quackback/quackback)** | [![Stars](https://img.shields.io/github/stars/quackback/quackback?style=social&color=white)](https://github.com/quackback/quackback/stargazers) | Open-source feedback platform (AGPL-3.0) with voting boards, roadmaps, changelogs, and AI agent workflows that incorporate customer feedback directly into development workflows. Freemium/self-hosted [citation:6][citation:12]. |
| **[PHPBack](https://github.com/phpback/phpback)** | [![Stars](https://img.shields.io/github/stars/phpback/phpback?style=social&color=white)](https://github.com/phpback/phpback/stargazers) | PHP/MySQL feedback application for collecting customer ideas and suggestions. Free and self-hostable. A lightweight option for community projects or small products [citation:6]. |
| **[PostHog](https://github.com/PostHog/posthog)** | [![Stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers) | **Not a survey tool, but relevant for behavior-based satisfaction measurement.** Open-source product analytics with session replay, feature flags, and SQL access to raw events. A Medium analysis recommends PostHog as the best open-source base for building behavior-based satisfaction scoring (rage taps, dead taps, journey abandonment) across web, Android, and iOS [citation:11]. |

**Frameworks for building custom systems**: Combine **Formbricks** for end-to-end survey collection and AI-enriched feedback unification, **LimeSurvey** for traditional survey research with branching logic, and **PostHog** for behavior-based satisfaction signals that surveys cannot capture—all deployable via Docker without per-response SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer feedback platforms collect personal data and sentiment; enforce consent management, data minimization, and compliance with GDPR, CCPA, and other applicable privacy regulations.
- **Open-source CSAT tooling has matured dramatically, but the landscape is bifurcated.** Formbricks is the most complete alternative to Qualtrics/Medallia for teams willing to self-host, with unlimited responses at infrastructure cost (~$5–15/month on Railway) [citation:7]. LimeSurvey offers a genuinely functional free tier (25 responses/month) for traditional survey research [citation:4]. **Surveys alone are insufficient for complete CSAT measurement**—they capture a self-selected minority and miss silent churn. Behavior-based signals (rage taps, journey abandonment) require additional tooling like PostHog or custom instrumentation [citation:11]. Commercial enterprise platforms (Qualtrics, Medallia, InMoment) remain quote-only with six-figure annual contracts.

---

**Made for CX leaders, product managers, support operations teams, and developers building feedback infrastructure.**  
Let's make customer feedback management more open, actionable, and closed-loop.
