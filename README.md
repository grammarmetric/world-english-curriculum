# World English Curriculum — Parent Guide

A single, self-contained parent-facing page laying out GrammarMetric's 12-week
English programme built on **Cambridge Primary World English, Stage 5**
(Hodder Education, endorsed by Cambridge Assessment International Education).

Live: https://grammarmetric.github.io/world-english-curriculum/

## What this is

Plain-language, week-by-week walkthrough of what a child learns in the
programme, how the weekly GrammarMetric web-app homework connects to it, and
the three points in the term (weeks 1, 6, 12) where parents get a progress
check-in. No login, no build step — one HTML file.

The week-by-week content is drawn from the real Stage 5 Learner's Book table
of contents (Welcome + Units 1–9: Feeling good!, You are what you eat and do,
Ancient buildings, Great stories, Be an eco-hero, Travel zone, Bake off, Red
Alert, Explorers through time), with the book's own built-in review spreads
(after Units 3, 6, 9) used as the term's three progress-review points, plus a
project-showcase week, a review week, and a final assessment week to round
out 12 weeks.

## Styling

Built on GrammarMetric's "ELECTRIC" design system (dark-mode default, Lexend
type, single lead accent per page — here, orange). Tokens are ported and
inlined directly into `index.html` rather than linked to
`grammarmetric.com/shared.css`, matching this repo's no-build,
single-file convention.

## Structure

```
index.html   — the entire page (styles, content, and theme-toggle script inline)
```

## Deploy

GitHub Pages, served from `main` / `/` (root). Push to `main` and it's live.

## Notes for whoever edits this next

- The exact grammar focus for weeks 2, 4, 5, 7, 8, and 9 is described in
  general, parent-friendly terms (topics and skills, not precise tense
  labels) because only Unit 1's grammar point was directly confirmed against
  the book; Units 2–9 are topic-led descriptions. Check the Teacher's Guide
  before quoting a specific grammar point to a parent.
- No pricing, teacher names, or contact details are included — point parents
  to grammarmetric.com or the enrolling teacher for those.
