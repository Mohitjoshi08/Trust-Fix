# Product Trade-offs

Every product decision involves balancing user value, engineering effort, business goals, and time-to-market. The following trade-offs shaped the MVP for TrustFix.

---

# 1. WhatsApp Entry vs Native App Onboarding

| Chosen | Alternative |
|---------|-------------|
| WhatsApp Entry | Native Mobile App |

### Why this decision?

Customers already use WhatsApp for neighborhood recommendations. Using it as the initial entry point reduces friction by eliminating the need to install a new application before exploring the service.

### Trade-off

- Lower onboarding friction
- Faster customer acquisition

**Accepted Limitation:** Less control over the initial user experience and dependence on WhatsApp deep linking.

---

# 2. Progressive Web App vs Native Applications

| Chosen | Alternative |
|---------|-------------|
| Progressive Web App (PWA) | Separate Android & iOS Apps |

### Why this decision?

The case assumed limited engineering resources. A PWA enables faster development, lower maintenance, and cross-platform compatibility while remaining sufficient for MVP validation.

### Trade-off

- Faster development
- Lower development cost
- Single codebase

**Accepted Limitation:** Reduced access to certain native device capabilities compared to dedicated mobile applications.

---

# 3. Verified Trust Score vs Ratings-Only System

| Chosen | Alternative |
|---------|-------------|
| Verified Trust Score | Star Ratings Only |

### Why this decision?

Traditional ratings can be manipulated and often lack context. TrustFix prioritizes verified completed services to build provider credibility using real work history rather than anonymous reviews alone.

### Trade-off

- More reliable reputation
- Stronger customer confidence

**Accepted Limitation:** Verification introduces additional steps after service completion.

---

# 4. Focused MVP vs Feature-Rich Marketplace

| Chosen | Alternative |
|---------|-------------|
| Core Marketplace Features | Large Feature Set |

### Why this decision?

The primary objective of the MVP is to validate whether verified neighborhood reputation improves customer trust. Features that do not directly support this hypothesis were intentionally deferred.

### Deferred Features

- AI recommendations
- Loyalty programs
- Insurance
- Escrow payments
- Referral rewards
- Subscription plans

**Accepted Limitation:** A simpler product with fewer convenience features during the initial launch.

---

# 5. Apartment Communities vs City-Wide Launch

| Chosen | Alternative |
|---------|-------------|
| Apartment Communities | Immediate City-Wide Expansion |

### Why this decision?

Marketplaces face a cold-start problem. Concentrating supply and demand within residential communities increases the likelihood of successful matches and allows provider reputation to develop more quickly.

### Trade-off

- Higher marketplace density
- Faster trust formation
- Easier operational validation

**Accepted Limitation:** Slower geographic expansion during the early stages.

---

# Key Takeaway

The objective of the MVP was not to build the most feature-rich home services platform, but to validate one core hypothesis:

> **Can verified neighborhood reputation increase customer trust and improve booking confidence?**

Every major product decision was evaluated against this hypothesis. Features or approaches that did not directly contribute to validating it were intentionally deferred to future iterations.