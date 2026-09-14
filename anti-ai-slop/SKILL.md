---
name: anti-ai-slop
description: Prevent generic AI-generated website aesthetics and review implementations for visual, UX, copy and frontend patterns that feel templated, interchangeable or obviously AI-generated. Use when designing, redesigning, reviewing or polishing websites, landing pages and frontend interfaces where the result should feel intentional, brand-specific, human-designed and premium.
---

# Anti-AI Slop

Create interfaces that feel deliberately designed for the actual business instead of assembled from generic AI website patterns.

Core principle:

**Specificity beats novelty. Intent beats decoration.**

If the design could be copied to another company by changing the logo, headline and colors, it is probably not finished.

## Required workflow

Before substantial implementation:

1. Inspect the existing project.
2. Inspect the existing website if a URL is available.
3. Understand the business and target audience.
4. Identify the primary conversion action.
5. Inspect branding, assets, typography and existing content.
6. Identify what is genuinely distinctive about the company.
7. Establish a visual direction from those findings.
8. Implement only patterns that support that direction.
9. Run an Anti-AI-Slop Audit before completion.

Never invent customer logos, statistics, testimonials, awards, certifications, partner counts or trust claims.

## Primary design test

Before adding a visual pattern, ask:

- Why is this here?
- What does it communicate?
- Why does it look this way?
- Is it derived from the brand, product, audience or content?
- Would removing it make the page clearer?

If there is no convincing answer, remove it.

## Common AI-slop warning signs

These are warning signs, not absolute bans:

- generic oversized hero headline
- vague marketing copy
- "The future of..." language
- excessive rounded cards
- six identical feature cards
- gradient blobs
- glowing borders
- glassmorphism everywhere
- purple/blue gradients without a brand reason
- giant centered hero with little useful information
- meaningless icon grids
- fake dashboards
- fake terminal windows
- generic SaaS illustrations
- unrelated stock photos
- excessive shadows
- excessive pill-shaped UI
- everything inside a card
- identical section rhythm throughout the page
- fade-up animation on every section
- random parallax
- cursor effects without purpose
- fake metrics or social proof
- generic badges
- generic "Features / Benefits / Solutions" sections

## Distinctiveness test

Ask:

> If I removed the logo and company name, could someone identify what business this is?

If not, derive visual language from the actual business.

Examples:

### Automotive

Prefer:

- road geometry
- movement
- vehicles
- maps
- logistics
- physical infrastructure
- real-world environments

Avoid defaulting to:

- glowing network spheres
- generic floating car renders
- technology gradients

### Construction

Prefer:

- materials
- plans
- structures
- scale
- tools
- real project imagery

### IT services

Prefer:

- actual workflows
- real devices
- infrastructure
- service processes
- human interaction

Avoid:

- fake terminals
- fake code screens
- meaningless laptop mockups

### Professional services

Prefer:

- typography
- editorial composition
- photography
- information hierarchy
- restrained motion

Avoid:

- six identical service cards
- giant generic gradient hero
- generic handshake stock photography

## Visual design

### Color

Choose color from:

- existing brand
- physical environment
- industry
- materials
- photography
- cultural context
- desired emotional tone

Do not automatically use purple-to-blue gradients, cyan glow or neon accents.

### Gradients

Use gradients only when they have a clear purpose such as lighting, depth, atmosphere or a genuine brand transition.

Do not add giant gradient blobs behind every section.

### Cards

Do not turn every piece of content into a card.

Consider:

- editorial sections
- lists
- dividers
- open layouts
- large typography
- image-led composition
- asymmetric layouts

### Layout

Avoid the default:

Hero -> 3 cards -> centered heading -> 3 cards -> image/text -> testimonials -> CTA

Derive layout from the content.

Useful alternatives:

- editorial
- asymmetric
- split-screen
- image-led
- narrative
- timeline
- map-driven
- process-driven
- product-led
- typography-led
- spatial/cinematic

If several consecutive sections use "heading + paragraph + 3 cards", redesign the composition.

## Typography

Do not use huge text merely to look premium.

Use hierarchy deliberately:

- display type
- body type
- labels
- numeric type
- controlled line length
- whitespace

The headline should say something specific.

Weak:

"Solutions that move your business forward."

Better:

"Bundesweite Pannenhilfe, zentral koordiniert."

Use only copy that reflects the real business.

## Copywriting

Avoid filler such as:

