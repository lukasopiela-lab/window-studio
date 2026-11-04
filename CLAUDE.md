# WINDOW STUDIO – project handoff

Premium website + customer platform for a Slovak company that sells and installs DRUTEX windows and doors.
Working name: **WINDOW STUDIO** (name, logo, company details must stay editable).

The full brief is in `docs/master-prompt.md`. Research findings are in `docs/drutex-research.md`.
Read both before starting work.

## Language
- Talk to the user in **Slovak**.
- All website content (public pages, forms, admin panel) in natural Slovak.
- Code, identifiers and comments in English.

## Decisions already made with the user
- Stack: Next.js (App Router) + TypeScript + React + Tailwind CSS + Supabase (DB, auth, storage, RLS). Deploy target: Vercel free tier.
- Supabase: the user has no project yet. Write the schema, RLS policies and setup steps now; the site must run without Supabase keys (fall back to local seed data, clearly marked as sample data) until keys are added in `.env.local`.
- Delivery: this GitHub repo (`lukasopiela-lab/window-studio`). Commit and push after each phase.
- Pacing: **phase by phase**. Finish a phase, test it (build, run, check in a browser at desktop and mobile widths), report to the user in Slovak (done / works / needs configuration / next phase), then wait for approval before the next phase.
- No invented prices, specs, company details, reviews, warranty terms or integrations. Unknown → editable field. Prices show „Cena na vyžiadanie“ until the admin configures a price list.
- Paid services (image-editing API for the visualizer, LLM API for the assistant) are built as modular integrations, switched off until a key is added. Never claim an image was generated when it was not.
- Emails: Resend free tier, connected later.

## Design direction (proposed, not yet reviewed by the user)
- Palette: White #FFFFFF, Mist #EDEFEE, Stone #8B9196, Graphite #2E3236, Charcoal #1A1C1E, accent "Glass edge" #3F7F74 (the green tint on the edge of float glass).
- Type: Archivo (variable width, latin-ext for Slovak diacritics). Expanded widths for headlines, normal width for body.
- Signature element: the hero photo divided by a window frame / mullion grid. Everything else quiet and left-aligned.
- No product photos from drutex.eu until the user has written permission from DRUTEX. Image slots stay replaceable in the admin panel.

## Next step
Phase 1 – Foundation: project scaffold, design system, navigation, homepage, responsive layout, product catalogue structure seeded from `docs/drutex-research.md`, and the full Supabase schema (covering all later phases).
