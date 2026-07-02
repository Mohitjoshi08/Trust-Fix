<p align="center">
  <img src="assets/hero-banner.png" alt="TrustFix Banner" width="100%">
</p>

<h1 align="center">TrustFix</h1>

<p align="center">
<b>Designing a Trust-First Home Services Marketplace for India</b>
</p>

<p align="center">
Transforming neighborhood trust into a scalable digital reputation system for home service professionals.
</p>

<p align="center">

![Product Management](https://img.shields.io/badge/Product-Management-blue?style=for-the-badge)
![Case Study](https://img.shields.io/badge/End--to--End-Case%20Study-success?style=for-the-badge)
![Prototype](https://img.shields.io/badge/Interactive-Prototype-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

<p align="center">

<a href="https://trust-fix-pwa.vercel.app">
<img src="https://img.shields.io/badge/🌐_Live_Demo-Visit-blue?style=for-the-badge">
</a>

<a href="docs/TrustFix_Presentation.pdf">
<img src="https://img.shields.io/badge/📑_Presentation-View-red?style=for-the-badge">
</a>

<a href="#product-overview">
<img src="https://img.shields.io/badge/📖_Case_Study-Read-black?style=for-the-badge">
</a>

</p>

---
## Repository Guide

| Looking for... | Location |
|---------------|----------|
| 📖 Complete Case Study | README.md |
| 📊 Presentation Deck | docs/TrustFix_Presentation.pdf |
| 🌐 Interactive Prototype | https://trust-fix-pwa.vercel.app |
| 📝 Product Decisions | research/product-decisions.md |
| ⚖️ Trade-offs | research/tradeoffs.md |
| 📈 Competitor Analysis | research/competitive-analysis.md |
| 💡 Assumptions | research/assumptions.md |

---

# Product Overview

TrustFix is an end-to-end **Product Management case study** that explores how trust can become the primary competitive advantage in India's fragmented home services market.

Instead of building another marketplace where every booking starts from zero, TrustFix introduces a **neighborhood-first reputation system** where every verified service strengthens a professional's credibility for future customers.

The project covers the complete product lifecycle-from problem discovery and user research to MVP definition, UX design, go-to-market planning, success metrics, and an interactive prototype.

> **Goal:** Design a marketplace where trust compounds after every completed service instead of disappearing with each transaction.

---

# Problem Statement

Finding a trustworthy plumber, electrician, carpenter, or appliance repair technician remains a frustrating experience for both customers and service professionals.

## Customer Challenges

- Finding reliable professionals
- Verifying service quality before booking
- Uncertain pricing
- Limited accountability after service
- Fragmented recommendations across WhatsApp groups and personal networks

## Provider Challenges

- Difficulty building long-term credibility
- Heavy dependence on word-of-mouth
- Irregular work opportunities
- Limited visibility beyond existing customers
- Poor customer retention

The core issue is simple:

> **Trust is created during every successful service, but it rarely persists beyond that transaction.**

---

# Market Gap

Customers currently discover home service professionals through multiple channels, each solving only part of the problem.

| Channel | Strength | Limitation |
|----------|----------|------------|
| Word of Mouth | High trust | Limited reach |
| WhatsApp Groups | Local recommendations | Information disappears over time |
| Online Listings | Large provider base | Difficult to verify quality |
| Marketplace Apps | Convenient booking | Reputation remains platform-specific |

While existing solutions simplify discovery, none preserve neighborhood trust in a structured and reusable way.

---

# Key Insight

During problem analysis, one insight consistently emerged:

> **People are not looking for the cheapest service professional. They are looking for someone they can trust.**

Every completed service already generates trust.

The opportunity is not to create trust-but to preserve it, verify it, and allow it to benefit future customers.

This insight became the foundation of TrustFix.

---

# Solution Overview

TrustFix is a neighborhood-first home services marketplace designed around one core principle:

> **Trust should compound-not reset-after every verified service.**

The platform combines:

- Neighborhood-based provider discovery
- Verified service completion
- Transparent booking
- Portable provider reputation
- Trust-based decision making

Instead of relying primarily on anonymous ratings, TrustFix builds provider credibility using verified work history and meaningful trust signals collected through completed services.

---

# Product Architecture

TrustFix minimizes onboarding friction while maintaining a structured service experience.

Customers begin from a familiar channel (WhatsApp) before moving into a lightweight Progressive Web App (PWA), while providers manage their operations through a dedicated Provider PWA.

```text
                      Customer (WhatsApp)
                               │
                               ▼
                      TrustFix Customer PWA
                               │
                               ▼
                  Booking & Verification Engine
                               │
                   ┌───────────┴───────────┐
                   ▼                       ▼
              Provider PWA          Reputation Engine
                   │
                   ▼
         Verified Service History
```

---

# User Journey

## Customer Journey

```text
Discover Service
        ↓
Browse Providers
        ↓
Compare Trust Signals
        ↓
Book Service
        ↓
Track Provider
        ↓
Complete Payment
        ↓
Verify Service
        ↓
Trust Score Updated
```

---

## Provider Journey

```text
Receive Request
        ↓
Accept Booking
        ↓
Navigate
        ↓
Complete Service
        ↓
Upload Work Photos
        ↓
Customer Verification
        ↓
Trust Score Updated
```

---

# Prototype Preview

The following screens demonstrate the proposed MVP experience for both customers and service professionals.

## Customer Experience

<p align="center">

<img width="278" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/customer-journey/02-home-dashboard.png" /><img width="278" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/customer-journey/04-provider-profile.png" /><img width="278" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/customer-journey/08-service-verification.png" />


</p>

---

## Provider Experience

<p align="center">

<img width="281" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/provider-journey/02-job-request.png" /><img width="281" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/provider-journey/05-waiting-verification.png" /> <img width="281" height="868" alt="image" src="https://github.com/Mohitjoshi08/Trust-Fix/blob/main/screenshots/provider-journey/06-reputation-dashboard.png" />

</p>

---

# Interactive Prototype

A high-fidelity interactive prototype was created to validate the proposed product experience.

### Live Demo

**🌐 https://trust-fix-pwa.vercel.app**

The prototype includes:

- Customer onboarding
- Service discovery
- Provider comparison
- Booking workflow
- Live service tracking
- Provider dashboard
- Service verification
- Reputation updates

> **Note:** The interface was generated using an AI-assisted UI generation tool. My contribution focused on defining the product strategy, user journeys, feature prioritization, interaction flows, information architecture, and validating the generated interface against the product requirements.

---

# MVP Scope

The objective of the MVP is to validate one hypothesis:

> **Can verified neighborhood reputation increase customer trust and improve booking confidence?**

## Customer Features

| Feature | Purpose |
|----------|----------|
| Service Discovery | Browse home service categories |
| Provider Search | Find nearby verified professionals |
| Provider Profiles | Compare trust signals before booking |
| Booking Flow | Schedule services |
| Live Tracking | Monitor provider arrival |
| Digital Payments | Complete transactions securely |
| Service Verification | Confirm completed work |
| Booking History | Access previous services |

---

## Provider Features

| Feature | Purpose |
|----------|----------|
| Dashboard | Manage daily operations |
| Job Requests | Accept or reject bookings |
| Navigation | Reach customer locations |
| Work Photo Upload | Verify completed work |
| Earnings Dashboard | Track weekly earnings |
| Reputation Dashboard | Monitor Trust Score and verified jobs |

---
# MVP Prioritization

The case study assumed limited engineering resources, making feature prioritization a key part of the solution. Rather than building a feature-rich marketplace, the MVP focuses on validating the product's core hypothesis while delivering value to both customers and service professionals.

## Prioritization Framework

Features were prioritized using four criteria:

- Customer Value
- Business Impact
- Engineering Effort
- Contribution to Marketplace Trust

| Priority | Feature | Rationale |
|----------|----------|-----------|
| P0 | Service Discovery | Core customer journey |
| P0 | Provider Profiles | Enables informed booking decisions |
| P0 | Booking Flow | Fundamental marketplace functionality |
| P0 | Provider Dashboard | Required for provider operations |
| P0 | Service Verification | Builds trusted reputation |
| P0 | Reputation System | Core product differentiator |
| P1 | Live Tracking | Improves customer confidence |
| P1 | Digital Payments | Simplifies transactions |
| P1 | Booking History | Encourages repeat usage |

### Out of Scope for MVP

The following ideas were intentionally deferred to keep the MVP focused.

- AI-powered recommendations
- Loyalty & referral programs
- Escrow payments
- Insurance integration
- Subscription plans
- Community discussions
- Advanced analytics
- Provider financing

Detailed reasoning behind these decisions is available in **research/product-decisions.md**.

---

# Go-To-Market Strategy

Launching a two-sided marketplace requires balancing supply and demand from day one.

Instead of scaling immediately, TrustFix adopts a phased rollout focused on building trust within dense local communities before expanding geographically.

## Phase 1 -Apartment Communities

**Objective**

- Validate the trust model
- Build provider reputation
- Generate repeat bookings

---

## Phase 2 -Neighborhood Expansion

**Objective**

- Increase marketplace liquidity
- Expand verified provider network
- Strengthen local network effects

---

## Phase 3 -City Expansion

**Objective**

- Scale operations
- Introduce additional service categories
- Build city-wide trust networks

---

# Success Metrics

The success of TrustFix is measured through customer, provider, and business outcomes.

## North Star Metric

> **Verified Repeat Bookings**

A repeat booking indicates that customers trust the platform enough to return while providers continue delivering quality service.

---

## Supporting Metrics

### Customer

- Booking Conversion Rate
- Customer Satisfaction (CSAT)
- Repeat Booking Rate
- Average Booking Time

### Provider

- Job Acceptance Rate
- Job Completion Rate
- Average Trust Score
- Repeat Customers

### Business

- Monthly Active Users
- Marketplace Liquidity
- Customer Retention
- Revenue Growth

---

# Repository Structure

```text
TrustFix
│
├── assets
│   └──hero-banner.png
│   
│ ── screenshots  
│   ├── customer-journey
│   └── provide-journey
│
├── docs
│   ├── TrustFix_Presentation.pdf
│   └── Problem_Statement.pdf
│
├── research 
│   ├── assumptions.md
│   ├── competitors.md
│   ├── product-decisions.md
│   └── tradeoffs.md
│
└── README.md
```

---

# Research

This repository includes supporting documents that capture the reasoning behind the final product decisions.

| Document | Description |
|----------|-------------|
| assumptions.md | Core assumptions identified during product discovery |
| competitors.md | Competitive landscape and market positioning |
| product-decisions.md | Key product decisions and the rationale behind them |
| tradeoffs.md | Important trade-offs made while defining the MVP |

These documents provide additional context without overloading the main README.

---

# Technology Stack

| Category | Technology |
|----------|------------|
| Product Documentation | Markdown |
| Wireframing | Figma |
| Prototype | React (AI-assisted generation via Lovable) |
| Styling | Tailwind CSS |
| Language | TypeScript |
| Deployment | Vercel |
| Version Control | Git & GitHub |

---

# Key Learnings

Building TrustFix reinforced several important product management principles.

- Great products start with a clear understanding of the problem-not the solution.
- Product managers create value by making informed trade-offs, not by adding more features.
- Trust is not a standalone feature; it emerges from consistent product experiences.
- Marketplace products require balancing customer and provider incentives simultaneously.
- A focused MVP creates faster learning than an overly ambitious first release.
- Every product decision should be supported by a clear hypothesis that can be validated.

---

# Future Roadmap

The MVP establishes the foundation for a trusted neighborhood marketplace. Future iterations can expand the product while preserving the core trust model.

## Phase 1 -Current MVP

- Customer PWA
- Provider PWA
- Verified Reputation System
- Booking Workflow
- Digital Payments

---

## Phase 2

- Smart Provider Matching
- Apartment Partnerships
- Service Packages
- Escrow Payments

---

## Phase 3

- Predictive Maintenance
- Enterprise & Society Management
- Provider Financing
- AI-assisted Scheduling

---
# What This Project Demonstrates

This project showcases an end-to-end Product Management workflow, including:

- Problem identification and market analysis
- User segmentation and pain point analysis
- Product vision and strategy
- MVP definition and feature prioritization
- Customer and provider journey mapping
- Go-to-market planning
- Success metrics and North Star Metric definition
- High-fidelity product prototyping
- Documentation of assumptions, decisions, and trade-offs

Rather than focusing only on the final solution, this repository documents the reasoning behind each major product decision.

---
# Acknowledgements

TrustFix was originally developed as a solution to a Product Management case competition and later expanded into a complete portfolio project.

The objective was not only to solve the problem but also to demonstrate structured product thinking, prioritization, UX design, and strategic decision-making under realistic engineering and business constraints.

---

# Contact

If you'd like to discuss this project or connect regarding Product Management opportunities, feel free to reach out.

**Mohit Joshi**

- LinkedIn: https://linkedin.com/in/mohit-joshi-iitp
- Email: mohitjoshi250806@gmail.com

---

<p align="center">

⭐ If you found this project interesting, consider starring the repository.

</p>
