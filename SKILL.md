---
description: Prevent generic AI-generated frontend designs. Enforce
  intentional UI/UX design, visual hierarchy, typography, spacing,
  color, composition, accessibility, and strict anti-AI-slop rules. Use
  when building, reviewing, or refining websites, web applications, SaaS
  products, dashboards, and frontend interfaces.
name: anti-slop-frontend-design
---

# Anti-Slop Frontend Design

## Purpose

Produce design that feels intentional, specific, legible, and
crafted---not like a generic template assembled from fashionable UI
patterns.

The goal is **not** to make every design minimal, monochrome, or
unconventional. The goal is to make every visual decision earn its place
and serve the product, audience, content, and task.

Use this skill when creating or reviewing: - Websites, landing pages,
and web applications - SaaS interfaces, admin panels, and dashboards -
Mobile and desktop product interfaces - Design systems and component
libraries - Presentations, posters, social graphics, and other visual
communication

## Core principle

**Design with intent, taste, and real context---not decoration by
default.**

A strong design should communicate its purpose quickly, guide attention
naturally, support the user's task, and contain details that are
relevant to the actual product or message.

## The 20-point anti-slop standard

Treat these as review prompts, not rigid rules. A pattern is not
automatically wrong; it becomes a problem when it is unmotivated,
repetitive, or inconsistent with the design's context.

1.  **Clear concept and message** --- Establish what the design is for
    and what the viewer should understand or do.
2.  **Purposeful typography** --- Choose typefaces for legibility, tone,
    language support, and hierarchy.
3.  **Consistent font pairing** --- Use a restrained, coherent type
    system. Avoid arbitrary font mixing.
4.  **Balanced visual hierarchy** --- Make primary, secondary, and
    supporting information distinguishable.
5.  **Intentional color palette** --- Choose colors based on brand,
    meaning, accessibility, and context---not trend alone.
6.  **Meaningful contrast** --- Use contrast to communicate priority,
    grouping, state, and readability.
7.  **Thoughtful composition and layout** --- Align content to a clear
    structure and give elements appropriate space.
8.  **Original, relevant content** --- Avoid generic filler copy,
    placeholder claims, and stock-sounding language.
9.  **Relevant, accurate imagery** --- Use visuals that explain,
    demonstrate, or reinforce the subject.
10. **Purpose-built graphics and icons** --- Use a consistent visual
    language; do not add icons merely to fill space.
11. **Correct spacing and alignment** --- Apply a deliberate spacing
    scale and consistent alignment rules.
12. **Cohesive visual system** --- Make components, states, typography,
    color, and spacing feel related.
13. **Restrained effects** --- Use shadows, blur, gradients, borders,
    and animation only when they improve meaning or usability.
14. **Readable, accessible design** --- Check contrast, text size, focus
    visibility, keyboard access, and responsive behavior.
15. **Context-aware details** --- Reflect real product terminology,
    content, data, workflows, and user needs.
16. **Distinctive product identity** --- Avoid default-template
    appearance; express the actual brand and product character.
17. **Iteration and critical review** --- Inspect the result, identify
    weak decisions, and refine them.
18. **Remove generic, overused elements** --- Question decorative pills,
    badges, cards, gradients, dividers, and floating elements.
19. **Consistency across screens and states** --- Maintain coherent
    patterns without making every section look identical.
20. **Human judgment and craft** --- Add specificity, narrative,
    editorial judgment, and detail where they improve the experience.

## Common AI-slop indicators

Watch for these patterns. Remove or revise them when they do not serve a
clear purpose:

-   Decorative tags, pills, badges, and chips with no functional meaning
-   Excessive italic styling or arbitrary emphasis
-   Overuse of fashionable display fonts or a single recognizable
    typeface without regard to context
-   Awkward letter spacing, cramped kerning, or inconsistent tracking
-   Over-detailed UI that makes simple tasks feel complicated
-   Dividers between every element or section
-   Unmotivated color shades, opacity layers, and translucent surfaces
-   Borders and nested containers around nearly everything
-   Elaborate diagrams that explain less than a simple sentence or chart
-   Verbose, repetitive, or generic copy
-   Breadcrumbs, section numbering, and labels added only for visual
    texture
-   Eyebrows and tiny uppercase labels used as a universal heading
    treatment
-   Dithering, noise, grain, or texture without a visual or
    communicative reason
