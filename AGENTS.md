# Beauty Echo Website — Agent Instructions

## 1. Business Context

Beauty Echo is a deep-tech beauty startup focused on post-purchase consumer engagement.

Beauty Echo helps beauty brands turn the period after product purchase into a personalized consumer experience through AI-powered conversations grounded in cosmetic science, product context, longitudinal consumer memory, and behavioral orchestration.

The website is primarily B2B.

Primary audience:
- Beauty brand CRM / LTV leaders
- EC / D2C leaders
- Brand managers
- Marketing leadership
- Prospective beauty-brand partners
- Investors as a secondary audience

The website's primary goal is to generate conversations with prospective beauty-brand partners.

Do NOT position Beauty Echo primarily as:
- a generic chatbot
- a consumer community
- a group-buy platform
- a social network
- an NLP analytics tool
- a replacement for dermatologists
- a generic AI skincare assistant

Core strategic idea:

"Generic AI starts from a question.
Beauty Echo starts from the consumer's product journey."

Treat this as an internal strategic principle. Homepage V2 should demonstrate the differentiation implicitly through the product journey, scientific grounding, continuity of context, and brand-specific communication capabilities rather than creating a standalone “Why Beauty Echo” section.

## 2. Current Website Objective

We are building Beauty Echo Homepage V2.

The previous website reflects an older business concept and must be updated to the post-purchase Beauty Echo strategy.

Preserve useful existing frontend infrastructure while replacing obsolete product messaging.

Speed and clarity are more important than extensive redesign.

## 3. Technical Constraints

The existing website is a lightweight static site.

Primary files include:
- index.html
- style.responsive.css
- assets/
- ja/

Do NOT introduce React, Next.js, Vue, Tailwind, build systems, databases, or unnecessary dependencies unless explicitly requested.

Prefer:
- semantic HTML
- plain CSS
- minimal vanilla JavaScript

Preserve:
- responsive behavior
- mobile navigation
- English/Japanese architecture
- existing logo assets
- existing domain structure
- accessibility basics

Avoid unnecessary JavaScript.

## 4. Design Principles

The target aesthetic is:
- premium
- scientific
- calm
- sophisticated
- modern beauty-tech
- credible to enterprise beauty brands

Avoid:
- stereotypical AI neon gradients
- excessive animation
- futuristic robot imagery
- clutter
- generic startup illustrations
- excessive glassmorphism
- excessive decorative effects

Use whitespace generously.

The website should feel closer to a premium skincare/scientific brand than a generic SaaS landing page.

## 5. Conversion Principles

The page must be understandable within 30–60 seconds.

Primary CTA:
"Discuss a Brand Partnership"

Secondary CTA:
"See How It Works"

Avoid generic CTAs such as:
"Learn More"
"Get Started"
"Contact Us"

Every major section should support one of these questions:

1. What problem exists after a beauty purchase?
2. What does Beauty Echo do?
3. What does the consumer experience?
4. What does the brand gain?
5. What evidence exists?
6. How does Beauty Echo demonstrate differentiated post-purchase value?
7. Why is this team credible?
8. How can a brand begin a partnership conversation?

## 6. Evidence and Claims Rules

Never invent:
- customer logos
- revenue
- partnerships
- repurchase improvements
- LTV improvements
- conversion results
- clinical efficacy
- consumer statistics

Current survey results from the Previous Proof of Concept that may be used only when explicitly requested:

- Product experience improvement: 4.81 / 5
- Questions solved / reassurance: 4.69 / 5
- Expertise / trust: 4.69 / 5
- Final survey respondents: n=16

Always identify these publicly as Previous Proof of Concept final survey results.

Do NOT claim these results proved increased LTV, repurchase, conversion, sales, or revenue.

Prefer language such as:
- designed to
- intended to
- may support
- potential commercial outcomes

rather than unsupported causal claims.

## 7. Scientific and Safety Rules

Do not make medical diagnoses.

Do not state or imply that:
- irritation proves a product is working
- irritation proves ingredient penetration
- negative skin reactions indicate barrier improvement
- Beauty Echo guarantees efficacy
- Beauty Echo guarantees compatibility or safety

Public-facing scientific claims must be conservative and defensible.

## 8. Coding Workflow

Before making significant changes:

1. Inspect the existing relevant files.
2. Explain briefly what you intend to change.
3. Preserve working functionality unless explicitly replacing it.
4. Make the smallest coherent implementation.
5. Check desktop and mobile behavior.
6. Check that navigation anchors still work.
7. Check the language switch.
8. Check for missing image references.
9. Summarize changed files after implementation.

When possible, reuse existing CSS components rather than creating duplicate styles.

Do not rewrite the entire codebase simply because a cleaner architecture is possible.

## 9. Current Priority

The objective is not to create the final Beauty Echo brand website.

The objective is to create a credible V2 homepage that can be sent to the first 20 prospective beauty-brand customers.

Optimize for:
1. clarity
2. credibility
3. conversion
4. speed
5. maintainability

in that order.