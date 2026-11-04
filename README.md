# Anti-Slop Frontend Design

A practical design-quality skill for AI coding agents. It helps produce
frontend interfaces that feel intentional, coherent, accessible, and
specific to the product---not generic, over-decorated, or unmistakably
AI-generated.

## What it does

Anti-Slop Frontend Design guides an agent to:

-   Establish the product's purpose, audience, content, and visual
    direction before designing.
-   Build a deliberate visual hierarchy with purposeful typography,
    color, spacing, and composition.
-   Use components, cards, borders, pills, gradients, shadows, and
    animation only when they serve a real purpose.
-   Avoid generic template patterns, decorative UI, filler copy, fake
    metrics, and unnecessary visual effects.
-   Consider responsive behavior, accessibility, interaction states, and
    realistic content.
-   Critique and refine the result before delivery.

The skill covers websites, web applications, SaaS products, dashboards,
and other frontend interfaces.

## The anti-slop principle

**Every design decision must earn its place.**

The goal is not to make every interface minimal or prohibit familiar
design patterns. A gradient, badge, card, divider, or monospaced font
can be appropriate when it serves the brand, content, or user task. The
skill discourages using these patterns automatically or decoratively.

## What's inside

The [`SKILL.md`](./SKILL.md) contains:

-   A 20-point anti-slop design standard.
-   Explicit "Do Not" rules for decorative UI, typography, visual
    effects, layout, content, and usability.
-   A step-by-step workflow from brief analysis through critique and
    refinement.
-   Practical guidance for design systems, responsive implementation,
    and accessibility.
-   A final review checklist and delivery expectations.

## Installation

Install this skill from the GitHub repository using the Skills CLI:

``` bash
npx skills add tharidul/anti-slop-frontend-design
```

Repository: <https://github.com/tharidul/anti-slop-frontend-design>

## Usage

Once installed, ask your AI coding agent to apply the skill when
creating or reviewing frontend work. For example:

> Build this dashboard using the anti-slop-frontend-design skill. Use
> the real product context, establish a clear hierarchy, avoid
> decorative UI, and review the result against the skill's Do Not rules
> before finishing.

Or:

> Review this page for AI-generated design patterns. Identify the
> highest-impact issues and make focused improvements without
> redesigning parts that already work.

## Repository structure

``` text
anti-slop-frontend-design/
├── README.md
└── SKILL.md
```

## Design review checklist

Before considering a design complete, check:

-   [ ] The purpose and primary user task are clear.
-   [ ] The visual hierarchy is deliberate.
-   [ ] Typography, color, spacing, and alignment are consistent.
-   [ ] Every prominent visual element has a purpose.
-   [ ] Cards, borders, pills, dividers, gradients, and effects are
    justified.
-   [ ] Copy is specific and free of filler or repetition.
-   [ ] Content and imagery reflect the actual product.
-   [ ] Responsive layouts and important interaction states are
    considered.
-   [ ] Accessibility fundamentals have been checked.
-   [ ] The result has a coherent identity rather than a generic
    template feel.

## Contributing

Contributions are welcome. Keep changes aligned with the skill's central
principle: improve clarity, usability, context, and craft rather than
adding rules or visual trends for their own sake.

When proposing a change, explain: 1. Which design problem it addresses.
2. Why the guidance is useful across real frontend projects. 3. Whether
it should be a strict prohibition or a context-dependent recommendation.

## License

Add a `LICENSE` file before publishing if you intend to distribute this
skill under a particular open-source license. No license is implied by
this README.
