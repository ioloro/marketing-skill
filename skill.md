---
name: marketing-copy
description: "Marketing copywriting skill with two modes: (1) Copy Review — a three-agent panel reviews and improves existing website copy, product descriptions, pricing pages, and FAQs section by section; (2) PR Kit — generates a complete press kit (boilerplate, fact sheet, bios, features, press release, FAQ, media contact) component by component. Use Copy Review when editing existing copy. Use PR Kit when building a press kit or media kit from scratch."
---

# Marketing Copy Skill

## Modes

This skill operates in two modes. Detect which mode the user wants from context. If ambiguous, ask: "Are we reviewing existing copy, or building a PR Kit?"

- **Copy Review** — review and improve existing marketing copy, section by section
- **PR Kit** — generate a complete press kit from scratch, component by component

Both modes share the same upfront configuration gathering.

---

## Shared Configuration

Before starting either mode, capture from the user:

### Brand Rules
- Words or phrases to always use (e.g., exact product name)
- Words or phrases to never use (e.g., "just," "simply," "easy")
- Any intentional exceptions and why

### Product Facts
- What is actually available at launch vs. planned
- Accurate feature-to-tier mapping for pricing
- Geographic availability
- Any stats that appear in copy and their source
- Platform(s) and OS compatibility

### Voice
- 2-3 adjectives that describe the brand tone
- A "this sounds like us / this doesn't" example if available
- The product's core positioning in one sentence

### PR Kit Only (additional config)
- Media contact: name, email, and optionally phone
- Target audience for the kit: consumer press, tech press, trade/B2B press, podcasters, etc.
- Any existing press coverage to reference
- Whether this is a launch kit, funding announcement, or evergreen kit

---

## Copy Review Mode

### Overview

Facilitates a structured three-agent marketing review for product copy. Works section by section, proposes changes, gets approval, then writes. Never edits copy without first discussing it with the panel.

Before starting, also ask for:
- **Sections:** List the sections on the page or in the material, in order. Work through them one at a time.

### The Copy Review Panel

Every copy decision runs through three agents before a word is changed:

**GTM (Go-to-Market):** Accuracy, positioning, and conversion. Flags false claims, misrepresented features, premature CTAs, and availability overstatements. Asks the hard questions about what is actually true right now.

**CMO (Chief Marketing Officer):** Brand voice and section-level strategy. Ensures copy is positioned strongly, sounds like the product, and protects the emotional arc of the page. Pushes for stronger statements and sharper differentiators.

**Copywriter:** Word-level craft. Kills weak closers, fixes rhythm, enforces the grammar rules, and rewrites anything that tells readers how to feel instead of showing them what they get.

### Universal Copy Rules (Copy Review)

These apply to every project unless the user explicitly overrides them:

1. **No em dashes in sentences.** Replace with a period. "X — Y" becomes "X. Y." It's almost always stronger.
2. **No unverified stats.** Flag any number before publishing. Ask the user to confirm or remove it.
3. **No CTAs that create false expectations.** If the action isn't available yet (app not launched, feature not built), remove the CTA or redirect to a waitlist.
4. **Lead with benefit, not mechanism.** Users care what it does for them, not how it does it.
5. **Don't tell readers how to feel.** Never write "beautifully designed" or "presented cleanly." Show what they get.
6. **End on the strong word.** Don't trail off with qualifiers. Cut the last weak clause.
7. **Frame negatives positively.** "Works offline" not "doesn't need signal." "Refreshed monthly" not "expires monthly."
8. **Short punches over long sentences.** Three short sentences beat one compound sentence. Rhythm matters.

### Copy Review Process

1. **Read the section** before proposing any changes.
2. **Run the panel.** Present the current copy. GTM, CMO, and Copywriter each respond. Synthesize into a concrete proposal.
3. **Propose before writing.** Show the proposed copy and get explicit approval. Never edit without approval.
4. **Flag accuracy issues immediately.** If copy makes a claim that seems unverified or outdated, pause and ask before proceeding.
5. **Go section by section.** Don't jump ahead. When the user says "next," move to the next section.
6. **One change at a time for visual or structural elements.** Describe the change and get approval before touching code or layout.

### What the Copy Review Panel Looks For

**GTM looks for:**
- Claims that don't match the actual product
- Features listed at the wrong tier
- Geographic or availability overstatements
- CTAs pointing to actions that aren't yet possible
- Stats that need verification

**CMO looks for:**
- Off-brand tone or vocabulary
- Headers that describe instead of position
- Sections that undersell or oversell relative to the product's actual differentiation
- Emotional arc across the full page

**Copywriter looks for:**
- Weak closers at the end of sentences or sections
- Em dashes where a period would hit harder
- Passive or vague language ("reads your round through your body")
- "Just," "simply," "easy," or any word that minimizes the product
- Telling readers how to feel instead of what they get
- Any forbidden words from the brand rules

### Common Patterns to Catch

