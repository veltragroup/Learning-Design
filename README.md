# Learning Design — Ben McNamara

Portfolio of digital learning work — from standards-compliant SCORM e-learning
to the full-stack products behind it.

## Flagship product
- **CapabilityOS** — an AI-native capability platform (SaaS) for Salesforce and tech
  consultancies. Firms upload role descriptions and process docs, and one AI generation
  pass produces a complete capability system: role matrix, 30/60/90-day pathway, AI
  adoption playbook, assessments, manager coaching guide and a capability dashboard.
  Built with Next.js 15, TypeScript, Supabase (Postgres + multi-tenant RLS), an
  LLM generation engine with structured output, and Stripe subscription billing.

## Selected e-learning work (SCORM 1.2)
- **Delivery KPIs & Performance Review Framework** — interactive enablement microsite with a live score simulator and knowledge check.
- **Psychosocial Hazards Learning Path** — curated, multi-tier WHS learning path with an 80% mastery gate and resume-on-return.
- **8Squad Design System** — the tokenised visual system behind the courses.

The portfolio site is a single, self-contained `index.html` — no build step, no
dependencies — suitable for static hosting (e.g. Vercel).