-   ASCII art or code-like decoration unrelated to the product
-   Rounded "squircle" shapes applied indiscriminately
-   Excessive monospaced typography outside technical contexts
-   All-caps subtitles that reduce readability
-   Gradient backgrounds used as a substitute for composition
-   Decorative punctuation, including unnecessary periods in short
    titles
-   Repeated layout patterns that make every page look like the same
    template

Do not mechanically ban these elements. For example, a pill can be
appropriate for a status, a gradient can express a brand, and a
monospaced font can be right for developer tooling. The test is whether
the choice has a clear reason.

## Workflow

### 1. Understand the brief

Before designing, identify: - The audience and their level of
familiarity - The primary task or message - The content and data that
must be represented - The platform, viewport, and usage context - Brand
constraints, accessibility requirements, and technical constraints - The
desired tone and degree of visual distinctiveness

If essential information is missing, ask a focused clarification rather
than inventing product details.

### 2. Define the design direction

Write a short design rationale before implementation: - **Purpose:**
What must this design achieve? - **Hierarchy:** What should be noticed
first, second, and third? - **Structure:** What layout best supports the
content and task? - **Visual language:** Which type, color, spacing,
shape, and imagery choices fit the context? - **Restraint:** Which
common decorative patterns should be deliberately avoided?

Do not begin by choosing a trendy visual style and forcing the content
into it.

### 3. Establish the system

Define only the tokens and components needed: - Typography roles and a
small, coherent type scale - Semantic color roles with accessible
contrast - Spacing and layout rules - Grid, breakpoints, and responsive
behavior - Border, radius, and elevation rules - Icon and illustration
style - Component states and interaction behavior

Prefer reusable rules over one-off styling. Avoid creating a large
design system for a small, isolated artifact.

### 4. Design the content and layout

-   Put the user's task or message before decoration.
-   Use real, representative content wherever available.
-   Make the primary action and key information easy to locate.
-   Group related content through proximity and alignment before adding
    borders.
-   Use whitespace to establish rhythm and hierarchy.
-   Choose cards only when they clarify grouping or independent actions.
-   Use charts only when the data relationship benefits from a chart.
-   Keep navigation and supporting details proportional to their
    importance.
-   Design empty, loading, error, success, and disabled states where
    relevant.

### 5. Implement with intent

When implementing an interface: - Use semantic structure and accessible
controls. - Keep interaction behavior predictable. - Ensure responsive
layouts are designed, not merely shrunk. - Use consistent component
variants and state styling. - Avoid arbitrary one-off values when a
shared token is appropriate. - Do not add fake functionality, invented
data, or misleading controls. - Keep visual complexity proportional to
the task's complexity.

### 6. Critique and refine

Review the work at its actual target size and in realistic content
conditions.

Ask: - Can a new user understand the purpose quickly? - Is the visual
hierarchy obvious without reading every word? - Does every prominent
element have a job? - Is anything repeated, redundant, or decorative
without purpose? - Does the design look specific to this product and
audience? - Are the typography and spacing consistent? - Does the design
remain usable with long text, real data, and narrow viewports? - Are
contrast, focus, keyboard, and touch requirements satisfied? - Would
removing an element improve clarity?

Make targeted revisions. Do not add more visual effects to compensate
for a weak concept or hierarchy.

## Quick review checklist

Before delivery, verify:

-   [ ] The purpose and primary message are immediately clear.
-   [ ] The layout reflects the actual content and user task.
-   [ ] Typography is readable and intentionally selected.
-   [ ] Color has semantic or brand purpose.
-   [ ] Spacing and alignment are consistent.
-   [ ] Images, icons, and graphics are relevant and coherent.
-   [ ] Cards, borders, pills, dividers, and effects are justified.
-   [ ] Copy is specific, concise, and free of filler.
-   [ ] Responsive behavior and important UI states are considered.
-   [ ] Accessibility fundamentals have been checked.
-   [ ] The result has a distinct identity rather than a generic
    template feel.
-   [ ] A critical review has removed unnecessary elements.

## Output expectations

When creating a design: 1. Deliver the requested artifact or
implementation, not just a description of a design direction. 2. Keep
the design rationale concise and tied to concrete choices. 3. Use
realistic content; clearly identify any unavoidable placeholder content.
4. Do not claim accessibility, responsiveness, or functionality has been
verified unless it has been checked. 5. Prefer a few well-executed
design decisions over many decorative details.

