# Product Decisions

## Overview

Every product is the result of hundreds of decisions made under constraints.

TrustFix was designed as a Product Management case study with limited engineering resources, a fixed MVP scope, and a strong emphasis on solving one core problem: **building trust in home service marketplaces.**

This document explains the reasoning behind the major product decisions made throughout the project.

---

# Decision 1 — Use WhatsApp as the Primary Customer Entry Point

## Decision

Customers enter TrustFix through WhatsApp before being redirected to the TrustFix Progressive Web App.

## Alternatives Considered

- Native Android Application
- Native iOS Application
- Progressive Web App (Direct Entry)
- **WhatsApp + Progressive Web App (Selected)**

## Why This Decision?

Many customers already discover service professionals through WhatsApp groups and personal conversations.

Instead of changing existing user behavior, TrustFix integrates into it.

Using WhatsApp reduces onboarding friction while keeping the product accessible to users who may not want to install another application.

This approach also aligns with the MVP objective of validating demand before investing in native applications.

## Trade-offs

### Advantages

- No installation required
- Familiar entry point
- Lower acquisition friction
- Faster MVP rollout

### Disadvantages

- Dependency on WhatsApp
- Less branding during onboarding
- Limited control over the first interaction

## Validation

- Measure onboarding completion rate
- Compare conversion with direct PWA entry
- Track customer acquisition cost

---

# Decision 2 — Build a Progressive Web App Instead of Native Apps

## Decision

Develop the MVP as a Progressive Web App for both customers and providers.

## Alternatives Considered

- Android Application
- Android + iOS
- Flutter
- **Progressive Web App (Selected)**

## Why This Decision?

The case explicitly assumes limited engineering resources.

A Progressive Web App enables faster development, easier maintenance, and cross-platform compatibility while still providing a modern user experience.

The goal of the MVP is to validate the product hypothesis—not optimize platform-specific experiences.

## Trade-offs

### Advantages

- Faster development
- Lower engineering cost
- Cross-platform support
- Instant updates

### Disadvantages

- Limited offline capabilities
- Reduced access to native APIs
- Less app-store visibility

## Validation

- Track session duration
- Monitor user retention
- Measure provider usability

---

# Decision 3 — Focus on Neighborhood-Based Trust

## Decision

Build reputation primarily around neighborhood-level trust rather than city-wide popularity.

## Alternatives Considered

- City-wide ranking
- Category ranking
- Rating-based discovery
- **Neighborhood trust (Selected)**

## Why This Decision?

Home service bookings involve inviting someone into personal spaces.

People naturally place greater confidence in professionals who have successfully worked within their own communities.

Local trust is significantly more meaningful than generic popularity.

## Trade-offs

### Advantages

- Higher booking confidence
- Better local relevance
- Stronger network effects

### Disadvantages

- Slower expansion
- Reputation grows gradually
- Smaller initial provider pool

## Validation

- Compare booking conversion between local and non-local providers
- Measure repeat bookings
- Conduct customer interviews

---

# Decision 4 — Prioritize Verified Service History Over Ratings

## Decision

Provider credibility should primarily come from verified completed services rather than anonymous ratings.

## Alternatives Considered

- Star Ratings
- Written Reviews
- Likes
- **Verified Service History (Selected)**

## Why This Decision?

Ratings alone are often subjective and susceptible to manipulation.

Verified completed services provide objective evidence that work was successfully delivered.

This creates stronger trust signals for future customers.

## Trade-offs

### Advantages

- Harder to manipulate
- More transparent
- Better long-term credibility

### Disadvantages

- Requires verification flow
- Higher implementation effort

## Validation

- Compare booking conversion
- Measure customer confidence
- Analyze provider engagement

---

# Decision 5 — Build Separate Experiences for Customers and Providers

## Decision

Create dedicated interfaces for customers and service professionals.

## Alternatives Considered

- Single application
- Role switching
- **Separate Customer & Provider PWAs (Selected)**

## Why This Decision?

Customers and providers have fundamentally different goals.

Customers focus on discovery and booking.

Providers focus on operations, scheduling, and reputation.

Dedicated experiences simplify both workflows.

## Trade-offs

### Advantages

- Cleaner interfaces
- Lower cognitive load
- Better usability

### Disadvantages

- Additional design effort
- More screens to maintain

## Validation

- Task completion time
- Usability testing
- User satisfaction

---

# Decision 6 — Keep the MVP Focused

## Decision

Only include features directly supporting trust, booking, and service completion.

## Alternatives Considered

Include:

- Loyalty Program
- Rewards
- AI Matching
- Chat
- Community Forum
- Escrow
- Insurance

**Selected**

A focused MVP.

## Why This Decision?

The objective of an MVP is to validate the core hypothesis with minimum engineering effort.

Adding secondary features increases complexity without validating the primary value proposition.

## Trade-offs

### Advantages

- Faster launch
- Lower engineering effort
- Clear product focus

### Disadvantages

- Limited functionality
- Some user expectations deferred

## Validation

- Feature request analysis
- User feedback
- Product adoption

---

# Decision 7 — Design for Low Digital Literacy

## Decision

The provider experience should prioritize simplicity over feature density.

## Alternatives Considered

- Advanced dashboards
- Feature-rich interface
- **Simple operational interface (Selected)**

## Why This Decision?

Service professionals have varying levels of digital literacy.

Reducing cognitive load improves usability and reduces onboarding friction.

The interface focuses only on essential actions.

## Trade-offs

### Advantages

- Faster learning
- Better adoption
- Lower support requirements

### Disadvantages

- Less customization
- Fewer advanced capabilities

## Validation

- Task completion success
- Onboarding time
- Error rate

---

# Decision 8 — Apartment-First Go-To-Market Strategy

## Decision

Launch within gated residential communities before expanding city-wide.

## Alternatives Considered

- City-wide launch
- Category-first launch
- Digital-only launch
- **Apartment-first rollout (Selected)**

## Why This Decision?

Marketplaces require both supply and demand.

Apartment communities naturally concentrate customers while enabling trusted referrals.

This increases the probability of achieving early marketplace liquidity.

## Trade-offs

### Advantages

- Easier trust building
- Dense demand
- Higher repeat bookings

### Disadvantages

- Smaller initial market
- Slower geographic expansion

## Validation

- Booking frequency
- Repeat customer rate
- Provider utilization

---

# Product Decision Framework

Every decision throughout this project was evaluated using four questions:

1. Does it increase customer trust?
2. Does it simplify the user experience?
3. Can it be realistically built within MVP constraints?
4. Does it create value for both customers and providers?

If a proposed feature failed any of these questions, it was intentionally excluded from the MVP.

---

# Key Takeaways

The strongest lesson from this project was that successful product management is rarely about choosing which features to build.

Instead, it is about deciding which features **not** to build.

Every decision in TrustFix reflects a balance between user value, engineering constraints, business viability, and long-term product vision.

The final product is intentionally focused—not because additional ideas were unavailable, but because solving one problem exceptionally well is often more valuable than solving many problems superficially.