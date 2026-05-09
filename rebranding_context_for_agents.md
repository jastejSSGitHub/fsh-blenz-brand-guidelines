# BLENZ 2.0 — Agent Context Document
## For use in Cursor, Antigravity, or any AI agent working on these files

---

## WHO IS WORKING ON THIS

**Designer:** Jastej Singh Sehra (goes by Jas)
**Role on this project:** Subcontractor to Sandeep Alexander (CEO, FSH Design)
**Jas's agency:** LoopSuit AI (loopsuitai.com) — AI automation + design agency
**Jas's portfolio:** PixelPilot (pixelpilot.design)

**Client chain:**
- End client: **Blenz Coffee** (blenz.com)
- Intermediary: **Sandeep Alexander / FSH Design** — he found the Blenz client and manages the relationship
- Executing designer: **Jas** — doing the actual creative and HTML delivery

**Deal structure:**
- $1,000 CAD flat for the first full creative direction
- One round of revisions included in that price
- Scope: colour system, logo exploration, typography, brand voice, brand expression/merch starter
- Additional directions (extra logo routes, extended merch, mockups across collateral) are add-ons

---

## WHAT THESE FILES ARE

Two HTML files. Both are the same brand guidelines document — one full version of Blenz 2.0 brand guidelines. The only difference between them is the logo treatment (dot vs no-dot).

### File 1: `blenz-2.0-brand-guidelines.html`
The **dot version**. The logo wordmark features a small rust-coloured dot before the "b" — `·blenz` — as a design charm/diacritical accent.

### File 2: `blenz-2.0-nodot.html`
The **no-dot version**. Identical in every way except the dot is removed everywhere — the wordmark is just `blenz`, and the single-letter app icon is just `b`.

**Both files are self-contained single-file HTML** — no external assets, no dependencies (except Google Fonts which load from CDN). They are ready to open in a browser or load in Cursor for editing.

---

## THE CLIENT: BLENZ COFFEE

**What Blenz is:**
- Canadian coffee chain, founded 1992 in Vancouver, BC
- ~58 locations currently (mostly BC), expanding into GTA (Milton opened Jan 2025)
- Target: 100+ Canadian locations + Asia/Middle East expansion by 2027
- Tagline: "coffee is the excuse. Human connection is the point."
- Hero products: handcrafted lattes with latte art, single-origin Colombian chocolate, organic whole-leaf teas, butterfly pea flower Blue Latte (underused Instagrammable asset), matcha
- Website: blenz.com

