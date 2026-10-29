# Operant Health help center

Customer-facing help for clinic staff (office manager, front desk, medical
assistant, provider). Built on [Mintlify](https://mintlify.com): MDX pages with
YAML frontmatter, configuration in `docs.json`. Preview with `npx mint dev`
and check links with `npx mint broken-links`.

## Terminology

- **Operant Health** is the company and the name of this help center.
- **OrthOS** is the name the iPhone and iPad app shows today (home screen,
  sign-in screen, iOS Settings). Use it wherever the reader needs to match
  what's on screen. When the app is renamed, replace it across every page.
- "Note" in prose; **Report** only where the UI says it (the **Reports** tab,
  **Generate report**).
- "Practice", not "clinic" or "organization".

## Accuracy rules

- Every UI label in bold must match the app exactly. Check the app's source
  before adding or changing a step. If you can't confirm a label, leave the
  step out.
- Document only what a new practice gets on day one. No roadmap, "coming
  soon", or features that are switched off by default.
- No security or compliance claims (HIPAA, BAA, SOC 2, encryption specifics)
  unless the founder has confirmed them in writing.
- Screenshots come from the demo environment only. Never show real patient
  data.
- When a product change alters what users see or do, update the matching page
  and merge it once the change reaches production.

## Style

- Second person, active voice, sentence-case headings.
- Terse: one idea per sentence, steps over paragraphs.
- Bold for UI elements: tap **Save**.
- Lead with what the reader is trying to do, not with how the product works.