When critiquing an existing design: 1. Identify the highest-impact
issues first. 2. Explain why each issue harms clarity, usability,
consistency, or identity. 3. Recommend specific changes rather than
vague advice such as "make it cleaner." 4. Preserve elements that
already work. 5. Avoid redesigning everything when a focused correction
is sufficient.

## Final standard

The finished work should feel **purposeful, coherent, context-aware,
readable, and recognizably crafted**.

Do not optimize for looking "AI-generated but polished." Optimize for
solving the communication or product problem with good judgment.

## Explicit "Do Not" Rules

This section turns the anti-slop indicators into direct implementation
constraints. Apply them by default unless the brief, brand system,
platform convention, or a real usability need gives a clear reason to
make an exception.

### Do not add decorative UI

-   Do not add tags, pills, chips, badges, or labels merely to make a
    screen look more designed.
-   Do not wrap every piece of content in a card, bordered container,
    panel, or nested surface.
-   Do not add dividers between every row, section, or content group.
    Prefer spacing, alignment, and typography.
-   Do not add breadcrumbs, section numbers, metadata labels, or eyebrow
    headings when they provide no navigation or comprehension value.
-   Do not add floating buttons, ornamental controls, or fake
    interaction affordances.
-   Do not create a component solely because it is visually fashionable.

### Do not use typography as decoration

-   Do not use italics repeatedly to create emphasis. Use hierarchy and
    restrained emphasis instead.
-   Do not select Instrument Serif---or any other currently fashionable
    typeface---by default. Choose typefaces for the product's character,
    legibility, language coverage, and typographic role.
-   Do not use awkward, excessively tight, or negative kerning to make a
    heading appear dramatic.
-   Do not mix unrelated typefaces or weights without a defined
    typographic system.
-   Do not use monospaced fonts throughout a product unless the content
    or brand genuinely calls for them.
-   Do not set subtitles or supporting copy in all caps by default.
-   Do not add periods to short titles and headings as a stylistic
    flourish. Use punctuation only when it belongs to the sentence or
    the established editorial style.

### Do not over-style the visual system

-   Do not use gradients as the default page background or as a
    substitute for a considered layout.
-   Do not layer colors, tints, shades, transparency, and opacity
    effects without a semantic or compositional reason.
-   Do not add noise, grain, dithering, or texture just to make a flat
    surface look sophisticated.
-   Do not apply large rounded corners or squircle shapes to every
    component.
-   Do not stack shadows, glows, blur, borders, and translucent surfaces
    on the same element without a specific need.
-   Do not introduce a new accent color for every section or component.

### Do not overcomplicate information

-   Do not make a simple interface look like a dense enterprise
    dashboard.
-   Do not create elaborate diagrams when a short explanation, table, or
    simple chart communicates better.
-   Do not use ASCII art or code-shaped imagery as decoration.
-   Do not add code breadcrumbs, file trees, terminal motifs, or
    developer-themed visuals to products that are not genuinely about
    software.
-   Do not number every section unless sequence, reference, or
    navigation requires numbering.
-   Do not repeat the same information in headings, labels, helper text,
    badges, and body copy.
-   Do not write verbose, generic, redundant, or marketing-heavy copy to
    fill empty space.
-   Do not invent metrics, testimonials, product claims, customer names,
    or realistic-looking data.

### Do not sacrifice usability for visual novelty

-   Do not reduce text size or contrast to preserve a visual aesthetic.
-   Do not hide important actions behind ambiguous icons or decorative
    interactions.
-   Do not use color as the only way to communicate status or meaning.
-   Do not make controls look interactive when they are not functional.
-   Do not ignore keyboard navigation, focus states, touch targets,
    loading states, errors, or narrow viewports.
-   Do not force every page into the same hero-plus-cards-plus-gradient
    template.
-   Do not add animation or motion unless it clarifies state, feedback,
    or spatial relationships.

### Exception test

Before using any item above, answer this question:

**What specific user, content, brand, or usability need does this choice
serve?**

If there is no concrete answer, leave it out. These are strong defaults,
not a ban on legitimate design conventions. A status pill can
communicate state; a gradient can be part of a real brand; a monospaced
font can improve code readability; and section numbering can support a
procedural document. Use such patterns deliberately, not automatically.
