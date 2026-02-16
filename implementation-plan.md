You are my coding assistant. Help me implement an MVP for a Pattern Library built with Next.js. I want clean, scalable, and production-ready code. Follow these steps:

1. Project Setup

Initialize a new Next.js 14 project using the App Router and TypeScript.

Install and configure TailwindCSS for styling.

Add shadcn/ui for ready-to-use UI components.

Set up eslint + prettier for code quality.

Host the project on Vercel (give me deploy instructions).

2. One-Page Layout

Build a one-page layout with these sections:

Navbar → logo + nav links (Home, Categories, About, GitHub).

Hero Section → headline, subheadline, CTA button.

Categories Grid → show 3–4 categories (e.g., Hero, Features, Pricing, Testimonials).

Featured Patterns → show 3 example sections with a preview + "Copy Code" button.

CTA Banner → "Contribute on GitHub" or "Request a Pattern".

Footer → copyright + social links.

3. Pattern Components

Create a folder /patterns/ where each pattern is a reusable React component.

Example: /patterns/hero/HeroOne.tsx, /patterns/pricing/PricingOne.tsx.

Each pattern should have:

A preview section (styled with Tailwind).

A copy-to-clipboard button that shows the code.

4. Categories System

Hardcode categories at first (Hero, Pricing, Features, Testimonials).

Later, make categories and patterns dynamically fetched from a JSON file in /data/patterns.json.

Each entry in JSON has:

{
  "id": "hero-one",
  "category": "Hero",
  "title": "Hero Section One",
  "componentPath": "/patterns/hero/HeroOne.tsx"
}

5. Open Source Ready

Add a README.md explaining the project.

Add CONTRIBUTING.md for contributors.

Add MIT License.

6. Future Enhancements (not MVP, just plan ahead)

Add search bar to filter patterns.

Add dark mode toggle.

Add copy as JSX/TSX and copy as HTML options.

Store patterns in a database later (SQLite or Supabase).