# Claude-Grade Frontend Design Vault for Gemini

![Repository Showcase Architecture](https://github.com/Vasiliy-katsyka/gemini-frontend-design/blob/main/assets/showcase.png?raw=true)

> **Transform Google Gemini into a world-class Frontend Engineer and UI/UX Architect.**  
> Inject Anthropic’s official `frontend-design` aesthetic engine + 70+ production-grade design systems and editorial references directly into Gemini's context window.

---

## 🎨 Overview

By default, LLMs tend to generate **"AI slop"**:
- Identical 8px-rounded cards with soft gray drop shadows
- Centered heroes with purple-to-blue linear gradients
- System fonts (Inter / Roboto) with zero typographic tension
- Predictable 3-column feature grids and generic hover scales

This vault eliminates those defaults. By grounding Gemini in Anthropic's battle-tested `frontend-design` instruction set alongside real design tokens from industry leaders (Linear, Stripe, Apple, A24, Nothing Tech), you force the model to write **distinctive, opinionated, production-ready frontend code**.

```
                           ┌───────────────────────────────┐
                           │ Anthropic frontend-design     │
                           │ Visual Craft & Restraint Rules│
                           └───────────────┬───────────────┘
                                           │
                                           ▼
┌──────────────────────────────┐   ┌───────────────────────────────┐
│  58+ Commercial Brands       │   │  Curated Editorial & Studios  │
│  (Linear, Stripe, Apple,     │ + │  (A24, Dinamo, Nothing Tech,  │
│   Vercel, Supabase, Tesla)   │   │   Basement Studio, Cosmos)    │
└──────────────┬───────────────┘   └───────────────┬───────────────┘
               │                                   │
               └─────────────────┬─────────────────┘
                                 │
                                 ▼
                 ┌───────────────────────────────┐
                 │    Master Gemini Bundles      │
                 │   (Drop into AI Studio / Gem) │
                 └───────────────┬───────────────┘
                                 │
                                 ▼
          ┌──────────────────────────────────────────────┐
          │ Production UI with Taste, Mechanical Feel,   │
          │ Sticky Reveal Scroll, and Expressive Type    │
          └──────────────────────────────────────────────┘
```

---

## 🚀 Recommended Gemini Models

Use the largest context window and highest-reasoning models available in [Google AI Studio](https://aistudio.google.com):

| Tier | Recommended Model | Best Use Case |
| :--- | :--- | :--- |
| **Flagship / Complex UI** | **Gemini Pro (Latest / Experimental)** | Complex web apps, stateful interactive dashboards, full page builds |
| **High Speed / Prototyping** | **Gemini Flash (Latest / Thinking)** | Rapid component generation, micro-interactions, responsive variants |
| **Consumer Web** | **Gemini Advanced (Custom Gems)** | Conversational UI iteration, component inspection, quick styling |

*(Thanks to Gemini's 1M–2M+ token window, you can paste the entire combined bundle into System Instructions with near-zero latency impact).*

---

## ⚡ Quick Start: 3 Ways to Use This Vault

### Method 1: Google AI Studio (Maximum Power)

1. Open [Google AI Studio](https://aistudio.google.com).
2. Create a new prompt and select your target model (e.g., Gemini Pro / Flash).
3. Open the **System Instructions** drawer on the left/top.
4. Copy and paste the contents of either:
   - `bundles/gemini-frontend-brands.md` (for tech, SaaS, developer tools, and fintech)
   - `bundles/gemini-frontend-curated.md` (for creative agencies, film, brutalist, and luxury editorial)
5. Set **Temperature** to `0.7` (encourages aesthetic variety while keeping code deterministic).
6. Enter your prompt:
   > *"Build a real-time observability dashboard for microservices. Style it strictly following the Linear design system. Implement sticky timeline inspection and subtle spring transitions using Tailwind CSS and Lucide icons."*

---

### Method 2: Custom Gem (Gemini Web App)

1. Navigate to [Gemini](https://gemini.google.com) → **Gems Manager** → **New Gem**.
2. **Name:** `Frontend Design Architect`
3. **Instructions:** Copy and paste the raw content of [`skills/frontend-design.md`](./skills/frontend-design.md).
4. When prompting the Gem, attach or paste an individual design spec from `brands/` or `curated/`:
   > *"Using the attached `brands/stripe.md` design spec, create a pricing card with a dynamic currency switcher."*

---

### Method 3: Gemini API & Context Caching (Developers)

Leverage context caching so you only pay for reading the bundle once:

```python
import os
from google import genai
from google.genai import types

client = genai.Client(api_key=os.environ["GEMINI_API_KEY"])

# Read the curated master bundle
with open("bundles/gemini-frontend-curated.md", "r") as f:
    system_instruction = f.read()

# Create cached session
response = client.models.generate_content(
    model="gemini-2.5-pro", # or latest Gemini Pro / Flash
    contents="Create a high-impact hero section for a boutique architecture firm.",
    config=types.GenerateContentConfig(
        system_instruction=system_instruction,
        temperature=0.7,
    )
)

print(response.text)
```

---

## 📁 Repository Structure

```tree
├── README.md
├── skills/
│   └── frontend-design.md       # The foundational Anthropic design craft skill
├── bundles/
│   ├── gemini-frontend-brands.md   # Claude Skill + 58 tech & consumer brands
│   └── gemini-frontend-curated.md  # Claude Skill + 18 world-class creative studios
├── brands/                      # Individual token & styling specs (58 files)
│   ├── linear.md                # Ultra-minimal, dark void, purple glow, keyboard-first
│   ├── stripe.md                # Multi-stop mesh gradients, weight-300 elegance
│   ├── apple.md                 # SF Pro typography, massive whitespace, hardware-feel
│   ├── vercel.md                # Monospaced data, crisp borders, Geist font
│   ├── supabase.md              # Emerald green, high-density developer aesthetic
│   ├── tesla.md                 # Radical subtraction, full-bleed imagery
│   └── ... (50+ more)
└── curated/                     # Award-winning web & editorial references
    ├── aaa24.a24films.com.md    # Editorial brutalism, cinematic serif typography
    ├── nothing.tech.md          # Teenage Engineering retro-futurism & dot-matrix
    ├── basement.studio.md       # High-craft WebGL, interactive micro-states
    ├── abcdinamo.com.md         # Avant-garde Swiss typography and grids
    ├── cosmos.so.md             # Tactile curation, fluid masonry layouts
    └── ... (13+ more)
```

---

## 🎯 What Changes in Gemini's Code Output?

| Aesthetic Axis | Default Gemini Output | With This Vault Injected |
| :--- | :--- | :--- |
| **Typography** | Generic sans-serif (`Inter`, `system-ui`) | Expressive pairings (e.g., `Syne` display + `Geist` body, or `DM Serif` + `Space Grotesk`) |
| **Color Schemes** | Flat purple/indigo gradients on `#0F172A` | Deep contrast ratios, rich dark canvas tokens (`#08090A`), deliberate accents |
| **Page Layout** | Centered hero with 3 identical cards below | Asymmetrical grids, sticky side-column reveals, split viewports |
| **Motion** | Scattered fade-and-slide on every DOM node | Single orchestrated page reveal, dampened spring curves (`cubic-bezier(0.16, 1, 0.3, 1)`) |
| **Scroll Experience**| Standard vertical scroll | Native CSS scroll-driven reveals (`animation-timeline: view()`), sticky card pinning |
| **Copy & Tone** | Corporate filler ("Empowering your workflow") | Actionable, user-focused verbs ("Inspect traces", "Fork sandbox") |

---

## 💡 Prompting Cheat Sheet

Copy and append these directives to your prompts for instant specialized aesthetics:

### 1. The "Linear" Dark-Mode Mechanical Feel
```text
Style strictly using the Linear design spec. Use ultra-fine borders (rgba(255,255,255,0.08)), 
void-black background (#08090A), deep violet accent, and high data density. Include keyboard shortcuts badges (Kbd).
```

### 2. The "A24 / Dinamo" High-Craft Editorial
```text
Design using the aaa24.a24films.com reference. Use an oversized serif headline, wide tracking on uppercase metadata, 
asymmetrical split layout, and a stark monochromatic palette with zero border radius.
```

### 3. The "Basement Studio" Interactive Experience
```text
Apply the basement.studio specification. Implement sticky section pinning, spring-dampened hover states on interactive cards, 
and modern CSS scroll-driven opacity transitions (animation-timeline: view()).
```

---

## 🤝 Contributing & License

- **Skill Prompt:** Derived from Anthropic's open-source frontend-design skill (Apache 2.0).
- **Design Tokens:** Extracted and open-sourced under MIT by the design engineering community.
- Pull requests adding new `DESIGN.md` specs for emerging web experiences are welcome!
