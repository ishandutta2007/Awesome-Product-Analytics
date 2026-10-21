# Awesome-Product-Analytics

# Top Product Analytics Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Event Tracking, Session Replay & Self-Hosted Product Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Product Analytics**. These tools help teams understand how users actually behave inside their product — tracking events, funnels, retention, and feature adoption, often alongside session replay and experimentation — so decisions are based on observed behavior rather than guesswork.

**Examples** include PostHog, Amplitude, Mixpanel, Heap, Pendo, FullStory, LogRocket, OpenPanel, Countly, and Matomo (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, event pipeline ownership, and transparent data retention — ideal for teams prioritizing privacy, avoiding per-event pricing that scales with growth, and building analytics infrastructure they fully control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amplitude](https://amplitude.com/)**  
  **Enterprise-grade behavioral analytics with warehouse-native queries.** Free plan includes **2M events/month**; Plus, Growth, and Enterprise tiers scale from there, with add-ons like Activation and Experimentation priced separately [citation:2]. **Startup program**: first year of the full Growth plan **100% free** (up to 100M events/month) for companies with <$10M raised and <20 employees; year two at **40% off** annual Plus, or drop to the free 2M-event plan and keep your data [citation:10]. **Best for enterprise teams** wanting deep behavioral analytics with warehouse-native flexibility.

- **[Mixpanel](https://mixpanel.com/)**  
  **Polished product analytics with session replay and A/B testing.** Free tier: **1M events/month** with core analytics and limited features; Growth starts around **$28/month per 10k events** after the base, scaling with volume; Enterprise is custom [citation:1]. **Key add-ons cost extra even on Growth**: Group Analytics (essential for B2B account-level analysis), Data Pipelines (warehouse export, estimated $19,000+/year at larger implementations), extra Session Replay beyond 20K/month, Warehouse Connectors, Feature Flags, and Experiment Reporting [citation:15]. **Mixpanel won't stop collecting data at your limit** — Free plan blocks report access until upgrade or reset; Growth charges overages at À La Carte rates the following month [citation:3]. **Startup program**: one year free with up to 1B events for companies <5 years old and <$8M raised, but data must start flowing within 90 days [citation:15]. **Best for product managers** wanting polished analytics, with the caveat that add-ons can 2-3x the base bill [citation:15].

- **[Heap](https://heap.io/)**  
  **Comprehensive autocapture with minimal instrumentation.** Free plan available; paid plans priced by quote. **Sense Chat** (AI-powered analysis) is free during beta with no announced plans to charge [citation:4]. **Best for teams wanting comprehensive event capture** without manually tagging every interaction.

- **[Pendo](https://www.pendo.io/)**  
  **Analytics combined with in-app guides, feedback, and roadmap tools.** Best for product teams wanting analytics tightly coupled with user onboarding and adoption workflows [citation:1].

- **[FullStory](https://www.fullstory.com/)**  
  **Session replay with product analytics and UX optimization.** Pricing is quote-based; **Vendr's median for 411 purchases is $27,500/year** [citation:5]. **Hidden costs to watch**: session overages at **1.5-2x effective per-session cost** (20-40% higher annual spend for teams that underestimate volume), **mobile sessions priced separately or at 30-50% premium**, data retention extensions adding 10-20%, and **implementation/onboarding fees of $5,000-$25,000** [citation:5][citation:13]. Multi-year contracts often carry **3-7% annual escalators** [citation:5]. **Best for UX and support teams** needing deep session replay, but budget carefully for overages.

- **[LogRocket](https://logrocket.com/)**  
  **Session replay with product analytics and error monitoring.** **Analytics, errors, and logs are unlimited on every plan** — you pay only for sessions captured [citation:6]. Small teams (5K-10K sessions/month) budget **$400-$700/month**; mid-market (25K-75K sessions) **$1,500-$3,500/month**; enterprise (150K-500K sessions) **$4,500-$9,000/month** per Vendr benchmarks [citation:14]. **Best for frontend teams** wanting replay plus error tracking without event-volume anxiety.

- **[Contentsquare](https://contentsquare.com/)**  
  **Digital experience analytics** with session replay, heatmaps, and journey analysis for enterprise websites and apps.

- **[Kissmetrics](https://www.kissmetrics.io/)**  
  **Person-based analytics** focused on customer journey and behavior across devices. Historically notable for its people-centric model.

- **[Woopra](https://www.woopra.com/)**  
  **Customer journey analytics** with real-time tracking and cross-platform behavior analysis.

## Open-Source GitHub Projects

- **[PostHog](https://github.com/PostHog/posthog)**  
  **The leading open-source Product OS** — MIT licensed, self-hostable, **97% of companies use PostHog for free** [citation:9]. **One platform covering analytics, session replay, feature flags, experiments, error tracking, surveys, data warehouse, data pipelines, LLM observability, and logs** — no stitching five vendors together [citation:1][citation:9]. **Free tier resets monthly, no credit card**: **1M analytics events, 5K session recordings, 1M feature flag requests, 100K exceptions, 1,500 survey responses, 1M synced warehouse rows** [citation:9]. **Transparent pay-as-you-go** after the free tier, with **per-product billing limits** so you cannot be surprised by a viral spike [citation:9]. **Anonymous events cost up to 80% less than identified events** — tracking your marketing site anonymously significantly reduces costs [citation:1]. **Startup program**: **$50K in free credits** for qualifying startups [citation:1]. **Best for engineering-led teams** wanting one platform that scales from MVP to growth without rebuilding the stack [citation:1].

- **[OpenPanel](https://github.com/Openpanel-dev/openpanel)**  
  **Open-source Mixpanel alternative with product analytics and session replay** — self-hostable with **unlimited events** when you deploy it yourself [citation:7]. **Cloud pricing is refreshingly simple**: pay only for event volume, everything else unlimited — **5K events/month at $2.50, 100K at $20, 1M at $90, 10M at $350, 50M at $900** [citation:7]. **No tiers, no hidden costs, unlimited websites, users, dashboards, charts, and profiles** [citation:7]. **Best for teams wanting predictable event-based pricing** or self-hosting without event caps.

- **[Countly](https://github.com/Countly/countly-server)**  
  **Open-source product analytics and engagement platform** — self-hostable with feature flags, push notifications, crash reporting, and user profiles. **Best for mobile-first teams** wanting analytics plus engagement tooling in one self-hosted stack.

- **[Matomo](https://github.com/matomo-org/matomo)**  
  **Open-source web analytics with full data ownership** — the leading Google Analytics alternative, self-hosted with no data sampling and no external data sharing. **Best for teams prioritizing privacy and GDPR compliance** across web and product analytics.

- **[Umami](https://github.com/umami-software/umami)**  
  **Simple, self-hosted open-source analytics** — lightweight alternative to Google Analytics with a clean interface and no cookie banners required. **Best for small teams and side projects** wanting basic product and web analytics without overhead.

- **[Plausible](https://github.com/plausible/analytics)**  
  **Lightweight, privacy-focused open-source analytics** — self-hosted or cloud, with a simple dashboard and no cookie consent requirements. **Best for teams wanting privacy-first analytics** without a heavy feature set.

- **[Jitsu](https://github.com/jitsucom/jitsu)**  
  **Open-source event data collection platform** — streams website, app, and CRM data to your own data warehouse (Snowflake, BigQuery, Redshift, Postgres, ClickHouse) with a Segment-like tag. **Best for teams wanting to own their event pipeline** and analyze product data in their warehouse.

- **[OpenReplay](https://github.com/openreplay/openreplay)**  
  **Open-source session replay and product analytics** — self-hostable with replay, co-browsing, and funnel analysis. **Best for teams prioritizing session replay** without per-session SaaS pricing.

### Additional Strong Open-Source Options

- **Metabase** — Open-source BI tool for exploring product data with a visual query builder and dashboards.
- **Apache Superset** — Enterprise-grade open-source BI with rich visualization and SQL Lab.
- **Grafana** — Open-source dashboards for product metrics alongside infrastructure monitoring.
- **Flagsmith** — Open-source feature flags and remote config, often paired with analytics for A/B testing.

**Frameworks for building custom systems**: Combine **PostHog** for the most complete open-source Product OS with analytics, replay, flags, and error tracking in one platform, **OpenPanel** for predictable event-based pricing or unlimited self-hosted events, **Jitsu** for owning the event pipeline into your own warehouse, **Matomo** or **Umami** for privacy-first web analytics, and **OpenReplay** for self-hosted session replay — to build a product analytics stack tailored to your event volume, privacy requirements, and tolerance for operational overhead.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Product analytics tools differ significantly in pricing model, add-on costs, and data ownership. **Mixpanel's base price is misleading** — Group Analytics, Data Pipelines, and extra Session Replay are paid add-ons even on Growth, and together can 2-3x the bill [citation:15]. **FullStory's overage fees run 1.5-2x per-session cost**, mobile sessions are priced separately, and implementation can add $5,000-$25,000 [citation:5][citation:13]. **LogRocket keeps analytics, errors, and logs unlimited on every plan** — you only pay for sessions [citation:6]. **PostHog's free tier is genuinely generous and resets monthly** with no credit card required, and billing limits prevent surprise charges [citation:9]. **Self-hosting removes event-volume pricing but adds operational responsibility** — you own upgrades, scaling, and data retention.
- Self-hosted open-source solutions require proper event pipeline infrastructure (Kafka or similar for high volume), database sizing for event storage, and monitoring of ingestion latency.

---

**Made for product managers, growth engineers, and teams building data-informed product experiences.**
Let's make product analytics more open, transparent, and event-pricing-honest.
