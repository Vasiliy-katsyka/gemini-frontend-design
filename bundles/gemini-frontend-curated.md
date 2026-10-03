---
name: frontend-design
description: Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making choices that don't read as templated defaults.
---

# Frontend Design

Approach this as the design lead at a design studio known for giving every client a distinct visual identity that is not mistaken for anyone else's. This client has already rejected proposals that felt cliché or templated, and is paying for a distinctive point of view: make deliberate, opinionated choices about palette, typography, and layout that are specific to this brief, and take aesthetic risk if justified.

## Ground your designs in the subject matter
If the brief does not identify what the product or subject matter is, identify it yourself before designing, and confirm with the client. You can come up with one concrete subject, the design's audience, and the design's primary job, as a proposal. The subject's industry, subject matter, materials, and vernacular are where distinctive visual choices come from. Build with the brief's real content and subject matter throughout.

## Design principles
- Hero: Open with the most characteristic thing in the subject's world: a headline, an image, an animation, a live demo, an interactive moment. Avoid the default "big number with a small label, supporting stats, and gradient wash".
- Typography: Typography carries the personality of the page. Choose typefaces deliberately. Avoid accenting just a single word in a headline (italic/bold/different color), all-caps labels, or unnecessary typographic eyebrows above content.
- Visual structure is information: Use borders, rules, and dividing lines intentionally. Only use numbered sequences (01 / 02 / 03) if the content actually is sequential.
- Motion: Use non-user-triggered motion sparingly. A single orchestrated entrance lands better than scattered hover transitions on every card.
- Tone & Copy: Plain verbs, sentence case, no filler. CTAs say exactly what happens: "Save changes", not "Submit".

