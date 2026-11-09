# Awesome Subscription Account Administration & Recurring Billing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of top Subscription Account Administration platforms, recurring billing engines, and open-source monetization infrastructure for managing customer accounts, subscriptions, invoicing, and billing operations from an administrative dashboard.

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source Software](#-open-source-software)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📈 Sector Overview & Market Dynamics

The global subscription and billing management software market is valued at approximately **$7.5B to $8.9B** (with projections climbing past $18B+ at ~14% CAGR). The sector exhibits a **two-tier market concentration structure**: the high-end enterprise layer is **moderately concentrated** around dominant platform giants and ERP/Q2C consolidators (such as Stripe, Zuora, and Salesforce), while the small-to-mid market (SMB) and specialized developer tiers remain **fragmented** across specialized merchant-of-record providers, modular billing gateways, and emerging open-source orchestration solutions.

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Subscription Account Administration platforms sorted by enterprise scale (valuation / market capitalization / annual revenue) in descending order:

| Platform | Scale (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Core Focus & Best For |
|:---|:---|:---|:---|:---|
| **[Stripe Billing](https://stripe.com/billing)** | **$159B Valuation** (>$5.1B Net Revenue) | **0.5%** per recurring transaction (Starter) or **0.8%** (Scale) + 2.9% + 30¢ card processing fee | **$0 monthly fee**; Free test mode forever with full API access & simulation; Free trials configurable up to 730 days (2 years) | Developer-first unified payments & billing control plane with automated tax and dunning |
| **[Chargebee](https://www.chargebee.com/)** | **$3.5B Valuation** (~$200M+ ARR) | **$599/month** (Performance plan, billed annually) for up to $100k/mo MRR + 0.75% overage | **Free forever Starter plan** up to **$250,000 cumulative lifetime billing**; Free trials configurable up to 5,470 days | Mid-market and scaling SaaS companies needing deep CRM/ERP integrations and complex billing logic |
| **[Zuora Central](https://www.zuora.com/)** | **$1.7B Valuation** (Acquired by Silver Lake / GIC; ~$450M ARR) | **~$75,000/year** base enterprise contract deployment (custom ACV quotes) | **No free tier**; Sandbox test environments available with enterprise sales agreements; flexible trial overrides | Global enterprises with complex quote-to-cash (Q2C) flows and strict ASC 606 / IFRS 15 revenue recognition |
| **[Paddle](https://www.paddle.com/)** | **$1.4B Valuation** (~$100M+ ARR) | **5% + $0.50** per successful checkout transaction | **$0/month platform fee**; pay-only-per-transaction; unlimited sandbox test environment with full feature access | Merchant of Record (MoR) model handling global sales tax, VAT, remittance, and compliance out of the box |
| **[Recurly](https://recurly.com/)** | **~$50M - $60M ARR** (Private Equity backed by Accel-KKR) | **$249/month** (Starter plan) + 0.9% of billing volume past $40,000/month included allowance | **90-day free trial** on the Starter plan with full feature access; unlimited sandbox testing | B2C, D2C, and subscription-heavy businesses focusing on automated dunning and involuntary-churn recovery |
| **[Rebilly](https://www.rebilly.com/)** | **~$5M - $7M ARR** (Bootstrapped & privately held) | **$0 base fee** + revenue-share fee scaling from 1% down to 0.5% with volume tiers | **30-day free trial** with no credit card required; permanent free sandbox developer account | High-flexibility payment orchestration, multi-gateway cascading, and risk/fraud routing rules |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Subscription Account Administration and recurring billing platforms. Sorted by GitHub star count in descending order:

### 1. [Lago](https://github.com/getlago/lago) [![GitHub stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers)
* **Stack:** Ruby / PostgreSQL / Redis | **License:** AGPL-3.0
* **Repository:** [getlago/lago](https://github.com/getlago/lago)
* **Description:** Lago is an open-source metering and usage-based billing engine built as an alternative to Chargebee and Stripe Billing. It provides a real-time event-metering dashboard, subscription management, coupons, prepaid credits, and payment gateway orchestration.

### 2. [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) [![GitHub stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers)
* **Stack:** PHP / Laravel / Flutter / MySQL | **License:** Elastic-2.0 (source-available)
* **Repository:** [invoiceninja/invoiceninja](https://github.com/invoiceninja/invoiceninja)
* **Description:** A leading open-source and source-available invoicing, client management, and recurring payments administration tool. Features client portals, expense tracking, automatic invoice generation, and recurring card processing across 30+ payment gateways.

### 3. [Polar](https://github.com/polarsource/polar) [![GitHub stars](https://img.shields.io/github/stars/polarsource/polar?style=social&color=white)](https://github.com/polarsource/polar/stargazers)
* **Stack:** Python / FastAPI / Next.js / PostgreSQL | **License:** Apache-2.0
* **Repository:** [polarsource/polar](https://github.com/polarsource/polar)
* **Description:** An open-source monetization and billing platform designed for developers, digital products, and SaaS businesses. Features complete subscription lifecycle management, usage-based fee tracking, checkout hosting, and developer entitlements.

### 4. [Akaunting](https://github.com/akaunting/akaunting) [![GitHub stars](https://img.shields.io/github/stars/akaunting/akaunting?style=social&color=white)](https://github.com/akaunting/akaunting/stargazers)
* **Stack:** PHP / Laravel / Vue.js | **License:** BUSL-1.1 (source-available)
* **Repository:** [akaunting/akaunting](https://github.com/akaunting/akaunting)
* **Description:** Open-source accounting and business management suite for small businesses and freelancers. Provides back-office dashboards for tracking customer accounts, recurring invoices, billing schedules, and company cash flow.

### 5. [Wallos](https://github.com/ellite/Wallos) [![GitHub stars](https://img.shields.io/github/stars/ellite/Wallos?style=social&color=white)](https://github.com/ellite/Wallos/stargazers)
* **Stack:** PHP / SQLite | **License:** GPL-3.0
* **Repository:** [ellite/Wallos](https://github.com/ellite/Wallos)
* **Description:** A self-hosted personal subscription tracker and expense manager. Features multi-currency tracking, recurring renewal calendar reminders, and notification webhooks (Discord, Telegram, Gotify, Email).

### 6. [Crater](https://github.com/crater-invoice-inc/crater) [![GitHub stars](https://img.shields.io/github/stars/crater-invoice-inc/crater?style=social&color=white)](https://github.com/crater-invoice-inc/crater/stargazers)
* **Stack:** PHP / Laravel / Vue.js / React Native | **License:** AGPL-3.0
* **Repository:** [crater-invoice-inc/crater](https://github.com/crater-invoice-inc/crater)
* **Description:** Open-source invoicing and payment administration suite built for freelancers and small businesses. Includes account dashboards for client management, automated payment reminders, recurring invoice generation, and mobile apps.

### 7. [Flexprice](https://github.com/flexprice/flexprice) [![GitHub stars](https://img.shields.io/github/stars/flexprice/flexprice?style=social&color=white)](https://github.com/flexprice/flexprice) [![GitHub stars](https://img.shields.io/github/stars/flexprice/flexprice?style=social&color=white)](https://github.com/flexprice/flexprice/stargazers)
* **Stack:** Go / PostgreSQL / ClickHouse | **License:** AGPL-3.0
* **Repository:** [flexprice/flexprice](https://github.com/flexprice/flexprice)
* **Description:** Open-source usage-based pricing and billing infrastructure for SaaS companies and developers. Provides real-time usage metering, wallet credits & top-ups, tiered and seat-based subscriptions, and no-code administrative pricing configuration.

### 8. [Kill Bill & Kaui](https://github.com/killbill/killbill) [![GitHub stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers)
* **Stack:** Java / MySQL / MariaDB / PostgreSQL | **License:** Apache-2.0
* **Repository:** [killbill/killbill](https://github.com/killbill/killbill) (Dashboard: [killbill/killbill-admin-ui](https://github.com/killbill/killbill-admin-ui))
* **Description:** Enterprise-grade open-source subscription billing and payments engine in production since 2010. Bundled with **Kaui** (Kill Bill Administrative User Interface), it enables finance and customer support teams to manage accounts, process refunds, view invoices, and execute complex dunning workflows.

### 9. [OpenMeter](https://github.com/openmeterio/openmeter) [![GitHub stars](https://img.shields.io/github/stars/openmeterio/openmeter?style=social&color=white)](https://github.com/openmeterio/openmeter/stargazers)
* **Stack:** Go / ClickHouse / Kafka / PostgreSQL | **License:** Apache-2.0
* **Repository:** [openmeterio/openmeter](https://github.com/openmeterio/openmeter)
* **Description:** Cloud-native open-source usage metering and AI-token consumption tracking engine. Bridges the gap between application usage data and billing platforms like Stripe and Lago, enabling metered recurring pricing.

### 10. [Tier](https://github.com/tierrun/tier) [![GitHub stars](https://img.shields.io/github/stars/tierrun/tier?style=social&color=white)](https://github.com/tierrun/tier/stargazers)
* **Stack:** Go | **License:** BSD-3-Clause
* **Repository:** [tierrun/tier](https://github.com/tierrun/tier)
* **Description:** Open-source pricing engine and SDK for Stripe. Manages pricing models, entitlement checking, feature metering, and tier transitions in code with JSON/YAML configuration without vendor lock-in.

### 11. [UniBee](https://github.com/UniBee-Billing/unibee) [![GitHub stars](https://img.shields.io/github/stars/UniBee-Billing/unibee?style=social&color=white)](https://github.com/UniBee-Billing/unibee/stargazers)
* **Stack:** Go / Vue.js / MySQL | **License:** AGPL-3.0
* **Repository:** [UniBee-Billing/unibee](https://github.com/UniBee-Billing/unibee)
* **Description:** Open-source subscription billing management system equipped with a dedicated merchant admin portal, customer self-service portal, user tier access control, and multiple payment gateway connectors.

### 12. [SubTracker](https://github.com/Smile-QWQ/SubTracker) [![GitHub stars](https://img.shields.io/github/stars/Smile-QWQ/SubTracker?style=social&color=white)](https://github.com/Smile-QWQ/SubTracker/stargazers)
* **Stack:** Vue 3 / Fastify / SQLite | **License:** GPL-3.0
* **Repository:** [Smile-QWQ/SubTracker](https://github.com/Smile-QWQ/SubTracker)
* **Description:** Modern self-hosted personal subscription manager with renewal calendar notifications, budgeting analytics, AI-assisted capture, Wallos data migration support, and multi-currency tracking.

---

## 📊 Comparison at a Glance

| Software | License | Model | Admin Dashboard | Business Billing | Self-Hosted | Best For |
|:---|:---|:---|:---:|:---:|:---:|:---|
| **[Stripe Billing](https://stripe.com/billing)** | Proprietary | Cloud SaaS | ✅ | ✅ | ❌ | Developer-first teams using Stripe |
| **[Chargebee](https://www.chargebee.com/)** | Proprietary | Cloud SaaS | ✅ | ✅ | ❌ | Mid-market subscription operations & CPQ |
| **[Zuora Central](https://www.zuora.com/)** | Proprietary | Enterprise Cloud | ✅ | ✅ | ❌ | Enterprise quote-to-cash & ASC 606 revenue recognition |
| **[Paddle](https://www.paddle.com/)** | Proprietary | Merchant of Record | ✅ | ✅ | ❌ | Global SaaS tax compliance & automated remittance |
| **[Recurly](https://recurly.com/)** | Proprietary | Cloud SaaS | ✅ | ✅ | ❌ | Churn reduction, smart dunning & DTC subscriptions |
| **[Rebilly](https://www.rebilly.com/)** | Proprietary | Cloud SaaS | ✅ | ✅ | ❌ | Multi-gateway cascading & payment orchestration |
| **[Lago](https://github.com/getlago/lago)** | AGPL-3.0 | Self-Hosted / Cloud | ✅ | ✅ | ✅ | Usage-based metering & modern OSS billing engine |
| **[Invoice Ninja](https://github.com/invoiceninja/invoiceninja)** | Elastic-2.0 | Self-Hosted / Cloud | ✅ | ✅ | ✅ | Invoicing, client portal & recurring billing |
| **[Polar](https://github.com/polarsource/polar)** | Apache-2.0 | Self-Hosted / Cloud | ✅ | ✅ | ✅ | Modern developer monetization & SaaS subscriptions |
| **[Akaunting](https://github.com/akaunting/akaunting)** | BUSL-1.1 | Self-Hosted / Cloud | ✅ | Basic | ✅ | Freelancers & small business accounting |
| **[Wallos](https://github.com/ellite/Wallos)** | GPL-3.0 | Self-Hosted | ✅ | ❌ (Personal) | ✅ | Personal recurring subscription tracking |
| **[Crater](https://github.com/crater-invoice-inc/crater)** | AGPL-3.0 | Self-Hosted | ✅ | ✅ | ✅ | Invoicing, recurring billing & mobile management |
| **[Flexprice](https://github.com/flexprice/flexprice)** | AGPL-3.0 | Self-Hosted / Cloud | ✅ | ✅ | ✅ | Real-time usage metering & credit top-ups |
| **[Kill Bill + Kaui](https://github.com/killbill/killbill)** | Apache-2.0 | Self-Hosted | ✅ (Kaui) | ✅ | ✅ | Enterprise-grade permissive OSS recurring billing |
| **[OpenMeter](https://github.com/openmeterio/openmeter)** | Apache-2.0 | Self-Hosted / Cloud | ✅ | Metering | ✅ | Real-time usage metering & AI token consumption |
| **[Tier](https://github.com/tierrun/tier)** | BSD-3-Clause | Self-Hosted / Cloud | CLI / SDK | ✅ | ✅ | Pricing-as-code & entitlement checking for Stripe |
| **[UniBee](https://github.com/UniBee-Billing/unibee)** | AGPL-3.0 | Self-Hosted | ✅ | ✅ | ✅ | All-in-one recurring billing with merchant & user portal |
| **[SubTracker](https://github.com/Smile-QWQ/SubTracker)** | GPL-3.0 | Self-Hosted | ✅ | ❌ (Personal) | ✅ | Personal subscription tracking with AI extraction |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source or notable subscription account administration tool, recurring billing platform, or usage-metering engine that belongs here, please feel free to contribute:

1. Fork this repository.
2. Create your branch: `git checkout -b feature/add-new-platform`.
3. Add the project with details (repository, stack, license, star badge, and description).
4. Submit a Pull Request!

---

## 📄 License

This repository is curated and released under the [CC0 1.0 Universal (Public Domain)](LICENSE). Listed software projects, trademarks, and logos retain their respective licenses and rights.

---

⭐ **If you found this curated list helpful, please consider starring the repository!** ⭐