- Innovative solutions
- Seamless experiences
- Powerful technology
- Your trusted partner
- Built for the future
- Take your business to the next level

unless the wording has a concrete meaning in context.

Prefer:

- actual services
- customer problems
- real processes
- specific differentiators
- concrete outcomes
- clear next actions

Every sentence should earn its place.

## Hero sections

A hero should quickly answer:

- What is this?
- Who is it for?
- Why does it matter?
- What can I do next?

A visually ambitious hero must still contain useful semantic HTML.

## Imagery

Priority:

1. Real company assets
2. Commissioned photography
3. Contextual photography
4. Carefully generated imagery
5. Generic stock only when appropriate

Do not use images simply to fill rectangles.

For generated imagery:

- no generated logos
- no generated text
- keep brand assets separate
- check physical plausibility
- keep lighting/perspective consistent

## Icons

Do not use icons merely because an icon library is installed.

Icons should communicate a real concept and remain secondary to content.

Avoid walls of identical outline icons.

## Animation

Animation should communicate:

- hierarchy
- process
- movement
- spatial relationships
- interaction feedback
- meaningful transitions

Avoid:

- every section fading up
- every card entering from a different direction
- random floating objects
- constant background motion
- unnecessary parallax
- cursor-following decoration
- excessive blur

If a genuine cinematic narrative is appropriate, use the `cinematic-web-motion` skill.

## 3D

Use 3D only when actual 3D communicates something:

- product visualization
- spatial explanation
- camera storytelling
- physical object interaction
- architecture

Do not use floating spheres, cubes or particles simply because Three.js is available.

## Social proof

Never manufacture:

- customer numbers
- review counts
- ratings
- partner logos
- certifications
- awards
- testimonials
- "trusted by" statements

If real proof exists, present it clearly. If it does not, omit it.

## Forms

Keep forms proportional to the task.

Do not create ten-field forms for a simple inquiry. Ask only what is needed to start the conversation.

## Mobile

Mobile is its own composition.

Check:

- typography
- spacing
- navigation
- image crops
- CTA visibility
- section ordering
- animation complexity
- touch targets

Do not merely shrink desktop.

## Accessibility

Check:

- contrast
- keyboard navigation
- focus states
- semantic HTML
- reduced motion
- readable text
- touch target sizes

## Technical implementation

Avoid unnecessary complexity.

Do not add dependencies, abstraction layers, state, GSAP or Three.js without a clear reason.

Respect the existing project architecture unless there is a compelling reason to change it.

## Anti-slop component rule

Repeated components are good when the underlying information is genuinely repetitive, such as:

- services
- pricing
- FAQs
- navigation
- product variants

Be suspicious when every repeated card contains:

- icon
- short heading
- two-line paragraph
- arrow

especially when repeated throughout the page.

## Anti-AI-Slop Audit

Before completion, explicitly review:

### Brand specificity
- Could this belong to any company?
- Is the visual language derived from the business?
- Are imagery and motion contextual?

### Layout
- Are there too many cards?
- Is everything centered?
- Is everything inside containers?
- Is section rhythm repetitive?

### Copy
- Is the language concrete?
- Is there filler?
- Are claims substantiated?

### Effects
- Are gradients necessary?
- Are shadows necessary?
- Is animation necessary?
- Is 3D justified?

### Mobile
- Does mobile feel intentionally designed?
- Is hierarchy clear?
- Is motion appropriate?

### Final question

> Could a generic AI website generator produce this same result by changing only the logo, colors and text?

If yes, redesign the most generic parts.

## Quality bar

Do not merely try to "look less AI".

Make the result feel inevitable for this particular brand.

It should be modern without being trend-dependent, distinctive without being weird, animated without being distracting, and polished without looking mass-produced.

## Completion checklist

- [ ] Existing project/site inspected
- [ ] Business and audience understood
- [ ] Primary CTA identified
- [ ] Visual direction derived from the actual business
- [ ] No invented claims
- [ ] No generic filler copy
- [ ] Hero communicates the business clearly
- [ ] Layout is not a generic template
- [ ] Cards are used only where appropriate
- [ ] Gradients have a purpose
- [ ] 3D has a purpose
- [ ] Animation has a purpose
- [ ] Imagery is contextual
- [ ] Mobile is intentionally composed
- [ ] Accessibility basics are covered
- [ ] Unnecessary dependencies avoided
- [ ] Anti-AI-Slop Audit completed