- Product name inconsistency — confirm the exact brand name and enforce it everywhere
- Overloaded feature bullets — each bullet should be one clear thing
- Pricing copy that doesn't match the app's actual tier gating
- Stats without confirmed sources
- "Worldwide" or similar scope claims that aren't accurate at launch
- Qualifier creep — "basic," "simple," "easy" softening strong features
- CTAs on pre-launch pages pointing to unavailable actions

---

## PR Kit Mode

### Overview

Generates a complete press kit from scratch, one component at a time. Unlike Copy Review, this mode is generative — there's no existing draft to review. The panel proposes each component, gets approval, then finalizes it. Never move to the next component without explicit sign-off.

The goal: a journalist should be able to cover the product accurately without asking a single follow-up question.

### The PR Kit Panel

**GTM (Go-to-Market):** Newsworthiness and accuracy. Would a journalist find this worth covering? Every claim must be true and verifiable right now. Flags anything that overstates availability, scale, or impact. Ensures stats are confirmed before they appear.

**CMO (Chief Marketing Officer):** Positioning and brand voice. Does this represent the brand at its strongest? Is the story compelling to the target press audience (consumer, tech, trade)? Pushes for sharper differentiators and a consistent narrative thread across all components.

**PR Director:** Press-specific craft. Knows what journalists actually need and how they use kit materials. Writes boilerplate that's tight enough to paste directly. Keeps bios credible without being braggy. Ensures the fact sheet is scannable in 30 seconds. Catches anything that sounds like marketing copy when it should sound like a press document.

### PR Kit Components (in order)

Work through these one at a time. Propose, get approval, finalize, then move on.

1. **Company Boilerplate** — 2-3 sentences, press-ready. This is what gets pasted at the end of articles and into press releases. Write it in third person. Neutral tone, not a tagline. Include what the product does, who it's for, and where to learn more.

2. **Product Description** — 1-2 paragraphs, written for a non-technical journalist. Benefit-led. Explains what the product does, why it exists, and what makes it different. No jargon. No mechanism-first explanations. The reader should understand the product after one read.

3. **Fact Sheet** — Bullet-point snapshot. Scannable in under 30 seconds. Include: founding date, platform(s), pricing, availability/regions, key stats (if verified), and any notable milestones. Each bullet is one clear fact. No sentences, no context — just the facts.

4. **Key Features** — 4-6 features, benefit-led. Each feature gets a name and one sentence explaining what it does for the user. Not "built with ML" — "recognizes your swing automatically, no manual tagging." Order by what matters most to the target press audience.

5. **Founder/Team Bios** — 50-100 words per person. Third person. Lead with credibility (relevant experience, past companies, domain expertise). End with a human detail if it's genuinely interesting. Include title and full name. One bio per person, one at a time.

6. **Visual Assets Checklist** — Don't generate image files, but produce a clear checklist of what the user needs to prepare: logo formats (SVG, PNG light/dark), app icon sizes, screenshots (current OS/device), lifestyle imagery, and any product video. Note any that are critical vs. nice-to-have.

7. **Sample Press Release** — A ready-to-send press release for the kit's purpose (launch, update, funding, evergreen). Standard format: headline, dateline, lead paragraph (who/what/when/where/why), supporting body paragraphs, a quote from the founder, a second quote from a customer or partner if available, boilerplate, and media contact block. Flag any sections where the user needs to supply a real quote.

8. **Press FAQ** — 5-7 questions a journalist is likely to ask, pre-answered. Prioritize questions about: what problem it solves, who it's for, what's different about it, pricing, availability, and what's coming next. Answers should be concise and quotable — a journalist can lift them directly.

9. **Media Contact Block** — Ready to paste. Format: Name, Title, Email, Phone (if provided), Website. Nothing else.

### PR Kit Rules

1. **Every stat must be confirmed.** Before including any number, ask the user to verify it. A wrong stat in a press kit damages credibility more than no stat.
2. **Write for the journalist, not the customer.** Press kit copy is neutral and informative, not persuasive. The CMO will push for stronger language — the PR Director must hold the line on press-document tone.
3. **Third person throughout.** Boilerplate, bios, press release body — all third person. The only exception is direct quotes.
4. **No jargon without a plain-English explanation.** If a technical term must appear, follow it with what it means.
5. **Availability must be accurate.** Do not write "available worldwide" unless it is. Do not list a launch date without confirming it with the user.
6. **Flag missing assets.** If the user hasn't mentioned visuals, remind them during the Visual Assets Checklist component. A press kit without logos is incomplete.
7. **Boilerplate is reused everywhere.** The Company Boilerplate written in step 1 should appear verbatim at the bottom of the press release in step 7. Don't rewrite it.
8. **One component at a time.** Propose the full draft for each component. Get explicit approval or edits. Finalize. Then and only then move to the next component.

### PR Kit Checklist (end of session)

After all components are approved, present a final checklist:

- [ ] Company Boilerplate
- [ ] Product Description
- [ ] Fact Sheet
- [ ] Key Features
- [ ] Founder/Team Bios
- [ ] Visual Assets (checklist provided — assets to be prepared by user)
- [ ] Sample Press Release
- [ ] Press FAQ
- [ ] Media Contact Block

Note any components that need follow-up (unconfirmed stats, missing quotes, assets not yet prepared).
