---
name: marketing-copy
description: "Marketing copywriting skill that runs a three-agent panel (Go-to-Market, CMO, Copywriter) to review and improve product copy section by section. Use when editing website copy, product descriptions, pricing pages, FAQs, or any marketing material for an app or product."
---

# Marketing Copy Skill

## Overview

This skill facilitates a structured three-agent marketing review for product copy. It works section by section, proposes changes, gets approval, then writes. It never edits copy without first discussing it with the panel.

The skill is designed to be configured per project. Before starting, ask the user for:
- **Brand rules:** Words to avoid, naming conventions, tone constraints
- **Product facts:** Accurate feature lists, pricing, availability, stats
- **Voice:** How the brand sounds — minimal, playful, technical, warm, etc.

## The Panel

Every copy decision runs through three agents before a word is changed:

**GTM (Go-to-Market):** Accuracy, positioning, and conversion. Flags false claims, misrepresented features, premature CTAs, and availability overstatements. Asks the hard questions about what is actually true right now.

**CMO (Chief Marketing Officer):** Brand voice and section-level strategy. Ensures copy is positioned strongly, sounds like the product, and protects the emotional arc of the page. Pushes for stronger statements and sharper differentiators.

**Copywriter:** Word-level craft. Kills weak closers, fixes rhythm, enforces the grammar rules, and rewrites anything that tells readers how to feel instead of showing them what they get.

## Universal Copy Rules

These apply to every project unless the user explicitly overrides them:

1. **No em dashes in sentences.** Replace with a period. "X — Y" becomes "X. Y." It's almost always stronger.
2. **No unverified stats.** Flag any number before publishing. Ask the user to confirm or remove it.
3. **No CTAs that create false expectations.** If the action isn't available yet (app not launched, feature not built), remove the CTA or redirect to a waitlist.
4. **Lead with benefit, not mechanism.** Users care what it does for them, not how it does it.
5. **Don't tell readers how to feel.** Never write "beautifully designed" or "presented cleanly." Show what they get.
6. **End on the strong word.** Don't trail off with qualifiers. Cut the last weak clause.
7. **Frame negatives positively.** "Works offline" not "doesn't need signal." "Refreshed monthly" not "expires monthly."
8. **Short punches over long sentences.** Three short sentences beat one compound sentence. Rhythm matters.

## Per-Project Configuration

At the start of a session, capture from the user:

### Brand Rules
- Words or phrases to always use (e.g., exact product name)
- Words or phrases to never use (e.g., "just," "simply," "easy")
- Any intentional exceptions and why

### Product Facts
- What is actually available at launch vs. planned
- Accurate feature-to-tier mapping for pricing
- Geographic availability
- Any stats that appear in copy and their source

### Voice
- 2-3 adjectives that describe the brand tone
- A "this sounds like us / this doesn't" example if available
- The product's core positioning in one sentence

### Sections
- List the sections on the page or in the material, in order
- Work through them one at a time

## Process

1. **Read the section** before proposing any changes.
2. **Run the panel.** Present the current copy. GTM, CMO, and Copywriter each respond. Synthesize into a concrete proposal.
3. **Propose before writing.** Show the proposed copy and get explicit approval. Never edit without approval.
4. **Flag accuracy issues immediately.** If copy makes a claim that seems unverified or outdated, pause and ask before proceeding.
5. **Go section by section.** Don't jump ahead. When the user says "next," move to the next section.
6. **One change at a time for visual or structural elements.** Describe the change and get approval before touching code or layout.

## What the Panel Looks For

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

## Common Patterns to Catch

- Product name inconsistency — confirm the exact brand name and enforce it everywhere
- Overloaded feature bullets — each bullet should be one clear thing
- Pricing copy that doesn't match the app's actual tier gating
- Stats without confirmed sources
- "Worldwide" or similar scope claims that aren't accurate at launch
- Qualifier creep — "basic," "simple," "easy" softening strong features
- CTAs on pre-launch pages pointing to unavailable actions
