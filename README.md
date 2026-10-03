# Claude-Grade Frontend Design Vault for Gemini

Turn Google Gemini into a top-tier frontend designer and UI architect.

This repository combines:
1. **Anthropic's official `frontend-design` `SKILL.md`** (the system prompt Claude uses to avoid generic "AI slop" and centered purple-gradient cards).
2. **58+ Brand `DESIGN.md` specs** (Linear, Stripe, Apple, Vercel, Supabase, Tesla, etc.).
3. **Curated High-Aesthetic Site Designs** (A24, Dinamo, Nothing Tech, Basement Studio, Cosmos, Are.na).

---

## ⚡ Quick Start: How to use with Gemini

### Option 1: Gemini Web / Custom Gem
1. In Google Gemini, go to **Gems Manager → New Gem**.
2. Name it: `Claude-Grade UI Architect`.
3. In **Instructions**, copy and paste the contents of `skills/frontend-design.md`.
4. Whenever you need a specific brand aesthetic (e.g., Stripe, Linear, or A24), attach or paste the relevant file from `brands/` or `curated/`.

### Option 2: Google AI Studio (Recommended for Full Power)
1. Open [Google AI Studio](https://aistudio.google.com).
2. Select **Gemini 1.5 Pro** or **Gemini 2.0 Pro Experimental**.
3. Under **System Instructions**, paste the contents of:
   * `bundles/gemini-frontend-brands.md` (to give Gemini complete knowledge of 58 design systems).
   * Or `bundles/gemini-frontend-curated.md` (for studio/editorial level craft).
4. Prompt Gemini:
   > *"Build a modern real-time monitoring dashboard following the Linear design system with Tailwind CSS."*

---

## 📁 Repository Structure
- `skills/frontend-design.md`: The unadulterated Anthropic visual craft skill.
- `brands/`: 58 individual brand `DESIGN.md` specs.
- `curated/`: Editorial and studio design specifications.
- `bundles/`:
  - `gemini-frontend-brands.md`: Claude Skill + 58 Brand Systems combined into a single file.
  - `gemini-frontend-curated.md`: Claude Skill + Curated Visual Standards combined into a single file.