## Defaults to strictly avoid:
1. Warm cream background (#F4F1EA) with serif display and terracotta/warm-clay accent.
2. Near-black background with a single bright acid-green or vermilion accent.
3. The SaaS-card kit: content chopped into identical rounded cards with identical soft gray shadows (rgba(0,0,0,.1)).
4. Tracked-out ALL-CAPS eyebrow labels above every heading.


# Curated High-Craft Visual Design References
Use these cutting-edge website design specifications to elevate UI craft, typography, and mood:


---
# Design Reference: AAA24.A24FILMS.COM
---

# How aaa24.a24films.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/aaa24.a24films.com-design)

Last updated: 2026-08-03

## Captured pages

[![Membership hero with huge price figures and benefit tiles](https://pin.fontofweb.com/6379?format=jpg)](https://design.withfudge.com/share/pin-6379)

[Membership hero with huge price figures and benefit tiles](https://design.withfudge.com/share/pin-6379)

[![Black FAQ page with left title rail and tall article stack](https://pin.fontofweb.com/6576?format=jpg)](https://design.withfudge.com/share/pin-6576)

[Black FAQ page with left title rail and tall article stack](https://design.withfudge.com/share/pin-6576)

[![Split account form with oversized JOIN rail and proceed bar](https://pin.fontofweb.com/6383?format=jpg)](https://design.withfudge.com/share/pin-6383)

[Split account form with oversized JOIN rail and proceed bar](https://design.withfudge.com/share/pin-6383)

[![Coral 404 landscape with wireframe floor and giant text](https://pin.fontofweb.com/6384?format=jpg)](https://design.withfudge.com/share/pin-6384)

[Coral 404 landscape with wireframe floor and giant text](https://design.withfudge.com/share/pin-6384)

[![Warm paper footer with four columns and fine legal text](https://pin.fontofweb.com/6577?format=jpg)](https://design.withfudge.com/share/pin-6577)

[Warm paper footer with four columns and fine legal text](https://design.withfudge.com/share/pin-6577)

## Overview

AAA24 is designed like a membership brochure that keeps turning into a utility interface. The dominant mood is severe and controlled: near-black content pages, warm paper footers, thin rules, and large Nb International Pro type that carries most of the personality. The system feels less like a glossy subscription funnel and more like an editorial film club with a strict grid.

The page family moves between two clear modes. On dark surfaces, white text, muted gray labels, and the coral accent hold the hierarchy. On paper surfaces, black text and the A24 mark take over, while the overall tone softens without becoming decorative. That flip gives the site its rhythm: black for actions, forms, FAQs, and error states; paper for the footer and legal endcap.

The visual hierarchy is simple and forceful. Big titles sit alone. Supporting copy stays narrow and quiet. Dividers do more work than containers. The result is a brand language built from contrast, spacing, and scale rather than from color variety or surface effects.

## Colors

The palette is small and disciplined. Black and near-black form the main stage. Warm paper softens the footer and the membership end of the journey. Gray handles hierarchy, while coral is reserved for a strong signal on the 404 page and other clearly marked emphasis.

| token | value | role |
|---|---|---|
| `action` | `#F95936` | Coral signal color for the error page and the loudest primary emphasis |
| `ink` | `#000000` | Brand mark, footer text, and dark-on-light copy |
| `muted-ink` | `#837E77` | Primary secondary text on paper and quiet utility text |
| `helper-ink` | `#83887C` | Page titles, subheads, and thin supporting labels on dark fields |
| `paper` | `#F5F1EA` | Main warm page ground for the footer and light utility surfaces |
| `paper-soft` | `#F1F1F1` | Pale button fill and light text-on-dark contrast value |
| `surface-dark` | `#0E0D0D` | Main dark panel tone for membership, FAQ, and account pages |
| `surface-deep` | `#000000` | Deepest black used for the page field and utility strips |
| `on-dark` | `#F1F1F1` | Primary text and button fill on black surfaces |
| `paper-muted` | `#9FA595` | Faint legal copy, subtle labels, and low-priority footer text |

The relationship between modes is the key color story. Dark screens are almost monochrome, with the accent held back until it is needed. The paper footer is not bright white; it keeps the page warm and slightly aged. Gray never turns cold or bluish, so the whole system stays in the same tonal family even as it switches surfaces. There are no visible gradients or decorative shadows doing hierarchy work. Flat fills, thin rules, and contrast do the job directly.

## Typography

Most supplied pages use **Nb International Pro** as their primary family. The 404 treatment also includes a distinct mono-styled cut in its oversized numerals, so keep that display treatment separate from the regular text system. The hierarchy depends on size, tracking, and placement more than on weight changes. Most visible text is Regular. Font licensing was not supplied; confirm reuse before publishing.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| `page-hero` | Nb International Pro | 18.781rem | 400 | 0.80 | -0.029em | Oversized utility numerals and the most extreme headline treatment |
| `membership-hero` | Nb International Pro | 10.8rem | 400 | 0.80 | -0.140em | The giant JOIN and membership headline scale |
| `section-display` | Nb International Pro | 6.425rem | 400 | 0.81 | -0.045em | Large FAQ section labels and major black-page headings |
| `card-display` | Nb International Pro | 4.5rem | 400 | 0.81 | -0.045em | Large plan, price, and utility callouts on dark panels |
| `article-heading` | Nb International Pro | 2.25rem | 400 | 0.92 | -0.045em | FAQ questions and smaller dark-page subheads |
| `body-strong` | Nb International Pro | 1.2rem | 400 | 1.20 | -0.010em | Short explanatory copy on the account and membership pages |
| `body` | Nb International Pro | 1.05rem | 400 | 1.33 | -0.010em | FAQ answers, supporting paragraphs, and form help text |
| `label` | Nb International Pro | 0.875rem | 400 | 1.33 | 0.005em | Top navigation, form labels, and small footer links |
| `meta` | Nb International Pro | 0.825rem | 400 | 1.20 | 0.015em | Footer columns, legal copy, and the smallest non-legal utility text |
| `micro` | Nb International Pro | 0.6875rem | 400 | 1.20 | 0.015em | Tiny legal lines and the quietest footer annotations |

The typography story is about restraint at small sizes and force at large sizes. The biggest headings are almost poster-like: very tight leading, negative tracking, and no decorative weight tricks. The smaller labels stay readable because they keep generous line-height and avoid crowding the rules around them. Keep the mono-styled 404 numerals as an isolated display treatment rather than allowing it to spread through the interface.

## Layout

The layout is driven by rails and fields. On the FAQ pages, a left-side title rail sits beside a ruled content column. On the account screens, the same split becomes a form zone: a large left keyword, a right content column, and a single field that sits in an otherwise empty black field. The membership page expands that same logic into a wide hero, a pricing cluster, and a grid of benefit tiles below.

Spacing is broad, not airy. There is a lot of blank black or paper ground around the content, but the rhythm comes from measured resets rather than random whitespace. The visible spacing tokens support that: a small page gutter, a clear column-rule gap, larger section gaps, and a much taller offset before the main content begins. Thin vertical lines often stand in for boxes; they divide columns without adding weight.

The footer changes the layout grammar again. It becomes a low-profile paper band with several narrow columns, all aligned to the same baseline and held apart by hairline dividers. The A24 mark anchors the far left, then the content fans out into link groups and legal text. Nothing is centered for comfort; the whole system prefers alignment, edge control, and a sharp sense of structure.

The 404 page is the most theatrical layout in the set. It keeps the same dark ground, but the composition becomes graphic rather than editorial: a huge coral message, a wireframe horizon, and a strong sense of depth created through line work instead of shadow. It is still the same system, just pushed to a more dramatic end.

## Visual language

AAA24 combines three visual registers. The first is editorial utility: FAQ pages, account forms, and legal footers that rely on sober grids and small text. The second is membership spectacle: giant headlines, price figures, and a benefit grid that turns the subscription into a staged offer. The third is error-page drama: the 404 screen uses coral, wireframe perspective, and oversized type to make a failure state feel branded rather than generic.

The system avoids softness. Corners stay square or nearly square. Borders stay hairline-thin. Shadows are absent as a rule. The pages do not feel pillowy or app-like; they feel printed, framed, and set against a stage. That same discipline keeps the coral accent powerful. Because the accent is rare, it reads immediately when it appears.

A24 also uses scale as a visual texture. Some screens are almost all typography, with words acting like architectural elements. Others use image tiles or graphic blocks to break the black field. In every case, the composition leaves enough open area for the type to breathe. The negative space is not empty; it is part of the brand tone.

## Components

### Header

- **Anatomy:** Small AAA24 wordmark on the left, compact utility links on the right, with occasional slash separators.
- **Surface:** Transparent on dark pages; paper on the footer page.
- **Typography:** Small caps-feeling label size, usually around 13px to 15.6px.
- **Shape:** No boxed chrome. The bar is defined by placement and spacing, not by panels.
- **Composition:** Keep the header visually light so it does not compete with the giant page titles below it.

### FAQ rail and article column

- **Anatomy:** A large left rail title, a thin vertical divider, and a stacked right column of section heads, questions, and answers.
- **Surface:** Pure black field with white text and gray accents.
- **Typography:** Section labels are large and compact; questions are smaller but still assertive, often around 36px and 54px scale.
- **Spacing:** Wide top offset, then clear separation between topic groups; paragraphs sit with enough breathing room to stay readable.
- **Visible states:** Inline links in answers stay understated and rely on underlining rather than a loud color shift.

### Membership hero

- **Anatomy:** A giant invitation line, a price cluster, a short supporting sentence, and a grid of benefit images or tiles beneath.
- **Surface:** Black with bright text and coral emphasis when needed.
- **Typography:** The hero line uses the biggest scale in the system, with prices and percentage figures pulling from the same oversized family.
- **Composition:** Keep the price block separated from the invitation text so the message reads in one glance.
- **Visible states:** Active or featured benefits can sit on a pale tile, but the surrounding system remains dark and controlled.

### Account form

- **Anatomy:** Left-side JOIN marker, right-side form panel, one email field, and a full-width proceed bar at the bottom.
- **Surface:** Black field with a pale footer button.
- **Typography:** Large headline, then a short explanatory line, then smaller form label and placeholder text.
- **Shape:** The field is underlined rather than boxed; the button is a flat rectangle with no soft rounding.
- **Composition:** Keep the form sparse. The page works because it gives the user very little to look at besides the title and the entry field.

### Footer

- **Anatomy:** A24 mark, AAA24 links, More A24 links, social links, and a legal column.
- **Surface:** Warm paper ground with fine vertical rules.
- **Typography:** Small label text in the link columns, with even smaller legal copy in the far-right block.
- **Spacing:** Wide column spacing and restrained internal padding.
- **Composition:** Treat the footer as a calibrated information band, not as a generic site-end panel.

### Error stage

- **Anatomy:** Oversized coral 404 language, a wireframe floor, and a dark skyline of line work.
- **Surface:** Deep black with coral text and highlights.
- **Typography:** Extremely large display type that dominates the frame.
- **Composition:** Use the graphic field as the main statement and keep utility links tiny and out of the way.
- **Visible states:** The page leans into the failure state instead of hiding it; the styling keeps it unmistakably branded.

## Responsive behavior

The design should preserve the same reading order when it compresses: title rail first, content column second, footer links last. On narrower screens, the split layouts should stack without losing the thin-rule logic. The hero type can shrink, but the page still needs a very large first word or number so the membership tone survives. The footer should stay column-based as long as it can, then collapse into a readable list without changing the warm paper and black contrast.

The most important responsive rule is hierarchy, not exact sizing. Keep the large keyword or price visible before the supporting copy. Keep the form field obvious before the proceed button. Keep the FAQ questions in a clear single column rather than turning them into dense cards. The system works when the structure stays austere.

## Practical implementation guidance

### Preserve

- Keep the paper/black flip intact. It is the core rhythm of the system.
- Keep coral rare. It should feel like a signal, not a theme color.
- Keep the page edges hard and the borders thin.
- Keep the typography mostly Regular and let size do the hierarchy work.
- Keep large spans of empty field around the hero, FAQ, and account form.

### Avoid

- Avoid rounded cards, soft shadows, and glossy surface treatments.
- Avoid centered marketing copy that erases the left rail structure.
- Avoid multi-color UI chrome. The palette works because it is narrow.
- Avoid turning the footer into a social-media-style cluster of badges or buttons.
- Avoid overusing the coral accent in body copy or links.

### Recommended build order

1. Lock the black and paper surfaces.
2. Rebuild the type scale from the largest heading down to the legal text.
3. Add the thin-rule grid and left-right split layouts.
4. Build the FAQ column and the account form.
5. Add the membership hero and benefit grid.
6. Finish with the footer and the 404 treatment.

### Accessibility

- Keep contrast strong on both black and paper surfaces.
- Do not rely on coral alone to indicate a current or important state.
- Preserve visible focus rings on links, form fields, and the proceed button.
- Keep paragraph line-height generous enough to hold the FAQ answers comfortably.
- Make the smallest legal copy readable without changing the overall scale of the footer.

## Scope note

This guide covers the desktop membership, FAQ, account, 404, and footer surfaces for aaa24.a24films.com. It does not specify mobile breakpoints, hover or focus styling, motion, loading states, or exact account and subscription flow behavior.


---
# Design Reference: ABCDINAMO.COM
---

# How abcdinamo.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/abcdinamo.com-design)

Last updated: 2026-08-03

## Captured pages

[![Centered home stage with left section links and utility pills](https://pin.fontofweb.com/40?format=jpg)](https://design.withfudge.com/share/pin-40)

[Centered home stage with left section links and utility pills](https://design.withfudge.com/share/pin-40)

[![Quote and Buy hero with neon selector and stacked option panels](https://pin.fontofweb.com/8621?format=jpg)](https://design.withfudge.com/share/pin-8621)

[Quote and Buy hero with neon selector and stacked option panels](https://design.withfudge.com/share/pin-8621)

[![Archive feed with bright header strip and thumbnail rows](https://pin.fontofweb.com/39?format=jpg)](https://design.withfudge.com/share/pin-39)

[Archive feed with bright header strip and thumbnail rows](https://design.withfudge.com/share/pin-39)

[![Hardware grid with pale product cards and price or status lines](https://pin.fontofweb.com/35?format=jpg)](https://design.withfudge.com/share/pin-35)

[Hardware grid with pale product cards and price or status lines](https://design.withfudge.com/share/pin-35)

## Overview

abcdinamo.com is a type-foundry storefront with the confidence of a studio archive and the restraint of a catalog. The design puts specimen type first, then surrounds it with compact utilities, pill-shaped actions, and very little ornamental framing. The site alternates between large typographic statements and orderly product or article grids, so the user always knows whether they are looking at a specimen, a purchase flow, or a store section.

The visual tone is severe but playful. Black remains the default for titles, labels, and marks. A bright neon green is reserved for the current action, active choice, or the family selector that sits inside the buy flow. Violet appears more sparingly, mostly as a secondary status color for small notes, price deltas, or supporting emphasis. The page field is a pale gray rather than a pure white, which keeps the interface soft enough to let the type and product imagery carry the contrast.

## Colors

The palette is intentionally narrow. That narrowness is part of the brand voice: the page does not need much color because the typography is already loud.

| token | value | role |
|---|---|---|
| `ink` | `#000000` | Main type, wordmarks, icons, form labels, and the strongest contrast on light surfaces |
| `muted-ink` | `#A0A0A0` | Helper copy, quiet counts, inactive utility text, and low-priority notes |
| `canvas` | `#F0F4F6` | Page field, card backplates, and the light neutral base under product grids |
| `action` | `#63F450` | Primary action, active selection, the family pill in the buy hero, and the archive header strip |
| `accent` | `#6E32E1` | Secondary emphasis, small status color, and rare price or support highlights |

The system depends on contrast more than layering. The packet does not supply gradient or shadow tokens, so depth should stay minimal and the hierarchy should come from color blocking, scale, and spacing. Black text on the pale gray field is the default reading condition. Neon green needs enough empty space around it because it is loud enough to become the focal point even at small sizes. Violet should stay secondary; if it starts competing with the green, the page loses its hierarchy. The muted gray is useful for supporting information, but it should never become the primary reading color on the pale background.

The light field does most of the structural work, while darker text holds the content together. If the interface is inverted for a dark treatment, the same roles should swap rather than gaining new hues: the canvas should become the readable base, ink should become the contrast layer, and action and accent should stay the only strong highlights. Photography and product imagery live on pale backplates, so the images add density without taking over the page colors.

## Typography

Both families are material to the site: **Monument Grotesk** carries the interface and most of the page, while **Abc Diatype** appears as a rare specimen accent in the hero selector and related emphasis moments. The packet does not state a licensing credit for either family, so confirm usage rights before production use.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| `hero-display` | Monument Grotesk | 5.244rem | 400 | 0.9 | -0.01em | Oversized page titles such as QUOTE & BUY and HARDWARE |
| `family-pick` | Abc Diatype | 4.195rem | 400 | 0.95 | 0em | The neon-green family name inside the selector pill |
| `intro` | Monument Grotesk | 1.360rem | 400 | 1.15 | 0em | Short centered explanatory copy and page intros |
| `body` | Monument Grotesk | 1.068rem | 400 | 1.25 | 0em | Form prompts, product names, article titles, and common reading text |
| `label` | Monument Grotesk | 0.639rem | 400 | 1.2 | 0.05em | Dates, counts, utility notes, and small status text |
| `utility` | Monument Grotesk | 0.388rem | 400 | 1.2 | 0.05em | Top-right utility pills, tiny counters, and compact control text |
| `legal-copy` | Monument Grotesk | 0.639rem | 400 | 1.2 | 0em | Small disclaimers, VAT notes, and short support lines |

The hierarchy is built by size and restraint rather than by many weights. Monument Grotesk stays regular and compact, which makes the giant titles feel more deliberate. The hero and section titles are set large enough to dominate the page, but the supporting copy remains calm and readable. Abc Diatype should stay special; if it starts appearing everywhere, the buy hero loses the contrast that makes the selector feel like a product object instead of another button.

The smallest Monument Grotesk role is useful for the utility cluster and other narrow metadata where the interface should stay visually quiet. The body role handles ordinary scanning, while the label and legal-copy roles cover the smaller explanatory lines that support the buying and catalog flows. Because the family split is so strong, size changes do most of the work; the page does not need many weight changes to establish hierarchy.

## Layout

The layout language is built from three rhythms: a centered specimen stage, a narrow stacked purchase lane, and wider product or article grids.

The home page begins with a very open header row: a small menu control at the far left, the DINAMO wordmark centered, and a tight utility cluster on the right. Under that, the home view uses a large centered specimen window with a lot of surrounding canvas. The left side of the page often carries a vertical list of sections, which gives the page a studio-directory feeling instead of a conventional marketing landing-page structure. The specimen itself sits in a framed panel with enough breathing room that the page feels like a poster system rather than a normal web layout.

The quote-and-buy page compresses the content into a single centered column. The headline is huge and all caps, the selector pill sits directly beside it, and the supporting explanation stays narrow and centered beneath. The step cards below are stacked vertically and use rounded white panels on the pale field. The flow is not a dense form; it is a sequence of selection blocks. That distinction matters because the user is choosing from large, legible options rather than entering lots of text.

The archive and hardware sections widen again. The archive feed uses a bright green top bar and then a long vertical list of dated entries with small thumbnails aligned to one side. The hardware page uses a centered title, a short explanatory paragraph, and then a grid of product cards. Product images sit on pale card fields with generous gutters, so the grid feels like a showroom wall rather than a retail matrix. Across all of these views, the large whitespace is doing real structural work: it lets the oversized titles and rounded controls feel intentional instead of crowded.

Spacing is strongly bimodal. Utility rows and chip groups sit close together, while section-to-section jumps are much larger. The result is a page that can switch from tiny administrative labels to giant display type without feeling noisy. The packet’s spacing scale supports that rhythm cleanly; the interface should keep using a small set of recurring gaps rather than inventing one-off values for every block.

The page is easiest to read when each major section keeps a single center line and a clear left edge for secondary navigation or labels. The home specimen, the buy flow, and the archive list all depend on that simple alignment system. When the layout widens, the content can open into cards and grids, but the underlying discipline stays the same: strong center for the hero, controlled widths for copy, and generous margins around the object-like elements.

## Visual language

Dinamo’s visual language mixes foundry seriousness with a little bit of playful studio theater. The site uses a desktop-software memory in the specimen windows, menu bars, and framed product views, but it strips away most of the heavy interface chrome. That leaves the type, the pills, and the product imagery to carry the brand.

Pill shapes are everywhere. They show up in the family selector, the utility buttons, the online-count badges, the archive button, and the little status tags around articles and products. That repeated shape gives the site a cohesive tactile feel. It also softens the otherwise blunt typography. The page never becomes rounded in a generic startup way, though; the pills are specific and fairly minimal, while the rest of the layout stays rectangular and orderly.

Color is used as punctuation. Neon green marks the active state and the most important action. Violet is more like annotation than branding paint. Black remains the default, which keeps the typography grounded. The pale gray field prevents the layout from feeling stark or clinical, and the product photography gets enough room to feel like curated objects on a table.

The image style leans toward object photography and printed matter. Product cards show shirts, boards, candles, books, and tote bags against light backplates. The archive page uses smaller photographic thumbnails to break up the list, but the text remains the main content. The result is a site that reads as a type shop first and a merchandise store second.

The visual system also depends on deliberate contrast between an oversized statement and a tiny supporting element. A giant title can sit next to a compact chip without feeling mismatched because both belong to the same family of plain geometry. This keeps the page from becoming decorative. Instead of layered illustration or elaborate ornament, the site uses scale, spacing, and the occasional neon surface to create emphasis.

## Components

### Header and utility row

- **Anatomy:** Hamburger at the left edge, centered DINAMO wordmark with a lips mark, and a compact utility cluster on the right for online count, trial fonts, login, search, and bag.
- **Typography:** Small utility text uses the `utility` role; the brand wordmark sits visually above it without needing a separate token.
- **Shape:** The right-side controls are pill-shaped and very rounded. Some are filled dark, others are pale, but they all stay compact.
- **Spacing:** The header is flat and shallow. It should not steal vertical space from the specimen stage.
- **Visible states:** Online counts appear as tiny badges; the bag can switch to a filled dark pill, while search stays icon-only.

### Quote & Buy stage

- **Anatomy:** Huge headline, neon-green family selector, centered explanatory copy, then a stacked set of license and company-size panels.
- **Surface:** The selector pill is the brightest object on the page and should feel like a product switch, not a decorative badge.
- **Typography:** The headline uses `hero-display`; the family name inside the pill uses `family-pick`; the supporting text uses `intro` and `body`.
- **Shape:** The family selector is a very wide capsule. The lower form cards use soft roundness and flatter edges than the action pill.
- **Composition:** The flow is vertically centered and kept narrow enough that each choice reads as a single unit.
- **Visible states:** Selected choices are shown by filled dark dots or filled pills; unselected choices remain outlined or pale. Discount notes sit on the right in violet.

### Step cards and chip groups

- **Anatomy:** Radio-like yes/no rows, a company-size matrix, and optional add-on rows with right-aligned percentage notes and tiny help marks.
- **Typography:** Prompts remain in the body style; the small dates, counts, and percentage notes use the label style.
- **Spacing:** The chips wrap into dense rows with even gaps. The matrix has enough breathing room to stay readable while still feeling compact.
- **Shape:** Each chip is a pill, but the overall panel remains rectilinear, so the rounded controls stand out against the more neutral container.
- **Visible states:** One size chip can be filled while the rest stay pale; unavailable states look quieter and lighter, never more colorful.

### Archive feed

- **Anatomy:** Bright green top strip, centered archive title, small corner marks, list rows with date, title, tags, and a thumbnail on the far side.
- **Typography:** Dates are small and light; post titles use a larger body-sized line that can wrap cleanly.
- **Surface:** The archive strip makes the page feel like a board or placard. The rows themselves stay calm and open.
- **Shape:** Tags are small pills with dark outlines or pale fills. Thumbnails have rounded corners and sit inside the reading rhythm, not outside it.
- **Visible states:** The bottom action repeats the green pill language and acts like the page’s main continuation control.

### Product grid and hardware cards

- **Anatomy:** Large image tile, light backplate, product name below, then price or status text.
- **Typography:** Product names stay in the body role. Prices and status notes can be smaller and more emphatic, but they should remain legible and direct.
- **Surface:** Product cards are quiet and pale, which lets the merchandise imagery stay central.
- **Spacing:** The grid uses wide gutters and a lot of vertical room between title blocks and image blocks.
- **Visible states:** Items that are unavailable stay labeled beneath the item name. That keeps the catalog honest and easy to scan.

### Home specimen panel

- **Anatomy:** Large framed central artwork, compact supporting copy below, and a left-side section list that acts like a table of contents.
- **Typography:** The hero image is the dominant object, while the supporting paragraph uses the body or intro role depending on width.
- **Shape:** The frame around the specimen is rectangular and calm, which lets the content inside feel like a poster or software window.
- **Composition:** The panel must remain centered and isolated from the edge of the viewport so the specimen reads as the site’s anchor.
- **Visible states:** The section list stays quiet and compact until one section becomes current, then the active item can take on the action color.

## Responsive behavior

The page should preserve the reading sequence when it tightens: brand row, specimen or headline, explanatory copy, then the stacked choices or grid. On narrower widths, the big title can wrap, but it should still remain the dominant object on screen. Utility controls should compress before the specimen type does. Chip rows may wrap sooner than on desktop, but they should remain pill-based and not collapse into dense text links. Product grids should reduce columns while keeping the card ratio and the generous inner padding. Archive rows can stack their thumbnail below or beside the text, but the date and title must remain the first reading pass.

A narrower layout should not change the personality of the page. It should only reduce the number of columns and the amount of side-by-side content. The header can tighten, but the centered brand mark and the small utility cluster should still read as a deliberate top line. The buy flow should keep the selector visible above the step cards, and the archive should keep its green strip and row rhythm even when the thumbnail arrangement changes. The key rule is to preserve the hierarchy, not the exact desktop arrangement.

## Practical implementation guidance

### Preserve

- Keep the palette narrow: black, pale gray, neon green, violet, and muted gray are enough.
- Keep Monument Grotesk as the daily interface face and reserve Abc Diatype for specimen moments.
- Keep the pill shape consistent across actions, badges, and selectors.
- Let whitespace do most of the separation work.
- Keep product imagery and specimen type large enough that the page still feels like a foundry site, not a generic shop.

### Avoid

- Avoid extra accent colors or decorative gradients.
- Avoid adding shadow-heavy depth; the page is mostly flat.
- Avoid small, overstyled cards inside cards.
- Avoid replacing the pill language with square buttons.
- Avoid lowering the title scale to the point where the specimen stops feeling like the product.
- Avoid claiming font credits or licensing facts that are not stated in the packet.

### Recommended build order

1. Set the type hierarchy and the two-family split.
2. Build the palette and the pill/button shape system.
3. Recreate the header and the centered specimen or buy hero.
4. Add the stacked form panels and chip groups.
5. Build the archive strip and list rows.
6. Build the hardware and product grids.
7. Tighten responsive wrapping and verify that the large title remains dominant.

### Accessibility

- Keep visible focus treatment on every pill, chip, and utility control.
- Do not rely on color alone for selected states; use fill, outline, and position together.
- Preserve strong contrast for black text on the pale field and for text on the neon-green pill.
- Give product photos and article thumbnails useful alt text.
- Keep label text large enough to remain readable when the layout compresses, especially dates, prices, and helper marks.

## Scope note

This guide covers the supplied home, buy, archive, and hardware views for abcdinamo.com. It does not define mobile breakpoints, motion, hover or focus states beyond general accessibility advice, or exact interaction states that are not visible here. Spacing and sizes are rounded to the packet’s 0.125rem step for implementation.


---
# Design Reference: NOTHING.TECH
---

# How nothing.tech is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/nothing.tech-design)

Last updated: 2026-08-10

## Captured pages

[![Homepage hero with teal Nothing Phone (3a) community edition, pixel-art cursor avatars, and retro desktop UI metaphor with floating .ntg file icons](https://pin.fontofweb.com/5524?format=jpg)](https://design.withfudge.com/share/pin-5524)

[Homepage hero with teal Nothing Phone (3a) community edition, pixel-art cursor avatars, and retro desktop UI metaphor with floating .ntg file icons](https://design.withfudge.com/share/pin-5524)

[![Support Centre landing page with large serif heading, floating product photography of transparent phone and earbuds, and rounded search input](https://pin.fontofweb.com/3035?format=jpg)](https://design.withfudge.com/share/pin-3035)

[Support Centre landing page with large serif heading, floating product photography of transparent phone and earbuds, and rounded search input](https://design.withfudge.com/share/pin-3035)

[![Support category grid with six pill-shaped outline buttons labeled Product Guide, Troubleshooting, FAQs, After-Sales Service, Software Download, Product Status](https://pin.fontofweb.com/3034?format=jpg)](https://design.withfudge.com/share/pin-3034)

[Support category grid with six pill-shaped outline buttons labeled Product Guide, Troubleshooting, FAQs, After-Sales Service, Software Download, Product Status](https://design.withfudge.com/share/pin-3034)

[![Contact Us section with dotted horizontal rule, body text, and a solid dark pill-shaped SEND US A MESSAGE button on light gray background](https://pin.fontofweb.com/3033?format=jpg)](https://design.withfudge.com/share/pin-3033)

[Contact Us section with dotted horizontal rule, body text, and a solid dark pill-shaped SEND US A MESSAGE button on light gray background](https://design.withfudge.com/share/pin-3033)

## Overview

Nothing's digital presence embodies a deliberate tension between raw technological transparency and playful retro-computing nostalgia. The system operates on a near-monochrome foundation—pitch black against clean white and soft gray—allowing product photography and occasional electric accents to command full attention. The homepage transforms the browser into a simulated desktop environment, complete with draggable file icons, pixel-art cursors, and chat-bubble annotations that frame product reveals as collaborative design sessions. This desktop metaphor extends to window chrome, title bars, and floating UI layers that recall early graphical interfaces without descending into pastiche.

The Support Centre strips back this theatricality for clarity while retaining the brand's typographic DNA. Large serif-style display headings anchor pages with editorial confidence, while body copy maintains the same measured, slightly technical tone. Product photography floats against neutral grounds, presented with museum-like isolation that emphasizes industrial design details—the transparent casings, visible screws, and internal components that define Nothing's hardware identity. The overall effect is a design system that feels simultaneously contemporary and anachronistic, rigorous and playful, minimal yet richly detailed.

## Colors

The palette is intentionally constrained, deriving visual energy from contrast and materiality rather than chromatic variety. Black serves as the primary structural ink for all text, borders, and key UI elements. White provides the dominant canvas, with a near-white gray softening large background fields. A single electric yellow-green appears as an accent in interactive moments and promotional highlights. Deep navy functions as the solid action color for primary buttons, offering a cooler alternative to pure black that maintains sophistication.

| token | value | use |
|---|---|---|
| ink | #000000 | Primary text, borders, window chrome, icon fills |
| canvas | #FFFFFF | Page backgrounds, input fields, product card surfaces |
| surface | #F5F5F5 | Section backgrounds, secondary page grounds, footer areas |
| accent | #E1FF00 | Promotional highlights, chat bubbles, hover states, badges |
| action | #002B5C | Primary button fills, critical CTAs, emphasis backgrounds |

The homepage deploys accent yellow-green sparingly in floating chat bubbles and annotation labels, creating focal points against the teal product photography without competing for dominance. Support pages largely suppress this accent in favor of the neutral triad, reserving the deep navy action color for the single most important conversion point on each page. Product photography introduces its own chromatic world—teal handsets, orange cables, metallic grays—that the UI palette deliberately steps back to frame. Dark mode is not visibly deployed in the captured surfaces; the system appears optimized for light-ground presentation with black as the dominant figure.

## Typography

Nothing's typographic system is built on three distinct families that serve different communicative registers. N Type 82, a contemporary serif with classical proportions, handles all display and body text with calm authority. Lettera Mono Ll provides the technical voice—labels, captions, metadata, and interface chrome—its monospaced rhythm evoking terminal output and engineering documentation. Ndot, a dot-matrix display face, appears in navigation and branding moments, its pixelated construction reinforcing the retro-computing aesthetic.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | N Type 82 | 4rem | 400 | 1 | -0.02em | Homepage headlines, major product announcements |
| section-display | N Type 82 | 2.5rem | 400 | 1.1 | -0.01em | Page titles, section headers, Support Centre headings |
| body | N Type 82 | 1rem | 400 | 1.5 | 0em | Paragraphs, descriptions, form text |
| label | Lettera Mono Ll | 0.75rem | 400 | 1.2 | 0.05em | Buttons, tags, metadata, timestamps |
| navigation | Ndot | 1rem | 400 | 1 | 0.08em | Primary nav, brand marks, category labels |
| legal-copy | Lettera Mono Ll | 0.625rem | 400 | 1.4 | 0.02em | Footnotes, copyright, fine print |

N Type 82 is designed by Colophon Foundry. Lettera Mono Ll is designed by Kobi Benezri for Lineto. Ndot is designed by Colophon Foundry. Verify licensing for these families before production use.

The type scale is built on a 4px relative unit. Display sizes use tight leading and negative tracking for impactful headlines, while body text opens up for comfortable reading. The monospaced label style is used extensively in pill buttons and interface elements, its even character widths creating visual regularity that complements the rounded geometric containers. The dot-matrix navigation face appears at a consistent size with generous letter-spacing to maintain legibility despite its pixelated construction.

## Layout

The layout system alternates between two distinct modes: the theatrical, non-linear compositions of the homepage and the disciplined, editorial grids of support and product pages.

Homepage layouts employ a centered, floating composition where a primary product image anchors the viewport, surrounded by satellite elements—file icons, cursor avatars, chat bubbles—that appear to exist in a shallow three-dimensional space. The central "window" containing the product maintains a fixed aspect ratio with subtle drop shadow, suggesting a layer above the desktop ground. Navigation sits at the top in a minimal bar, with the brand mark centered and utility icons flanking. This layout resists conventional responsive reflow; elements maintain their relative positions through scale transformations rather than stack-based reordering.

Support and content pages adopt a conventional single-column flow with generous margins. The Support Centre hero places a large heading and search input in the left third of the viewport, with product photography occupying the right two-thirds in a floating, asymmetrical arrangement. Below this, content sections stack vertically with consistent section spacing. Category grids use a three-column layout of equal-width pill buttons with uniform gaps.

The underlying grid appears to be fluid rather than fixed-width, with content areas that expand to fill available space while maintaining comfortable measure for text. Section spacing is generous, creating clear rhythmic separation between functional areas without excessive whitespace that would feel austere.

## Visual language

Nothing's visual language is defined by three core motifs: transparency, pixelation, and industrial precision.

Transparency appears literally in product photography—phones with clear backs revealing internal circuitry, earbuds in open cases—and metaphorically in the UI's refusal to hide its own structure. Window chrome, title bars, and visible grid lines on the homepage background all suggest a system that exposes rather than conceals its workings.

Pixelation manifests in the dot-matrix typeface, the 1-bit cursor icons, and the dithered aesthetic of floating avatars. These elements are not merely decorative but functional: the pixel cursors indicate interactive presence, the chat bubbles suggest real-time collaboration, the file icons imply a navigable file system. This is a UI that asks to be manipulated, not merely consumed.

Industrial precision appears in the exacting geometry of all components. Pill buttons have perfectly semicircular ends. Search inputs maintain mathematically consistent corner radii. Borders are hairline-thin and exactly 1px. The dotted horizontal rule in the Contact section uses a regular dot pattern that feels machined rather than hand-drawn. Even the playful elements obey rigorous constraints.

Imagery treatment favors high-key photography with soft, diffuse lighting that eliminates harsh shadows. Products float against neutral grounds, often with subtle reflections that suggest premium presentation without ostentation. The overall impression is of a design studio that treats consumer electronics with the same reverence traditionally reserved for luxury goods or museum pieces.

## Components

### Primary action button

A solid filled pill with deep navy background and white text. Uses the monospaced label typography with generous horizontal padding, creating a substantial target that feels authoritative without heaviness.

- Anatomy: Text label centered within a full pill shape
- Surface: Solid action color background, canvas text
- Typography: `{typography.label}`, uppercase or title-case depending on context
- Shape: Full pill border radius
- Spacing: 1rem vertical padding, 2.5rem horizontal padding
- Composition: Typically right-aligned or centered within its container
- Variants: None visible; appears as single emphasis element per section

### Secondary outline pill

A transparent pill with 1px black border and black text. Used for category navigation and non-primary choices, creating a lighter visual weight that allows multiple instances to coexist without competing.

- Anatomy: Text label centered within outlined pill
- Surface: Transparent background, ink border and text
- Typography: `{typography.label}`
- Shape: Full pill border radius
- Spacing: 1rem vertical padding, 2rem horizontal padding
- Composition: Grid of three columns with consistent gaps
- Variants: None visible; uniform treatment across all category instances

### Search input

A white rounded rectangle with subtle shadow or border, containing a search icon and placeholder text. The generous corner radius creates a friendly, approachable entry point that softens the technical context.

- Anatomy: Icon prefix, text input area, optional clear button
- Surface: Canvas background, ink icon and placeholder text
- Typography: `{typography.body}`
- Shape: 2rem border radius, creating a stadium shape
- Spacing: 1rem vertical padding, 1.5rem horizontal padding
- Composition: Full-width within its container on mobile, constrained width on desktop

### Dotted rule

A horizontal divider composed of evenly spaced dots rather than a continuous line. This element appears in content sections to separate headings from body copy with visual interest that avoids the severity of a solid rule.

- Anatomy: Single horizontal line of dots
- Surface: Ink color at 1px weight
- Shape: Continuous dot pattern
- Spacing: 1.5rem vertical margin above and below
- Composition: Full-width within content area

### Product window

The homepage's central content container, presenting a product image within a simulated window frame with title bar, close/minimize/expand controls, and subtle shadow suggesting elevation above the desktop ground.

- Anatomy: Title bar with window controls, content area, optional status elements
- Surface: Canvas background, ink chrome elements
- Typography: `{typography.label}` for title bar text
- Shape: Small radius on outer corners, sharp or slightly rounded on window controls
- Spacing: Tight internal padding, substantial external margin
- Composition: Centered in viewport with surrounding satellite elements

### Cursor avatar

Pixel-art hand cursor icons that serve as user presence indicators in the collaborative desktop metaphor. Each cursor carries a name label in a small black pill, suggesting multiple simultaneous viewers or contributors.

- Anatomy: 1-bit pixel hand icon, name label pill
- Surface: Black label with white text, monochrome cursor
- Typography: `{typography.legal-copy}` for name labels
- Shape: Irregular cursor outline, pill label
- Composition: Scattered around product window at various angles

## Responsive behavior

The desktop experience prioritizes the full theatrical presentation of the homepage desktop metaphor and the generous proportions of the Support Centre layout. At narrower viewports, the system should maintain its essential character while adapting for touch interaction and reduced horizontal space.

The homepage's floating window composition likely scales down proportionally, with satellite elements repositioning to avoid overlap. The three-column category grid on Support pages should reflow to two columns and then single column, with pill buttons expanding to full width for comfortable touch targets. The asymmetrical hero layout with left text and right imagery should stack vertically, preserving text hierarchy by placing the heading and search input above the product photograph.

Touch targets should maintain minimum 44px height; the existing pill buttons already exceed this. The search input should remain easily tappable with its generous padding. Cursor avatars and desktop metaphors may require alternative presentation or suppression on touch devices where hover and precise positioning are unavailable.

Typography should scale down proportionally, with hero display reducing to section-display size and section-display reducing to a size that maintains impact without overwhelming narrow viewports. The monospaced label style remains legible at small sizes due to its generous x-height and clear construction.

## Practical implementation guidance

### Preserve
- The exacting contrast between black and white as the primary figure-ground relationship
- The three-family typographic hierarchy: serif for editorial voice, monospace for technical voice, dot-matrix for brand voice
- Full pill shapes for all interactive elements—buttons, inputs, category selectors
- The transparent, exposed aesthetic in product presentation and UI chrome
- Generous section spacing that allows each functional area to breathe
- The dotted rule as a distinctive separator that avoids solid-line severity

### Avoid
- Introducing additional accent colors beyond the electric yellow-green; the system's power comes from restraint
- Rounded rectangles with modest radii where pills are established; the semicircular ends are essential to the language
- Drop shadows on content cards or buttons; elevation should be suggested through composition, not decorative shadow
- Generic sans-serif substitutions for N Type 82; the serif construction provides necessary warmth and editorial authority
- Crowding the desktop metaphor with too many interactive elements; the current sparse arrangement maintains clarity

### Recommended build order
1. Establish the color foundation with ink, canvas, and surface tokens
2. Implement N Type 82 for all display and body text with appropriate scale and leading
3. Build the pill button system with primary and secondary variants
4. Create the search input component with its distinctive stadium shape
5. Develop the Support Centre page template with hero layout, category grid, and contact section
6. Layer in the homepage desktop metaphor with window chrome, cursor avatars, and floating elements
7. Add the dot-matrix navigation face and monospaced label system for complete typographic coverage

### Accessibility
- Ensure all text meets WCAG contrast ratios against its background; the black-on-white and white-on-navy pairings exceed requirements
- Provide visible focus indicators for all interactive elements; the existing 1px borders can be enhanced with outline offsets
- Consider motion sensitivity for the homepage's floating elements; provide reduced-motion alternatives that maintain layout without parallax or drift
- Ensure the dotted rule is not relied upon as the sole visual separator for users with low vision; structural headings and spacing should reinforce section boundaries
- Test the pixelated Ndot face at navigation sizes to confirm legibility for users with visual impairments; the generous letter-spacing aids recognition but may require larger minimum sizes

## Scope note

This guide covers the homepage desktop metaphor and Support Centre surfaces as captured. Product detail pages, checkout flows, account interfaces, and mobile-specific layouts are not represented. The CMF sub-brand pages with their warmer color palette and distinct photography treatment would require separate documentation. Motion behavior, hover states, and form validation patterns are not visible in still images and should be designed to match the system's restrained, precise character. Measurements are practical adaptation targets.


---
# Design Reference: ARE.NA
---

# How are.na is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/are.na-design)

Last updated: 2026-08-10

## Captured pages

[![User profile page showing a grid of colorful image blocks against a pure black background with white navigation and minimal UI chrome](https://pin.fontofweb.com/4174?format=jpg)](https://design.withfudge.com/share/pin-4174)

[User profile page showing a grid of colorful image blocks against a pure black background with white navigation and minimal UI chrome](https://design.withfudge.com/share/pin-4174)

[![Testimonials section with white text quotes in rounded dark pill containers on a black background](https://pin.fontofweb.com/2938?format=jpg)](https://design.withfudge.com/share/pin-2938)

[Testimonials section with white text quotes in rounded dark pill containers on a black background](https://design.withfudge.com/share/pin-2938)

[![Road to self-sustainability section with progress bar showing blue gradient fill and white statistics text](https://pin.fontofweb.com/2937?format=jpg)](https://design.withfudge.com/share/pin-2937)

[Road to self-sustainability section with progress bar showing blue gradient fill and white statistics text](https://design.withfudge.com/share/pin-2937)

[![Pricing FAQs accordion with white text, chevron indicators, and expanded answer text on black background](https://pin.fontofweb.com/2936?format=jpg)](https://design.withfudge.com/share/pin-2936)

[Pricing FAQs accordion with white text, chevron indicators, and expanded answer text on black background](https://design.withfudge.com/share/pin-2936)

## Overview

Are.na is a dark-themed platform for collecting, organizing, and connecting ideas through visual blocks and channels. The interface prioritizes user-generated content by submerging its own chrome into a near-black canvas, letting colorful images and media take visual precedence. The design language is restrained and editorial: generous negative space, minimal UI decoration, and a single variable typeface that scales from small functional labels to large section headings without changing family. Navigation is sparse, typically appearing as simple text links in the upper portion of pages. The overall impression is of a creative tool that refuses to compete with the material it holds—content blocks float on darkness like items in a vitrine, while text remains crisp and highly legible through disciplined contrast. The system supports both personal profile browsing and informational pages through the same visual vocabulary of black grounds, white type, and subtle blue accents for interactive emphasis.

## Colors

The color system is built on extreme contrast: a pure black canvas against white text, with a narrow range of supporting grays and a single electric blue for action states. This restraint ensures that user content—photographs, illustrations, and video thumbnails—becomes the primary source of color in any view.

| token | value | use |
|---|---|---|
| canvas | #000000 | Page background, empty states, all chrome areas |
| surface | #161616 | Elevated containers, testimonial pills, progress bar tracks |
| ink | #ffffff | Primary text, headings, navigation, icons |
| muted-ink | #a0a0a0 | Secondary text, expanded FAQ answers, metadata, captions |
| action | #4a5cff | Progress bar fill, interactive emphasis, links on hover |
| border | #333333 | Subtle dividers, pill outlines, FAQ item separators |

The canvas token is applied globally as the page background, creating the immersive dark environment that defines the platform's character. Surface raises certain elements slightly above this plane—testimonial quotes live in rounded pills with this fill, and the progress bar track uses it to create depth against the black ground. Ink serves all primary reading text at full contrast. Muted-ink steps back for supporting information without disappearing, maintaining the hierarchy through lightness rather than color temperature. Action appears as a saturated blue with slight purple undertone, used sparingly for the progress indicator and interactive states. Border provides structural separation at low contrast, keeping divisions visible without drawing attention.

## Typography

Are.na employs a single variable font family across all text roles, leveraging weight and size variation rather than family changes to create hierarchy. The typeface is Areal Variable, designed by Dinamo Typefaces GmbH. Verify licensing for this family before production use.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Areal Variable | 3rem | 400 | 1.1 | -0.02em | Page titles, major headings |
| section-display | Areal Variable | 1.5rem | 400 | 1.2 | -0.01em | Section labels, testimonial quotes |
| body | Areal Variable | 1rem | 400 | 1.5 | 0em | Paragraphs, descriptions, answers |
| label | Areal Variable | 0.75rem | 400 | 1.3 | 0.02em | Metadata, captions, small functional text |
| navigation | Areal Variable | 0.875rem | 400 | 1 | 0em | Top-level nav, links, buttons |

The type system is notably calm: no bold weights appear in the visible interface, and even headings maintain a regular weight with tight tracking for presence. Hero-display uses negative tracking to feel intentional and designed rather than default. Body text is set with generous line height for comfortable reading in longer passages like FAQ answers and mission statements. Label and navigation sizes are practical adaptations from the 4px relative unit, keeping functional text small but not fragile. The absence of italic or bold styles in the visible system suggests the variable font's weight axis may be reserved for future states or simply unused in favor of size-based hierarchy.

## Layout

The layout system is fundamentally simple: full-width black canvas with centered or left-aligned content bands, generous vertical breathing room between sections, and content constrained to readable widths for text-heavy pages.

Page gutters are set at 1.5rem on each side, creating consistent horizontal padding across viewports. Sections stack vertically with 4rem of separation, allowing each content band to feel distinct without heavy rules. Text content is constrained to approximately 65-75 characters per line for readability, while image grids and block collections expand toward the edges to feel immersive.

The profile grid visible in the reference images uses a masonry or staggered arrangement where blocks of varying aspect ratios interlock, creating visual rhythm through the content itself rather than through UI structure. This grid sits directly on the black canvas with minimal gap—approximately 0.5rem between blocks—so that the colorful thumbnails form a continuous tapestry against the dark ground.

Informational pages like About use a single-column layout with left-aligned text blocks. The FAQ section shows an accordion pattern where questions stack vertically with thin border separators, and answers expand below their triggers. The progress bar section centers its bar and statistics, creating a focal point for the sustainability narrative.

No sidebar navigation is visible; wayfinding happens through top navigation and in-page scrolling. The overall spatial philosophy is one of reduction: remove everything that is not content or essential navigation, then add back just enough structure to make the content legible and the interactions discoverable.

## Visual language

The visual language of Are.na is deliberately austere, drawing from editorial and gallery traditions rather than conventional web application patterns. The near-black canvas functions as negative space in the traditional design sense—it is not merely a background but an active compositional element that isolates and elevates content blocks.

Rounded corners appear selectively: image blocks use moderate rounding to feel contemporary without becoming playful, while testimonial pills use full rounding to create a distinct container shape that separates quotes from the surrounding darkness. The progress bar uses full rounding at its track ends, making a technical element feel approachable.

Shadows are absent from the visible system; depth is created solely through tonal separation between canvas and surface. This flatness reinforces the gallery-like quality of the interface, where objects appear to rest on a single plane rather than floating in layered space.

User content provides all color variation. The platform's design makes a bet that its users will upload visually rich material, and the interface steps back to let that material speak. When content is sparse or text-heavy, the system relies on typography and spacing to maintain interest.

The blue accent is used with surgical precision—only where interaction or progress needs emphasis. This restraint makes the color feel electric when it does appear, drawing the eye immediately to the progress bar or to a hovered link.

## Components

**Testimonial Pill**

Anatomy: A rounded container holding a single quote string. No quotation marks in the UI—the text itself carries the message.

Surface and text color: Surface background (#161616) with ink text (#ffffff). A subtle border in border color (#333333) defines the pill edge against the black canvas.

Typography: Section-display token at 1.5rem, regular weight, with the quote text centered or left-aligned depending on length.

Shape and border: Full pill rounding (9999px), creating a capsule shape. Border is 1px solid.

Spacing: Generous internal padding, approximately 1rem vertical and 4rem horizontal, giving the quote room to breathe.

Composition: Pills stack vertically with consistent gap between them, each sized to its content width rather than forced to full width. This creates a ragged right edge that feels conversational and informal.

**Progress Bar**

Anatomy: A horizontal track with a fill portion indicating completion, flanked by text statistics below.

Surface and text color: Track uses surface (#161616), fill uses action (#4a5cff). Labels and numbers use ink (#ffffff), with muted-ink (#a0a0a0) for secondary metric labels.

Typography: Section-display for the section title, body for the descriptive paragraph, label for the metric labels and values.

Shape and border: Full pill rounding on the track, creating a pill-shaped indicator. Height is approximately 1.5rem.

Spacing: The bar sits below a text block with standard section spacing. Statistics align to the left and right ends of the bar, creating a clear today-to-goal narrative.

**FAQ Accordion**

Anatomy: A stack of question rows, each with a chevron indicator and expandable answer text.

Surface and text color: Transparent background on questions, ink text. Answers use muted-ink for reduced emphasis.

Typography: Body token for questions and answers. Questions may use slightly tighter line height to feel button-like.

Shape and border: No rounding. Each item separated by a 1px border in border color (#333333). Chevron icons indicate expandability.

Spacing: Items have approximately 1rem vertical padding. Expanded answers add tight padding below the question text.

Composition: The accordion sits within a text-constrained column, left-aligned. Expanded state reveals answer without animation visible in still images.

**Image Block**

Anatomy: A rectangular container for user-uploaded media, appearing in profile grids and channel views.

Surface and text color: Content-dependent. The block itself has no chrome—media fills the container.

Typography: Optional caption or metadata may appear below in label token.

Shape and border: Moderate rounding (0.5rem) on corners. No border visible.

Spacing: Tight gap (approximately 0.5rem) between blocks in grid contexts.

Composition: Blocks arrange in masonry or staggered grid, with varying heights creating organic rhythm. The black canvas shows through gaps, making the grid feel like scattered objects on a dark surface.

## Responsive behavior

The visible images show desktop layouts exclusively. Based on these, the following responsive guidance is recommended:

The masonry grid of image blocks should reflow to fewer columns as viewport narrows, likely from four or five columns down to two and then single column on the narrowest devices. Gap between blocks should remain constant to preserve the tapestry effect.

Text-constrained sections like FAQs and mission statements should maintain their readable line length by adjusting margins rather than stretching text to full width. The 1.5rem page gutter provides a reasonable minimum padding on small screens.

Navigation, visible as sparse text links in the upper area, should collapse to a hamburger or simplified menu on narrow viewports to preserve the clean header aesthetic.

Testimonial pills, which size to their content, should remain comfortable to read by preventing excessive horizontal stretching—either through max-width constraints or by allowing them to remain narrow and centered.

The progress bar and its statistics should stack vertically on very narrow screens, with the bar remaining full-width and statistics moving below rather than beside.

## Practical implementation guidance

**Preserve**

- The absolute black canvas (#000000) as the foundation of every page; this is not merely a dark mode but the core brand expression
- Single-family typography throughout; do not introduce secondary fonts for headings or UI elements
- The extreme contrast between ink and canvas; never place dark text on dark backgrounds
- Content-forward grid layouts where user media dominates the visual field
- The restrained use of action blue; reserve it for genuine interactive emphasis and progress indication

**Avoid**

- Adding shadows or depth effects; the system achieves hierarchy through tone and spacing alone
- Rounding everything to full pills; reserve full rounding for quote containers and progress tracks
- Introducing additional accent colors; the palette is intentionally narrow
- Heavy borders or rules; use the subtle #333333 border only where structural separation is essential
- Bold typography for emphasis; the system uses size and spacing, not weight, to create hierarchy

**Recommended build order**

1. Establish the black canvas and white text foundation with Areal Variable loaded
2. Implement the text hierarchy with hero-display, section-display, body, and label tokens
3. Build the image block component with rounded corners and tight grid gaps
4. Create the testimonial pill with surface background and full rounding
5. Add the progress bar with action fill and statistics layout
6. Implement the FAQ accordion with border separators and expand behavior
7. Refine spacing tokens across all components for vertical rhythm

**Accessibility**

- Maintain the 21:1 contrast ratio between ink (#ffffff) and canvas (#000000) for all primary text
- Ensure muted-ink (#a0a0a0) is used only for non-essential text, as it may fall below WCAG AA against black
- Provide visible focus indicators for interactive elements; the current subtle borders may need enhancement for keyboard navigation
- Consider a reduced-motion preference for any masonry grid animations or accordion transitions
- Test the blue action color (#4a5cff) against both black and white backgrounds for sufficient contrast in all states

## Scope note

This guide covers the visible desktop surfaces of Are.na's profile, about, and informational pages. Mobile breakpoints, hover and focus states, loading skeletons, form validation, and channel editing interfaces are not represented in the supplied images. Measurements are practical adaptation targets derived from visual inspection against a 4px relative unit grid. The Areal Variable font family requires licensing verification before production use; attribution to Dinamo Typefaces GmbH is supported by the supplied source data.


---
# Design Reference: BASEMENT.STUDIO
---

# How basement.studio is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/basement.studio-design)

Last updated: 2026-08-10

## Captured pages

[![Contact form overlay styled as retro radio device with orange neon text on black screen, hands holding hardware interface](https://pin.fontofweb.com/5122?format=jpg)](https://design.withfudge.com/share/pin-5122)

[Contact form overlay styled as retro radio device with orange neon text on black screen, hands holding hardware interface](https://design.withfudge.com/share/pin-5122)

[![Massive BSMT.25 display type spanning viewport width above minimal footer with newsletter signup and navigation links](https://pin.fontofweb.com/5121?format=jpg)](https://design.withfudge.com/share/pin-5121)

[Massive BSMT.25 display type spanning viewport width above minimal footer with newsletter signup and navigation links](https://design.withfudge.com/share/pin-5121)

[![Capabilities section with large italic manifesto text and four-column service grid with pill tags on black background](https://pin.fontofweb.com/5120?format=jpg)](https://design.withfudge.com/share/pin-5120)

[Capabilities section with large italic manifesto text and four-column service grid with pill tags on black background](https://design.withfudge.com/share/pin-5120)

[![Hero section with architectural photography, studio tagline, and dense logo grid of client brands in bordered cells](https://pin.fontofweb.com/5119?format=jpg)](https://design.withfudge.com/share/pin-5119)

[Hero section with architectural photography, studio tagline, and dense logo grid of client brands in bordered cells](https://design.withfudge.com/share/pin-5119)

## Overview

The basement.studio identity is a dark-mode digital studio presentation built on absolute contrast: a void-black canvas supports massive, tightly-tracked display type and selective warm-orange accents. The system communicates creative confidence through scale rather than ornament—typography dominates the viewport, photography appears in controlled moments, and interactive elements borrow from retro-futuristic hardware interfaces. The visual language balances brutalist directness with polished execution: headlines are oversized and unapologetic, body copy is restrained and legible, and the occasional interactive set piece (such as the radio-styled contact form) introduces tactile personality without breaking the monochrome discipline. The overall impression is of a studio that treats its own site as a portfolio piece—every section is composed, every type scale is intentional, and the black ground serves as continuous negative space that lets content breathe.

## Colors

The palette is severely restricted, deriving its power from restraint and the single warm accent against an absolute dark ground.

| token | value | use |
|---|---|---|
| canvas | #000000 | Primary background for all sections, hero, footer, and overlays |
| ink | #e6e6e6 | Primary text, headlines, body copy, navigation links |
| muted-ink | #808080 | Secondary text, labels, captions, disabled states, footer metadata |
| accent | #ff5500 | Active navigation states, interactive highlights, retro form elements, CTAs |
| surface | #1a1a1a | Elevated panels, input backgrounds, subtle card differentiation |
| border | #333333 | Dividers, logo grid cell borders, hairline separators |

The color logic follows a near-monochrome structure with one energetic warm accent. Black dominates every surface, creating a cinematic depth that makes photography and typography appear to float. The near-white ink avoids pure #ffffff, reducing eye strain and introducing a subtle material quality. The orange accent appears sparingly—primarily in active states and the distinctive retro contact form—so that every instance feels intentional and draws the eye. No gradients are visible in the interface; all transitions are handled through opacity or the single accent color. Photography in the hero uses its own warm, desaturated palette but is treated as content rather than system color.

## Typography

Two families drive the typographic hierarchy: a compressed, ultra-light display face for monumental headlines, and a clean geometric sans for everything else.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Ff Flauta-200 | 8rem | 200 | 0.85 | -0.04em | Massive section identifiers, brand marks, viewport-spanning type |
| section-display | Geist | 3.5rem | 400 | 1.1 | -0.02em | Manifesto statements, section headlines, contact CTAs |
| body | Geist | 1rem | 400 | 1.5 | 0 | Paragraphs, service descriptions, general reading |
| label | Geist | 0.75rem | 400 | 1.2 | 0.02em | Tags, metadata, small captions, counts in parentheses |
| navigation | Geist | 0.875rem | 400 | 1 | 0 | Primary nav, footer links, UI controls |

The hero-display token at 8rem produces the signature BSMT.25 treatment—letters that approach the edges of the viewport, their ultra-light weight creating a ghostly presence against black. Section-display at 3.5rem handles the manifesto voice with slightly tighter leading that stacks aggressively. Body text remains comfortable for reading at 1rem with generous 1.5 line height. The label token at 0.75rem serves the service category tags and parenthetical counts, while navigation at 0.875rem keeps the header and footer links unobtrusive yet crisp.

Geist is credited to designers Basementstudio Andrés Briganti Mateo Zaragoza and vendors Basementstudio Vercel Andrés Briganti Guido Ferreyra Mateo Zaragoza. Ff Flauta-200 carries no supported attribution. Verify licensing for these families before production use.

## Layout

The layout system is fundamentally single-column with strategic asymmetric interruptions. The viewport is treated as a continuous scrollable canvas with full-bleed sections separated by generous vertical whitespace.

Section rhythm relies on a 6rem section spacing token, creating distinct pauses between content blocks without visible dividers. The hero section occupies the full viewport width with a large architectural photograph positioned in the upper portion, overlaid by the studio tagline in section-display type. Below, the "Trusted by Visionaries" logo grid uses a strict multi-column arrangement with equal-width cells separated by 1px borders, creating a tessellated pattern of client marks.

The capabilities section introduces an asymmetric four-column grid for service descriptions, each column containing a headline, paragraph, and row of pill-shaped tags. This is the most structured layout moment—elsewhere, the system prefers free placement of large type against black space.

The footer splits into two zones: a newsletter capture area on the left with stacked text and an email input, and a vertical navigation stack on the right with oversized link text. Social links and copyright sit at the extreme bottom edge in a horizontal row.

No container max-width is enforced for display type, which bleeds to viewport edges. Content text maintains comfortable measure through implicit padding rather than explicit containers. The retro contact form breaks this pattern entirely, appearing as a centered hardware object with fixed proportions, framed by hands and floating above the page content.

## Visual language

The visual language merges digital studio polish with analog hardware nostalgia. The dominant mode is austere: black fields, precise typography, and grid-based information architecture. Against this, specific interactive moments introduce unexpected materiality—the radio-styled contact form with its orange CRT-style text, physical knobs, and embossed "basement" logo.

Photography appears in controlled doses. The hero image shows an interior architectural space with warm wood tones and dramatic lighting, establishing spatial depth without competing with the overlay text. This image is treated atmospherically rather than illustratively—it provides texture and scale while the type remains the primary message.

The logo grid is a key visual motif: dozens of client marks arranged in bordered cells, each mark rendered in white or light gray against black. The grid creates a sense of density and social proof while maintaining the monochrome discipline. Cell borders at 1px provide just enough separation without visual weight.

Motion is implied by the form of the typography—tight tracking and extreme scale suggest kinetic energy even in static compositions. The retro form elements introduce skeuomorphic depth through simulated buttons, dials, and screen glow, creating a deliberate anachronism against the flat digital surface.

## Components

### Primary navigation

- **Anatomy**: Horizontal row of text links with active state indicator, positioned at viewport top
- **Surface**: Transparent background over page content
- **Typography**: `{typography.navigation}` in `{colors.ink}`, active link in `{colors.accent}`
- **Spacing**: Compact horizontal arrangement with consistent gap between items
- **Composition**: Left-aligned logo mark, center-aligned page links, right-aligned utility controls and "Contact Us" CTA

### Hero section

- **Anatomy**: Full-width background photograph, overlaid tagline in two lines, supporting paragraph below
- **Surface**: Photographic background with dark gradient overlay preserving text legibility
- **Typography**: Tagline in `{typography.section-display}` at `{colors.ink}`, body in `{typography.body}` at `{colors.ink}`
- **Spacing**: Generous padding above and below text block, photograph fills upper portion

### Logo grid

- **Anatomy**: Multi-row grid of equal cells, each containing a centered client logo mark
- **Surface**: `{colors.canvas}` background, `{colors.border}` 1px borders between cells
- **Typography**: Logo marks as SVG or image, no text styling applied
- **Shape**: Rectangular cells with no border-radius
- **Spacing**: Tight packing with shared borders, no gap between cells
- **Composition**: Centered alignment within each cell, consistent visual weight across marks

### Service card

- **Anatomy**: Column containing service headline, descriptive paragraph, and horizontal row of capability tags
- **Surface**: Transparent, inherits `{colors.canvas}`
- **Typography**: Headline in `{typography.body}` at `{colors.ink}`, description in `{typography.body}` at `{colors.muted-ink}`, tags in `{typography.label}`
- **Shape**: Tags use `{rounded.pill}` with `{colors.surface}` background
- **Spacing**: Vertical stack with consistent rhythm, tags arranged horizontally with small gap

### Newsletter capture

- **Anatomy**: Text prompt, email input field, submit action with arrow indicator
- **Surface**: Input field uses `{colors.surface}` background
- **Typography**: Prompt in `{typography.body}` at `{colors.ink}`, input placeholder in `{typography.body}` at `{colors.muted-ink}`, action text in `{typography.body}` at `{colors.ink}`
- **Shape**: Input field with minimal or no border-radius
- **Spacing**: Stacked vertically with tight grouping

### Retro contact form

- **Anatomy**: Hardware frame with screen, physical controls, and hands; screen contains form fields and submit action
- **Surface**: Matte black plastic texture with embossed branding, screen area with orange phosphor glow
- **Typography**: Form labels and input text in monospace-style orange (`{colors.accent}`), "CONTACT US" and "CLOSE" headers in same treatment
- **Shape**: Rounded rectangle hardware body, rectangular screen with thin orange border
- **Spacing**: Form fields arranged in two-column grid within screen, full-width message area below, full-width submit button at bottom
- **Composition**: Centered in viewport, partially obscuring page content, hands entering from edges to hold device
- **Variants**: "CLOSE" control in upper right of screen area

### Footer navigation

- **Anatomy**: Vertical stack of page links with parenthetical counts on some items
- **Surface**: Transparent over `{colors.canvas}`
- **Typography**: Links in `{typography.section-display}` at `{colors.ink}`, counts in `{typography.label}` at `{colors.muted-ink}`
- **Spacing**: Generous line spacing between links, creating monumental list appearance

## Responsive behavior

The design is documented from a desktop viewport. At narrower widths, the massive hero-display type should scale down to preserve legibility and avoid excessive horizontal scrolling—consider a reduction to 4rem or 5rem on tablet and 3rem on mobile. The four-column capabilities grid should collapse to two columns on tablet and single column on mobile, maintaining the vertical stack of headline, text, and tags within each service block.

The logo grid, currently showing approximately eight columns, should reduce column count proportionally: five to six columns on tablet, three to four on mobile. The footer navigation stack may remain vertical but should reduce type size to prevent excessive wrapping.

The retro contact form, being a fixed-proportion hardware object, should scale to fit within the viewport without cropping, potentially reducing to 80% or 90% of viewport width on smaller screens. The hands framing the device may need to be repositioned or hidden at extreme narrow widths to preserve the form's usability.

Touch targets for navigation and the submit action should maintain minimum 44px height. The email input in the newsletter capture and all fields in the retro form should use appropriate mobile input types and prevent zoom on focus.

## Practical implementation guidance

### Preserve
- The absolute black canvas as the dominant ground; any deviation weakens the system's impact
- The extreme scale contrast between hero-display and body type
- The single orange accent used sparingly and only for interactive emphasis
- The bordered logo grid as a signature social-proof pattern
- The retro hardware form as a distinctive interactive moment with its phosphor-orange screen treatment

### Avoid
- Introducing additional accent colors; the monochrome-plus-orange structure is intentionally severe
- Using borders heavier than 1px for dividers or cells
- Applying border-radius to the logo grid cells; the sharp rectangular tessellation is essential
- Setting hero-display type in weights heavier than 200; the ethereal quality depends on the ultra-light stroke
- Adding gradient backgrounds or drop shadows to interface elements

### Recommended build order
1. Establish the black canvas and Geist family for body text and navigation
2. Implement the hero section with viewport-width display type and photographic background
3. Build the logo grid with 1px bordered cells and centered marks
4. Create the capabilities section with four-column responsive grid and pill tags
5. Add the footer with newsletter capture and vertical navigation
6. Implement the retro contact form as an overlay with hardware styling and orange screen text

### Accessibility
- Ensure the orange accent on black meets WCAG AA contrast ratios for interactive elements; the current #ff5500 against #000000 achieves this for large text and UI components
- Provide visible focus indicators that extend beyond color alone, such as outline offsets on navigation links and form controls
- The retro form's orange-on-black screen text should be verified at small sizes; consider increasing weight or size if needed for the monospace-style treatment
- Maintain semantic heading hierarchy despite the visual flattening: the hero tagline should be h1, section headlines h2, service titles h3
- Ensure the email input and all retro form fields have associated labels, not just placeholder text

## Scope note

This guide covers the homepage surface including hero, capabilities, logo grid, footer, and the retro-styled contact overlay. Interior pages, mobile-specific layouts, motion behavior, hover states, and loading sequences are not represented in the supplied material. Measurements are practical adaptation targets derived from the visible desktop compositions.


---
# Design Reference: COSMOS.SO
---

# How cosmos.so is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/cosmos.so-design)

Last updated: 2026-08-08

## Captured pages

[![Centered sign-up hero with drifting tiles and oversized COSMOS wordmark](https://pin.fontofweb.com/8596?format=jpg)](https://design.withfudge.com/share/pin-8596)

[Centered sign-up hero with drifting tiles and oversized COSMOS wordmark](https://design.withfudge.com/share/pin-8596)

[![Editorial page with a tall image card between a big headline and side copy](https://pin.fontofweb.com/8594?format=jpg)](https://design.withfudge.com/share/pin-8594)

[Editorial page with a tall image card between a big headline and side copy](https://design.withfudge.com/share/pin-8594)

[![Three-card comparison row under a centered headline on a white field](https://pin.fontofweb.com/3791?format=jpg)](https://design.withfudge.com/share/pin-3791)

[Three-card comparison row under a centered headline on a white field](https://design.withfudge.com/share/pin-3791)

[![Dark mobile workspace with a top chip row and a mostly empty canvas](https://pin.fontofweb.com/8595?format=jpg)](https://design.withfudge.com/share/pin-8595)

[Dark mobile workspace with a top chip row and a mostly empty canvas](https://design.withfudge.com/share/pin-8595)

[![Sparse dark profile page with a compact chip row and little content](https://pin.fontofweb.com/3239?format=jpg)](https://design.withfudge.com/share/pin-3239)

[Sparse dark profile page with a compact chip row and little content](https://design.withfudge.com/share/pin-3239)

## Overview

Cosmos.so feels like a calm discovery system built from a paper-white canvas, a black typographic spine, and a loose field of rounded image tiles. The page is not dense or dashboard-like. It opens with a centered call to action surrounded by floating thumbnails, then moves into editorial chapters where a single headline, one image, and a short explanatory block do most of the work. Further down, a three-card comparison row turns the interface into a clearer product explanation, and the dark app shell at the end shifts the mood without changing the restraint.

The strongest pattern is contrast through spacing, not decoration. Large empty margins let the typography breathe, the rounded pills keep interactions soft, and the image collage brings color only where the page wants attention to drift. The whole system reads as curated, minimal, and image-led.

## Colors

Cosmos keeps the interface almost monochrome. Warm paper tones and white surfaces carry the reading experience, black ink supplies the main contrast, and a muted gray handles quieter text. Color appears most clearly in the floating thumbnail collage and in the comparison cards, where the page allows cool blues, lilacs, roses, and olive notes to surface. Those tones should stay secondary so the interface still feels like a clean discovery product rather than a colorful control panel.

### Core UI colors

| token | value | use |
|---|---|---|
| `action` | `#000000` | Solid primary pills, the COSMOS wordmark, and strong emphasis |
| `ink` | `#000000` | Main headlines and body text on light surfaces |
| `mutedInk` | `#6E6962` | Supporting copy, captions, and quieter link text |
| `canvas` | `#F7F4ED` | Page background and the open space around major sections |
| `surface` | `#FFFFFF` | White cards, ghost buttons, and small top-bar chips |
| `surfaceDark` | `#000000` | The dark app stage and high-contrast end sections |
| `border` | `#DDD6CB` | Hairline outlines and card edges |
| `onDark` | `#F7F4ED` | Text and icons on the dark stage |

### Image-led tones

| token | value | use |
|---|---|---|
| `imageBlue` | `#4A87D6` | Blue-toned thumbnail fragments and cool image accents |
| `imageLilac` | `#D4A7D7` | Lilac thumbnail fragments and soft collage accents |
| `imageRose` | `#E3C0BD` | Rose thumbnail fragments and warm collage accents |
| `imageOlive` | `#B7B39B` | Olive thumbnail fragments and muted collage accents |

The light system should stay mostly paper white and black. The darker chapter should switch to `surfaceDark` with `onDark` text, while the colored thumbnail tones should never take over buttons, borders, or background shells. Keep the contrast simple in chrome and let the imagery carry the variety.

## Typography

Cosmos uses two families with different jobs. Favorit carries the interface and editorial reading rhythm, while Cosmos Oracle can support the oversized brand wordmark and any moment that needs a more sculpted, logo-like presence. The scale is bold but not noisy: large headings, short supporting copy, and tiny quiet labels. Spacing in the type system comes from size jumps and tight tracking more than from heavy weight changes.

Verify licensing for these families before production use.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| `brandWordmark` | Cosmos Oracle | 7.5rem | 400 | 0.88 | -0.05em | Huge COSMOS logotype at the bottom of the hero |
| `heroDisplay` | Favorit | 4rem | 400 | 0.95 | -0.04em | Large centered statements and main page hooks |
| `sectionDisplay` | Favorit | 3.5rem | 400 | 0.95 | -0.035em | Big editorial headlines beside image cards |
| `cardHeading` | Favorit | 1.5rem | 400 | 1.1 | -0.02em | Card titles and short section labels |
| `body` | Favorit | 1rem | 400 | 1.5 | 0em | Explanatory paragraphs and supporting text |
| `bodyMedium` | Favorit | 1rem | 500 | 1.45 | 0em | Buttons, chips, and short emphasized copy |
| `label` | Favorit | 0.75rem | 500 | 1.2 | 0.08em | Tiny upper labels and chip text |
| `legalCopy` | Favorit | 0.75rem | 400 | 1.4 | 0em | Footer text, legal lines, and minor metadata |

The large headings should feel almost airless, with compact line height and slightly tightened tracking. Body copy should open up enough to read easily against the wide layouts. Labels should stay small, quiet, and precise. Avoid adding a second decorative family for emphasis; the system already gets its character from scale, contrast, and the brand wordmark.

## Layout

The layout is built from wide, centered chapters with generous negative space between them. The hero is the most open section: a small line of copy sits above the main action, the primary pill anchors the center, and small floating tiles drift around the composition while the huge wordmark sits low and wide. That structure makes the page feel airy even before the user reaches the product explanation.

Below the hero, the design turns more editorial. One section pairs a big headline on the left with a tall, rounded image card in the middle and a short supporting paragraph on the right. The image card is the anchor, so the text stays brief and aligned to its edges. Another section uses a three-column comparison row under a centered headline. The cards are evenly spaced and similarly sized, which gives the page a calm explanatory rhythm after the looser hero.

The dark chapter changes the tone without changing the structure. It uses a near-black shell, small top-right controls, and large empty fields that leave the interface breathing room. The layout depends on repetition of rounded rectangles, consistent gutters, and strong horizontal alignment. Use `spacing.hero` for the largest open vertical moments, `spacing.wide` for chapter separation, and `spacing.gutter` to keep the cards from feeling crowded. Smaller controls can sit on `spacing.compact` and `spacing.control` so the interaction layer stays light.

## Visual language

Cosmos is quiet, curated, and slightly playful. The floating thumbnail tiles give the page motion without using animation language in the layout itself. Their rounded corners, soft edges, and varied image content make the page feel like a collection wall. The monochrome chrome keeps that collage from becoming busy. Black pills, white chips, and dark shells create a very stable frame around the imagery.

The system also likes contrast between softness and structure. Pills are fully rounded and friendly, but the headline typography is severe and direct. The image cards are tall and rounded, while the text around them stays open and linear. That balance makes the page feel premium without becoming formal. Flat fills work better than heavy shadows here; the visual interest comes from spacing, image tone, and the shift between paper-white and near-black surfaces. Keep borders light and sparse so the layout keeps its gallery-like calm.

## Components

### Hero stage

- **Anatomy:** A small line of supporting copy, one primary pill, one secondary pill, scattered floating tiles, and the oversized COSMOS wordmark.
- **Surface:** `canvas` for the open field; `action` for the primary pill; `surface` for the secondary pill.
- **Typography:** `bodyMedium` for the pills and `brandWordmark` for the bottom wordmark.
- **Shape:** Use `pill` for the two actions and `tile` for the drifting thumbnails.
- **Composition:** Keep the action centered and the wordmark low and wide. The tiles should feel dispersed, not grouped into a grid.
- **Visible states:** The primary action is solid black with light text. The secondary action is white with a light border and dark text.

### Editorial story card

- **Anatomy:** A tall image card, a large headline block, and a short supporting paragraph.
- **Surface:** White card face on the paper canvas, with the image filling most of the vertical space.
- **Typography:** `sectionDisplay` for the headline and `body` for the supporting text.
- **Shape:** `panel` corners make the card feel substantial without becoming heavy.
- **Spacing:** Keep a wide gutter between headline, image, and supporting text so each part can read on its own.
- **Composition:** Let the image carry the middle of the section. The text should remain brief and aligned to the visual edges of the card.

### Comparison row

- **Anatomy:** Three equal cards with different internal fields and a short label beneath each one.
- **Surface:** Neutral white or canvas-backed cards with image-led color inside the card area.
- **Typography:** `cardHeading` for the card copy and `label` for the small captions below.
- **Shape:** The same panel radius across all three cards keeps the row balanced.
- **Spacing:** Use consistent horizontal gaps and equal vertical alignment so the row reads like one system, not three separate features.
- **Composition:** The cards should be visually distinct through tone, not through size. Blue, slate, and deep indigo fields work well because they preserve the page’s quiet feel.

### Dark app shell

- **Anatomy:** A top-right chip row, a mostly empty black workspace, and a floating round control near the lower edge.
- **Surface:** `surfaceDark` with `onDark` text and light controls.
- **Typography:** `bodyMedium` for the top chips and `body` or `label` for tiny utility text.
- **Shape:** Rounded chips and a soft circular control keep the dark stage from feeling rigid.
- **Spacing:** Leave large amounts of empty black space. The emptiness is part of the composition.
- **Composition:** Keep the controls close to the top edge and the workspace otherwise sparse. The page should feel focused, not filled.

### Top bar chip

- **Anatomy:** Compact rounded buttons, small utility icons, and a colored avatar dot.
- **Surface:** White chips against the surrounding dark or light field.
- **Typography:** `bodyMedium` so the labels stay legible at small size.
- **Shape:** `pill` radii with small horizontal padding.
- **Visible states:** Solid chips are used for the strongest action; lighter chips and simple icons stay visually quieter.
- **Composition:** Group the controls tightly so they feel like a single toolbar rather than scattered buttons.

## Responsive behavior

On smaller screens, keep the order of information intact: hero message first, action next, image or tile collage after that, then supporting details. The oversized wordmark should shrink without losing its wide, low placement. The three-card comparison row should stack cleanly, with consistent gaps and captions that remain attached to their cards. The dark shell should keep its sparse feel, with controls compressed into one compact top row and enough empty space below to preserve the mood. Favor vertical flow over nested side-by-side layouts once the width gets tight.

## Practical implementation guidance

### Preserve

- Keep the page mostly paper white and black in chrome.
- Let the floating thumbnail collage provide color, not the controls.
- Use large type with tight tracking and short blocks of copy.
- Keep rounded pills and rounded cards consistent across the system.
- Preserve the large gaps between sections so the page feels editorial.

### Avoid

- Avoid bright brand colors in navigation, buttons, or borders.
- Avoid dense card shadows or heavy framing.
- Avoid mixing too many radii in one section.
- Avoid long paragraphs beside the biggest headlines.
- Avoid making the thumbnail colors into global chrome colors.

### Recommended build order

1. Build the canvas, ink, and spacing foundation.
2. Add the primary and secondary pill actions.
3. Recreate the hero composition with floating tiles and the wordmark.
4. Build the editorial image card and supporting text layout.
5. Add the comparison row with three equal cards.
6. Finish with the dark app shell and compact top controls.
7. Check the mobile stack so the reading order stays intact.

### Accessibility

- Keep text over imagery backed by strong contrast.
- Make every pill and chip large enough to tap comfortably.
- Use distinct visual cues for the primary and secondary actions.
- Do not rely on color alone to distinguish the comparison cards.
- Keep text alternatives useful for the floating thumbnails and the tall image card.

## Scope note

This guide covers cosmos.so’s homepage hero, editorial story card, comparison row, and dark app shell. Mobile-specific layouts, motion, and interaction states are not included. Measurements are practical adaptation targets for implementation.


---
# Design Reference: ARC.NET
---

# How arc.net is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/arc.net-design)

Last updated: 2026-08-10

## Captured pages

[![Hero section with electric-blue textured background, large white display quote, and paired download buttons for Mac and Windows](https://pin.fontofweb.com/4907?format=jpg)](https://design.withfudge.com/share/pin-4907)

[Hero section with electric-blue textured background, large white display quote, and paired download buttons for Mac and Windows](https://design.withfudge.com/share/pin-4907)

[![Testimonial grid on cream background with electric-blue quotes, followed by a solid blue CTA band and textured footer](https://pin.fontofweb.com/4909?format=jpg)](https://design.withfudge.com/share/pin-4909)

[Testimonial grid on cream background with electric-blue quotes, followed by a solid blue CTA band and textured footer](https://design.withfudge.com/share/pin-4909)

[![Browser window mockup showing Arc's sidebar with Spaces and Profiles, featuring a purple-tinted architecture website](https://pin.fontofweb.com/4908?format=jpg)](https://design.withfudge.com/share/pin-4908)

[Browser window mockup showing Arc's sidebar with Spaces and Profiles, featuring a purple-tinted architecture website](https://design.withfudge.com/share/pin-4908)

[![Developers page with dark slate background, white testimonial quote, and browser screenshot showing code editor and map](https://pin.fontofweb.com/4910?format=jpg)](https://design.withfudge.com/share/pin-4910)

[Developers page with dark slate background, white testimonial quote, and browser screenshot showing code editor and map](https://design.withfudge.com/share/pin-4910)

## Overview

Arc's marketing site presents a browser as a cultural object rather than a utility. The design language is built on electric-blue dominance, high-contrast white typography, and playful surface textures that suggest both technical precision and creative warmth. The homepage moves through distinct atmospheric zones: a textured electric-blue hero with oversized display quotes, a cream-colored social-proof band with electric-blue testimonials, and a solid blue conversion footer. The developers page inverts this logic, using a dark slate canvas with white type to signal technical depth. Throughout, the system relies on expressive display typography—heavy, tightly tracked sans-serifs for headlines, clean geometric sans for body copy, and a monospace face for labels and attributions. The result is a site that feels simultaneously confident and approachable, premium without austerity.

## Colors

The palette is intentionally small and high-contrast, built around a signature electric blue that functions as both background and accent. Darker and lighter variants support hierarchy without diluting brand recognition.

| token | value | use |
|---|---|---|
| electric-blue | #3B3BFF | Primary brand color; hero backgrounds, testimonial text, footer surfaces, active states |
| deep-indigo | #1A1A8C | Announcement bar backgrounds, secondary button fills, hover depths |
| cream | #FFFEF0 | Testimonial section backgrounds, light-mode canvas alternative |
| ink | #000000 | Body text on light surfaces, code editor chrome, technical UI elements |
| white | #FFFFFF | Hero display text, primary button fills, navigation on dark backgrounds |
| muted-ink | #6B6B8C | Secondary body text, captions, inactive navigation states |

The electric-blue serves as the dominant atmospheric color, appearing in textured hero fields, solid CTA bands, and as the text color for testimonials on cream. Deep-indigo provides depth for announcement bars and secondary actions. Cream offers warmth and visual rest between high-energy blue sections. Ink and white establish the core reading contrast, with muted-ink reserved for de-emphasized content. The developers page introduces a dark slate field that reads as a near-black with subtle warmth, treated here as an extension of ink rather than a separate token.

## Typography

The type system combines three distinct voices: a heavy display family for headlines, a clean geometric sans for interface and body text, and a monospace face for technical labels and attributions.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Marlin Soft-Extra Black | 4rem | 900 | 1 | -0.02em | Homepage hero quotes, major section headlines |
| section-display | Marlin Soft Sq | 2.5rem | 700 | 1.1 | -0.01em | Testimonial quotes, feature headlines |
| body | Inter | 1rem | 400 | 1.5 | 0 | Descriptions, explanatory copy, navigation |
| body-large | Inter | 1.25rem | 400 | 1.5 | 0 | Introductory paragraphs, emphasized descriptions |
| label | Abc Favorit Mono | 0.75rem | 700 | 1.2 | 0.05em | Attribution pills, button text, category labels |
| navigation | Inter | 0.875rem | 400 | 1.4 | 0 | Primary navigation, announcement bar text |

Marlin Soft-Extra Black and Marlin Soft Sq, designed by Michael Hagemann, provide the system's expressive weight. Inter, designed by Rasmus Andersson and available from Rsms, handles all functional reading. Abc Favorit Mono, designed by Johannes Breyer, Fabian Harb, and Chi Long Trieu for Dinamo, supplies the technical voice. Verify licensing for these families before production use.

Font sizes are set in rem at whole-number multiples of 0.25rem. The hero-display at 4rem (64px) and section-display at 2.5rem (40px) create clear hierarchy. Body text at 1rem (16px) maintains standard readability, while body-large at 1.25rem (20px) serves introductory content with greater presence. Label at 0.75rem (12px) provides fine-grained UI text with slight positive tracking for all-caps or small-caps treatments.

## Layout

The page architecture uses full-bleed atmospheric bands that stack vertically, each with distinct color and texture treatments. The hero occupies the full viewport width with centered content and generous vertical padding. Navigation sits fixed or sticky at the top, with a logo mark, text links, and a download button arranged horizontally.

Content within bands is typically centered with a max-width container, estimated at approximately 75rem (1200px) based on comfortable reading measure and button placement. The testimonial grid uses a four-column layout on desktop, with each quote centered within its column and attribution pills below. The footer converts to a two-zone layout: navigation links on the left, company mark on the right, with social icons anchored near the link columns.

Spacing between sections is dramatic, using 6rem (96px) or greater to create clear atmospheric shifts. Within components, 1.5rem (24px) separates related elements like headlines and body copy, or quotes and attributions. Buttons carry 0.75rem (12px) vertical padding and 1.5rem (24px) horizontal padding, creating pill-like proportions without full circularity.

The developers page narrows the content focus, centering a single testimonial with supporting screenshot below. The browser mockup receives subtle shadow treatment and rounded corners, floating above the textured background to suggest depth without breaking the flat graphic language.

## Visual language

Surface texture is a defining characteristic. The electric-blue backgrounds carry a fine grain or noise texture that prevents flatness and suggests digital materiality. This texture appears consistently across the hero, footer, and announcement bar, unifying disparate page sections. The cream testimonial band is smooth, providing tactile contrast to the textured fields.

Decorative elements include wavy horizontal rules that separate major zones—these appear as scalloped or zigzag edges in deep-indigo against electric-blue, or electric-blue against cream. A circular "Now Available on Windows" stamp appears in the hero, adding a playful, almost sticker-like quality to the otherwise clean composition. Small emoji-style icons (peace sign, heart, sparkle) appear above the testimonial grid, reinforcing the personable brand voice.

The browser mockups are presented with realistic chrome—traffic lights, address bar, sidebar—rendered in a flattened, illustrative style rather than photorealistic. This maintains the graphic unity of the page while still communicating product function. Screenshots within the browser frame show actual interface states: code editors, maps, web pages, reinforcing the product's utility through contextual demonstration.

## Components

### Primary button

- **Anatomy**: Icon prefix (Apple logo or Windows grid), label text, full background fill
- **Surface**: White background on electric-blue or deep-indigo fields; deep-indigo background when appearing on white or cream
- **Typography**: `{typography.label}` in all-caps or title-case with tracking
- **Shape**: 0.75rem border radius, creating a rounded rectangle rather than a full pill
- **Spacing**: 0.75rem vertical padding, 1.5rem horizontal padding
- **Composition**: Centered within its container, often paired with a secondary button variant
- **Variants**: White fill with electric-blue text (primary), deep-indigo fill with white text (secondary/inverted)

### Secondary button

- **Anatomy**: Icon prefix, label text, full background fill
- **Surface**: Deep-indigo background, white text
- **Typography**: `{typography.label}`
- **Shape**: 0.75rem border radius
- **Spacing**: Matches primary button
- **Composition**: Appears adjacent to primary button, slightly subordinate in visual weight

### Testimonial quote

- **Anatomy**: Opening quotation mark glyph, quote text, closing quotation mark glyph, attribution line below
- **Surface**: Electric-blue text on cream background; white text on dark slate (developers page)
- **Typography**: `{typography.section-display}` for quote, `{typography.label}` for attribution
- **Shape**: Text wraps naturally, no containing border
- **Spacing**: 1.5rem between quote and attribution, generous vertical padding within the band
- **Composition**: Centered within grid column, four columns across on desktop

### Attribution pill

- **Anatomy**: Handle or name text, optional border container
- **Surface**: Transparent with 1px electric-blue border; or text-only without border
- **Typography**: `{typography.label}` in uppercase with positive tracking
- **Shape**: Full pill border radius (9999px) when bordered
- **Spacing**: Horizontal padding approximately 1rem, vertical padding 0.5rem
- **Composition**: Centered below quote, or inline with quote text

### Announcement bar

- **Anatomy**: Text message, arrow indicator, product icon (Dia browser)
- **Surface**: Deep-indigo background, white text
- **Typography**: `{typography.navigation}`
- **Shape**: Full-width band, wavy or scalloped bottom edge
- **Spacing**: Compact vertical padding, approximately 0.75rem
- **Composition**: Centered text with icon positioned to the right of the message

### Navigation bar

- **Anatomy**: Logo mark, text links (Max, Mobile, Developers, Students, Blog), download button
- **Surface**: Transparent over textured electric-blue, or matching background
- **Typography**: `{typography.navigation}` for links, `{typography.label}` for button
- **Shape**: No visible container, links as plain text
- **Spacing**: Horizontal distribution with logo left, links center-left, button right
- **Composition**: Flex row with space-between logic

### Footer

- **Anatomy**: Link columns (Product, Resources), social icons, company mark and location
- **Surface**: Textured electric-blue matching hero
- **Typography**: `{typography.navigation}` for links, `{typography.label}` for column headers
- **Shape**: No containing card, full-bleed band
- **Spacing**: Generous top padding, moderate gap between link rows
- **Composition**: Left-aligned link clusters, right-aligned company mark with decorative underline

## Responsive behavior

The four-column testimonial grid should collapse to two columns on tablet and single column on mobile, maintaining centered text alignment throughout. Hero display text should scale down to approximately 2.5rem on narrow viewports to prevent overflow. Navigation links should collapse to a menu trigger or horizontal scroll when space is constrained.

The announcement bar may wrap to two lines on mobile; the product icon should remain adjacent to the text rather than breaking to a new line. Browser mockups should scale proportionally, potentially switching from side-by-side layouts to stacked single views. Button pairs should stack vertically on mobile with the primary action above the secondary.

The textured backgrounds should maintain their grain quality across densities; consider a slightly larger noise tile on high-DPI displays to prevent moiré patterns.

## Practical implementation guidance

### Preserve
- The electric-blue textured surface as the primary brand atmosphere—this texture is not decorative excess but core identity
- The three-typeface hierarchy: heavy display, clean sans, monospace label
- High-contrast white-on-blue for hero moments, blue-on-cream for social proof
- The wavy section dividers as zone-transition markers
- Centered, generous spacing that lets display type breathe

### Avoid
- Flat, untextured electric-blue backgrounds—the grain is essential to the material quality
- Adding more than one or two additional colors; the palette's restraint is part of its impact
- Tightening letterspacing on body text; the display tracking is specific to headline sizes
- Replacing the monospace label face with a proportional sans, which would lose the technical voice
- Cluttering the hero with multiple messages; the single-quote format is proven

### Recommended build order
1. Establish the textured electric-blue surface and noise/grain implementation
2. Set up the type hierarchy with Marlin display, Inter body, and Favorit Mono labels
3. Build the navigation and announcement bar as shared top elements
4. Implement the hero section with display quote and button pair
5. Create the testimonial grid with attribution pills
6. Add the footer with link columns and company mark
7. Adapt the developers page variant with dark slate surface

### Accessibility
- Ensure the textured electric-blue background meets contrast requirements with white text; the deep-indigo variant may be needed for smaller text
- Provide visible focus states for navigation links and buttons, using outline or background shift rather than relying on color change alone
- Maintain keyboard operability for the announcement bar as a clickable region
- Consider reduced-motion preferences for any scroll-triggered animations; the static design should communicate fully without motion
- Test the grain texture at high zoom levels to ensure it does not interfere with text legibility for low-vision users

## Scope note

This guide covers the Arc marketing homepage and developers landing page as visible in desktop screenshots. Mobile layouts, additional product pages, and interactive states such as hover, focus, and loading are not represented. Motion design, video backgrounds, and the browser application interface itself are outside this scope. Measurements are practical adaptation targets derived from visible proportions.


---
# Design Reference: EXOAPE.COM
---

# How exoape.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/exoape.com-design)

Last updated: 2026-08-10

## Captured pages

[![Hero viewport with full-bleed twilight basilica photography, oversized white display typography, and minimal top navigation on a cinematic blue gradient.](https://pin.fontofweb.com/5739?format=jpg)](https://design.withfudge.com/share/pin-5739)

[Hero viewport with full-bleed twilight basilica photography, oversized white display typography, and minimal top navigation on a cinematic blue gradient.](https://design.withfudge.com/share/pin-5739)

[![Dark immersive section with large warm-tan display heading, orbital 3D render, and structured multi-column footer with address and social links.](https://pin.fontofweb.com/5740?format=jpg)](https://design.withfudge.com/share/pin-5740)

[Dark immersive section with large warm-tan display heading, orbital 3D render, and structured multi-column footer with address and social links.](https://design.withfudge.com/share/pin-5740)

[![Contact page with split white background, oversized multilingual display type, portrait photography, and underlined contact details with bullet markers.](https://pin.fontofweb.com/5742?format=jpg)](https://design.withfudge.com/share/pin-5742)

[Contact page with split white background, oversized multilingual display type, portrait photography, and underlined contact details with bullet markers.](https://design.withfudge.com/share/pin-5742)

[![Our Story section with black background, warm-tan hero typography, elliptical 3D render, and organized footer columns with navigation and social links.](https://pin.fontofweb.com/5741?format=jpg)](https://design.withfudge.com/share/pin-5741)

[Our Story section with black background, warm-tan hero typography, elliptical 3D render, and organized footer columns with navigation and social links.](https://design.withfudge.com/share/pin-5741)

## Overview

Exo Ape's design system is built around cinematic visual storytelling that alternates between immersive darkness and pristine light. The studio presents itself through full-bleed photography, atmospheric 3D renders, and typography that commands attention through scale rather than weight. The visual language speaks to a global digital practice—multilingual, boundary-crossing, and technologically sophisticated.

The system operates in two primary modes: a dark immersive mode where near-black backgrounds let warm-tan typography and luminous imagery become the focal point, and a light editorial mode where white canvases support bold black display type with documentary photography. This duality creates rhythm across the experience, with each mode serving different narrative purposes. The dark mode carries emotional weight and mystery; the light mode delivers clarity and direct communication.

Navigation remains deliberately minimal, appearing as understated text links or a simple menu trigger, never competing with the visual content. The overall impression is of a studio confident enough to let space, type, and image do the work without decorative embellishment.

## Colors

| token | value | use |
|---|---|---|
| ink | `#000000` | Primary text on light backgrounds, dark section backgrounds, footer surfaces |
| canvas | `#ffffff` | Light page backgrounds, contact page base, hero text on photographic scenes |
| warm-tan | `#dcc8b8` | Display headings on dark backgrounds, accent text in story sections, footer links |
| deep-space | `#0a0a0a` | Near-black section backgrounds for immersive content areas |
| muted-ink | `#1a1a1a` | Subtle dark variation for layered surfaces, footer columns |

The color system is intentionally restrained, functioning as a stage for photography and 3D imagery rather than competing with it. Black and white establish the foundational contrast, with warm-tan serving as the singular emotional accent that humanizes the otherwise stark palette. This tan appears exclusively on dark backgrounds, where its muted warmth creates an organic counterpoint to digital renders and architectural photography.

The dark mode dominates the experience, with sections plunging into deep-space and ink tones that allow luminous imagery—glowing orbital rings, lit screens, twilight skies—to become the true color events. The light mode appears strategically for contact and informational pages, where readability and openness take precedence. No gradients or shadows are employed as structural elements; all depth comes from photography and deliberate spatial composition.

## Typography

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Twk Lausanne-300 | 8rem | 300 | 0.9 | -0.03em | Homepage hero words, massive viewport-filling statements |
| section-display | Twk Lausanne-300 | 6rem | 300 | 0.95 | -0.02em | Section headings like "Our Story", multilingual contact headers |
| body-large | Twk Lausanne-300 | 1.25rem | 300 | 1.5 | 0 | Introductory paragraphs, descriptive copy |
| body | Twk Lausanne-300 | 1rem | 300 | 1.6 | 0 | Footer addresses, contact details, general content |
| label | Twk Lausanne-300 | 0.875rem | 300 | 1.4 | 0.01em | Small metadata, captions, secondary information |
| navigation | Twk Lausanne-300 | 0.875rem | 300 | 1 | 0 | Top navigation links, menu triggers |

The typographic system relies on a single family, Twk Lausanne-300, designed by Nizar Kazan and available through Typeweltkern. The 300 weight is used exclusively across all roles, creating consistency through weight rather than contrast. The design achieves hierarchy through dramatic scale differences rather than boldness, with display sizes reaching 8rem while body text remains light and airy.

Tight negative tracking on display sizes (-0.03em to -0.02em) gives large headings a refined, editorial density. Line heights are compressed for display use (0.9–0.95) to create solid typographic blocks that feel architectural and intentional. Body text receives more generous leading (1.5–1.6) for comfortable reading.

Verify licensing for Twk Lausanne-300 through Typeweltkern before production use.

## Layout

The layout system is built on expansive spatial generosity. Sections frequently occupy full viewport height or greater, with content positioned asymmetrically rather than centered. The grid is loose and editorial—elements align to invisible margins rather than rigid columns, creating a sense of curated placement.

Horizontal padding is substantial, approximately 4rem to 6rem from viewport edges, giving content room to breathe. Vertical rhythm is driven by section breaks of 6rem or more, with internal spacing between text blocks typically 2rem. The contact page demonstrates a split composition: oversized display type occupies the left portion while a portrait photograph anchors the right, with contact details floating in the lower left at comfortable remove from the heading.

The footer organizes into multiple columns—address, navigation links, social links—spaced evenly across the width with thin horizontal rules separating footer from content above. This multi-column structure repeats consistently across dark sections.

Navigation sits fixed or absolute at the top, with the logo mark on the left and text links or menu trigger on the right. On the homepage hero, navigation overlays the photographic content directly, relying on sufficient contrast for legibility.

## Visual language

The visual language merges documentary realism with speculative digital aesthetics. Photography tends toward architectural and environmental subjects—twilight cityscapes, interior workspaces, historic buildings—captured in natural or available light with muted, atmospheric color. These images fill viewports edge-to-edge, serving as both content and background.

3D renders introduce a contrasting synthetic element: orbital rings, planetary bodies, and abstract geometric forms rendered with physical accuracy but impossible scale. These elements glow with warm light against void-black backgrounds, creating moments of wonder that offset the grounded photography.

The logo mark—a stylized primate face in profile—appears small and discrete, rendered in white or black depending on background. It carries a subtle sparkle or star accent, suggesting exploration and discovery without literal space imagery.

Typography itself becomes a visual element at display sizes, with characters large enough to read as shapes rather than merely words. The multilingual contact header demonstrates this: Chinese characters and Latin letters share equal visual weight, both treated as graphic forms at massive scale.

## Components

### Hero Section

- **Anatomy**: Full-bleed background image or video, overlaid navigation bar, massive display typography positioned lower-left or center-left, optional scroll indicator
- **Surface**: Background image dominates; text in pure white (`{colors.canvas}`) with no backing surface
- **Typography**: `{typography.hero-display}` for primary statement words
- **Shape**: No border radius; edges are crisp and photographic
- **Spacing**: Generous internal padding, text positioned well above bottom edge with comfortable margin
- **Composition**: Asymmetric, with text block occupying roughly 40% of width and positioned to avoid conflicting with image focal points

### Story Section

- **Anatomy**: Dark background panel, large display heading left-aligned, 3D render or image right-aligned, descriptive paragraph below heading, horizontal rule, multi-column footer
- **Surface**: `{colors.ink}` or `{colors.deep-space}` background; heading in `{colors.warm-tan}`; body text in muted warm tone
- **Typography**: `{typography.section-display}` for heading, `{typography.body-large}` for description
- **Shape**: Sharp rectangular edges throughout
- **Spacing**: Heading sits high in section with substantial gap to description text; footer columns begin below horizontal rule with 4rem+ top padding
- **Composition**: Two-zone layout with text left and visual right; footer spans full width below

### Contact Section

- **Anatomy**: Light background, oversized multilingual heading, supporting paragraph, bullet-marked contact links with underlines, portrait photograph, address block, map link
- **Surface**: `{colors.canvas}` background; text in `{colors.ink}`; links underlined
- **Typography**: `{typography.section-display}` for heading, `{typography.body}` for details and links
- **Shape**: No border radius; photograph is rectangular with sharp edges
- **Spacing**: Heading positioned upper-left with generous margin; photograph floats right at partial width; contact details cluster lower-left with bullet markers
- **Composition**: Asymmetric two-column feel with text dominant left and image anchoring right

### Footer

- **Anatomy**: Multi-column grid containing address block, navigation links, social platform links, occasional additional link with bullet marker
- **Surface**: Inherits parent section background (typically `{colors.ink}`); text in `{colors.warm-tan}` or muted equivalent
- **Typography**: `{typography.body}` for all content; links appear as plain text without button styling
- **Shape**: No border radius; separated from content by thin horizontal rule
- **Spacing**: Columns evenly distributed with consistent internal line height; substantial top and bottom padding
- **Composition**: Three to four columns on desktop, address leftmost, navigation center, social rightmost

### Navigation Bar

- **Anatomy**: Logo mark left, text links or menu trigger right
- **Surface**: Transparent, adapting to underlying content
- **Typography**: `{typography.navigation}` for links
- **Shape**: No background shape or border
- **Spacing**: Full width with horizontal padding matching section gutters
- **Composition**: Flex row, space-between alignment

## Responsive behavior

The system is documented from desktop viewports. At narrower widths, the massive display typography should scale down proportionally, maintaining hierarchy while preserving readability. The hero display at 8rem may reduce to 4rem or 3rem on tablet, and to 2.5rem on mobile, always remaining a whole-number multiple of the 0.25rem base unit.

The asymmetric two-column layouts—story section with text left and render right, contact section with heading left and portrait right—should stack vertically on narrow viewports, with text preceding imagery. Footer columns should collapse to single-column stacked lists with increased vertical spacing between groups.

Navigation text links visible in the homepage hero should condense to a single "Menu" trigger or hamburger icon on smaller screens, preserving the minimal aesthetic while accommodating touch targets. The logo mark should remain consistently sized and positioned.

Full-bleed photography should maintain coverage without cropping critical subjects; consider `object-fit: cover` with focal-point awareness. The massive display type that overlays photography on the homepage may require text-shadow or subtle darkening gradient to maintain contrast if the underlying image shifts on resize.

## Practical implementation guidance

### Preserve
- The stark weight-300 consistency across all typographic roles; do not introduce bolder weights for hierarchy
- The generous spatial margins and asymmetric compositions; the design depends on breathing room
- The warm-tan accent exclusively for dark backgrounds; never use it on white
- The sharp, unrounded edges throughout; the system is deliberately rectilinear
- The multilingual capability of display type; test with CJK and extended Latin character sets

### Avoid
- Adding decorative borders, shadows, or background patterns that compete with photography
- Centering display headings; the asymmetric left alignment is integral to the character
- Using gradients as backgrounds or overlays; rely on photography and solid colors
- Introducing additional font weights or families; the single-weight discipline is essential
- Crowding the navigation with multiple elements; keep it minimal

### Recommended Build Order
1. Establish the typographic foundation with Twk Lausanne-300 at all defined sizes
2. Implement the dark/light section system with ink, deep-space, and canvas backgrounds
3. Build the hero section with full-bleed image and oversized display type
4. Create the story section with two-zone layout and footer pattern
5. Develop the contact section with asymmetric text-image composition
6. Add navigation with transparent overlay behavior
7. Refine responsive scaling for display typography and stacked layouts

### Accessibility
- Ensure text over photography meets contrast minimums; the homepage hero white text on twilight blue generally succeeds, but verify with actual image content
- Provide `aria-label` descriptions for the logo mark and menu trigger
- Maintain visible focus indicators for navigation links despite the minimal styling; consider underline or outline that respects the aesthetic
- The light weight of Twk Lausanne-300 at small sizes may challenge low-vision users; consider slightly increased size or tracking for critical small text
- Ensure interactive areas meet minimum 44×44dp touch targets when navigation condenses

## Scope note

This guide covers the homepage hero, story section, and contact page surfaces visible in the supplied images. Mobile breakpoints, animation behavior, hover states, form interactions, and additional interior pages are not represented. Measurements are practical adaptation targets derived from visual estimation against the 0.25rem base unit.


---
# Design Reference: PANGRAMPANGRAM.COM
---

# How pangrampangram.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/pangrampangram.com-design)

Last updated: 2026-08-10

## Captured pages

[![Eiko product page showing style list with Thin to Light Italic variants in light gray rounded cards, black preview area, and orange accent numerals](https://pin.fontofweb.com/9783?format=jpg)](https://design.withfudge.com/share/pin-9783)

[Eiko product page showing style list with Thin to Light Italic variants in light gray rounded cards, black preview area, and orange accent numerals](https://design.withfudge.com/share/pin-9783)

[![Neue Montreal product page featuring a dark carousel with metallic 3D chain imagery, white text overlay, and orange Branding pill badge](https://pin.fontofweb.com/8534?format=jpg)](https://design.withfudge.com/share/pin-8534)

[Neue Montreal product page featuring a dark carousel with metallic 3D chain imagery, white text overlay, and orange Branding pill badge](https://design.withfudge.com/share/pin-8534)

[![Neue Montreal Glyphs Set tab showing uppercase and lowercase letter grid in rounded light gray cells with selected glyph highlighted in black](https://pin.fontofweb.com/8533?format=jpg)](https://design.withfudge.com/share/pin-8533)

[Neue Montreal Glyphs Set tab showing uppercase and lowercase letter grid in rounded light gray cells with selected glyph highlighted in black](https://design.withfudge.com/share/pin-8533)

[![Neue Montreal glyph detail view with large white letter I on black background showing ascender, cap height, x-height, baseline, and descender metrics](https://pin.fontofweb.com/8532?format=jpg)](https://design.withfudge.com/share/pin-8532)

[Neue Montreal glyph detail view with large white letter I on black background showing ascender, cap height, x-height, baseline, and descender metrics](https://design.withfudge.com/share/pin-8532)

## Overview

Pangram Pangram's website is a type-centric showcase built around the dramatic presentation of fonts. The design system employs a stark, high-contrast visual language where black and white dominate, punctuated by a warm, aggressive orange that signals action and energy. The interface functions as both a catalog and a specimen viewer, with product pages organized into tabbed sections that let designers explore styles, glyph sets, variable axes, features, and font pairings.

The visual hierarchy relies on extreme scale contrasts. Massive display type—often set at sizes exceeding 80 pixels—anchors hero sections and specimen previews, while compact 14-pixel functional text handles navigation, labels, and metadata. This tension between monumental typography and restrained UI elements creates a gallery-like atmosphere where the fonts themselves become the artwork. Rounded corners appear throughout, from pill-shaped buttons to soft-cornered cards and circular glyph cells, lending a contemporary, approachable quality to an otherwise austere palette.

## Colors

The color system is intentionally minimal, built on a near-monochrome foundation with a single warm accent. Black serves as the primary surface for dramatic previews and active states, while a progression of warm grays provides subtle hierarchy for cards, borders, and backgrounds. The orange accent appears sparingly but decisively, reserved for primary actions, active navigation states, and numerical highlights.

| token | value | use |
|---|---|---|
| ink | #000000 | Primary text, active glyph cells, dark preview panels, primary backgrounds |
| ink-secondary | #151515 | Near-black for subtle depth on dark surfaces |
| ink-tertiary | #282828 | Dark gray for secondary text on light backgrounds |
| muted-ink | #666666 | Tertiary text, disabled states, metadata |
| border | #ABABAB | Hairline borders, dividers, inactive controls |
| surface | #D0D0D0 | Mid-gray for inactive or secondary surfaces |
| surface-light | #D9D9D9 | Light gray for hover states on interactive elements |
| canvas | #EDEDED | Card backgrounds, glyph cells, style list items |
| canvas-warm | #FAFAFA | Page background, header bar, lightest surface |
| action | #FF2F00 | Primary buttons, active navigation, accent numerals, badges |
| action-warm | #FFB700 | Secondary warm accent for gradients or highlights |
| white | #FFFFFF | Text on dark surfaces, inverted buttons, glyph preview characters |

The warm gray scale from #FAFAFA to #000000 creates a cohesive tonal range that avoids the sterility of pure neutral grays. Dark surfaces use pure black with white text for maximum contrast in specimen previews, while light surfaces use the warm canvas tones to keep the interface feeling tactile and paper-like. The orange accent (#FF2F00) is reserved for interactive emphasis—appearing in "Buy Now" buttons, active tab underlines, weight numerals in style lists, and category badges—ensuring it retains its signaling power.

## Typography

The typographic system is built on PP Neue Montreal as the primary functional and display typeface, with Eiko providing an elegant serif contrast for product-specific moments. Several display families from the foundry's catalog appear in promotional contexts. The scale spans from 12.4448-pixel labels to 134.4-pixel monumental display, with most functional text locked at 14 pixels.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | PP Neue Montreal | 8.4rem | 530 | 1 | normal | Monumental specimen previews, massive single glyphs |
| section-display | PP Neue Montreal | 5.25rem | 530 | 1 | normal | Large section headings, variable axis demonstrations |
| large-display | PP Neue Montreal | 3.5rem | 530 | 1.1 | normal | Medium display, paired font showcases |
| body-large | PP Neue Montreal | 2.06rem | 530 | 1.3 | normal | Glyph grid cells, style list names |
| body | PP Neue Montreal | 0.875rem | 450 | 1.3 | normal | Navigation, body copy, descriptions |
| body-small | PP Neue Montreal | 0.7775rem | 450 | 1.3 | normal | Metadata, captions, secondary labels |
| label | PP Neue Montreal | 0.7775rem | 450 | 1.166 | normal | Button text, compact UI labels |
| label-small | PP Neue Montreal | 0.7775rem | 600 | 1.3 | normal | Badges, emphasis labels, active states |
| navigation | PP Neue Montreal | 0.875rem | 450 | 1.3 | normal | Header links, tab navigation |
| display-serif | Eiko | 3.889rem | 100 | 1 | normal | Product page display, elegant headlines |
| body-serif | Eiko | 1.4016rem | 200 | 1.3 | normal | Style list items, serif specimen text |
| display-corp | PP Neue Corp | 4.2rem | 400 | 1 | normal | Homepage promotional display |
| display-watch | PP Watch | 4.2rem | 485 | 1 | normal | Homepage promotional display, alternate weight |

PP Neue Montreal, designed by Mathieu Desjardins for Pangram Pangram Foundry, serves as the system's backbone with its variable weight axis enabling precise control from 450 to 700. Eiko, used at light weights (100–200), provides delicate contrast for serif product pages. PP Neue Corp and PP Watch appear in homepage hero contexts at 67.2 pixels. The foundry's broader catalog includes PP Kyoto by Caio Kondo, PP Lettra Mono by Francesca Bolognini and Mat Desjardins, PP Model Plastic by Caio Kondo, PP Mondwest by Steve Marchal Datalaze, PP Monument-Narrow, PP Museum, PP Neue Bit by Steve Marchal Datalaze, PP Neue Corp-Normal Medium by Maksym Kobuzan, PP Neue Montreal-Variable by Mathieu Desjardins, and PP Valve. SF Pro appears in the Eiko page header. Verify licensing for these families before production use.

## Layout

The layout system favors generous whitespace and clear sectional division. Product pages follow a consistent tabbed architecture with a fixed header containing navigation, product identity, and primary actions. Content areas below scroll independently, with section margins of 128 pixels top and 32 pixels bottom creating rhythmic breathing room.

The header bar spans full width with 8 pixels vertical padding, establishing a compact but present top anchor. Below, tab navigation sits flush or slightly offset, with active states marked by color change rather than underline. Content sections employ asymmetric two-column layouts for glyph exploration: a dense grid of selectable cells on the left, a large preview panel on the right. This split-view pattern prioritizes browsing density while maintaining focus on the selected item.

Cards and containers use 20-pixel rounded corners as a default, with 32-pixel internal padding creating comfortable inset. Full-bleed dark panels for specimen previews contrast against the light page background. The glyph grid uses a unique 35% border-radius, creating soft squircle shapes that feel between circular and rounded-rectangular. Pill shapes at 9999 pixels radius appear for buttons, badges, and variable axis controls.

Horizontal margins vary by context: 90 pixels for centered content blocks, 32 pixels for standard container padding, and 188 pixels for maximum-width centered sections. The system avoids rigid grids in favor of fluid, content-driven spacing that responds to the scale of the type being displayed.

## Visual language

The visual language balances brutalist clarity with warm materiality. Black and white establish a gallery-like neutrality that lets the fonts command attention, while the warm gray surfaces and rounded corners prevent the interface from feeling cold or institutional. The orange accent functions as a signature color—appearing in the "Buy Now" button, active tab states, weight numerals, and category badges—creating a consistent thread of energy through otherwise restrained pages.

Photography and 3D imagery appear in project showcases, typically presented in rounded containers with dark overlays for text legibility. The "Neue Montreal in use" section demonstrates this pattern: a full-bleed carousel with metallic imagery, white text overlay, and an orange "Branding" badge floating above. This treatment elevates client work while maintaining the site's typographic focus.

The specimen viewer represents the core interactive expression of the brand. A black preview panel with white type, metric lines for ascender, cap height, x-height, baseline, and descender, and precise numerical readouts embodies the foundry's technical authority. The variable axis controls—sliders for weight and italic with numerical feedback—extend this precision into interaction design.

Glyph cells in the grid use a distinctive soft-square shape (35% radius) with light gray backgrounds, inverting to black with white text when selected. This binary on/off state mirrors the site's broader high-contrast philosophy. The overall impression is of a tool made by designers for designers: rigorous, beautiful, and unafraid of dramatic scale.

## Components

### Header Bar

- Anatomy: Full-width bar containing home icon, product name pill, tab navigation, primary actions, and utility icons
- Surface: Background `{colors.canvas-warm}`, text `{colors.ink}`
- Typography: `{typography.navigation}` for all text elements
- Shape: Product name rendered in pill-shaped container with white background and rounded corners
- Spacing: 8 pixels vertical padding, horizontal distribution with center-aligned tabs and right-aligned actions
- Composition: Flex row with space-between logic; tabs centered, actions grouped right

### Primary Action Button

- Anatomy: Text label within fully rounded container
- Surface: Background `{colors.action}`, text `{colors.white}`
- Typography: `{typography.label}`
- Shape: Pill shape at 9999 pixels radius
- Spacing: 8 pixels vertical, 24 pixels horizontal padding
- Variants: "Buy Now" uses filled orange; "Try for Free" uses outlined black variant

### Secondary Action Button

- Anatomy: Text label within rounded container with border
- Surface: Transparent background, `{colors.ink}` text and border
- Typography: "{typography.label}"
- Shape: 20 pixels radius
- Spacing: 8 pixels vertical, 16–24 pixels horizontal padding
- States: Hover inverts to filled black with white text

### Style List Card

- Anatomy: Style name left-aligned, weight numeral right-aligned, within rounded container
- Surface: Background `{colors.canvas}`, text `{colors.ink}`; active variant uses `{colors.ink}` background with `{colors.white}` text
- Typography: `{typography.body-serif}` for style name, `{typography.label-small}` in `{colors.action}` for numeral
- Shape: 20 pixels radius
- Spacing: 22.953 pixels padding
- Composition: Two-column grid with alternating light and dark variants for visual rhythm

### Glyph Cell

- Anatomy: Single character centered within soft-square container
- Surface: Background `{colors.canvas}`, text `{colors.ink}`; active state uses `{colors.ink}` background with `{colors.white}` text
- Typography: `{typography.body-large}` for character display
- Shape: 35% border-radius creating squircle appearance
- Spacing: Generous internal padding for touch targets
- Composition: Grid layout with consistent gaps

### Glyph Preview Panel

- Anatomy: Large dark panel containing single glyph at monumental scale with metric annotations
- Surface: Background `{colors.ink}`, text `{colors.white}`
- Typography: Hero-scale display at 134.4 pixels or 84.1165 pixels depending on context
- Shape: 20 pixels radius
- Spacing: 32 pixels padding
- Composition: Glyph centered with metric lines (ascender, cap height, x-height, baseline, descender) marked with dotted rules and numerical values

### Variable Axis Control

- Anatomy: Slider track with draggable handle, numerical readout, and axis label
- Surface: White track on black background for contrast
- Typography: `{typography.label}` for axis name, `{typography.body-small}` for value
- Shape: Pill-shaped track container
- Composition: Paired controls for weight and italic axes, horizontally arranged

### Project Showcase Card

- Anatomy: Full-bleed image with dark overlay, category badge, project title, and action link
- Surface: Image with black gradient overlay, white text
- Typography: `{typography.body}` for title, `{typography.label}` for action
- Shape: 20 pixels radius for card container
- Spacing: Internal padding for text placement at bottom
- Composition: Badge positioned top-center, title and link centered or bottom-aligned

## Responsive behavior

The system appears optimized for desktop viewing with substantial horizontal real estate. The two-column glyph explorer, large specimen previews, and generous section margins all assume a wide viewport. On narrower screens, the glyph grid should reflow to fewer columns, the preview panel should stack below the grid, and the monumental display sizes should scale down proportionally.

The tab navigation in the header may collapse to a horizontal scroll or hamburger menu on mobile. Variable axis controls should remain accessible but may stack vertically. The 188-pixel centered margins should reduce to 32 pixels or the standard container padding on mobile. Touch targets for glyph cells must maintain minimum 44-pixel dimensions regardless of viewport.

## Practical implementation guidance

### Preserve
- The stark black/white/orange color hierarchy—this tripartite system is the brand's signature
- Monumental display type in specimen previews; the scale contrast is central to the experience
- Rounded corners throughout: 20 pixels for cards, 9999 pixels for pills, 35% for glyph cells
- The warm gray progression from #FAFAFA to #000000 rather than pure neutral grays
- Binary active states: black background with white text for selected items

### Avoid
- Introducing additional accent colors beyond the orange; the restraint is intentional
- Sharp corners on interactive elements; the rounded language is consistent
- Body text smaller than 14 pixels or larger than 22.4256 pixels for functional content
- Gray text on gray backgrounds; maintain minimum contrast ratios
- Decorative elements that compete with the type specimens

### Recommended Build Order
1. Establish the color foundation with the full warm gray scale and orange accent
2. Implement PP Neue Montreal at 14 pixels/450 weight for all navigation and UI text
3. Build the header component with product pill, tab navigation, and action buttons
4. Create the card system with 20-pixel radius and 32-pixel padding
5. Implement the glyph grid with 35% radius cells and binary selection states
6. Build the specimen preview panel with black background and white display type
7. Add variable axis controls with pill-shaped sliders
8. Integrate Eiko for serif product page contexts

### Accessibility
- Ensure 4.5:1 contrast minimum for all body text; the black-on-white and white-on-black pairings exceed this
- Provide visible focus indicators for keyboard navigation through glyph grids and tab interfaces
- Make variable axis controls operable via keyboard and screen reader accessible with live region announcements for value changes
- Include aria-labels for icon-only buttons in the header (search, cart, menu)
- Respect reduced-motion preferences for any carousel or slider animations
- Ensure touch targets for glyph cells meet 44-pixel minimum dimensions

## Scope note

This guide covers the product page and specimen viewer surfaces for Pangram Pangram's font catalog, including the Eiko and Neue Montreal product experiences. Homepage promotional layouts, account pages, checkout flows, and mobile-specific adaptations are not represented in the supplied material. The 35% border-radius value for glyph cells and the 2-pixel relative unit step for type scaling should be verified against production requirements.


---
# Design Reference: PENTAGRAM.COM
---

# How pentagram.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/pentagram.com-design)

Last updated: 2026-08-10

## Captured pages

[![Homepage footer with oversized Pentagram wordmark, news events list, and contact emails on black background](https://pin.fontofweb.com/8273?format=jpg)](https://design.withfudge.com/share/pin-8273)

[Homepage footer with oversized Pentagram wordmark, news events list, and contact emails on black background](https://design.withfudge.com/share/pin-8273)

[![Contact page with large serif heading and four office building photographs in a two-column grid](https://pin.fontofweb.com/8272?format=jpg)](https://design.withfudge.com/share/pin-8272)

[Contact page with large serif heading and four office building photographs in a two-column grid](https://design.withfudge.com/share/pin-8272)

[![News listing page with filterable categories, date-stamped events, and press article thumbnails](https://pin.fontofweb.com/8271?format=jpg)](https://design.withfudge.com/share/pin-8271)

[News listing page with filterable categories, date-stamped events, and press article thumbnails](https://design.withfudge.com/share/pin-8271)

[![About page partner grid with black-and-white portrait photographs and name-location captions](https://pin.fontofweb.com/8270?format=jpg)](https://design.withfudge.com/share/pin-8270)

[About page partner grid with black-and-white portrait photographs and name-location captions](https://design.withfudge.com/share/pin-8270)

## Overview

The Pentagram website presents a confident, gallery-like experience rooted in extreme contrast and typographic restraint. The system alternates between pure white content surfaces and immersive black sections, using a single serif type family at carefully calibrated sizes to establish hierarchy without visual noise. Editorial photography—whether partner portraits, office architecture, or project imagery—receives maximum breathing room through generous margins and a disciplined grid. The overall impression is institutional yet contemporary: a design consultancy's own site functioning as a clean, confident frame for its work and people.

Navigation remains minimal and persistent, with the Pentagram wordmark anchoring the upper left and primary sections arranged horizontally at the upper right. Content pages unfold with large display headings set in the same serif face, followed by structured grids of imagery or text. The footer inverts the entire palette, dropping white typography onto a black canvas and culminating in an oversized Pentagram logotype that spans the full viewport width.

## Colors

The palette is intentionally austere, built on a near-black ink, pure white canvas, and a narrow band of muted grays for secondary information. Color is used structurally rather than expressively—photography and project imagery supply the chromatic interest.

| token | value | use |
|---|---|---|
| ink | #1A1A1A | Primary text, headings, body copy on light surfaces |
| ink-secondary | #767676 | Muted captions, locations, metadata, inactive filters |
| ink-tertiary | #8C8C8C | Footer body text, tertiary labels on dark surfaces |
| canvas | #FFFFFF | Primary page background, card surfaces, button fills |
| surface-inverse | #000000 | Footer background, immersive dark sections, hero overlays |
| surface-elevated | #222222 | Slightly lifted dark surfaces, subtle depth on black |
| surface-muted | #E3E4E5 | Tag backgrounds, subtle UI chrome |
| border-light | #E8E8E8 | Horizontal rules, card dividers, news list separators |

The light mode dominates content pages: white backgrounds with #1A1A1A text. Dark mode appears selectively in the footer and in project hero sections where white text overlays photographic or black backgrounds. The system avoids gradients, shadows, and decorative color fields—every hue serves a structural or legibility purpose. Image palettes from project photography are never extracted into UI tokens; the design relies on the photographs themselves to introduce warmth, saturation, or thematic color.

## Typography

The entire typographic system is set in By Francois Rappo, with the exact source file identified as By Francois Rappo-17138443775533187087, designed by Francois Rappo and distributed by Optimo Sarl. The face carries classical proportions with contemporary crispness, making it equally effective at display sizes and compact body settings. Weights are restrained: Regular (400) for most text, with Medium (500) appearing sparingly for emphasis in footer headings and select labels.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | By Francois Rappo | 3.25rem | 400 | 1.05 | -0.02em | Page titles, major section headings |
| section-display | By Francois Rappo | 2rem | 400 | 1.2 | -0.01em | Subsection headings, pull quotes |
| body | By Francois Rappo | 1.1875rem | 400 | 1.315 | normal | Paragraphs, navigation, news descriptions |
| body-small | By Francois Rappo | 1rem | 400 | 1.25 | normal | Captions, footer text, partner locations |
| label | By Francois Rappo | 0.8125rem | 400 | 1.25 | normal | Tags, dates, metadata badges |
| navigation | By Francois Rappo | 1.1875rem | 400 | 1.315 | normal | Primary nav, header links |

The hero-display size at 52px with tight negative tracking creates immediate presence on page load. Body text at 19px with 25px line height maintains comfortable reading density for editorial content. The 16px body-small size handles captions and dense footer information without feeling cramped. Labels at 13px appear as date stamps and category tags, kept legible through generous line height. Verify licensing for these families before production use.

## Layout

The layout system is built on a fluid grid with consistent horizontal margins and vertical section spacing. Content is typically constrained by side margins of 24px, expanding to 32px or 48px for internal padding on larger elements. The grid favors asymmetry when needed—hero sections often break the margin with full-bleed imagery offset by negative margins, while text content maintains strict alignment.

Vertical rhythm follows a doubling pattern from the 4px base unit. Tight spacing at 8px handles internal element gaps and tag padding. Compact 16px spacing appears between related text blocks. Comfortable 24px spacing separates distinct content groups. Generous 48px spacing precedes major headings or section breaks. Section spacing at 96px and section-large at 192px create dramatic pauses between page regions, particularly between the final content block and the footer.

The partner grid on the About page uses a four-column layout with consistent gutters, each cell containing a square portrait photograph with name and location stacked beneath. News listings employ a hybrid approach: a top row of date-stamped events in four columns, followed by a two-column grid of press articles with thumbnail images. The Contact page presents a two-by-two image grid of office buildings, with the page title occupying the full width above.

## Visual language

The visual language is characterized by restraint, scale, and material honesty. Photography is presented without borders, shadows, or decorative frames—images sit directly on the white background or extend to full bleed. The black-and-white partner portraits establish a consistent, dignified tone that unifies individual personalities into a collective identity. Project and office photography retains its original color, creating natural variation against the neutral interface.

Typography functions as the primary visual element. The oversized Pentagram wordmark in the footer demonstrates the system's comfort with extreme scale—letterforms become architectural, functioning as both branding and spatial divider. Headings on content pages achieve similar presence through size and tracking rather than weight or color variation.

The interface avoids decorative elements: no icons in navigation, no background patterns, no gradient overlays on imagery. Interactive states are implied through cursor change and subtle underline behavior rather than color shifts. Tags and badges use minimal pill or rounded-rectangle shapes with muted backgrounds, never competing with content for attention.

## Components

### Site header

- **Anatomy**: Fixed-position bar containing the Pentagram wordmark (text, not image) at left, primary navigation links at right, search icon, and archive link.
- **Surface**: Transparent or white background, no border, no shadow.
- **Typography**: Navigation token, Regular weight.
- **Spacing**: 24px horizontal margins, 24px vertical padding.
- **Composition**: Flex row with space-between alignment, links evenly distributed at right.

### Page title

- **Anatomy**: Single heading element, often the only text above the fold.
- **Typography**: Hero-display token, #1A1A1A on light pages.
- **Spacing**: 64px top margin, no bottom margin—content sits directly below.
- **Composition**: Left-aligned, full width, no max-width constraint.

### Partner card

- **Anatomy**: Square photograph, partner name in body-small, location in ink-secondary below.
- **Surface**: White background, no border, no radius on image.
- **Typography**: Name in body-small Regular, location in body-small Regular with ink-secondary color.
- **Spacing**: Image fills cell, 8px gap between image and text, minimal bottom margin.
- **Composition**: Stacked vertically within grid cell, text left-aligned.

### News card

- **Anatomy**: Optional thumbnail image, category tag, date, headline with arrow indicator.
- **Surface**: White background, 1px top border in border-light.
- **Typography**: Headline in body token, date in label token, category tag in label with muted background.
- **Spacing**: 24px vertical padding, 32px right padding on text blocks.
- **Composition**: Horizontal flex on desktop with image at left, text at right; stacks vertically on narrower viewports.

### Footer

- **Anatomy**: Multi-section dark region containing news events, contact emails, about text, oversized logotype, and legal links.
- **Surface**: Pure black background (#000000).
- **Typography**: Body-small in ink-tertiary for general text, body-small in canvas for emphasized links and headings, footer subheadings in Medium weight.
- **Spacing**: 24px bottom padding on sections, 24px horizontal margins.
- **Composition**: Asymmetric two-column layout for contact and about sections; full-width logotype below; legal links in a single row at bottom.

### Tag

- **Anatomy**: Inline pill or rounded rectangle containing category or status text.
- **Surface**: Muted gray background (#E3E4E5).
- **Typography**: Label token, Regular weight.
- **Shape**: 4px radius, 4px 8px internal padding.
- **Composition**: Appears inline before headlines or in filter lists.

## Responsive behavior

The system maintains its core character across viewport sizes through proportional scaling and selective reflow. The four-column partner grid should collapse to two columns on tablet and single column on mobile, preserving square aspect ratios on portraits. News event cards reflow from four columns to two, then stack vertically. The oversized footer logotype scales down proportionally, remaining readable without breaking layout.

Navigation should collapse to a menu trigger on mobile rather than wrapping. Page titles maintain hero-display size where possible, scaling down to section-display on the narrowest viewports. Horizontal margins of 24px remain consistent, though internal grid gutters may compress to 16px. Touch targets for footer links and tags should maintain minimum 44px height.

## Practical implementation guidance

### Preserve
- The stark black-white-gray palette; do not introduce accent colors for interactive states.
- The single serif family across all text roles; avoid pairing with sans-serif for UI elements.
- Generous whitespace around imagery and between sections; the site's authority depends on breathing room.
- Full-bleed photography without borders, shadows, or overlays.
- The oversized footer wordmark as a distinctive brand moment.

### Avoid
- Drop shadows on cards or containers; the system relies on flat planes and spacing for separation.
- Gradient backgrounds or decorative patterns; photography supplies all visual richness.
- Multiple font weights within a single component; hierarchy comes from size and color, not weight variation.
- Rounded corners on photographs; keep imagery rectilinear and direct.

### Recommended build order
1. Establish the 4px base grid and spacing tokens.
2. Implement the single serif type family with all six size/role combinations.
3. Build the site header with transparent background and right-aligned navigation.
4. Create the page title component with hero-display sizing.
5. Implement the partner grid with square image constraints and caption stacking.
6. Build news cards with horizontal layout and top-border separation.
7. Construct the footer with inverted colors and the oversized logotype treatment.
8. Add tags and filter UI with muted backgrounds.

### Accessibility
- Ensure text on dark surfaces meets WCAG AA contrast; the canvas-on-black combination exceeds requirements.
- Provide visible focus indicators for keyboard navigation; the minimal UI benefits from clear focus rings.
- Maintain semantic heading hierarchy despite visual uniformity; screen readers depend on proper h1-h6 structure.
- The oversized footer wordmark should be implemented as decorative or include appropriate aria-label if interactive.

## Scope note

This guide covers the homepage, About, News, and Contact page surfaces visible in the supplied images. Project detail pages, search functionality, archive browsing, and mobile navigation patterns are not represented. Motion, hover states, and loading behavior are not described. Measurements are derived from the retained interface values where available.


---
# Design Reference: POLYMARKET.COM
---

# How polymarket.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/polymarket.com-design)

Last updated: 2026-08-10

## Captured pages

[![Homepage showing dark-themed prediction market cards with category navigation, featured Bitcoin market, and breaking news sidebar with percentage indicators](https://pin.fontofweb.com/8585?format=jpg)](https://design.withfudge.com/share/pin-8585)

[Homepage showing dark-themed prediction market cards with category navigation, featured Bitcoin market, and breaking news sidebar with percentage indicators](https://design.withfudge.com/share/pin-8585)

[![NCAA Tournament market detail view with multi-line probability chart, team percentage breakdown, and comment thread](https://pin.fontofweb.com/8584?format=jpg)](https://design.withfudge.com/share/pin-8584)

[NCAA Tournament market detail view with multi-line probability chart, team percentage breakdown, and comment thread](https://design.withfudge.com/share/pin-8584)

[![Esports match page for Kiwoom DRX vs DN SOOPers showing live score, team tabs, and diverging probability chart with volume indicator](https://pin.fontofweb.com/8583?format=jpg)](https://design.withfudge.com/share/pin-8583)

[Esports match page for Kiwoom DRX vs DN SOOPers showing live score, team tabs, and diverging probability chart with volume indicator](https://design.withfudge.com/share/pin-8583)

## Overview

Polymarket presents a dark, data-dense prediction market interface designed for rapid scanning and decision-making. The visual system prioritizes legibility of numerical data—probabilities, prices, and volumes—against a near-black canvas. Information hierarchy is established through color saturation rather than size variation: bright accent colors signal actionable data points while muted grays recede into supporting context. The interface organizes markets into scannable cards, each containing embedded probability charts, outcome buttons, and metadata. A persistent navigation bar provides category filtering, while sidebars surface trending topics and breaking news with percentage indicators. The overall impression is of a financial terminal reimagined for consumer prediction markets: serious, efficient, and visually restrained except where color encodes meaning.

## Colors

The color system operates on a dark-mode foundation with semantic accent colors that encode market outcomes and data states. Every token below is drawn from the live interface.

| token | hex | use |
|---|---|---|
| canvas | #000000 | Page background, deepest layer |
| surface | #15191D | Primary card backgrounds, elevated panels |
| surface-elevated | #181D21 | Hover states, active navigation items |
| surface-highlight | #1E2428 | Subtle highlights, category pill backgrounds |
| ink | #FFFFFF | Primary text, headings, active data |
| ink-secondary | #E5E5E5 | Secondary headings, emphasized body text |
| ink-tertiary | #BBC4CD | Tertiary information, timestamps |
| muted | #7B8996 | Labels, placeholders, inactive metadata |
| muted-dim | #586879 | Disabled states, subtle borders |
| border | #242B32 | Card borders, dividers, chart grid lines |
| border-subtle | #1E2428 | Hairline separators within cards |
| action-primary | #0093FD | Primary buttons, links, active chart lines |
| action-primary-hover | #4080E0 | Button hover states, link underlines |
| success | #3DB468 | "Yes" outcomes, positive price movement, winning probabilities |
| success-dim | #D4FFAF | Success backgrounds, subtle positive indicators |
| danger | #CB3131 | "No" outcomes, negative price movement, losses |
| warning | #FF9900 | Attention states, price alerts, featured highlights |
| accent-purple | #6A5A9A | Secondary chart lines, team identifiers |
| accent-pink | #FABBF1 | Gradient accents, decorative highlights |
| accent-teal | #0E446B | Deep informational backgrounds |
| chart-blue | #0093FD | Primary data series, main probability line |
| chart-orange | #FF9900 | Secondary data series, comparison lines |
| chart-purple | #6A5A9A | Tertiary data series, team-specific encoding |
| chart-green | #3DB468 | Positive trend indicators, volume bars |

The dark canvas creates a theater-like environment for data visualization. Bright accents against black achieve high perceived contrast without eye strain during extended sessions. Color carries semantic weight: green universally indicates "Yes" or positive outcomes, red indicates "No" or negative outcomes, and blue serves as the neutral action color. Charts use a diverging palette where each data series receives a distinct hue, with opacity and line weight providing additional differentiation. A subtle radial gradient in pink (#FABBF1) appears as a decorative background element in featured sections, softening the otherwise austere palette.

## Typography

The interface uses Inter as the sole typeface for UI elements, with Open Sauce One reserved for legal and policy text. Inter's extensive weight range supports fine-grained hierarchy without size inflation.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Inter | 2rem | 600 | 1.25 | -0.02em | Featured market titles, page headlines |
| section-display | Inter | 1.5rem | 600 | 1.33 | -0.0125em | Section headings, "All markets" |
| market-title | Inter | 1.25rem | 600 | 1.2 | -0.01em | Card titles, market names |
| body | Inter | 1rem | 400 | 1.5 | normal | Descriptions, comments, general content |
| body-medium | Inter | 0.875rem | 500 | 1.43 | -0.005em | Emphasized body, tab labels |
| label | Inter | 0.8125rem | 500 | 1.23 | normal | Badges, tags, metadata labels |
| caption | Inter | 0.75rem | 400 | 1.33 | -0.005em | Timestamps, volume figures, fine print |
| stat-large | Inter | 2rem | 500 | 1.5 | normal | Large percentages, prices, countdowns |
| navigation | Inter | 0.875rem | 600 | 1.43 | -0.005em | Top nav categories, breadcrumbs |
| button | Inter | 0.875rem | 600 | 1.43 | -0.005em | All button labels |
| legal-copy | Open Sauce One | 1rem | 400 | 1.5 | normal | Terms, disclaimers, legal text |

Tracking tightens at larger sizes to maintain visual density. The 14px/0.875rem size with 500-600 weight serves as the workhorse for interactive elements, providing clear affordance without overwhelming. Percentage values in market cards use the same size as body text but with heavier weight to create numerical prominence. Open Sauce One, designed by Alfredo Marco Pradil and provided by Creative Sauce Fz Llc, appears only where distinct legal voice is required. Verify licensing for these families before production use.

## Layout

The page structure follows a centered content model with generous horizontal margins. The main content area sits within a maximum width container, creating focused reading zones against the full-bleed dark canvas.

**Grid and containment.** The primary layout uses a single centered column for market listings, with a secondary sidebar appearing at wider viewports. Content maxes at approximately 73rem (1168px), with 185px auto margins creating substantial side gutters. Internal card grids use flexible layouts: market cards arrange in responsive rows, typically 3-4 columns on desktop, with consistent 1rem gaps.

**Navigation architecture.** A persistent top bar contains the logo, search field, authentication actions, and a full-width category strip below. The category navigation scrolls horizontally when viewport width is insufficient, with "Trending" anchored as the first item with a distinctive zigzag icon. Navigation items use compact pill-shaped containers with 4px 10px padding.

**Card composition.** Market cards follow a strict internal hierarchy: thumbnail or icon at top-left, title and subtitle as primary block, probability or price data as prominent right-aligned figures, and outcome buttons at the bottom. Charts embed directly within cards when space permits, with sparklines showing recent price history. Card padding is asymmetric—more horizontal breathing room (20px) than vertical—to accommodate varying content heights.

**Detail views.** Individual market pages expand to full-width data visualization, with probability charts dominating the right two-thirds and market metadata, comments, and outcome selection occupying the left third. Breadcrumb navigation traces category hierarchy above the title.

**Spacing scale.** The system uses a 2px base unit. Common increments: 4px for tight internal padding, 8px for related element grouping, 12px for card internal spacing, 16px for section separation, 20px for card padding, 24px for major section breaks, and 32-40px for page-level vertical rhythm.

## Visual language

The interface communicates through a financial-terminal aesthetic tempered by consumer-friendly color coding. Visual density is high—multiple data points compete for attention within each card—yet the dark canvas and careful color restraint prevent chaos.

**Iconography and imagery.** Market thumbnails are photographic or branded icons, small and square with rounded corners. Category icons are minimal line drawings. The Polymarket logo appears as a geometric mark beside wordmark. User avatars in comment threads are circular with subtle colored rings indicating status.

**Data visualization.** Probability charts use thin lines (1-2px) with dot markers at current values. Area fills appear beneath lines with low opacity. Grid lines are extremely subtle, nearly blending into the canvas. Multiple series use distinct hues with sufficient separation in hue space. Y-axis labels are minimal, often omitted in sparkline contexts. Time axes show abbreviated timestamps.

**Motion and feedback.** While static images cannot confirm motion, the interface suggests micro-interactions: outcome buttons likely shift color on hover, chart lines may animate on load, and probability values probably tick with live updates. The "LIVE" indicator uses a pulsing red dot convention.

**Texture and depth.** Elevation is minimal—no heavy shadows. A single subtle shadow appears on elevated elements: `oklab(0 0 0 / 0.04) 0px 8px 16px 0px`. Borders provide most structural definition, with 1px solid lines in muted tones. The overall effect is flat but layered, like a sophisticated spreadsheet.

## Components

**Market card.** The fundamental unit of the interface. Anatomy: thumbnail image (40x40px, rounded), title block (market name + subtitle), probability display (large percentage or price), outcome buttons ("Yes"/"No" or specific options), volume indicator, and optional sparkline chart. Surface: background at surface token, 1px border in border token, 15.2px border radius. Spacing: 20px left padding, 12px top, 8px bottom, with internal elements stacked at 8px intervals. Typography: title at market-title token, metadata at caption, probabilities at stat-large or body-medium depending on prominence.

**Outcome button.** Compact toggle for binary or multiple-choice markets. Two variants visible: filled pill with success or danger background for selected/active state, and outlined or muted pill for unselected. Anatomy: label text with optional percentage, contained in rounded rectangle. Surface: selected "Yes" uses success green with canvas text; selected "No" uses danger red with white text; unselected uses surface-highlight background with muted text. Shape: 6px radius, padding 8px 16px for standard, 4px 12px for compact. Typography: label token, weight 500-600.

**Probability chart.** Line or area chart showing price/probability history. Anatomy: SVG path with optional area fill, Y-axis grid lines, X-axis time labels, current value marker dot, and legend for multi-series data. Surface: transparent background, grid lines at border-subtle. Composition: occupies right portion of detail view or embeds in card footer. Multi-series charts use color-coded lines with corresponding legend pills.

**Category navigation.** Horizontal scrollable list of market categories. Anatomy: text labels with optional dropdown chevron, "Trending" with distinctive icon. Surface: transparent background, individual items as subtle pills on hover. Spacing: items at 0px 14px padding, with 24px section padding above and below. Typography: navigation token.

**Search bar.** Prominent top-bar element. Anatomy: magnifying glass icon, placeholder text, optional clear button. Surface: surface background, pill shape (9999px radius), full-width within constraints. Typography: body token in muted color.

**Breaking news sidebar.** Vertical list of trending markets with percentage indicators. Anatomy: numbered list, market title, probability figure with directional arrow. Surface: transparent, separated by subtle borders. Typography: body for titles, stat-large for percentages, caption for metadata.

**Comment thread.** Nested discussion within market detail. Anatomy: avatar, username, comment text, timestamp. Surface: transparent, indented replies. Typography: body for comments, caption for metadata.

## Responsive behavior

The interface appears optimized for desktop viewing with substantial content width. At narrower viewports, the following adaptations should occur: the sidebar collapses or stacks below main content; market cards reduce from multi-column to single-column layout; category navigation becomes horizontally scrollable with fade indicators; search bar may collapse to icon-only trigger; and probability charts maintain aspect ratio with reduced axis labeling. Touch targets should maintain minimum 44px height for outcome buttons. The dense data presentation may require horizontal scrolling for tables or alternative card layouts on mobile.

## Practical implementation guidance

**Preserve.** The dark canvas as default—never implement a light mode without complete color recalculation. The semantic color mapping: green for positive/yes, red for negative/no, blue for neutral actions. The tight tracking on large headings. The asymmetric card padding with more horizontal than vertical space. The subtle border-based elevation rather than heavy shadows.

**Avoid.** Light backgrounds behind charts—they destroy the terminal aesthetic. Pure white (#FFFFFF) for large areas; use ink-secondary and ink-tertiary for reduced emphasis. Saturated colors for non-semantic decoration. Drop shadows on individual cards—use borders instead. Generic button styling that doesn't encode outcome state.

**Recommended build order.** 1) Establish dark canvas and surface color tokens. 2) Implement Inter at base 16px with full weight range. 3) Build market card component with all spacing and border tokens. 4) Create outcome button variants with semantic colors. 5) Implement category navigation and search bar. 6) Add probability chart with line/area rendering. 7) Build detail view layout with chart prominence. 8) Add breaking news sidebar. 9) Implement responsive breakpoints for card grid collapse.

**Accessibility.** Ensure probability values are not color-only—supplement with text labels or patterns. Provide sufficient contrast for success/danger text against their backgrounds (the green on black passes, but verify for thinner weights). Chart lines should have distinct patterns or labels for colorblind users. Interactive elements need visible focus states, likely a 2px outline in action-primary. The high information density may overwhelm screen readers; implement proper heading hierarchy and ARIA labels for market data.

## Scope note

This guide covers the Polymarket homepage, market detail views, and esports match pages as visible in the supplied images. Mobile layouts, authentication flows, wallet interfaces, market creation tools, and real-time WebSocket update animations are not represented. The Open Sauce One font appears only in legal contexts and may have limited interface presence. Measurements derive from the desktop viewport state shown.


---
# Design Reference: RABBIT.TECH
---

# How rabbit.tech is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/rabbit.tech-design)

Last updated: 2026-08-10

## Captured pages

[![Research page with orange header bar, black canvas, large orange 'research' display type with floating device illustrations, and article list with thumbnails](https://pin.fontofweb.com/1571?format=jpg)](https://design.withfudge.com/share/pin-1571)

[Research page with orange header bar, black canvas, large orange 'research' display type with floating device illustrations, and article list with thumbnails](https://design.withfudge.com/share/pin-1571)

[![Legal disclaimer page with dense white body text on black background, social icons, and minimal footer links](https://pin.fontofweb.com/1570?format=jpg)](https://design.withfudge.com/share/pin-1570)

[Legal disclaimer page with dense white body text on black background, social icons, and minimal footer links](https://design.withfudge.com/share/pin-1570)

[![FAQ section with large white questions in display type, small white answers, and decorative rabbit device illustration with question mark](https://pin.fontofweb.com/1569?format=jpg)](https://design.withfudge.com/share/pin-1569)

[FAQ section with large white questions in display type, small white answers, and decorative rabbit device illustration with question mark](https://design.withfudge.com/share/pin-1569)

[![Software updates section with white display heading, orange 'view all updates' link with arrow icon, and download icon with descriptive text](https://pin.fontofweb.com/1568?format=jpg)](https://design.withfudge.com/share/pin-1568)

[Software updates section with white display heading, orange 'view all updates' link with arrow icon, and download icon with descriptive text](https://design.withfudge.com/share/pin-1568)

## Overview

The rabbit.tech visual system is built around the physical presence of the r1 AI assistant device, expressed through stark contrast and disciplined restraint. Every page sits on an unapologetic black canvas that lets product photography and bold typographic moments command attention. An electric orange serves as the singular accent—appearing in the persistent site header, key navigation moments, and interactive calls-to-action—creating immediate brand recognition without decorative excess.

The design language favors large, tightly-tracked display type for section headings and questions, set in a geometric sans-serif that feels contemporary and slightly technical. Body copy is rendered in an extra-light weight, creating a deliberate hierarchy where headings assert themselves and supporting text recedes into a whisper. Layouts are sparse, with generous vertical breathing room between content blocks and minimal structural ornament. The overall impression is of a company confident enough to let its product and message speak without visual competition.

## Colors

| token | value | use |
|---|---|---|
| canvas | #000000 | Primary page background; establishes the dark, immersive environment |
| surface | #111111 | Slightly elevated panels or secondary backgrounds when needed |
| ink | #FFFFFF | Primary text, headings, icons, and UI elements on dark backgrounds |
| muted-ink | #B3B3B3 | Secondary body text, captions, dates, and de-emphasized content |
| action | #FF4D00 | Header bar, primary links, interactive accents, and brand moments |
| action-hover | #E64500 | Slightly deeper orange for hover states on action elements |
| border | #333333 | Subtle dividers and structural boundaries when required |

The color system operates in a single dark mode with no light variant visible. The black canvas is absolute, not merely dark gray, which creates maximum contrast for the white typography and allows the orange accent to feel luminous rather than merely bright. The orange appears strategically—never as large fields beyond the header, but as precise punctuation that guides the eye to interactive elements. Muted ink serves to create hierarchy within text-dense areas like FAQs and legal disclaimers, preventing visual fatigue without introducing additional hues. No gradients or shadows are employed; the system relies on flat color and spatial arrangement for structure.

## Typography

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Power Grotesk | 6rem | 400 | 0.9 | -0.03em | Page-level display headings, oversized section titles |
| section-display | Power Grotesk | 3rem | 400 | 1 | -0.02em | Section headings, FAQ questions, article titles |
| body | Archivo | 1rem | 200 | 1.6 | 0em | Standard body copy, descriptions, answers |
| body-large | Archivo | 1.25rem | 200 | 1.5 | 0em | Lead paragraphs, emphasized descriptions |
| label | Archivo | 0.75rem | 400 | 1.2 | 0.02em | Small labels, badges, metadata |
| navigation | Archivo | 0.875rem | 400 | 1 | 0.01em | Header navigation, footer links |

Power Grotesk, designed by Teguh Arief of Power Type Foundry, provides the display voice—geometric, confident, and slightly condensed with aggressive negative tracking that creates a contemporary technical character. Archivo, designed by Hector Gatti of Omnibus Type, handles all functional text in its Extra Light weight, offering exceptional readability at low weights that maintains the system's airy, premium feel. The extreme weight contrast between display (400) and body (200) is intentional, creating clear hierarchy without size alone.

All type sizes are whole-number multiples of 4px (0.25rem), with display sizes at 96px and 48px, body at 16px and 20px, and functional sizes at 12px and 14px. Verify licensing for these families before production use.

## Layout

The layout system is fundamentally single-column with generous margins. Content blocks stack vertically with substantial section spacing, creating a scrolling narrative that reveals information deliberately. The header is fixed-height and full-bleed in orange, containing the rabbit wordmark left-aligned and navigation centered, with a lock icon at the far right indicating account or cart access.

Main content areas employ asymmetric padding—typically 4rem to 6rem from the left edge for primary text, with display headings sometimes breaking further left or bleeding to the edge for dramatic effect. The research page demonstrates this with its oversized "research" heading that spans nearly the full viewport width, interspersed with floating device illustrations that break the typographic line.

Article listings use a horizontal thumbnail-plus-text pattern: a square or slightly rectangular image left, with the title and date stacked to its right. This creates a clean scanable rhythm without grid complexity. FAQ sections place a small decorative illustration to the left of each question-answer pair, maintaining visual interest in an otherwise text-heavy format.

The footer is minimal and functional: social icons left-aligned, legal and utility links center, copyright right. No newsletter capture, no elaborate sitemap—just essential paths and attribution.

## Visual language

The visual language is defined by restraint and precision. Photography and product imagery is presented without borders, shadows, or frames, letting the objects exist as pure forms against the black void. The r1 device itself—with its distinctive rounded square shape, side button, and camera module—appears repeatedly as both product hero and decorative motif, reinforcing brand identity through repetition.

Line-art illustrations of the device appear in white outline form, sometimes with small expressive details like a question mark or X mark, adding personality without color complexity. These illustrations float freely, overlapping type or sitting adjacent to it, creating a sense of playful technicality.

Iconography is simple and geometric: a download arrow, a rightward arrow for links, social platform marks. All icons share the same stroke weight and directness as the typography. There are no decorative patterns, no background textures, no gradient overlays. The system trusts in the power of absolute contrast and careful spacing.

The orange header creates a persistent brand beacon that anchors every page. Below it, the black canvas extends infinitely, making each page feel like a stage where content performs under spotlight conditions.

## Components

### Site header

- **Anatomy**: Full-width bar containing rabbit wordmark (left), navigation links with "new" badge (center), lock icon (right)
- **Surface**: Solid action orange background
- **Typography**: Navigation token, white ink
- **Shape**: No border radius; sharp rectangular bar
- **Spacing**: 3.5rem height, 2rem horizontal padding
- **Composition**: Flex row with space-between alignment; navigation links evenly distributed with small gaps

### Article card

- **Anatomy**: Thumbnail image left, title and date stacked right
- **Surface**: Transparent on canvas background
- **Typography**: Section-display for title, body for date in muted-ink
- **Shape**: Thumbnail has subtle rounding (0.5rem)
- **Spacing**: 2rem gap between thumbnail and text; 3rem vertical gap between cards
- **Composition**: Horizontal flex, thumbnail approximately 8rem square

### FAQ item

- **Anatomy**: Decorative device illustration left, question and answer stacked right
- **Surface**: Transparent
- **Typography**: Section-display for question, body for answer; links within answers use action color with underline
- **Shape**: Illustration approximately 4rem, white line art
- **Spacing**: 2rem gap between illustration and text; 3rem vertical gap between items
- **Composition**: Horizontal flex with illustration as visual anchor

### CTA link

- **Anatomy**: Text label plus rightward arrow icon
- **Surface**: Transparent
- **Typography**: Body-large in action color
- **Shape**: Arrow icon in circle or standalone; icon 1.25rem
- **Spacing**: 0.5rem gap between text and icon
- **Composition**: Inline flex, center-aligned
- **Variants**: "view all updates" style with arrow-in-circle; plain text links with underline in body copy

### Footer

- **Anatomy**: Social icons left, utility links center, copyright right
- **Surface**: Transparent on canvas
- **Typography**: Navigation token for links, label for copyright
- **Shape**: No dividers or borders
- **Spacing**: 2rem vertical padding; generous horizontal margins
- **Composition**: Three-zone flex with space-between

## Responsive behavior

The system should maintain its single-column, generous-margin approach across viewports. The hero display size may scale down to section-display on narrower screens to prevent overflow. Navigation in the orange header should collapse to a hamburger menu on mobile, preserving the brand bar's presence without crowding. Article card thumbnails may stack above text on narrow viewports rather than sitting side-by-side. FAQ illustrations should remain visible but scale proportionally, maintaining their role as visual anchors. The absolute black canvas and orange accent should persist unchanged; these are identity-defining elements not subject to breakpoint variation.

## Practical implementation guidance

### Preserve
- The absolute black canvas as the only background mode
- The electric orange header as a persistent, full-width brand element
- The extreme weight contrast between Power Grotesk display and Archivo Extra Light body
- Floating device illustrations as decorative accents
- Generous vertical spacing between content sections
- Minimal footer with essential links only

### Avoid
- Adding background colors or gradients behind content blocks
- Introducing additional accent colors beyond the orange
- Using borders or shadows to create depth
- Crowding the header with too many navigation items
- Reducing the display type to sizes that lose its impact

### Recommended build order
1. Establish the black canvas and orange header as the foundational frame
2. Implement the typography scale with both families at their specified weights
3. Build the article card and FAQ item patterns as primary content components
4. Add floating illustrations and iconography
5. Refine spacing and responsive behavior

### Accessibility
- Ensure white text on black maintains WCAG AAA contrast (it does at normal sizes)
- The orange action color should not be used for small text alone; pair with white or use for large interactive elements only
- Provide focus indicators that complement the flat aesthetic, such as 2px white outlines on orange buttons
- Maintain touch targets of at least 44px for header navigation and footer links

## Scope note

This guide covers the rabbit.tech marketing site as visible on desktop, including the research page, product page sections, FAQ, and software updates. Mobile breakpoints, animation, form interactions, e-commerce checkout flows, and the r1 device interface itself are not represented in the supplied material. Measurements are practical adaptation targets derived from visual inspection.


---
# Design Reference: REFERO.DESIGN
---

# How refero.design is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/refero.design-design)

Last updated: 2026-08-10

## Captured pages

[![Homepage hero with sidebar navigation, search input, and category links on dark canvas](https://pin.fontofweb.com/9837?format=jpg)](https://design.withfudge.com/share/pin-9837)

[Homepage hero with sidebar navigation, search input, and category links on dark canvas](https://design.withfudge.com/share/pin-9837)

[![Upgrade banner with rounded pill button and search bar with filter chips](https://pin.fontofweb.com/9685?format=jpg)](https://design.withfudge.com/share/pin-9685)

[Upgrade banner with rounded pill button and search bar with filter chips](https://design.withfudge.com/share/pin-9685)

[![Research page with follow-up input and mobile app preview card](https://pin.fontofweb.com/9684?format=jpg)](https://design.withfudge.com/share/pin-9684)

[Research page with follow-up input and mobile app preview card](https://design.withfudge.com/share/pin-9684)

[![Homepage hero with centered display heading and expanded category grid](https://pin.fontofweb.com/9683?format=jpg)](https://design.withfudge.com/share/pin-9683)

[Homepage hero with centered display heading and expanded category grid](https://design.withfudge.com/share/pin-9683)

## Overview

Refero is a design research platform built for the AI era, helping designers, builders, and AI systems discover real product screens, flows, and patterns. The visual system is immediately distinctive: a deep, near-black canvas serves as the stage for elegant serif display typography and a prominent AI search interface. The homepage centers on a large, inviting search input that encourages natural language queries, surrounded by category navigation and example prompts. The overall impression is sophisticated yet approachable—premium without being cold, technical without being sterile.

The design employs a dark-first palette with carefully calibrated elevation layers. Surfaces rise from the canvas through subtle shifts in lightness rather than heavy borders or shadows. Typography creates clear hierarchy through family contrast: a refined serif for emotional impact in headlines, and a precise geometric sans-serif for all functional UI text. The interface feels spacious and breathable, with generous horizontal margins and deliberate vertical rhythm.

## Colors

The color system is built on a dark foundation with restrained accent usage. Every surface exists on a continuum from deep canvas to elevated panels, creating depth through value rather than chroma.

| token | value | use |
|---|---|---|
| canvas | #101216 | Primary page background, deepest layer |
| canvas-elevated | #181A20 | Secondary backgrounds, banner surfaces |
| surface | #1D1F27 | Cards, inputs, elevated containers |
| surface-highlight | #24252B | Hover states, active selections |
| ink | #FFFFFF | Primary text, icons, emphasis |
| ink-muted | #9399AD | Secondary text, descriptions, placeholders |
| ink-dim | #6D768E | Tertiary text, disabled states |
| ink-subtle | #4B546B | Decorative elements, subtle dividers |
| border-subtle | #2F323D | Hairline borders, separators |
| border-highlight | #BABCF3 | Focus rings, active indicators |
| accent-blue | #00AAFF | Links, interactive highlights |
| accent-coral | #FF6154 | Badges, alerts, destructive actions |
| accent-orange | #FF4400 | Strong emphasis, gradient stops |
| action-primary | #FFFFFF | Primary button background |
| action-primary-text | #101216 | Primary button text |
| action-secondary-bg | #1D1F27 | Secondary button background |
| action-secondary-text | #FFFFFF | Secondary button text |
| shadow-glow | #BAC0EF | Subtle ambient glow on elevated surfaces |

The dark palette creates a cinematic quality that makes screenshot previews and image content pop. Elevation is achieved through layered surfaces: canvas at the bottom, canvas-elevated for mid-ground elements like banners, surface for interactive containers like the search bar, and surface-highlight for pressed or selected states. The ink scale provides four distinct text intensities for flexible hierarchy without introducing additional colors. Accent colors appear sparingly—blue for links and interactive elements, coral and orange for attention-grabbing moments like badges or gradient accents.

## Typography

The type system pairs two distinct families for emotional and functional roles. Kalice, a refined serif designed by Margot Lévêque, handles display headlines with elegant curves and moderate contrast. PP Neue Montreal, a geometric sans-serif from Pangram Pangram Foundry designed by Mathieu Desjardins, manages all interface text with clean lines and excellent legibility at small sizes. The platform also loads Satoshi, a variable sans-serif by Deni Anggara via Indian Type Foundry, for use on search and results surfaces. Applesystem and System-Monospace appear in the font stack as system-level fallbacks for native UI rendering and code blocks respectively.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Kalice | 3.125rem | 400 | 1.2 | -0.02em | Homepage headlines, hero statements |
| section-display | Recoleta | 3.375rem | 400 | 1.13 | normal | Section titles, feature headings |
| body | PP Neue Montreal | 1rem | 500 | 1.5 | -0.02em | Primary UI text, navigation, descriptions |
| body-small | PP Neue Montreal | 0.8125rem | 500 | 1.54 | -0.015em | Secondary descriptions, metadata |
| label | PP Neue Montreal | 0.75rem | 500 | 1.33 | -0.02em | Tags, timestamps, fine print |
| navigation | PP Neue Montreal | 1rem | 500 | 1.5 | -0.02em | Sidebar links, category names |
| button | PP Neue Montreal | 1rem | 600 | 1.5 | -0.02em | Button labels, call-to-action text |

Kalice appears at 50px (3.125rem) for hero headlines with tight tracking that gives it a contemporary editorial feel. PP Neue Montreal serves as the workhorse at 16px (1rem) for body text, with a slightly smaller 13px (0.8125rem) variant for secondary information and 12px (0.75rem) for labels. Weights range from 500 (Medium) for most text to 600 (Semibold) for buttons and emphasis. The system maintains consistent negative letter spacing across sizes to preserve the geometric character of PP Neue Montreal.

Verify licensing for Kalice, PP Neue Montreal, Recoleta, and Satoshi before production use. Kalice is by Margot Lévêque. PP Neue Montreal is by Mathieu Desjardins via Pangram Pangram Foundry. Recoleta is by Jorge Cisterna via Latinotype Ltda. Satoshi is by Deni Anggara via Indian Type Foundry.

## Layout

The layout system uses a centered content model with generous horizontal breathing room. The homepage places its primary search interface in the optical center of the viewport, with navigation elements anchored to the periphery.

Page margins are substantial: 96px (6rem) horizontal padding on main containers, with content often further constrained by max-width centers. The search bar and category grid sit within a narrower central column, creating a focused workspace effect. Vertical rhythm uses 28px (1.75rem) as a standard section gap, with larger 80px (5rem) and 90px (5.625rem) spacers for major section breaks.

The sidebar navigation on the homepage uses a fixed or sticky positioning pattern, occupying the left edge with compact link items stacked vertically. Each link includes an icon and text label with comfortable 8px (0.5rem) gaps. The main content area flows independently, allowing the search interface to remain centered regardless of sidebar state.

Grid patterns for category links use multi-column layouts with consistent 16px (1rem) gaps between items. The composition balances density with scannability—enough items to suggest depth, spaced to prevent visual fatigue.

## Visual language

The visual language communicates precision and creative sophistication. Rounded corners are a defining feature: panels use 24px (1.5rem), cards use 18px (1.125rem), and buttons use 12px (0.75rem) radii. Full pill shapes appear for filter chips and certain badges, creating a friendly, approachable character against the dark canvas.

Shadows are extremely subtle, functioning as inner glows rather than drop shadows. The signature shadow is an inset 1px ring in `rgba(186, 192, 239, 0.047)`—barely perceptible but essential for defining surface boundaries without harsh borders. A secondary shadow layer adds slight depth with `rgba(12, 41, 126, 0.09)` for floating elements.

Borders are hairline-thin, typically 0.5px to 1px in `border-subtle` or `border-highlight`. The search bar uses no visible border, relying entirely on the background value difference and subtle inner shadow to define its shape.

Iconography is simple and functional, paired with text labels in navigation and filter chips. The "Research mode" chip uses a sparkle icon to denote AI-powered functionality, with a coral accent color that draws attention without overwhelming.

## Components

### Search bar

The search bar is the central interaction point of the homepage. It presents as a large, rounded panel floating on the canvas.

- **Anatomy**: Container with placeholder text, filter chip row, and submit button
- **Surface**: `surface` background with `shadow-glow` inset ring
- **Typography**: Placeholder uses `ink-muted` at body size; active input uses `ink`
- **Shape**: `rounded.panel` (24px) with full width up to max-width constraint
- **Spacing**: 20px (1.25rem) internal padding, 15px (0.9375rem) vertical padding
- **Composition**: Filter chips arranged horizontally with 8px (0.5rem) gaps; submit button as circular icon at right edge

### Filter chip

Compact toggle buttons for refining search scope.

- **Anatomy**: Icon + text label, optionally with active state indicator
- **Surface**: `action-secondary-bg` background, transparent when inactive
- **Typography**: `typography.body-small` in `action-secondary-text`
- **Shape**: `rounded.chip` (12px) or full `rounded.pill`
- **Spacing**: 10px (0.625rem) vertical, 16px (1rem) horizontal padding; 8px (0.5rem) internal gap
- **Variants**: Active state uses `accent-coral` icon and slightly elevated background

### Upgrade banner

A persistent notification bar for plan limitations.

- **Anatomy**: Text block with headline and description, plus primary action button
- **Surface**: `canvas-elevated` background
- **Typography**: Headline uses `typography.body` at 600 weight; description uses `typography.body-small` in `ink-muted`
- **Shape**: `rounded.card` (18px)
- **Spacing**: 12px (0.75rem) to 14px (0.875rem) padding; button aligned to right
- **Composition**: Horizontal flex with space-between, button as prominent pill

### Category link grid

Organized lists of searchable topics with icon prefixes.

- **Anatomy**: Icon + text label, arranged in multi-column grid
- **Typography**: `typography.navigation` in `ink`
- **Spacing**: 16px (1rem) gap between items; 8px (0.5rem) icon-text gap
- **Composition**: Left-aligned category tabs with right-aligned link columns; 45px (2.8125rem) gap between major groupings

### Sidebar navigation

Vertical stack of primary navigation destinations.

- **Anatomy**: Icon + text label, with optional badge
- **Typography**: `typography.navigation` in `ink`
- **Spacing**: 8px (0.5rem) vertical padding per item; 8px (0.5rem) icon-text gap
- **Composition**: Fixed left position; items stack with consistent 8px gaps

## Responsive behavior

The design appears optimized for desktop viewing with its generous margins and centered search interface. At narrower viewports, the sidebar navigation should collapse to a horizontal top bar or hamburger menu, and the category grid should reflow from multiple columns to a single scrollable list. The search bar should maintain its central prominence but expand to full width minus safe margins.

The large display typography scales down proportionally: hero-display should reduce to approximately 2rem on tablet and 1.5rem on mobile to maintain line-length readability. Section margins compress from 96px to 24px on narrow screens.

## Practical implementation guidance

### Preserve
- The dark canvas as the default and primary viewing mode
- The serif/sans-serif pairing for display and body text
- Extremely subtle shadows and borders—elevation should be felt, not seen
- Generous horizontal margins and centered content composition
- Rounded corners at all scales, from chips to panels
- The search bar as the dominant visual and interactive element

### Avoid
- Light mode as the default experience
- Heavy drop shadows or pronounced borders
- Additional accent colors beyond the established blue-coral-orange trio
- Tight line spacing on display text
- Removing the icon from navigation and filter items

### Recommended build order
1. Establish the dark canvas and surface elevation layers
2. Implement PP Neue Montreal as the primary typeface with size/weight hierarchy
3. Add Kalice for hero display text
4. Build the search bar component with inner shadow and filter chips
5. Create the sidebar navigation and category grid
6. Add the upgrade banner and other secondary components
7. Polish with micro-interactions and focus states

### Accessibility
- Ensure all `ink-muted` text meets WCAG AA contrast against `canvas` backgrounds; use `ink` for essential information
- Provide visible focus indicators using `border-highlight` for keyboard navigation
- Maintain touch targets of at least 44px for filter chips and navigation items
- Include aria-labels on icon-only buttons like the search submit

## Scope note

This guide covers the homepage and research interface surfaces visible in the supplied images. Interior pages such as search results, individual design entries, and account settings are not represented. Motion design, loading states, and mobile-specific layouts are not documented. Measurements are exact where retained in the source data.


---
# Design Reference: KREA.AI
---

# How krea.ai is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/krea.ai-design)

Last updated: 2026-08-10

## Captured pages

[![Pricing page hero with large display type and four-column plan cards on light canvas](https://pin.fontofweb.com/9749?format=jpg)](https://design.withfudge.com/share/pin-9749)

[Pricing page hero with large display type and four-column plan cards on light canvas](https://design.withfudge.com/share/pin-9749)

[![Business and Enterprise tier cards with slider control and dark inverted CTA](https://pin.fontofweb.com/9748?format=jpg)](https://design.withfudge.com/share/pin-9748)

[Business and Enterprise tier cards with slider control and dark inverted CTA](https://design.withfudge.com/share/pin-9748)

[![Dark-themed sign-up modal with OAuth buttons and generative art preview](https://pin.fontofweb.com/9747?format=jpg)](https://design.withfudge.com/share/pin-9747)

[Dark-themed sign-up modal with OAuth buttons and generative art preview](https://design.withfudge.com/share/pin-9747)

[![Moodboards feature section with layered imagery and dark immersive background](https://pin.fontofweb.com/9746?format=jpg)](https://design.withfudge.com/share/pin-9746)

[Moodboards feature section with layered imagery and dark immersive background](https://design.withfudge.com/share/pin-9746)

## Overview

Krea's design system operates across two distinct modes: a light, airy marketing surface for plans and pricing, and an immersive dark environment for the generative product experience. The light mode prioritizes clarity and conversion through generous whitespace, crisp borders, and a disciplined typographic hierarchy. The dark mode shifts to cinematic presentation, letting generated imagery and interactive controls dominate while maintaining legibility through careful contrast management. Both modes share a common structural language—rounded cards, consistent spacing rhythms, and the same Swiss typographic foundation—creating continuity as users move from discovery to creation.

The system's personality emerges from restraint: minimal decoration, precise geometric relationships, and typography that commands attention without shouting. Color is used sparingly as an accent, primarily for interactive states and the signature blue action element. Photography and generated imagery provide the visual richness, while the interface recedes into a neutral, supportive role.

## Colors

| token | value | use |
|---|---|---|
| ink | #000000 | Primary text, primary button backgrounds, header elements |
| ink-secondary | #171717 | Elevated dark surfaces, secondary headings |
| ink-tertiary | #404040 | Tertiary text, subtle UI elements |
| muted | #737373 | Descriptions, captions, disabled states |
| canvas | #FAFAFA | Light mode page background |
| surface | #FFFFFF | Cards, modals, elevated containers |
| surface-elevated | #F5F5F5 | Subtle background variations, input fields |
| border | #E5E5E5 | Card outlines, dividers, subtle separators |
| border-strong | #D4D4D5 | Focused borders, active controls |
| action | #006EFF | Primary interactive accent, links, active states |
| action-contrast | #FFFFFF | Text on action backgrounds |
| dark-canvas | #0C0C0C | Dark mode page background |
| dark-surface | #101010 | Dark mode cards, containers |
| dark-surface-elevated | #171717 | Elevated dark elements, inputs |
| dark-border | #262626 | Dark mode subtle borders |
| dark-border-strong | #202020 | Dark mode focused borders |
| dark-ink | #FFFFFF | Primary text on dark backgrounds |
| dark-muted | #A3A3A3 | Secondary text on dark backgrounds |

The light mode establishes a near-white canvas with pure black ink, creating maximum contrast for reading and scanning. The dark mode inverts this relationship, using deep charcoal backgrounds that let colorful generated imagery and the blue action accent pop. Both modes avoid gradients in favor of flat, material surfaces with subtle border definitions. The action blue appears consistently across modes as the singular brand accent, used for primary buttons, active slider states, and link text.

## Typography

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Font | 4.5rem | 600 | 1.05 | -0.025em | Page headlines, pricing hero |
| section-display | Font | 3.5rem | 500 | 1 | -0.02em | Section titles, feature headers |
| feature-headline | Font | 2.25rem | 600 | 1.11 | -0.01em | Card titles, sub-section headings |
| body | Font | 1rem | 400 | 1.5 | 0 | Paragraphs, descriptions, navigation |
| body-small | Font | 0.875rem | 400 | 1.43 | 0 | Captions, metadata, fine print |
| label | Font | 0.75rem | 600 | 1.33 | 0 | Tags, badges, category labels |
| navigation | Font | 0.9375rem | 400 | 1.5 | 0.01em | Header links, menu items |
| button-primary | Font | 0.8125rem | 600 | 1 | 0 | Button labels, CTAs |

The type system is built on Font, supplied by Swiss Typefaces as "Font-Copyright C 2016 Swiss Typefaces Sàrl All Rights Reserved". Weights range from 400 to 600, with the heavier weights reserved for display and interactive elements. Display sizes employ negative tracking for a tighter, more intentional feel, while body text maintains neutral spacing for extended reading. The hierarchy is established through size and weight rather than color variation, keeping the palette restrained. Applesystem appears as a system fallback at 14px in limited contexts. Verify licensing for these families before production use.

## Layout

The layout follows a centered content model with generous horizontal margins. Light mode sections use substantial vertical padding—160px top, 128px bottom—to create breathing room between content blocks. Content containers are constrained by side margins of 260px on the pricing page, creating a narrow, focused reading column that draws attention to plan comparisons.

Dark mode product pages expand to wider margins, with 356px side gutters on feature sections that let imagery breathe against the deep background. The header maintains consistent horizontal padding across modes: 64px in light, 32px in dark, reflecting the different density expectations of marketing versus product contexts.

Grid structures are implicit rather than explicit. Pricing cards arrange in equal-width columns with 20px gutters. Feature sections use asymmetric compositions, with text blocks offset from imagery to create visual tension. The moodboards section demonstrates this clearly: text occupies the left third while layered imagery fills the right two-thirds, breaking the centered convention for editorial impact.

Spacing follows a modular rhythm based on 2px increments. Common values include 8px for tight element grouping, 12px for related items, 16px for component internal padding, 24px for card padding, 32px for section internal spacing, 48px for major element separation, 64px for section breaks, and 128-160px for page section divisions.

## Visual language

The visual language balances clinical precision with creative warmth. Interface elements are reduced to essential forms: flat buttons with minimal radius, hairline borders that define without decorating, and shadows so subtle they register as depth rather than ornament. The only decorative elements are the generated images themselves, which appear in rounded containers with consistent 16px radius.

Imagery treatment varies by context. Marketing pages show clean product screenshots and UI mockups with light borders. Product pages display full-bleed generated art with no border, letting the content merge with the dark canvas. The moodboards feature uses layered, overlapping images with slight rotation and offset, suggesting creative process and experimentation.

Iconography is minimal and functional, rendered in the current text color at small sizes. Checkmarks indicate plan features, arrows suggest navigation, and social provider logos appear at standard sizes in authentication flows. No custom icon font is used; system and brand SVGs serve all needs.

The slider control in pricing cards introduces the most complex interactive visual: a track with filled progress, a draggable thumb with subtle shadow, and labeled tick marks. This element bridges the gap between static information and dynamic configuration.

## Components

**Pricing Card**

- Anatomy: Card container, plan name, description, price display with currency and period, feature list with checkmarks, primary action button
- Surface: White background (#FFFFFF), 1px border (#E5E5E5), 16px radius
- Typography: Plan name uses feature-headline token, description uses body-small in muted, price uses hero-display at reduced size, features use body-small
- Shape: 16px border radius, consistent across all plan tiers
- Spacing: 24px internal padding, 20px gap between elements
- Composition: Vertical stack with left-aligned text, full-width button at bottom
- Variants: Enterprise tier inverts to dark surface (#000000) with white text and white-outlined button; Business tier includes slider control for compute unit selection

**Primary Button**

- Anatomy: Text label, optional icon, full-width or intrinsic width
- Surface: Black background (#000000), white text (#FFFFFF), no border
- Typography: button-primary token, 600 weight
- Shape: 8px border radius in light mode, 10px in dark mode product contexts
- Spacing: 12px vertical padding, 20px horizontal padding in navigation; 8px vertical, 24px horizontal in product contexts
- Composition: Centered text, flex row with 4-8px gap when icon present
- Variants: Inverted for dark backgrounds (white surface, black text); outlined variant with 1px border for secondary actions

**Sign-Up Modal**

- Anatomy: Overlay backdrop, modal container, split layout with form left and imagery right, close control, OAuth buttons, email input, submit button, legal text
- Surface: Dark modal (#171717) on darker backdrop (#0C0C0C at opacity), right panel shows generative art preview
- Typography: Headline uses section-display at reduced size, buttons use body weight, legal text uses body-small in muted
- Shape: 10px modal radius, 14px input radius, full-width buttons with 8px radius
- Spacing: 16px internal padding, 12px gap between form elements
- Composition: Two-column on desktop, stacked on smaller viewports; left column constrained to readable width

**Feature Section**

- Anatomy: Section container, eyebrow label, headline, body text, imagery block, optional CTA
- Surface: Dark background (#0C0C0C), text in white, imagery with subtle border or shadow
- Typography: Headline uses section-display, body uses body at 20px for lead paragraphs, labels use body-small in muted
- Shape: Imagery containers at 16px radius, overlapping images may break grid with rotation
- Spacing: 160px vertical section padding, 80px gap between text and imagery blocks
- Composition: Asymmetric two-column with text left, imagery right; imagery may extend beyond container bounds

**Slider Control**

- Anatomy: Track, filled progress indicator, draggable thumb, value labels
- Surface: Track in border color, fill in ink or action color, thumb in surface with shadow
- Typography: Value labels in body-small, weight 600 for active value
- Shape: Track height 4px, thumb 16px diameter with full rounding
- Spacing: Labels positioned above track with 8px gap
- Composition: Full-width within card, labels distributed across track length

## Responsive behavior

The system adapts through margin reduction and column stacking rather than breakpoint-specific redesigns. Pricing cards transition from four columns to two columns to single column as viewport narrows, maintaining internal spacing and typography scale. The sign-up modal collapses from split-panel to single column, hiding the imagery preview on smallest viewports.

Dark mode product pages maintain their immersive character across sizes, with imagery scaling proportionally and text blocks gaining horizontal padding as side margins compress. The moodboards section's layered imagery reconfigures from overlapping desktop composition to vertical scroll on mobile.

Typography scales down modestly: hero-display reduces to 3rem, section-display to 2.5rem. Body text remains at 1rem for readability. Touch targets maintain minimum 44px height for accessibility.

## Practical implementation guidance

**Preserve**
- The stark black-and-white contrast in light mode; it defines the brand's clinical precision
- Generous vertical spacing between sections; the rhythm feels intentional and premium
- Single-font typographic system; the discipline of Font across all weights
- Consistent 16px card radius; this small detail unifies all container types
- The dark mode's near-black canvas; anything lighter loses the immersive product feel

**Avoid**
- Introducing additional accent colors beyond the action blue; the system depends on chromatic restraint
- Heavy shadows or elevation effects; the flat material language is core to the aesthetic
- Decorative gradients in UI elements; photography and generated art provide all necessary visual interest
- Tightening display letterspacing further; the current values are calibrated for legibility at scale
- Using border-radius inconsistently; the 8px/10px/16px hierarchy serves distinct component roles

**Recommended build order**
1. Establish the dual color modes with complete token sets before any component work
2. Implement the typography scale with Font at all specified weights and sizes
3. Build the pricing card as the primary light-mode component; it exercises surface, border, spacing, and button systems
4. Create the dark mode feature section with asymmetric layout to validate imagery handling
5. Implement the sign-up modal to test overlay, form, and split-panel composition
6. Add the slider control last, as it requires the most complex interactive state management

**Accessibility**
- Maintain 4.5:1 minimum contrast for all body text; the light mode's black-on-white and dark mode's white-on-charcoal both exceed this
- Ensure the action blue (#006EFF) meets contrast requirements when used for text; test against both canvas colors
- Provide visible focus states for all interactive elements; the current design implies focus through border color shifts
- Add aria-labels to icon-only buttons in the header and modal close controls
- Consider reduced-motion preferences for the moodboards imagery transitions and slider interactions

## Scope note

This guide covers the marketing and product landing surfaces visible in the supplied images, including pricing, authentication, and feature presentation. It does not include the in-app generation interface, real-time canvas, video editing timeline, or mobile-native layouts. Motion design for generative previews, hover states on interactive cards, and form validation feedback are not documented here.


---
# Design Reference: PAPER.DESIGN
---

# How paper.design is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/paper.design-design)

Last updated: 2026-08-10

## Captured pages

[![Documentation page with left sidebar navigation, monospace section labels, and a dark technical diagram showing MCP server architecture with connected app icons.](https://pin.fontofweb.com/7126?format=jpg)](https://design.withfudge.com/share/pin-7126)

[Documentation page with left sidebar navigation, monospace section labels, and a dark technical diagram showing MCP server architecture with connected app icons.](https://design.withfudge.com/share/pin-7126)

[![Homepage section featuring Paper Roadmap heading with abstract geometric pixel art, followed by a two-column layout with filtered photography and build log announcements.](https://pin.fontofweb.com/7125?format=jpg)](https://design.withfudge.com/share/pin-7125)

[Homepage section featuring Paper Roadmap heading with abstract geometric pixel art, followed by a two-column layout with filtered photography and build log announcements.](https://design.withfudge.com/share/pin-7125)

[![Hero section with centered large display type reading the full-circle anti-slop workflow, a subtle curved line graphic, and a light download button on pure black.](https://pin.fontofweb.com/7124?format=jpg)](https://design.withfudge.com/share/pin-7124)

[Hero section with centered large display type reading the full-circle anti-slop workflow, a subtle curved line graphic, and a light download button on pure black.](https://design.withfudge.com/share/pin-7124)

[![Feature section showing connected to real content with a Paper Desktop application screenshot displaying a layered playlist interface with component tree navigation.](https://pin.fontofweb.com/7123?format=jpg)](https://design.withfudge.com/share/pin-7123)

[Feature section showing connected to real content with a Paper Desktop application screenshot displaying a layered playlist interface with component tree navigation.](https://design.withfudge.com/share/pin-7123)

## Overview

Paper's visual system is built for a design tool that bridges creative work and engineering. The interface commits fully to darkness: a pure black canvas sets the stage for warm off-white typography that feels more like aged paper than stark digital white. This creates a distinctive mood—technical but not cold, precise but not sterile. The system pairs a thin, elegant sans-serif display face with utilitarian monospace labels, establishing a clear hierarchy between expressive headlines and functional metadata. Pixel-art accents and abstract geometric imagery reinforce the brand's craft-oriented, hands-on philosophy. Every element serves the narrative of a tool built for designers who care about the underlying structure of their work, from canvas to code and back.

## Colors

The palette is intentionally narrow, deriving its character from temperature and contrast rather than breadth. The near-black canvas absorbs light, while the warm off-white ink prevents the harshness of pure white on pure black. Muted grays handle secondary information and borders without competing for attention. A reserved set of syntax colors appears in code contexts, drawn from a familiar dark-editor vocabulary.

| token | value | use |
|---|---|---|
| canvas | #000000 | Primary page background, deepest layer |
| surface | #080808 | Slightly elevated panels, subtle differentiation |
| surface-elevated | #272727 | Active UI chrome, selected states, code backgrounds |
| ink | #F0EFE4 | Primary text, headings, interactive labels |
| ink-muted | #909090 | Secondary descriptions, captions, disabled states |
| ink-dim | #555555 | Tertiary metadata, timestamps, subtle borders |
| border | #333333 | Structural dividers, card outlines, section separators |
| border-subtle | #2A2A2A | Hairline rules, inset panel edges |
| action | #F0EFE4 | Primary button fill, emphasized interactive surfaces |
| action-inverse | #080808 | Text on action surfaces |
| code-green | #4ADE80 | Success states, string literals in code |
| code-teal | #4EC9B0 | Types, interfaces in code |
| code-blue | #569CD6 | Keywords, control flow in code |
| code-yellow | #DCDCAA | Functions, methods in code |
| code-orange | #CE9178 | Strings, attributes in code |
| code-cyan | #9CDCFE | Variables, parameters in code |
| code-gray | #DDDDDD | Default code text, comments |

The warm ink against cold canvas creates the system's signature tension. Code colors remain subordinate, appearing only within technical contexts like documentation or embedded snippets. No gradients or shadows are used; depth comes from surface value shifts alone.

## Typography

Three families divide the typographic labor: Matter handles all display and body text with an extremely thin weight that feels drawn rather than rendered; Inter serves as a secondary body face for longer reading contexts; Paper Mono manages labels, tags, and technical annotations with a compact, square-rigged character. System Monospace appears only for inline code and preformatted blocks.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Matter | 4rem | 360 | 1 | -0.02em | Homepage hero headlines |
| section-display | Matter | 3.5rem | 360 | 1 | -0.02em | Section-opening statements |
| body | Matter | 1.125rem | 400 | 1.556 | 0.01em | Default paragraphs, navigation |
| body-large | Inter | 1.125rem | 400 | 1.556 | -0.015em | Extended reading, documentation |
| body-small | Inter | 0.875rem | 400 | 1.714 | -0.015em | Dense text, captions |
| section-heading | Matter | 1.125rem | 550 | 1.778 | 0.01em | Subsection titles |
| label | Paper Mono | 0.75rem | 400 | 1.333 | 0.015em | Category tags, metadata |
| label-small | Paper Mono | 0.6875rem | 400 | 2 | 0.016em | Inline badges, status pills |
| navigation | Matter | 1.125rem | 400 | 1.556 | 0.01em | Top-bar links |
| code | System-Monospace | 0.75rem | 550 | 2 | 0.1em | Preformatted blocks, syntax |

Matter's weight 360 is the system's visual signature—lighter than typical thin weights, it creates an almost engraved quality at large sizes. Paper Mono's tight proportions and minimal tracking keep labels from feeling decorative; they read as functional equipment. Verify licensing for these families before production use. Matter is designed by Martin Vácha and available from Displaay. Paper Mono is designed by Guido Ferreyra and Javier Quintana Godoy.

## Layout

The page architecture favors centered single-column compositions for persuasive content and split asymmetric layouts for feature exposition. A consistent horizontal margin system keeps content from touching viewport edges while allowing full-bleed dark canvas to dominate the visual field.

The top navigation spans the full width with generous horizontal margins—12rem on each side at desktop scale. Navigation links are evenly distributed between a left-aligned logo mark and right-aligned utility actions. The main content area typically centers within a maximum width of 60rem, though hero sections occasionally break this constraint for dramatic scale.

Section spacing follows a rhythmic pattern: 3.75rem for standard content blocks, expanding to 5.625rem for major section transitions. Internal padding within cards and panels sits at 3.75rem, creating breathable containers without excessive separation from the dark ground. The documentation layout introduces a left sidebar occupying roughly one-quarter of the content width, with a clear vertical hierarchy of section labels and nested page links.

Grid lines appear as subtle visual texture in some sections—faint rules that suggest drafting paper or blueprint grids without imposing a rigid column structure. These are decorative rather than structural, reinforcing the tool's design-craft positioning.

## Visual language

Imagery and graphics follow a consistent logic: photographic content receives heavy processing—halftone dithering, color separation, and pixelation—that transforms natural imagery into something closer to print media or early digital graphics. This treatment unifies diverse subject matter under the brand's technical-aesthetic umbrella.

Abstract geometric elements appear as standalone accents: interlocking rectangles in muted olive and periwinkle, pixelated checkerboard patterns, and sparse grid lines. These never compete with content; they occupy negative space as visual punctuation. The homepage hero features a subtle curved line that arcs behind the centered headline, suggesting completeness or cyclical process without literal illustration.

The application screenshot in the feature section demonstrates the tool's actual interface: dark chrome with layered panels, a component tree on the left, and a rendered preview on the right. This honest presentation—showing the real product rather than an idealized mockup—extends the system's straightforward, engineering-credible tone.

Color in imagery tends toward warm naturals: golden flowers, amber foliage, earth tones. These connect the digital tool to physical craft traditions and prevent the dark interface from feeling purely technological.

## Components

**Navigation bar**

Anatomy: Logo mark left, primary links center-left, utility actions right. The Paper wordmark uses a small geometric icon paired with the name in Matter at body size.

Surface and text color: Transparent background over canvas, ink color for all text.

Typography: `{typography.navigation}` for all links.

Spacing: Full-width bar with horizontal margins of 12rem.

**Primary button**

Anatomy: Text label with optional leading icon, contained within a rounded rectangle.

Surface and text color: Action fill with action-inverse text.

Typography: `{typography.body}`.

Shape: 0.25rem corner radius.

Spacing: 0.375rem vertical padding, 0.875rem horizontal padding.

Variants: A secondary variant inverts the scheme—canvas background with ink text and a subtle border.

**Feature card**

Anatomy: Full-width container with large display heading, supporting paragraph, and optional media or screenshot.

Surface and text color: Canvas background, ink heading, ink-muted body text.

Typography: `{typography.section-display}` for headings, `{typography.body}` for descriptions.

Spacing: 3.75rem internal padding, often with 5.625rem section margins.

Composition: Asymmetric two-column layouts alternate image and text placement.

**Documentation sidebar**

Anatomy: Fixed left panel with section labels in uppercase monospace, followed by nested page links.

Surface and text color: Canvas background, ink for active items, ink-muted for inactive.

Typography: `{typography.label}` for section headers, `{typography.body-small}` for page links.

Spacing: 0.75rem vertical spacing between section labels, 0.75rem indentation for nested items.

**Code block**

Anatomy: Preformatted text container with optional language indicator.

Surface and text color: Surface-elevated background, code-gray default text with syntax highlighting.

Typography: `{typography.code}`.

Shape: No border radius, 1px border in border-subtle.

**Status badge**

Anatomy: Compact inline label with optional leading dot indicator.

Surface and text color: Transparent or surface background, ink or contextual color text.

Typography: `{typography.label-small}`.

Shape: Full pill with 9999px radius.

Spacing: 0.25rem vertical, 0.5rem horizontal padding.

## Responsive behavior

The system presents a desktop-first organization. For narrower viewports, the documentation sidebar should collapse into a toggleable drawer or move above the content stream. Hero display type should scale down proportionally—section-display at tablet, with further reduction to body-large for narrow mobile screens. The asymmetric two-column feature layouts should stack vertically, preserving image-text order. Navigation links may compress into a condensed menu or hamburger toggle when horizontal space is constrained. Maintain the generous dark margins even at small sizes; the canvas is the brand's most recognizable element and should never feel crowded.

## Practical implementation guidance

**Preserve**

- The extreme contrast between warm ink and cold canvas; this is the system's emotional core.
- Matter's weight 360 for display type; substituting a standard 300 or 400 weight loses the distinctive etched quality.
- Paper Mono for all functional labels and metadata; this family provides necessary texture against the smooth sans-serif body.
- Generous section spacing; the dark canvas needs room to breathe, and cramped layouts feel oppressive.

**Avoid**

- Pure white text; the warm off-white ink is calibrated specifically for reduced eye strain on black.
- Rounded corners larger than 0.25rem on buttons; the system favors sharp, precise geometry.
- Decorative shadows or gradients; depth comes from surface value alone.
- Saturated colors outside the code palette; the restrained spectrum is intentional.

**Recommended build order**

1. Establish the canvas and ink colors as CSS custom properties.
2. Implement Matter at weight 360 for hero and section display sizes.
3. Add Paper Mono for labels and navigation section headers.
4. Build the navigation bar with correct spacing and link treatments.
5. Create the primary and secondary button components.
6. Implement feature card layouts with asymmetric image-text composition.
7. Add documentation sidebar with nested link hierarchy.
8. Integrate code block styling with syntax color tokens.

**Accessibility**

- The high contrast between ink (#F0EFE4) and canvas (#000000) exceeds WCAG AAA standards for normal text.
- Ensure interactive elements have visible focus indicators; consider a 2px outline in code-blue or a subtle background shift.
- Paper Mono at small sizes should maintain minimum 12px rendering; the 11px variant is reserved for non-critical status indicators.
- When using the dark code palette for syntax highlighting, verify that color combinations maintain 4.5:1 contrast ratios against the surface-elevated background.

## Scope note

This guide covers the homepage, documentation, and pricing surfaces visible in the supplied images. Mobile breakpoints, animation behavior, form validation states, and the full code syntax highlighting specification are not included. Measurements are practical adaptation targets.


---
# Design Reference: BOLT.NEW
---

# How bolt.new is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/bolt.new-design)

Last updated: 2026-08-04

## Captured pages

[![Dark builder workspace with left chat rail and large preview stage](https://pin.fontofweb.com/6001?format=jpg)](https://design.withfudge.com/share/pin-6001)

[Dark builder workspace with left chat rail and large preview stage](https://design.withfudge.com/share/pin-6001)

[![Centered marketing hero with bordered role cards and dark panels](https://pin.fontofweb.com/6000?format=jpg)](https://design.withfudge.com/share/pin-6000)

[Centered marketing hero with bordered role cards and dark panels](https://design.withfudge.com/share/pin-6000)

[![Blue design-system board with swatches, type samples, and tiles](https://pin.fontofweb.com/5999?format=jpg)](https://design.withfudge.com/share/pin-5999)

[Blue design-system board with swatches, type samples, and tiles](https://design.withfudge.com/share/pin-5999)

## Overview

Bolt.new uses one visual language for two related surfaces: the marketing page and the builder workspace. Both feel like a dark developer cockpit rather than a glossy consumer site. The canvas stays near-black, the borders stay visible, and the blue action color does almost all of the emphasis work. That restraint matters. The page does not depend on ornament or on a heavy display-font hierarchy; it depends on tight geometry, readable Inter text, and large areas of empty space that make the active panel feel intentional.

The workspace view is the clearest expression of the system: a narrow left rail for conversation, a wide preview stage on the right, and a compact top bar that holds mode icons and publishing actions. The marketing views reuse the same attitude at a larger scale. Centered headings sit above bordered cards, and the cards contain nested screenshots, charts, toggles, and short explanatory copy. The result is one family of surfaces that can move from editor to promotional page without changing temperament.

## Colors

The palette is deliberately narrow. Most surfaces live in a dark charcoal range, so tiny shifts in tone separate the shell, the inset panes, and the border lines. Blue carries all action weight. Purple appears only as a secondary accent in the swatch board, which keeps the brand from feeling noisy. White comes in two forms: a clean white for the brightest labels and a slightly softened white for broad headline text. Mid-greys handle secondary copy, status text, and quiet metadata.

The dark charcoal UI is the base layer. Brighter card fills, image-backed panels, and white-headed showcase blocks sit on top of it as contained counter-surfaces, so the page can move between flat shells and brighter content areas without changing tone. Blue and purple stay accent-only treatments for actions and examples; they never replace the dark base mode.

| token | value | use |
|---|---|---|
| `deep-black` | `#000000` | The deepest cuts in the chrome and rare mark details |
| `action` | `#1488FC` | Primary buttons, links, and the strongest interactive emphasis |
| `action-strong` | `#3B82F6` | Secondary blue emphasis in charts, chips, and illustrated highlights |
| `action-soft` | `#2BA6FF` | Lighter blue accents in the design-system board and helper cues |
| `canvas` | `#1E1E21` | Main page background behind the rails and marketing panels |
| `surface` | `#171719` | Inset panels, cards, and the main content stage |
| `surface-raised` | `#2C2C30` | Hairline borders and raised shell edges |
| `muted-ink` | `#525252` | Disabled or low-contrast text and quiet chrome labels |
| `subdued-ink` | `#73737B` | Secondary helper copy and less prominent UI text |
| `soft-ink` | `#A3A3AC` | Supporting text in the workspace and cards |
| `ink-soft` | `#FEFEFF` | Large headline text that should stay crisp but not harsh |
| `ink` | `#FFFFFF` | Strong text, icons, and button labels |
| `accent-purple` | `#8B5CF6` | Rare secondary accent on the swatch board and color samples |

The system works because dark surfaces and blue actions are never separated from one another. Blue appears on top of charcoal, not on white. White appears on dark panels, not on pale backgrounds. That consistent pairing lets the interface stay readable even when the page is mostly empty.

## Typography

Inter is the only visible family. The type system is compact and product-like. It does not chase oversized display drama through family switching; instead, it leans on weight, alignment, and contrast against the dark canvas. In the retained measurements, 18px is the top size, so the page gains presence from boldness and spacing rather than from a huge size ladder. Licensing details for Inter are not supplied here.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| `hero-display` | Inter | 1.125rem | 700 | 1.2 | -0.02em | Large centered marketing headings |
| `section-display` | Inter | 1rem | 700 | 1.25 | -0.015em | Feature titles and showcase headings |
| `body` | Inter | 1rem | 400 | 1.5 | 0em | Explanatory copy, rail text, and panel body text |
| `body-medium` | Inter | 1rem | 500 | 1.5 | 0em | Button labels, active controls, and emphasized copy |
| `label` | Inter | 0.875rem | 500 | 1.43 | 0em | Tabs, small control text, and short captions |
| `small-note` | Inter | 0.875rem | 400 | 1.43 | 0em | Helper lines, timestamps, and quiet status text |

The hierarchy stays readable because the strongest headings are centered or isolated inside cards, while the body copy remains short and close to the controls it explains. The page should keep line lengths short in the rail and allow the center stage to breathe. That balance is more important than pushing size upward.

## Layout

The workspace layout uses a strong two-column split. The left rail stays narrow and functions like a conversation and control column. It stacks a small header, a message stream, and a bottom composer. The right side is much larger and behaves like a preview or output stage. Its emptiness is part of the layout language: the center of the stage is supposed to feel open, as if the page is waiting for the next build result. Hairline borders and 12px corners keep the split visible without making it feel boxed-in.

The top bar is thin and dense. It holds compact icon groups, a path or mode field, and action buttons at the far edge. This strip should remain visually lighter than the content beneath it. Padding stays close to the 16px, 24px, and 32px steps from the packet, with the larger 40px and 64px measures reserved for the marketing page and the wide sections that need extra air.

The marketing page uses centered composition. The headline stack sits above a row of large cards, each card framed by a dark border and a modest radius. Inside those cards, nested panes, charts, screenshots, or checklist tiles create depth without introducing shadows. The blue design-system showcase pushes that pattern further: a centered title, small color chips, broad sample swatches, and a staged set of type and component examples.

## Visual language

Bolt.new feels like a controlled builder environment, not an office dashboard. The visual language is made from quiet surfaces, thin borders, and small blue flashes rather than from ornament. The brand mark is minimal. Icons are spare. Panels sit close together but still breathe because the borders hold them apart. That combination gives the interface a precise, technical mood without turning hard or mechanical.

The empty preview stage is important. It is not a dead zone; it is the visual pause that makes the rest of the shell feel active. The left rail, by contrast, is dense and conversational. This contrast between dense and open spaces is one of the main ordering principles of the design. The marketing views use the same principle with cards: each card is a contained world, and the grid keeps enough gap between them that the page still feels composed rather than crowded.

Color usage is similarly disciplined. Blue is the only persistent action color. Purple is a supporting accent, not a competing brand note. White text against charcoal surfaces gives the interface its clarity, while the slightly softened white helps larger headings feel less stark. Shadows are not part of the language. Borders and fill contrast do the structural work.

## Components

### Shell and top bar

- **Anatomy:** Brand mark, mode icons, a central field, and right-aligned share or publish actions.
- **Surface:** Near-black chrome with a slightly darker content inset beneath it.
- **Typography:** Small Inter labels and compact button text.
- **Shape:** 12px corners on controls, with pill-like treatment on the strongest actions.
- **Spacing:** Tight horizontal padding; compact vertical rhythm.
- **Visible states:** One icon group reads as active through blue fill, while the main action buttons stay bright against the dark bar.

### Conversation rail

- **Anatomy:** Small header, message history, status line, and a bottom composer.
- **Surface:** Flat charcoal panel with a visible border rather than a shadow.
- **Typography:** 16px body text for the main message, 14px helper text for status and hints.
- **Shape:** Rounded but not soft to the point of blurring; the composer sits inside a 12px panel.
- **Spacing:** The rail compresses content vertically and leaves only a small amount of breathing room between items.
- **Visible states:** The lower input area reads as ready for action through contrast and a blue send control.

### Preview stage

- **Anatomy:** Large empty field with a centered placeholder mark and a quiet footer area.
- **Surface:** The same dark family as the rail, but opened up into a much larger uninterrupted plane.
- **Typography:** Small, low-contrast helper text.
- **Shape:** Wide rounded frame, hairline border, and minimal internal decoration.
- **Spacing:** Generous interior space, especially around the center point.
- **Visible states:** The stage should stay subdued until content arrives; the placeholder exists to mark the center, not to compete with it.

### Marketing role cards

- **Anatomy:** Centered heading stack above a row of bordered cards, each with a title, short copy, and nested product or analytics imagery.
- **Surface:** Deep charcoal with a slight tonal separation between the card fill and the page background.
- **Typography:** Strong 16px titles and lighter supporting copy beneath them.
- **Shape:** 12px to 24px corners depending on the card scale.
- **Spacing:** Cards need enough width to hold small internal demos without feeling crowded.
- **Visible states:** The content inside each card can be a version list, a publish panel, a chart, or a checklist, but the chrome remains the same.

### Design-system showcase

- **Anatomy:** Centered title, color chips, component samples, and oversized type examples.
- **Surface:** A deep, uniform stage that lets the blue swatches and white type read cleanly.
- **Typography:** Heavy heading treatment, then a compact sequence of sample text sizes.
- **Shape:** Rounded panels and swatches, with visible borders around the sample blocks.
- **Spacing:** The composition is open and symmetrical, with enough room around every sample to make the system legible.
- **Visible states:** Bright blue samples become the dominant emphasis, while dark swatches and neutral blocks support them.

## Responsive behavior

The visual system should collapse by preserving order, not by changing character. The rail should stack before the stage becomes cramped. The top bar should keep its compact control language even when it wraps. Marketing cards should move from three across to fewer columns without changing border weight, text color, or the blue action tone. The page can become narrower, but it should not become brighter, flatter, or more decorative. The same dark surfaces and blue emphasis need to remain the anchor at every width.

## Practical implementation guidance

### Preserve

- Keep the dark shell, narrow rail, and wide stage relationship intact.
- Keep 1px borders visible on panels, cards, and controls.
- Keep blue as the only durable action color.
- Keep Inter as the single text family.
- Keep the page calm; empty space is part of the design.

### Avoid

- Avoid drop shadows as the main source of depth.
- Avoid introducing additional bright accent colors.
- Avoid turning panels into soft glass or glossy cards.
- Avoid pushing type beyond the 14/16/18px ladder.
- Avoid filling the preview stage with decorative noise.

### Recommended build order

1. Build the dark shell and border system first.
2. Add the top bar and the left conversation rail.
3. Establish the large preview stage and its empty-state center.
4. Recreate the marketing card grid with the same border and radius language.
5. Finish with the design-system showcase and its blue-led swatches.

### Accessibility

- Keep light text on dark surfaces at strong contrast.
- Make icon-only controls readable with labels or accessible names.
- Preserve visible focus treatment on every control.
- Keep helper text readable; do not let muted text become decorative.
- Avoid relying on color alone for active states; use shape, placement, and border contrast as well.

## Scope note

This guide covers the desktop marketing page and builder workspace shown in the supplied views. It does not include mobile breakpoints, motion, hover or focus choreography, loading states, error states, or alternate authenticated branches that are not visible here. Inter licensing is not specified in the supplied material.


---
# Design Reference: FIRECRAWL.DEV
---

# How firecrawl.dev is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/firecrawl.dev-design)

Last updated: 2026-08-10

## Captured pages

[![Hero CTA section with orange dot-matrix illustrations and primary action buttons on light canvas](https://pin.fontofweb.com/7576?format=jpg)](https://design.withfudge.com/share/pin-7576)

[Hero CTA section with orange dot-matrix illustrations and primary action buttons on light canvas](https://design.withfudge.com/share/pin-7576)

[![Footer with product links, social proof badges, and orange ASCII art landscape](https://pin.fontofweb.com/7575?format=jpg)](https://design.withfudge.com/share/pin-7575)

[Footer with product links, social proof badges, and orange ASCII art landscape](https://design.withfudge.com/share/pin-7575)

[![FAQ accordion with orange-accented headings and categorized question groups](https://pin.fontofweb.com/7574?format=jpg)](https://design.withfudge.com/share/pin-7574)

[FAQ accordion with orange-accented headings and categorized question groups](https://design.withfudge.com/share/pin-7574)

[![Pricing page with orange numerals, tier cards, and code parameter callouts](https://pin.fontofweb.com/7573?format=jpg)](https://design.withfudge.com/share/pin-7573)

[Pricing page with orange numerals, tier cards, and code parameter callouts](https://design.withfudge.com/share/pin-7573)

## Overview

Firecrawl presents a developer-focused web data platform built on a stark black canvas with energetic orange accents. The visual system prioritizes technical credibility through Swiss typographic discipline while maintaining approachable warmth through its signature flame-orange action color. The interface alternates between immersive dark sections and carefully structured content areas, creating rhythm through generous whitespace and precise grid alignment. Every element serves the core narrative: transforming chaotic web data into structured, actionable intelligence. The design language speaks directly to engineers and technical founders—clean, confident, and unafraid of density when complexity demands it.

## Colors

The palette operates on a high-contrast dark mode foundation with a single vibrant accent. Black dominates every surface, creating infinite depth and making the orange action color feel electric against the void.

| token | value | use |
|---|---|---|
| canvas | #000000 | Primary page background, all section containers, card backgrounds |
| surface | #000000 | Elevated panels, modal backgrounds |
| ink | #FFFFFF | Primary text, headings, active navigation |
| ink-muted | #999999 | Secondary text, descriptions, inactive states, card borders |
| ink-subtle | #C2C2C2 | Tertiary labels, metadata, footer links |

The orange accent appears strategically in the flame logo mark, primary call-to-action buttons, highlighted words within headings, and numerical pricing displays. This concentrated use prevents visual fatigue while establishing brand recognition. The grayscale text hierarchy—white for primary content, medium gray for supporting copy, light gray for metadata—creates clear information architecture without competing with the accent. Photographic and illustrative content uses the same orange in dot-matrix and ASCII art treatments, unifying brand imagery with interface elements.

The exact interface colors extracted from the source are black (#000000), medium gray (#999999), light gray (#C2C2C2), and white (#FFFFFF). The orange accent values visible in images and gradients are derived from the image palette and gradient stops rather than direct interface color declarations.

## Typography

Two families serve distinct roles: Suisse Intl carries all interface and marketing copy with Swiss precision, while Geist Mono handles code, parameters, and technical annotations with engineered clarity.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Suisse Intl | 3.75rem | 500 | 1.07 | -0.005em | Homepage hero headlines |
| section-display | Suisse Intl | 3.25rem | 500 | 1.08 | -0.01em | Section headings, FAQ titles |
| feature-heading | Suisse Intl | 2rem | 500 | 1.13 | -0.005em | Feature card titles, pricing tiers |
| body | Suisse Intl | 1rem | 400 | 1.5 | 0em | Paragraphs, descriptions, navigation |
| body-small | Suisse Intl | 0.875rem | 400 | 1.43 | 0.01em | Secondary descriptions, footer links |
| label | Suisse Intl | 0.75rem | 450 | 1.67 | 0em | Buttons, tags, category labels |
| code | Geist Mono | 0.75rem | 400 | 1.33 | 0em | Inline parameters, API references |
| code-small | Geist Mono | 0.6875rem | 400 | 1.45 | 0em | Dense code blocks, terminal output |

Suisse Intl appears in Regular (400), Book (450), and Medium (500) weights. The Book weight serves button labels and subtle emphasis, while Medium anchors all display hierarchy. Geist Mono appears in Regular (400) and occasionally Medium (500) for emphasized code tokens. The type scale uses a 2px relative unit, with sizes snapping to clean multiples: 12px, 13px, 14px, 16px, 20px, 24px, 32px, 40px, 52px, 60px, and 64px.

Verify licensing for these families before production use. Suisse Intl is designed and distributed by Swiss Typefaces. Geist Mono is designed by Basement Studio and distributed through Vercel.

## Layout

The layout system centers content within generous horizontal margins, typically 304px on each side at maximum width, creating a focused reading column that floats within the black canvas. Sections stack vertically with substantial breathing room—88px to 143px vertical padding creates clear territorial boundaries between content types.

The grid alternates between full-bleed immersive sections and contained content areas. Hero sections push content deep into the viewport with 254px top padding, establishing dramatic entry points. Feature grids use asymmetric layouts: two-column splits for FAQ categories, three-column tiers for pricing cards, and multi-column footer matrices for navigation density.

Spacing follows a 2px base unit, expressed in rem at 0.125rem per step. Common increments include 8px for tight internal padding, 16px for component gutters, 24px for card padding, 32px for section internal spacing, 40px for card padding, 56px for hero content blocks, and 88px for major section breaks. Negative margins of -1px appear at component boundaries to collapse adjacent borders, creating seamless grid lines between cards.

Border radius scales from 4px for subtle rounding through 8px for buttons, 10px for small cards, 12px for feature cards, and 9999px for pill-shaped tags and badges. The 16px radius appears on larger interactive containers.

## Visual language

The visual identity merges technical precision with organic energy. The flame-orange dot-matrix illustrations—abstract landscapes built from thousands of tiny orange dots—serve as the signature graphic motif. These appear in hero sections, footer art, and decorative backgrounds, creating brand recognition through algorithmic texture rather than literal imagery.

Interface elements favor restraint: no drop shadows on cards, no gradients on surfaces, no glassmorphism. Elevation is communicated through border definition alone—1px solid lines in subtle gray create card boundaries against the black canvas. The single exception is a careful gradient on certain buttons: a linear fade from white to transparent that suggests luminous depth without breaking the flat design language.

Iconography uses simple geometric marks: chevrons for accordion states, arrows for external links, minimal glyphs for social platforms. The code-influenced aesthetic extends to parameter callouts—`maxCredits` and endpoint paths appear in Geist Mono within subtle rounded rectangles, reinforcing the API-first product positioning.

Interactive states are understated: text shifts slightly brighter on hover, buttons maintain solid fills without complex transitions. The confidence of the system comes from its stillness—elements hold their ground rather than competing for attention.

## Components

### Primary Button
- **Anatomy**: Solid fill with white label text, optional icon prefix
- **Surface**: Black background with white text, or gradient-enhanced treatment
- **Typography**: `{typography.label}` at 14px Book weight
- **Shape**: 10px border radius, 8px 12px padding
- **Spacing**: Often paired with secondary button at 16px horizontal gap
- **Variants**: Default fill with gradient overlay for depth on featured CTAs

### Secondary Button
- **Anatomy**: Transparent background with subtle border, dark text
- **Surface**: Transparent fill, 1px border in muted gray
- **Typography**: `{typography.label}` matching primary button
- **Shape**: 10px border radius, equivalent padding to primary
- **Composition**: Positioned adjacent to primary with consistent height

### Feature Card
- **Anatomy**: Bordered container with internal padding, optional header badge
- **Surface**: Black background, 1px border in medium gray
- **Typography**: Feature heading in Medium 24px, description in body 16px
- **Shape**: 12px border radius, 28px to 40px internal padding
- **Spacing**: 16px to 24px between cards in grid layouts
- **Variants**: Pricing cards include orange numerical highlights and "Most Accurate" pill badges

### FAQ Accordion
- **Anatomy**: Category sidebar with expandable question groups
- **Surface**: Black background, 1px horizontal dividers
- **Typography**: Category labels in 24px Medium, questions in 16px Regular, answers in 16px Regular with muted color
- **Shape**: Full-width rows with 20px horizontal padding
- **Composition**: Two-column layout with sticky category navigation
- **States**: Collapsed shows chevron-down; expanded reveals answer with chevron-up

### Code Parameter Callout
- **Anatomy**: Inline code snippet within rounded container
- **Surface**: Black background with subtle border treatment
- **Typography**: `{typography.code}` in Geist Mono Regular
- **Shape**: 6px to 8px border radius, 4px 8px internal padding
- **Composition**: Embedded within descriptive text or feature descriptions

### Navigation Bar
- **Anatomy**: Logo mark with flame icon, text links, action buttons
- **Surface**: Transparent or black background
- **Typography**: Links in 14px Regular with 0.14px letter spacing
- **Shape**: 8px border radius on interactive elements
- **Composition**: Horizontal flex with 16px gaps between links

### Footer
- **Anatomy**: Multi-column link matrix with brand art and social proof
- **Surface**: Black background, 1px top border
- **Typography**: Column headers in 16px Medium, links in 14px Regular muted
- **Shape**: Full-width with contained content
- **Composition**: Four-column product grid, social links with platform icons, Y Combinator and SOC 2 badges

## Responsive behavior

The design maintains its dark character across viewport sizes, with primary adaptation occurring in content width and column count. The 304px side margins collapse on narrower screens, allowing content to breathe while preserving the centered column aesthetic. Multi-column grids—pricing tiers, footer links, feature cards—stack to single columns on mobile with maintained internal spacing.

Typography scales down modestly: hero display may reduce from 60px to 40px, section display from 52px to 32px. The dot-matrix illustrations remain visible but may crop or scale to fit narrower containers. Accordion layouts transition from two-column to single-column, with category labels becoming horizontal scroll or dropdown selectors.

Touch targets maintain minimum 44px height for buttons and navigation items. Code blocks and parameter callouts gain horizontal scroll rather than text wrapping to preserve readability.

## Practical implementation guidance

### Preserve
- The absolute black canvas as the dominant surface—any lightening breaks the brand
- Orange accent concentration in buttons, highlighted heading words, and numerical data
- Swiss typographic hierarchy: Medium for display, Regular for body, Book for subtle emphasis
- Geist Mono exclusivity for all code and technical parameters
- Generous vertical section spacing—crowding destroys the premium technical feel
- Dot-matrix illustration style for brand imagery

### Avoid
- Adding shadows or gradients to cards and surfaces—the flat border system is intentional
- Using orange for large background fills or text blocks—reserve for accents only
- Mixing additional font families beyond Suisse Intl and Geist Mono
- Reducing contrast below WCAG AA for the muted gray text
- Adding decorative elements that compete with the dot-matrix art

### Recommended Build Order
1. Establish the black canvas and base typography scale
2. Implement the 304px-contained content column with responsive collapse
3. Build the button system with primary and bordered secondary variants
4. Create the card component with 1px border and consistent padding
5. Add the FAQ accordion with two-column layout
6. Integrate Geist Mono for all code and parameter displays
7. Implement dot-matrix illustrations as SVG or canvas elements
8. Polish with footer multi-column grid and social proof badges

### Accessibility
- Ensure action elements meet 3:1 contrast against black for UI components
- White text on black exceeds 7:1 for all primary content
- Provide visible focus indicators on all interactive elements
- Maintain keyboard navigation for accordion expand/collapse
- Code blocks should include copy functionality and avoid horizontal scroll when possible
- Respect `prefers-reduced-motion` for any dot-matrix animation

## Scope note

This guide covers the marketing site surfaces including homepage, agent product page, pricing, and onboarding flows. Dashboard interfaces, API documentation rendering, and authenticated application states are not represented in the supplied material. Motion behavior for the dot-matrix illustrations and exact hover transition timing were not captured. The orange accent color values are interpreted from image palettes and gradient stops rather than direct interface color declarations.


---
# Design Reference: SUNO.COM
---

# How suno.com is designed

[Open the live Fudge conversation](https://design.withfudge.com/share/suno.com-design)

Last updated: 2026-08-10

## Captured pages

[![Pricing page with three dark cards, pink accent border on Pro Plan, and white pill buttons against near-black background](https://pin.fontofweb.com/4866?format=jpg)](https://design.withfudge.com/share/pin-4866)

[Pricing page with three dark cards, pink accent border on Pro Plan, and white pill buttons against near-black background](https://design.withfudge.com/share/pin-4866)

[![Hero section with warm gradient glow, large display headline, and app store rating cards with white download buttons](https://pin.fontofweb.com/4865?format=jpg)](https://design.withfudge.com/share/pin-4865)

[Hero section with warm gradient glow, large display headline, and app store rating cards with white download buttons](https://design.withfudge.com/share/pin-4865)

[![Pricing page showing monthly/yearly toggle with checkmark icons and feature list hierarchy in dark theme](https://pin.fontofweb.com/4864?format=jpg)](https://design.withfudge.com/share/pin-4864)

[Pricing page showing monthly/yearly toggle with checkmark icons and feature list hierarchy in dark theme](https://design.withfudge.com/share/pin-4864)

[![Feature card with audio stem visualization using blue, orange, and green waveform blocks on dark surface](https://pin.fontofweb.com/4863?format=jpg)](https://design.withfudge.com/share/pin-4863)

[Feature card with audio stem visualization using blue, orange, and green waveform blocks on dark surface](https://design.withfudge.com/share/pin-4863)

## Overview

Suno's design system is built for a music creation platform that communicates creative possibility through restraint and contrast. The interface sits on a near-black canvas, letting generative imagery and warm atmospheric gradients become the emotional center of each section. Typography splits duties between an elegant, high-contrast editorial serif for headlines and a precise neo-grotesque sans-serif for everything functional. The result feels like a professional audio tool that has been given the visual confidence of a culture magazine—dark, spacious, and punctuated by moments of vivid pink and clean white.

The system prioritizes readability in low-light conditions while using color and scale to guide users toward conversion points. Pricing, app downloads, and feature explanations share a consistent card-based architecture that floats above the canvas with subtle borders rather than heavy shadows. Every interactive element is immediately identifiable: white pills for primary actions, dark pills for secondary choices, and pink badges for social proof and urgency.

## Colors

The palette is intentionally narrow, deriving its energy from a single warm accent against a deep neutral ground. This constraint keeps the interface feeling focused and premium while allowing marketing imagery to supply chromatic variety.

| token | value | use |
|---|---|---|
| canvas | #0a0a0a | Page background, deepest layer behind all content |
| surface | #171717 | Card backgrounds, elevated panels, pricing tiers |
| surface-elevated | #1f1f1f | Featured cards, hover states, active selections |
| ink | #ffffff | Primary text, headlines, primary button fill |
| ink-muted | #a3a3a3 | Secondary descriptions, feature list text, metadata |
| ink-dim | #737373 | Tertiary labels, disabled hints, fine print |
| action | #ec4899 | Featured borders, badges, "MOST POPULAR" labels, accent strokes |
| action-subtle | #be185d | Darker pink for pressed states or subtle action backgrounds |
| success | #22c55e | Checkmark icons, positive indicators, included features |
| border | #262626 | Default card borders, dividers, structural lines |
| border-subtle | #404040 | Input borders, inactive toggles, hairline separators |

The color logic follows a clear hierarchy: canvas recedes, surface elevates, and ink commands attention. The action pink is reserved for moments of conversion emphasis—never used as a background wash, only as a signal. Success green appears exclusively in functional contexts like feature verification. Warm gradients in hero sections are photographic or generated assets, not CSS gradients, and should be treated as imagery rather than interface color.

## Typography

Two families from Pangram Pangram Foundry, designed by Mathieu Desjardins, define the typographic voice. Pp Editorial New supplies the editorial personality; Pp Neue Montreal handles utilitarian clarity. Verify licensing for these families before production use.

| token | family | size | weight | leading | tracking | use |
|---|---|---:|---:|---:|---:|---|
| hero-display | Pp Editorial New | 5rem | 300 | 1 | -0.02em | Homepage hero headlines, major value propositions |
| section-display | Pp Editorial New | 2.5rem | 300 | 1.1 | -0.01em | Section titles, pricing plan names, card headers |
| body-large | Pp Neue Montreal | 1.25rem | 400 | 1.5 | 0 | Lead paragraphs, app store descriptions |
| body | Pp Neue Montreal | 1rem | 400 | 1.5 | 0 | Feature lists, body copy, general content |
| body-medium | Pp Neue Montreal | 1rem | 500 | 1.5 | 0 | Button labels, emphasized body text |
| label | Pp Neue Montreal | 0.875rem | 500 | 1.25 | 0.02em | Badges, tags, category labels |
| caption | Pp Neue Montreal | 0.75rem | 500 | 1.25 | 0.01em | Fine print, review counts, legal hints |

The editorial serif is always light weight, never heavier, preserving its airy elegance even at display scale. The sans-serif spans 400 and 500 weights only—no bold is used in the visible system, maintaining a calm, confident tone. Negative tracking on display type tightens word shapes without collapsing them. Body sizes use neutral tracking and generous leading for comfortable reading in dark mode.

## Layout

The layout system is centered and spacious, with content constrained to a readable maximum width and generous vertical breathing room between sections.

The page uses a single centered column for hero messaging, expanding to a three-column grid for pricing cards. Cards are equal-width with consistent internal padding, separated by gutters that match the card padding value. The overall rhythm is: full-bleed atmospheric hero, then contained structured content, then another full-bleed transition if needed.

Section spacing uses 4rem between major content blocks, with 2rem internal padding for cards. The pricing grid shows a clear hierarchy through elevation: the featured Pro Plan card receives a pink border and slightly elevated surface color, while flanking cards sit at the default surface level. Toggle controls for monthly/yearly billing sit centered above the grid, reinforcing the decision point before users reach the cards.

App store rating cards in the hero use a two-column layout with identical internal structure: platform icon, category label, star rating with numeric score, review count, and download button. These cards float above the gradient background with subtle borders rather than solid backgrounds, letting the atmospheric color show through.

## Visual language

The visual identity balances technical credibility with creative warmth. Dark surfaces dominate, but they never feel heavy because of the generous whitespace, light typography weights, and strategic use of atmospheric gradient imagery.

Gradients appear as full-bleed background photography—warm amber, rose, and gold tones that evoke stage lighting or sunset hours. These are not interface elements but environmental textures that position the product in a world of music and performance. Against these, white text and clean cards maintain perfect legibility.

Borders are thin and dark, functioning as subtle separators rather than outlines. The only vivid border is the pink stroke on the featured pricing tier, which draws the eye without shouting. Rounded corners are consistent: cards use 1rem, buttons are fully pill-shaped, and small badges use tighter rounding. There are no sharp corners in the component set.

Iconography is minimal and functional: checkmarks for included features, crosses for excluded ones, platform logos for app stores. These icons inherit color from their context—success green for checks, muted ink for crosses, white for platform marks.

## Components

### Pricing Card

The pricing card is the system's most complex visible component, appearing in three variants.

**Anatomy:** Card container, plan name, description, price block with currency and interval, primary action button, and feature list with icon-leading items.

**Surface and text color:** Default cards use surface background (#171717) with border (#262626). The featured variant uses surface-elevated (#1f1f1f) with action pink border (#ec4899). All text starts with ink (#ffffff) for plan names and prices, shifting to ink-muted (#a3a3a3) for descriptions and feature lists.

**Typography:** Plan names use section-display token. Prices use body-large with the currency symbol and interval in caption. Feature items use body token.

**Shape and border:** 1rem radius, 1px solid border. Featured variant keeps identical geometry, only changing border color.

**Spacing:** 2rem internal padding. Price block sits with 1.5rem vertical space from description and 2rem above the button. Feature list begins after 2rem below the button, with 0.75rem between items.

**Composition:** Three cards in a row, equal width, with the featured card centered. On the featured card, a "MOST POPULAR" badge floats in the top-right corner, using action background and label typography.

**Variants:** Free Plan uses a dark secondary button (surface-elevated background, ink text). Pro Plan uses a white primary button (ink background, canvas text). Premier Plan uses a dark secondary button matching Free Plan.

### App Store Rating Card

**Anatomy:** Card container, platform icon and category label, numeric rating with star icon, review count, and download button.

**Surface and text color:** Transparent or near-transparent background with subtle border, allowing the hero gradient to show through. All text is ink (#ffffff).

**Typography:** Category label uses body-medium. Rating number uses section-display scale. Review count uses caption.

**Shape and border:** 1rem radius, 1px border-subtle outline.

**Spacing:** 1.5rem internal padding. Rating number has 1rem above and 0.25rem below. Download button sits at the bottom with standard button padding.

**Composition:** Two cards side by side, equal width, with identical internal structure. Platform icons (Apple, Google Play) lead the category label.

### Feature List Item

**Anatomy:** Icon indicator and text label.

**Surface and text color:** No independent background. Text uses ink-muted. Included features use success (#22c55e) checkmark. Excluded features use ink-dim cross mark.

**Typography:** Body token.

**Spacing:** 0.75rem between items, icon sized to match text line height with 0.5rem right margin.

### Toggle Control

**Anatomy:** Radio-style selector with two options and a save indicator.

**Surface and text color:** Selected option shows checkmark icon in ink. Unselected option shows empty circle in border-subtle. "SAVE 20%" label uses action background with label typography.

**Typography:** Body-medium for option text. Label token for the save badge.

**Shape and border:** Circular indicators, 1rem size. Badge uses standard badge rounding.

**Composition:** Horizontally arranged, centered above pricing grid, with 1rem gap between options.

### Primary Button

**Anatomy:** Pill-shaped container with centered text and optional leading icon.

**Surface and text color:** Ink (#ffffff) background, canvas (#0a0a0a) text.

**Typography:** Body-medium.

**Shape and border:** Full pill (9999px radius). No border.

**Spacing:** 1rem vertical padding, 2rem horizontal minimum.

### Secondary Button

**Anatomy:** Pill-shaped container with centered text.

**Surface and text color:** Surface-elevated (#1f1f1f) background, ink (#ffffff) text.

**Typography:** Body-medium.

**Shape and border:** Full pill. No border.

## Responsive behavior

The three-column pricing grid should collapse to a single stacked column on narrow viewports, with the featured Pro Plan card remaining visually distinct through its pink border. Card padding can reduce from 2rem to 1.5rem to preserve proportional spacing.

Hero display type should scale down to section-display size on smaller screens to prevent excessive line breaks. The two app store rating cards should stack vertically when horizontal space is constrained.

Toggle controls should remain horizontally arranged but may wrap if localized text expands. The save badge should stay adjacent to its associated option.

Atmospheric gradient backgrounds should remain full-bleed and centered, with content maintaining safe margins. No horizontal scrolling should occur at any viewport width.

## Practical implementation guidance

### Preserve
- The dark canvas as the default page background; never introduce a light mode without rethinking the entire color hierarchy.
- The editorial serif for headlines only; using it for body copy would degrade readability and dilute its impact.
- The pink accent as a scarce resource; overuse will eliminate its power to signal importance.
- Pill-shaped buttons as the exclusive button style; sharp-cornered buttons would break the system's calm rhythm.
- Generous internal card padding; the spaciousness is part of the premium feel.

### Avoid
- Adding drop shadows to cards; the system uses borders and surface elevation instead.
- Using pure black (#000000) for backgrounds; the slightly lifted canvas (#0a0a0a) prevents the harshness of absolute black.
- Introducing additional accent colors beyond pink and success green; the palette's restraint is intentional.
- Making the editorial serif heavier than 300; the light weight is essential to its character.
- Using gradients as CSS backgrounds for UI elements; reserve them for photographic or generated imagery.

### Recommended Build Order
1. Establish the canvas, surface, and ink color tokens with dark mode as the only mode.
2. Implement the typography scale with both families loaded, verifying that Editorial New Light renders crisply at display sizes.
3. Build the pricing card component with all three variants, ensuring the featured border color is exact.
4. Create the pill button system with primary and secondary states.
5. Add the toggle control and badge components.
6. Implement the hero section with atmospheric background handling and app store cards.
7. Compose the pricing page layout with grid behavior and responsive stacking.

### Accessibility
- Maintain a minimum contrast ratio of 4.5:1 for all body text; the ink-on-canvas pairing exceeds 15:1.
- Ensure the pink action color on white or dark backgrounds meets 3:1 for large text and UI components.
- Provide visible focus states for all interactive elements; consider a 2px outline in action pink offset from the element edge.
- Do not rely on color alone for feature inclusion; the checkmark and cross icons provide necessary non-color indicators.
- Respect reduced-motion preferences for any gradient or atmospheric background animations.

## Scope note

This guide covers the Suno homepage and pricing surface as visible in the supplied images. Mobile layouts, navigation menus, footer content, audio player interfaces, account dashboards, and motion or sound design are not represented. Measurements are practical adaptation targets. Verify licensing for Pp Editorial New and Pp Neue Montreal before production use.

