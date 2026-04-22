# marketing-copy

A Claude Code skill for marketing copywriting. Two modes: review existing copy section by section, or generate a complete press kit from scratch.

## What it does

### Copy Review

A three-agent panel (GTM, CMO, Copywriter) reviews your existing marketing copy and proposes improvements one section at a time. Claude never edits without showing you the proposal first.

The panel catches things models typically miss:
- Claims that don't match what's actually in the product
- CTAs pointing to features that aren't launched yet
- Stats that aren't confirmed
- Copy that tells readers how to feel instead of what they get
- Weak closers, em dash overuse, qualifier creep

### PR Kit

Generates a complete press kit from scratch, one component at a time. A different three-agent panel (GTM, CMO, PR Director) proposes each component, you approve or edit, then it's finalized before moving to the next.

The kit covers: company boilerplate, product description, fact sheet, key features, founder bios, visual assets checklist, sample press release, press FAQ, and media contact block.

## Examples

**Copy Review:**
- "Let's review the marketing copy for my app's website"
- "Go through my App Store description and tighten it up"
- "Review the pricing page — I think the tiers aren't reading clearly"
- "The hero section feels weak, let's start there"

**PR Kit:**
- "Help me build a press kit for my app launch"
- "I need a PR kit for our funding announcement"
- "Let's put together media materials before we go public"

## Install

```bash
mkdir -p ~/.claude/skills/marketing-copy
curl -o ~/.claude/skills/marketing-copy/skill.md \
  https://raw.githubusercontent.com/ioloro/marketing-skill/main/skill.md
```

Or clone and symlink if you want to stay in sync with updates:

```bash
git clone https://github.com/ioloro/marketing-skill.git ~/marketing-skill
mkdir -p ~/.claude/skills/marketing-copy
ln -s ~/marketing-skill/skill.md ~/.claude/skills/marketing-copy/skill.md
```

Once installed, the skill activates automatically when you ask Claude to review copy or build a press kit. To invoke it explicitly: `/marketing-copy`.

## How it works

Both modes start by gathering configuration — brand rules (words to always/never use), product facts (what's actually available), and voice. This context is what separates a useful review from generic feedback.

From there:

**Copy Review** goes section by section. You tell Claude which sections exist, in order. For each one, the panel discusses it, proposes a rewrite, and waits for your approval before moving on.

**PR Kit** goes component by component in a fixed order, starting with company boilerplate (since it gets reused verbatim in the press release). Each component is proposed, refined, and signed off before the next begins.

## Why section by section

Marketing copy fails in specific, predictable ways. A claim that's slightly wrong, a CTA that creates a false expectation, a feature positioned at the wrong tier — these are hard to catch when reviewing a whole page at once. Working one section at a time keeps the panel focused and keeps you in control of what changes.
