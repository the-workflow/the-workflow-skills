# The content marketing skills pack

Ten Claude Agent Skills that turn your agent into a full content marketing team: SEO, AI search, copywriting, strategy, psychology, social, ads, cold email, conversion, and lead magnets. Free, from The Workflow.

Drop them into Claude Code, or any tool that supports the [Agent Skills spec](https://www.anthropic.com/engineering/agent-skills) (Cursor, Codex, Windsurf, Gemini, Cline), and your agent stops guessing at marketing best practice and starts working like a specialist for each job.

## What's inside

| Skill | What it does |
|---|---|
| [`seo-audit`](skills/seo-audit) | Full technical and on-page SEO audit with a prioritized fix list |
| [`ai-seo`](skills/ai-seo) | Optimizes content to get cited by ChatGPT, Perplexity, AI Overviews, and Claude (AEO/GEO) |
| [`copywriting`](skills/copywriting) | Writes persuasive copy for landing pages, homepages, and product pages |
| [`content-strategy`](skills/content-strategy) | Plans topics, content calendars, and editorial pillars |
| [`marketing-psychology`](skills/marketing-psychology) | Applies behavioral science (anchoring, social proof, loss aversion) to messaging |
| [`social`](skills/social) | Writes platform-native LinkedIn, X, Instagram, and TikTok content, plus social listening |
| [`ad-creative`](skills/ad-creative) | Generates and iterates ad copy at scale for Meta, Google, and LinkedIn |
| [`cold-email`](skills/cold-email) | Writes B2B cold outreach and follow-up sequences that get replies |
| [`cro`](skills/cro) | Analyzes and improves conversion rates on landing pages and forms |
| [`lead-magnets`](skills/lead-magnets) | Plans lead magnets that actually capture emails and convert |

Each skill is a self-contained folder: a `SKILL.md` with the full instructions Claude follows, plus `references/` and `evals/` with supporting detail. Nothing to configure, nothing to prompt-engineer yourself.

## Quick start

**Claude Code CLI, one line per skill:**

```bash
npx skills add the-workflow/the-workflow-skills/seo-audit
npx skills add the-workflow/the-workflow-skills/ai-seo
npx skills add the-workflow/the-workflow-skills/copywriting
npx skills add the-workflow/the-workflow-skills/content-strategy
npx skills add the-workflow/the-workflow-skills/marketing-psychology
npx skills add the-workflow/the-workflow-skills/social
npx skills add the-workflow/the-workflow-skills/ad-creative
npx skills add the-workflow/the-workflow-skills/cold-email
npx skills add the-workflow/the-workflow-skills/cro
npx skills add the-workflow/the-workflow-skills/lead-magnets
```

This pulls each skill straight into your project's `.claude/skills/` folder.

**No CLI? Do it manually:**

1. Create a `.claude/skills/` folder in your project if you don't have one.
2. Clone this repo, then copy any of the folders from `skills/` into `.claude/skills/`.
3. Restart Claude Code in that project. Skills are picked up automatically, no config needed.
4. Just ask for what you need. "Write me a cold email sequence" or "audit my SEO" triggers the matching skill on its own, because Claude reads each skill's description and matches it against your request.

**Other agents (Cursor, Codex, Windsurf, Gemini, Cline):** same manual copy, into whichever skills folder your tool expects. Check your tool's docs if you're not sure where that is.

## Using them

You don't call a skill by name. Talk to your agent the way you'd talk to a marketer on your team: "plan my content calendar for next quarter," "I need LinkedIn posts for this launch," "why isn't my landing page converting." The agent reads the ten skill descriptions, picks the right one, and runs the playbook inside it.

Skills also reference each other. Ask for landing page copy and `copywriting` might point you toward `cro` for a follow-up conversion pass, or `lead-magnets` toward `content-strategy` for what to build next.

## Why these ten

Picked from a much bigger open-source pack, filtered down to one skill per discipline so you get a full-funnel toolkit instead of ten variations on the same thing: something to get found (SEO, AI SEO), something to say it well (copywriting, psychology), something to plan it (content strategy), something to distribute it (social, ads, cold email), and something to turn attention into leads (CRO, lead magnets).

---

Brought to you by The Workflow.
