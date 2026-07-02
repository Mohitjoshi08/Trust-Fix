# Product Decisions

This document explains the major product decisions made while designing TrustFix. Each decision was evaluated against the project's primary objective:

> **Increase customer trust while remaining feasible to build as a constrained MVP.**

---

# 1. WhatsApp as the Primary Entry Point

## Decision

Use WhatsApp as the first customer touchpoint instead of requiring users to install a dedicated mobile application.

## Why?

The problem statement highlighted that customers already rely heavily on WhatsApp groups and local communities for home service recommendations. Rather than changing existing user behavior, TrustFix builds on it.

Starting from a familiar platform reduces friction, lowers customer acquisition effort, and allows users to begin their journey without installing another application.

## Alternative Considered

A traditional app-first onboarding flow.

## Why It Was Rejected

Requiring an app download introduces unnecessary friction before users experience any value, reducing adoption during the MVP stage.

---

# 2. Progressive Web App (PWA) Instead of Native Apps

## Decision

Build both customer and provider experiences as Progressive Web Apps.

## Why?

The case assumed limited engineering resources. A PWA provides a modern user experience while requiring significantly less development and maintenance effort than separate Android and iOS applications.

This allows engineering resources to focus on validating the core product hypothesis instead of platform-specific implementation.

## Alternative Considered

Separate native applications.

## Why It Was Rejected

Higher development cost, longer release cycles, and unnecessary complexity for an MVP.

---

# 3. Neighborhood-Based Reputation

## Decision

Build provider reputation around verified work completed within local communities.

## Why?

Trust in home services is often highly local. Customers naturally place greater confidence in professionals who have successfully completed work for nearby residents.

Neighborhood-based reputation makes trust more relevant, easier to understand, and harder to manipulate than platform-wide ratings alone.

## Alternative Considered

A global provider rating system.

## Why It Was Rejected

Overall ratings lack local context and may not accurately represent trust within a customer's immediate community.

---

# 4. Verified Trust Score Instead of Ratings Alone

## Decision

Use verified service completion as the foundation of provider reputation.

## Why?

Star ratings are useful but can be subjective, inconsistent, or manipulated.

TrustFix gives greater importance to verified work history, allowing reputation to reflect actual completed services rather than anonymous opinions alone.

The Trust Score combines multiple signals, including verified jobs, completion rate, repeat customers, and neighborhood reputation.

## Alternative Considered

Traditional five-star ratings.

## Why It Was Rejected

Ratings alone do not provide sufficient confidence for high-trust services such as plumbing, electrical work, or appliance repair.

---

# 5. Separate Experiences for Customers and Providers

## Decision

Design dedicated interfaces for customers and service professionals.

## Why?

Customers and providers have fundamentally different goals.

Customers focus on discovering, comparing, and booking trusted professionals, while providers need operational tools to manage jobs, earnings, and reputation.

Separate experiences reduce unnecessary complexity and improve usability for both user groups.

## Alternative Considered

A single application supporting both roles.

## Why It Was Rejected

Combining both experiences would increase interface complexity and create unnecessary friction, particularly for providers with varying levels of digital literacy.

---

# 6. Trust-Focused MVP

## Decision

Prioritize only the features required to validate the core trust hypothesis.

## Why?

The objective of the MVP is learning—not feature completeness.

Every included feature contributes directly to one of three activities:

- Discover trusted providers
- Complete verified services
- Build provider reputation

Features that did not support this learning objective were intentionally deferred.

## Deferred Features

- AI recommendations
- Referral programs
- Loyalty rewards
- Insurance
- Escrow payments
- Subscription plans
- Advanced analytics

---

# Decision-Making Framework

Major product decisions were evaluated using four criteria:

| Criterion | Purpose |
|----------|---------|
| Customer Value | Does it solve a meaningful user problem? |
| Business Impact | Does it strengthen the marketplace? |
| Engineering Effort | Can it be delivered within MVP constraints? |
| Trust Contribution | Does it increase customer confidence? |

Only decisions that performed well across these dimensions were included in the proposed MVP.

---

# Summary

Every major decision in TrustFix supports the same guiding principle:

> **Trust should become a product capability rather than a marketing promise.**

Instead of maximizing the number of features, the product focuses on validating whether verified neighborhood reputation can improve customer confidence, strengthen provider credibility, and create sustainable marketplace growth.