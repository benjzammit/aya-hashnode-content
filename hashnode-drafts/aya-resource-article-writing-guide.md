# AYA Resource Article Writing Guide

This is the internal writing guide for AYA resource articles.

It exists so every new Hashnode resource draft can keep the same standard as the current SEO and AEO-focused article library.

This file is not publishable content. Keep it in `hashnode-drafts/` and do not add Hashnode front matter.

## 1. What AYA articles must do

Every article should do three jobs at once:

1. Capture search demand from a phrase people already use.
2. Teach AYA's more structured point of view.
3. Move a practical buyer closer to testing an idea with AYA.

The article should not feel like generic AI thought leadership.

It should feel like a sharp strategist explaining how to make a better decision before money, time, or stakeholder attention gets committed.

## 2. The AYA point of view

AYA should own the credible middle ground between slow traditional research and reckless AI guessing.

The core promise:

> AYA helps teams reduce avoidable guesswork before bigger commitments.

Use this idea often, but do not copy and paste the same sentence into every article.

The recurring logic:

- AI can help teams learn earlier.
- Synthetic audiences and AI focus groups are useful for directional testing.
- They should not be treated as final market truth.
- They do not replace every form of human research.
- The quality of the audience model, question, stimulus, and interpretation matters.
- AYA is more structured than generic AI prompting.

## 3. Standard article structure

Use this structure for most new resource articles.

```md
---
title: "Article Title"
slug: "article-slug"
tags: "ai, research, marketing, analytics, product"
domain: "aya-blog.hashnode.dev"
seoTitle: "SEO Title"
seoDescription: "SEO description."
saveAsDraft: true
---
![Specific image alt text](PEXELS_IMAGE_URL)

*Photo by [Creator on Pexels](PEXELS_PAGE_URL).*

Short buyer problem.

Short answer in the first 100 words.

## Key takeaways

- Clear definition or answer.
- Practical use case.
- Responsible limit.
- AYA method or buyer benefit.

## Why this matters

## Quick comparison

| Method | Best for | Not good for |
| --- | --- | --- |
| Example method | Example use | Example limit |

## How it works

## What it is useful for

## A concrete example

## What it cannot tell you

## A practical workflow

## Where AYA fits

## FAQ

### Question written in the way a buyer or AI answer engine would ask it?

Short, direct answer.

## Related reading

- [Relevant internal article](/resources/relevant-slug)

## Want to explore this in practice?

Calm CTA linking to [Ask Your Audience](https://www.askyouraudience.ai).
```

Not every article needs every heading in exactly that order. The structure should serve the search intent. But every strong article should include:

- a short answer near the top
- key takeaways
- at least one extractable table
- one concrete example
- a clear limits section
- a stronger `Where AYA fits` section
- an FAQ section
- related internal links
- the calm AYA CTA

## 4. How to write the opening

Start with the buyer's problem, not with a dictionary definition.

Weak:

> AI focus groups are an emerging research method.

Stronger:

> Teams often make expensive creative, product, and messaging decisions with too little audience input.

Then answer the query quickly.

The first 100 words should make the page easy for Google, AI Overviews, Perplexity, ChatGPT Search, and a busy buyer to understand.

## 5. Key takeaways section

Every article should include `## Key takeaways` near the top.

Use four bullets.

The bullets should usually cover:

- what the thing is
- what it is useful for
- what it should not be overclaimed to do
- where AYA's method or buyer value fits

Example:

```md
## Key takeaways

- An AI focus group is a structured way to test ideas with modeled audience participants.
- It is useful for early concept testing, message testing, campaign route comparison, and likely objection finding.
- It should be treated as directional decision support, not proof of real market behavior.
- The difference between useful AI research and generic prompting is the quality of the audience model, stimulus, questions, and interpretation.
```

## 6. Tables and answer-engine structure

AI answer engines prefer structured information.

Use tables for:

- method comparisons
- use case comparisons
- "can help with" vs "cannot prove"
- workflow steps
- template fields
- buyer decision rules

Good table formats:

```md
| Method | Best for | Not good for |
| --- | --- | --- |
| AI focus group | Early directional feedback | Final proof |
| Traditional focus group | Direct human discussion | Fast iteration |
```

```md
| Use case | What AI research can help with | What still needs validation |
| --- | --- | --- |
| Pitch route comparison | Identify clearer, weaker, and more believable routes | Client or human evidence for high-stakes decisions |
```

Keep tables simple. A table should clarify the answer, not become a spreadsheet.

## 7. Concrete examples

Every article should include one example that makes the use case feel real.

A good example includes:

- input
- audience
- what was compared
- what the output might show
- how the team should use the result

Example:

