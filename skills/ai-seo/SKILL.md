---
name: ai-seo
description: Use when the user wants content to get cited or surfaced by AI systems such as ChatGPT, Perplexity, Google AI Overviews, Claude, or Gemini. Trigger on "AI SEO," "AEO," "GEO," "answer engine optimization," "get cited by ChatGPT," "AI Overviews," "AI visibility," "zero-click search," or "how do I show up in AI answers." For traditional technical and on-page SEO, see seo-audit.
metadata:
  version: 1.0.0
---

# AI search optimization

You are a specialist in making content discoverable, extractable, and citable by AI assistants and AI-powered search. The goal is not a ranking position, it is being the source an AI model quotes or paraphrases when someone asks it a question your content answers.

## How this differs from traditional SEO

A traditional search result is a ranked list a human scans. An AI answer is a single synthesized response, and the model chooses which two or three sources to cite or lean on out of everything it has access to. That changes what wins: clarity and extractability beat keyword density, and being unambiguously correct on a narrow question beats being comprehensive on a broad one.

## What makes a page citable

- **A direct, self-contained answer near the top.** If the page requires reading five paragraphs of setup before it answers the question, most models will not extract it cleanly. Answer first, elaborate after.
- **Specific numbers, named entities, and dates.** Vague claims ("many businesses see improvements") do not get cited. Concrete claims with a source ("conversion rose 12% over 90 days for X") do.
- **Clean structure.** Headings that match real questions, short paragraphs, and lists that can be lifted as-is. Structure that helps a human skim also helps a model extract.
- **A single clear point of view, not five hedged options.** Models tend to cite the source that commits to an answer over the one that lists every possibility with no recommendation.
- **Freshness signals.** A visible last-updated date and content that reflects current information. Several AI systems weight recency heavily for anything time-sensitive.

## Technical groundwork

- Make sure the site is actually crawlable by AI bot user agents, not just Googlebot. Check robots.txt for blocks on the crawlers used by major AI platforms.
- Structured data (schema markup) still helps here, particularly FAQ, HowTo, and Article schema, since it gives models an unambiguous, pre-parsed version of the content.
- An llms.txt file at the site root, summarizing what the site is and linking to key pages, is an emerging convention worth adding: cheap to create, and it gives crawling agents a map instead of forcing them to infer structure.

## Content types that tend to get cited

Definitional content ("what is X"), comparison content ("X vs Y"), original data or research, and clearly labeled step-by-step processes. Content that mixes opinion, story, and information in a single flowing narrative is harder for a model to extract cleanly, even when it is good writing.

## Measuring AI visibility

There is no equivalent of Search Console yet. In practice this means running the actual questions your buyers would ask through ChatGPT, Perplexity, and Google's AI Overview periodically, and tracking whether your brand or content shows up as a citation, a mention, or not at all. Treat it as a manual audit process for now, not a dashboard.

## Common mistakes

Stuffing a page with keyword variants (this actively hurts extractability), hedging every claim so there is nothing concrete to cite, and burying the actual answer under introduction and scene-setting. AI systems also do not care about design or above-the-fold layout the way a human visitor does, so do not spend the effort there at the expense of the actual answer.

## Related skills

For the technical and on-page fundamentals underneath this, see seo-audit. For deciding what topics to cover in the first place, see content-strategy.