**Current brand (before 2.0):**
- Rose-windmill icon + `BLENZ COFFEE` in bold uppercase Frutiger
- Dominant yellow (Pantone 1215, #FBD672 "Honey") — described as muted/millennial
- Secondary palette: matcha green, ice blue, pea flower purple, crema orange, fog grey
- Visual language: handcrafted, print-making, embossing — dated ~2017 artisanal aesthetic
- Mascot: "Cuppy" — watercolor coffee cup character (underused)

---

## THE BRIEF: BLENZ 2.0

This is a **brand evolution**, not a rebrand from scratch.

### What Sandeep told Jas (the actual brief):
1. **Blenz is not just coffee anymore** — they are branching into beverages broadly (matcha, blue lattes, protein drinks, fruit drinks, etc.). The new brand system must flex across all of these, not just coffee.
2. **Colors need to pop** — the old yellow is muted and millennial. New system should feel inviting, bright, vibrant — appropriate for a beverage brand.
3. **Appeal to Gen Z** — the primary new audience. Younger, digital-first, social media-forward, aesthetic-driven.
4. **Previous branding looks too millennial** — Sandeep's word: it's not "popping." Too safe, too beige, too corporate-casual.
5. **Logo re-look** — explore lowercase "b," softer/more contemporary forms. Current uppercase lockup is too formal.
6. **Typography: trend-forward, youthful, digital-first** — brand voice more casual and engaging.
7. **Merch & brand expression** — lifestyle brand feel, shareable/desirable in-store moments.
8. **Sandeep liked Jas's LoopSuit AI brand guidelines** (loop-suit-branding.vercel.app) — specifically liked the depth and the sections used. He wants similar depth and section structure applied to Blenz, but with completely different visual direction (LoopSuit is dark/agency; Blenz is bright/beverage/Gen Z).

### Reference brands Sandeep gave:
- **Dutch Bros Coffee** — Royal blue + yellow + red, Peignot font, sticker drops, streetwear collabs, run-club energy, Gen Z following
- **7 Brew Coffee** — Dominant turquoise/teal, energy-forward service culture, sticker-driven
- **Scooter's Coffee** — Red/cream, circular badge logo, smiley sticker ritual, heritage-coded

### Additional reference brands (Jas's research added these):
- **Blank Street Coffee** — Fern green as single ownable color on everything (cup, storefront, straws). Hit $500M valuation 2024. The cup became a status object/social media prop. Wolff Olins rebrand: palette of greens named after times of day, custom typography, Only NY streetwear collab. Key insight applied to Blenz: **Blenz Yellow should become what Blank Street Green is for them.**

### Strategic shift:
> This is a beverage brand rebrand where coffee is the heritage anchor, not the sole identity.
> Blenz 2.0 is beverage-first, coffee-heritage.

---

## DESIGN DECISIONS MADE

### Color System
| Name | HEX | Role |
|------|-----|------|
| Blenz Yellow | #FFC94B | Primary / Hero |
| Pop Yellow | #FFD60A | Accent |
| Deep Navy | #003F88 | Primary type / anchor |
| Rusty Orange | #C2410C | Secondary warm |
| Icy Blue | #B8DCEC | Secondary cool |
| Butter | #FFEDB5 | Support soft |
| Cream | #FFF8E7 | Neutral background |
| Espresso | #1A0F08 | Neutral dark anchor |
| Paper | #FBF7EE | Page background |

CSS variables are defined in `:root` at the top of both HTML files. All colors use these variables — never hardcoded.

### Typography
- **Display / Headlines:** Fraunces (Google Font) — variable serif, bold optical sizes, confident italic. Weight 600–700. Always italic for headlines.
- **Body / Interface:** Geist (Google Font) — neo-grotesque, clean, modern. Weight 400–600.
- **Accent / Labels / Eyebrows:** Geist Mono (Google Font) — monospace. Uppercase, letter-spacing 0.15em.

CSS variables: `--font-display`, `--font-body`, `--font-mono`

### Logo Direction
- Lowercase wordmark: `blenz` in bold italic Fraunces
- **Dot version:** Small rust dot (`·`) preceding the wordmark as a design charm — `·blenz`
- **No-dot version:** Clean wordmark only — `blenz`
- Single-letter app icon / favicon: `b` (or `b.` in dot version)
- Logo has 6 color variants (navy/yellow, yellow/navy, rust/cream, ice/navy, cream/navy, espresso/yellow)
- The rust `®` superscript appears in the primary lockup stage

### Brand Voice
- Warm, specific, brief, local
- "This not that": present-tense, short sentences, no corporate filler
- Master tagline: **"Smile after every sip."** (already exists in Blenz's current brand — preserved as heritage)
- Voice rules: Real ingredients, real places, no passive voice, no wellness-speak

### Merch (scope-limited — only these two items)
1. **The Everyday Tote** — 12oz natural cotton canvas, 2-colour screen print (navy + rust on cream), 38×42cm, heritage badge inside seam
2. **The Sticker Card** — 85×54mm credit card format, 350gsm uncoated navy, yellow foil block on logo, 7 sticker spots, monthly sticker drops = collect 7 → earn 8th drink free

### Cuppy 2.0
- The existing watercolor mascot "Cuppy" is retained but modernized to a clean flat vector style
- Rules: Always Blenz Yellow with rust accents, sidekick not hero, works best at sticker/badge scale, always charming never sarcastic

---

## HTML DOCUMENT STRUCTURE

Both files have **14 sections** in this order:

| # | ID | Title | Background |
|---|-----|-------|------------|
| 00 | `#cover` | Cover / Hero | Yellow |
| 01 | `#story` | The Shift | Paper |
| 02 | `#personality` | Personality | Ice |
| 03 | `#logo` | Logo | Cream |
| 04 | `#logo-usage` | Logo Usage | Paper |
| 05 | `#color` | Colour | Cream |
| 06 | `#typography` | Typography | Paper |
| 07 | `#graphic` | Graphic System | Navy |
| 08 | `#photography` | Photography | Cream |
| 09 | `#cuppy` | Cuppy 2.0 | Yellow |
| 10 | `#voice` | Voice | Paper |
| 11 | `#applications` | Applications | Cream |
| 12 | `#merch` | Merch | Yellow |
| 13 | `#digital` | Digital | Ice |
| 14 | `#motion` | Motion | Paper |

Plus a `<footer>` at the bottom (no section ID, not in nav).

Sections are identified by `data-title` attribute — the JS reads this to build navigation automatically. **Do not remove `data-title` from any section.**

---

## NAVIGATION BEHAVIOR (DO NOT BREAK)

### Desktop (≥1280px wide)
- **Sticky left-side TOC** (`.sidetoc`) — fixed, vertically centered on left edge
- Each TOC item is a dash line that expands when hovered or active
- Section labels on the left **only appear while the user is scrolling** — they auto-hide 1.5 seconds after scroll stops
- This is controlled by the `.is-scrolling` class toggled on `.sidetoc` via a scroll event + setTimeout
- Active section is tracked via `IntersectionObserver` and highlighted with a yellow dash

### Mobile (≤900px wide)
- **Sticky top nav** showing current section name
- **Hamburger button** (pill-shaped dark button, top right) toggles the mobile menu
- **Mobile dropdown** is a glassmorphism panel — `backdrop-filter: blur(40px)`, soft white with transparency, rounded corners, subtle border, soft shadow
- Clicking any link in the mobile menu closes the menu and smooth-scrolls to the section
- Active section is highlighted in the mobile menu (dark background, cream text)

### Active section tracking
- Uses `IntersectionObserver` with `rootMargin: '-20% 0px -60% 0px'`
- The section with the best intersection ratio is set as active
- Active state updates: top nav label, mobile menu highlighted item, desktop TOC highlighted item

### Scroll behavior
- `scroll-behavior: smooth` on `html`
- `scroll-padding-top: 100px` to account for sticky nav

---

## IMAGE PLACEHOLDERS

The document has 7 image placeholders. These are styled placeholder divs with IDs for reference. They should be replaced with real images or AI-generated images later. Here is the full prompt list for each:

**[IMG-01]** — Section 08 Photography, large hero tile (grid-column span 8)
> Top-down macro photograph of a Blenz Blue Latte in a clear glass cup on a warm yellow surface (#FFC94B). Butterfly pea flower swirl visible in the milk, creating purple-blue gradients. Soft natural directional sunlight from the upper left, warm honey-gold tone. Editorial food magazine quality, shallow depth of field, slight grain. Steam rising. No text, no logo. 16:9 aspect ratio.

**[IMG-02]** — Section 08 Photography, rust-background tile (grid-column span 4)
> A young woman's hand holding a yellow takeaway coffee cup against a rust-orange wall (#C2410C). Slight motion blur as she walks, golden hour light, candid street photography style. The cup has a small navy blue script wordmark visible. Warm Vancouver afternoon vibes. Square 1:1.

**[IMG-03]** — Section 08 Photography, ice-background tile (grid-column span 4)
> A Vancouver café entrance scene at golden hour, a Gen Z customer in a beige jacket leaving with a yellow Blenz cup, glass door and brick exterior, warm light spilling out. Editorial documentary style, soft film grain, no logos visible up close. Vertical 4:5.

**[IMG-04]** — Section 08 Photography, butter-background tile (grid-column span 4)
> Flatlay of a matcha latte in a butter-yellow ceramic cup beside a fresh croissant on a cream linen napkin, a small navy stamp visible on the napkin corner. Soft directional window light from the right, slight shadow play, food magazine aesthetic. Vertical 4:5.

**[IMG-05]** — Section 08 Photography, espresso-background tile (grid-column span 4)
> Three friends in their early 20s laughing on a wooden bench in a Vancouver park at dusk, each holding a yellow Blenz takeaway cup. Candid, slightly out of focus, warm late-light, film stock feel. Backs partially turned, hands and cups in clear focus. Vertical 4:5.

**[IMG-06]** — Section 09 Cuppy 2.0, mascot illustration placeholder
> Modern flat vector illustration of a friendly yellow coffee cup mascot character on a white background. Simplified clean line work, two stick legs, two stick arms, a warm smile with two small dots for eyes. Body in Blenz Yellow (#FFC94B), accents and outlines in Rust orange (#C2410C). One small four-point star ✦ floating beside him in rust. Approachable, charming, contemporary — think Duolingo's Duo or MoonPay character style. Centred, no shadow, white background.

**[IMG-07]** — Section 11 Applications, hot cup product tile (grid-column span 7)
> Three yellow paper takeaway coffee cups stacked at slight angles on a cream surface, each cup wrapped with a navy blue italic serif "blenz" wordmark and a small rust-orange dot. Studio product photography, soft shadows, warm natural light. The brand mark is the hero. 16:10 aspect ratio.

**How to add images:**
Replace the `.photo-placeholder` div inside the relevant `.photo-tile` with an `<img>` tag. Example:
```html
<!-- Before -->
<div class="photo-tile photo-tile--01">
  <div class="photo-placeholder">
    <span class="photo-placeholder__id">[IMG-01]</span>
    ...
  </div>
</div>

<!-- After -->
<div class="photo-tile photo-tile--01">
  <img src="your-image.jpg" alt="Hero drink" style="width:100%;height:100%;object-fit:cover;" />
</div>
```

---

## DESIGN DECISIONS TO KEEP LOCKED

These were intentional decisions. Do not change without explicit instruction from Jas:

1. **Fraunces is always italic for display text** — do not set it to roman for headings
2. **Yellow is always the hero colour** — no section should make navy the dominant background unless it's an intentional dark section (graphic system, merch footer area)
3. **The "·" dot in the dot version is intentional** — it's a design charm, not a typo
4. **Lowercase `blenz` — never uppercase BLENZ** in any new content or components
5. **Geist Mono for all eyebrows/labels** — uppercase, letter-spacing 0.15em+
6. **Rust (#C2410C) is the accent** — not a primary color, not overused. It appears as: the dot, the ® mark, hover accents, number labels, sticker elements
7. **The scroll-fade behavior on desktop left TOC labels** — labels only show while scrolling, hide after 1.5s idle. This is intentional UX, not a bug
8. **Section backgrounds alternate** — the rhythm of yellow/paper/ice/cream/navy sections is intentional

---

## WHAT HAS BEEN APPROVED

- **Cover page** — cleaned and simplified (Sandeep reviewed, Jas approved)
- **Overall structure and sections** — Sandeep said he likes the depth and section approach (his exact words: "quite lengthy and deep, has a lot of depth to it")
- **Color palette** — approved direction
- **Typography** — Fraunces + Geist system approved
- **The two-file approach** (dot vs no-dot) — Jas is presenting both to Sandeep

---

## WHAT IS STILL PENDING / OPEN

- [ ] **Sandeep review** — first full draft has not been formally presented to Blenz client yet
- [ ] **Image placeholders** — IMG-01 through IMG-07 need real or AI-generated images
- [ ] **Cuppy 2.0 illustration** — IMG-06 needs an actual vector illustration created
- [ ] **Dot vs no-dot decision** — Jas will present both versions, Sandeep/Blenz decides
- [ ] **Logo section note** — the HTML uses Fraunces as a stand-in wordmark. In a real brand rollout, a custom-drawn or properly tuned typeface/vector logo would replace this. The HTML is a guidelines document, not the final logo file.
- [ ] **Round two revisions** — after Sandeep/client review, one round of revisions is included in the $1,000 scope
- [ ] **Potential add-ons** (out of current scope): additional logo routes, extended merch lookbook, applied mockups across all collateral, motion/animation specs in more detail

---

## TECHNICAL NOTES FOR AGENTS

### Stack
- Pure HTML/CSS/JS — no framework, no build step
- Google Fonts loaded from CDN (requires internet connection to render correctly)
- No localStorage, no sessionStorage, no cookies
- All state is in-memory JS only
- Single file — CSS is in `<style>` tag in `<head>`, JS is in `<script>` tag before `</body>`

### CSS Architecture
- CSS custom properties (variables) in `:root` — always use these, never hardcode colors
- BEM-ish naming convention: `.section__element--modifier`
- Mobile-first breakpoints: `max-width: 700px`, `max-width: 800px`, `max-width: 900px`, `min-width: 1280px`
- `clamp()` used throughout for fluid type and spacing — do not replace with fixed px values

### JS Architecture
- Sections array built from `querySelectorAll('section[data-title]')`
- Navigation built dynamically from this array — adding a new section with `id` and `data-title` will automatically add it to all navs
- `IntersectionObserver` handles active section tracking
- Scroll event + `setTimeout` handles the sidetoc label show/hide
- No external JS libraries

### Adding a new section
```html
<section id="new-section-id" data-title="Section Name" class="new-section">
  <div class="container">
    <div class="section-head">
      <div class="section-head__row">
        <span class="section-head__num">XX — Section Name</span>
        <span class="eyebrow">Subtitle · Keywords</span>
      </div>
      <h2 class="display-l">Heading <em>in italic.</em></h2>
    </div>
    <!-- content -->
  </div>
</section>
```
The `id` must be unique. The `data-title` is what appears in navigation. The section will automatically be added to both the desktop TOC and mobile dropdown.

### Editing the color palette
All colors are in `:root` at the very top of the `<style>` block. Change there and every instance updates automatically.

### Editing typography
Font imports are in the `<head>`. The three font variables are `--font-display`, `--font-body`, `--font-mono`. Change the Google Fonts import URL and the variable values to swap fonts globally.

---

## TONE NOTES FOR COPY AGENTS

If you are writing or editing copy inside these documents:

- **Blenz voice:** Warm, specific, brief, local. Short sentences. Strong verbs.
- **This:** "Made by hand. Made in BC. Made for you."
- **Not this:** "Elevating your daily ritual through premium experiences."
- **Headlines are always Fraunces italic** — they should feel like a confident whisper, not a shout
- **Eyebrows/labels** are monospace, uppercase, short — 3 words max
- **The tagline "Smile after every sip"** is sacred — do not rewrite it
- **Do not write "BLENZ" uppercase** anywhere in the document copy

---

## CONTACT / OWNERSHIP

- **Jas (designer):** jastej@pixelpilot.design — executing the work
- **Sandeep (client-side):** FSH Design — client relationship owner
- **End client:** Blenz Coffee — blenz.com

*This document was written by Claude (Anthropic) on behalf of Jas to provide full context for any AI agent or IDE session working on the Blenz 2.0 HTML brand guidelines files.*

---

*Last updated: May 2026 — v1.0 draft phase*