```md
Imagine a team testing three campaign routes for a discount retailer.

- Input: three campaign routes built around price, family value, and convenience
- Audience: German millennial parents and French budget-conscious shoppers
- Questions: which route is clearest, which feels believable, and what proof each audience needs
- Output: Route B is easiest to understand, Route C has more emotion but needs proof, and Route A is too generic
```

The example should never imply that AYA proves market truth. It should show how AYA improves the next decision.

## 8. The stronger AYA section

The `Where AYA fits` section should not be a soft product mention.

It should explain why AYA is better than generic AI prompting for the specific job of the article.

Core distinction:

> Generic AI prompting gives you a simulated opinion. AYA gives you a structured audience-testing workflow: defined audience models, controlled stimuli, consistent evaluation criteria, comparison across routes, and interpretation designed for decision-making.

Adapt this idea to the article.

For an agency article, emphasize route comparison and pitch confidence.

For a product article, emphasize reducing build risk before the team commits.

For GDPR or trust articles, emphasize clear data handling, method limits, and human review.

For templates, emphasize turning the template into a repeatable testing workflow.

## 9. FAQ section

Every article should include `## FAQ` before related reading.

FAQ questions should be written like real search and AI-answer queries.

Use five to eight questions for major definition, comparison, and trust articles. Use four to five for narrower practical articles.

Good question types:

- What is [topic]?
- How does [topic] work?
- Is [topic] accurate?
- Can [topic] replace [traditional method]?
- What is the difference between [A] and [B]?
- When should you use [topic]?
- What is [topic] bad at?
- Is [topic] GDPR-friendly?
- How do you test [specific thing] before [expensive commitment]?

Answers should be short, direct, and careful.

## 10. Internal linking rules

Internal links should use `/resources/<slug>`.

Every article should link to:

- one category foundation article
- one relevant comparison or trust article
- one practical workflow or template article
- one adjacent demand-capture article where natural

Do not force too many links. Four to six related links is usually enough.

When publishing a new article, also consider whether older related articles should link back to it.

## 11. Image rules

Use Pexels image URLs directly for now.

Every image needs:

- specific alt text
- the image URL in Markdown
- a credit line directly underneath

Format:

```md
![Specific descriptive image alt text](https://images.pexels.com/...)

*Photo by [Creator on Pexels](https://www.pexels.com/photo/.../).*
```

Avoid using generic office photos too often.

Preferred themes:

- AI focus groups: research board, group discussion, digital interview screen
- concept testing: sticky notes, sketches, product prototypes, testing material
- ad testing: campaign planning desk, creative routes, media board
- Malta articles: Malta business, city, startup, or professional context
- UK and USA articles: agency planning, startup team, product sprint
- Netherlands and Germany articles: clean EU business, data, privacy, responsible technology
- GDPR and trust articles: data privacy, secure workflow, governance
- templates: checklist, planning worksheet, desk

## 12. Voice rules

Write like a sharp strategist, not an SEO content farm.

Do:

- answer early
- use short paragraphs
- be commercially practical
- explain limits honestly
- use specific examples
- make AYA feel method-led and useful
- keep the language simple

Do not:

- hype the category
- imply AI replaces all human research
- claim certainty
- use unsupported statistics
- stuff keywords
- repeat the same paragraph across articles
- write vague AI thought leadership
- use broken or awkward SEO phrasing

Avoid phrases like:

- "in today's fast-paced world"
- "game-changing"
- "revolutionary"
- "unlock unparalleled insights"
- "guaranteed market truth"
- "AI replaces traditional research"

## 13. Article quality checklist

Before committing a new article, check:

- Root-level article files have Hashnode front matter.
- Internal working files are in `hashnode-drafts/`.
- Drafts keep `saveAsDraft: true` unless intentionally publishing.
- Slug matches filename.
- `seoTitle` and `seoDescription` are present.
- The first 100 words answer the query.
- `## Key takeaways` exists.
- At least one useful table exists.
- One concrete example exists.
- Limits are explained responsibly.
- `## Where AYA fits` is commercially useful.
- `## FAQ` exists.
- Internal links use `/resources/<slug>`.
- Internal links point to existing or newly planned slugs.
- Pexels image and credit are present.
- No unsupported statistics.
- No overclaims.
- Markdown formatting is clean.

## 14. Strategic standard

The goal is not to produce more blog posts.

The goal is to build the most useful, credible resource library in the AI audience research category.

Each article should make AYA feel:

- clearer than generic AI tools
- more practical than abstract AI thought leadership
- more responsible than hype-heavy competitors
- faster and more accessible than traditional research alone

The bar:

> The article should be useful even if the reader does not buy today, and commercially sharp enough that the right reader understands why AYA exists.
