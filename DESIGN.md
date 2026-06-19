---
name: Kantaphon Aochampa — Portfolio
description: A detective-noir portfolio for a data-driven marketer — evidence laid out on black.
colors:
  bowtie-red: "#e11d2e"
  detective-blue: "#3b82f6"
  ink: "#000000"
  surface: "#0a0a0a"
  card: "#111111"
  border: "#1f1f1f"
  text: "#ffffff"
  muted: "#a1a1aa"
typography:
  display:
    fontFamily: "Poppins, sans-serif"
    fontSize: "clamp(2rem, 4.5vw, 3.8rem)"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Poppins, sans-serif"
    fontSize: "clamp(1.8rem, 4vw, 2.8rem)"
    fontWeight: 700
    lineHeight: 1.2
  title:
    fontFamily: "Poppins, sans-serif"
    fontSize: "clamp(1rem, 2vw, 1.4rem)"
    fontWeight: 600
    lineHeight: 1.3
  body:
    fontFamily: "Poppins, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Poppins, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 600
    letterSpacing: "0.2em"
rounded:
  sm: "8px"
  md: "12px"
  lg: "16px"
  pill: "999px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "32px"
  section: "96px"
components:
  button-primary:
    backgroundColor: "{colors.bowtie-red}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    padding: "0.85rem 2rem"
  button-outline:
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    padding: "0.85rem 2rem"
  card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.lg}"
    padding: "1.5rem"
  tag:
    backgroundColor: "{colors.card}"
    textColor: "{colors.detective-blue}"
    rounded: "{rounded.pill}"
---

# Design System: Kantaphon Aochampa — Portfolio

## 1. Overview

**Creative North Star: "The Case File"**

This is a detective's case file rendered for the web: evidence laid out on a black desk, one exhibit at a time, under a focused light. The owner is a data-driven marketer whose edge is *noticing what others miss* — so the interface behaves like an investigator presenting findings, not a brochure shouting features. Pure black (#000000) is the desk; content arrives as discrete, well-spaced exhibits — work experience, competitions, certificates, case studies — each able to stand on its own. Two signal colors cut through the dark: **Bowtie Red** for the decisive marks and **Detective Blue** for the clues and quiet labels.

The personality is **investigative, observant, and refined** — sharp without being loud. Authority comes from restraint and craft, not decoration: generous negative space, calm motion, and solid signal colors — never gradient text, which hurts legibility. The detective influence is *mood*, never costume — there are no cartoon props, no manga halftones, no kawaii. It should read as a sophisticated analyst's portfolio that happens to think like a detective.

This system explicitly rejects: the **interchangeable portfolio template** (hero + three identical cards + contact form that could belong to anyone); **cluttered, cramped density**; **stiff corporate formality**; and anything **childish or cartoonish**. If a visitor could guess the layout from the category alone, it has failed.

**Key Characteristics:**
- True-black canvas; content as spotlit "exhibits," never wall-to-wall fill
- Two-signal palette — red decides, blue informs — used sparingly on black
- Poppins throughout; weight and size carry hierarchy, not extra typefaces
- Flat at rest; a soft red glow is the only thing that "lifts" on interaction
- Calm, intentional motion — feedback, not choreography

## 2. Colors

A near-monochrome black field punctuated by exactly two saturated signals. Restraint is the strategy: the dark does the talking, the colors point.

### Primary
- **Bowtie Red** (#e11d2e): The decisive accent — primary buttons, the active timeline dot, hover glows, focus marks, key borders. It marks *the thing that matters* on a given screen. High energy; used in small doses against black so it always reads as a signal, never wallpaper.

### Secondary
- **Detective Blue** (#3b82f6): The "clue" color — section labels, tags, secondary highlights, the cooler half of the signature gradient. Calmer than the red; it informs and organizes rather than commands.

### Neutral
- **Ink** (#000000): The desk. The body background and the base every exhibit sits on.
- **Surface** (#0a0a0a): Faintly raised zones — alternate section bands, input fields.
- **Card** (#111111): Exhibit surfaces — project, certificate, and skill cards.
- **Border** (#1f1f1f): Hairline 1px dividers and card edges; structure without noise.
- **Text** (#ffffff): Primary copy and headings on black.
- **Muted** (#a1a1aa): Secondary copy, captions, metadata. **Verify ≥4.5:1** — on #000 it passes; over background images it can fail, so darken the photo or lighten the text there.

### Named Rules
**The Two-Signal Rule.** Only two chromatic colors exist: Bowtie Red and Detective Blue. Red decides, blue informs. Introducing a third accent (green, amber, purple) breaks the investigation; if something needs emphasis, use one of the two, weight, or size — never a new hue.

**The Spotlight Rule.** Color is a signal on black, capped at roughly ≤10% of any screen. Its rarity is the point. The moment red or blue fills a large surface, it stops meaning "look here."

## 3. Typography

**Display / Body / Label Font:** Poppins (with sans-serif fallback), loaded at weights 300 / 400 / 600 / 700.

**Character:** One geometric sans, full stop. Hierarchy is built from weight and scale, not from a second typeface — disciplined and modern, which keeps the page calm enough for the color signals to carry meaning. (Per the brand: no mismatched second sans; one family in multiple weights.)

### Hierarchy
- **Display** (700, `clamp(2rem, 4.6vw, 4rem)`, line-height 1.12): Hero headline ("Hi, I'm …"). The name is **solid Bowtie Red** on white "Hi, I'm" — no gradient (see Named Rules).
- **Headline** (700, `clamp(1.8rem, 4vw, 2.8rem)`, line-height 1.2): Section titles ("Portfolio", "My Certificates"). Solid white.
- **Title** (600, `clamp(1rem, 2vw, 1.4rem)`, line-height 1.3): Role subtitles and card headings.
- **Body** (400, 1rem, line-height 1.6): Paragraphs and descriptions. Cap measure at 65–75ch; white for primary, Muted for secondary.
- **Label** (600, 0.8rem, letter-spacing 0.2em, uppercase, Detective Blue): The section eyebrow ("MY WORK", "WHAT I'VE EARNED").

### Named Rules
**The No-Gradient-Text Rule.** Text is never painted with a gradient — it reads as decoration and hurts legibility. The nav wordmark and the hero name are **solid Bowtie Red (#e11d2e)**. Everywhere else, emphasis is weight, size, or a single solid signal color. Gradients are for button *backgrounds* and the photo ring only — never letters.

**The One-Family Rule.** Poppins only. Reach for another weight before another typeface.

## 4. Elevation

Flat by default. Exhibits rest directly on black with a 1px #1f1f1f hairline; there is no ambient drop-shadow vocabulary at rest. Depth is a *response to interaction*, not a permanent property — and when it appears, it glows red rather than casting gray. This is what makes the page feel like lit evidence instead of a stack of Material cards.

### Shadow Vocabulary
- **Red Glow — rest** (`box-shadow: 0 4px 24px rgba(225,29,46,0.35)`): Ambient lift under the primary button so the one decisive control reads as live.
- **Red Glow — hover** (`box-shadow: 0 8px 32px rgba(225,29,46,0.5)` / cards `0 16px 48px rgba(225,29,46,0.15)`): Interaction feedback; the exhibit leans toward the light.
- **Structural lift** (`box-shadow: 0 12px 32px rgba(0,0,0,0.25)`): Neutral depth for raised timeline cards, paired with the red glow on the current role.

### Named Rules
**The Flat-Until-Touched Rule.** Surfaces are flat at rest; shadow is earned by state (hover / focus / "current"). A card with a permanent drop shadow at rest is wrong — if it looks like a 2014 app, the gray shadow is doing work the red glow should do on hover.

## 5. Components

The component voice is **refined and restrained** — clean edges, quiet defaults, one confident move on interaction.

### Buttons
- **Shape:** Gently rounded, 8px radius (`{rounded.sm}`); padding `0.85rem 2rem`, weight 600, size 0.95rem.
- **Primary:** The red→blue signature gradient (`linear-gradient(135deg, #e11d2e, #3b82f6)`), white text, resting red glow. Reserved for the single most important action in a view (View My Work, Send Message).
- **Outline:** Transparent with a 1px border; on hover the border and text shift to Bowtie Red. The everyday/secondary action.
- **Hover / Focus:** `translateY(-2px)` lift plus glow, ~0.2s. Add a visible `:focus-visible` ring in Bowtie Red for keyboard users.

### Cards / Containers
- **Corner Style:** 16px (`{rounded.lg}`) for project, certificate, and timeline cards; 12px (`{rounded.md}`) for compact skill cards.
- **Background:** Card #111111 on the black field.
- **Border:** 1px #1f1f1f hairline at rest.
- **Shadow Strategy:** Flat at rest; red glow on hover (see Elevation).
- **Internal Padding:** 1.5rem.

### Chips / Tags
- **Style:** Pill (999px), Card background, Detective Blue text, 1px border. Used for competition skill tags.
- **Badges:** "Current" badge and company badges use a red-tinted fill (`rgba(225,29,46,0.15)`) — small, quiet markers, not loud pills.

### Inputs / Fields
- **Style:** Surface (#0a0a0a) fill, 1px #1f1f1f border, 8px radius.
- **Focus:** Border shifts to Bowtie Red with a soft red ring; never remove the focus indicator.

### Navigation
- **Style:** Fixed top bar on near-opaque black (`rgba(0,0,0,0.92)`). The wordmark carries the signature gradient. Links are Muted, shifting to white/red on hover/active. Provide an accessible mobile menu.

### Signature Component — The Exhibit Timeline
The horizontal work-experience timeline with a pulsing red "current" dot and red-glow hover is the system's signature surface. A "View My Work" button opens a focused case-study modal (title, date, image, findings, link) — evidence on demand. Keep it sparse; one exhibit reads at a time.

## 6. Do's and Don'ts

### Do:
- **Do** keep the canvas pure black (#000000) and let content arrive as spaced exhibits with room to breathe.
- **Do** treat Bowtie Red (#e11d2e) and Detective Blue (#3b82f6) as scarce signals — red decides, blue informs — on ≤10% of any screen.
- **Do** build hierarchy with Poppins weight and size; reach for a heavier weight before any second typeface.
- **Do** keep surfaces flat at rest and let the red glow be the reward for hover/focus.
- **Do** verify body and muted text hit ≥4.5:1, especially over background images — darken the photo or lighten the text until it passes.
- **Do** give every animation a `prefers-reduced-motion` fallback and every control a visible Bowtie-Red focus ring.

### Don't:
- **Don't** ship the **interchangeable portfolio template** — hero + three identical cards + contact form. Vary card sizes and rhythm so the layout couldn't belong to anyone else.
- **Don't** let it get **cluttered or cramped**; negative space is the investigator's composure. Density is the enemy.
- **Don't** drift **corporate, stiff, or formal** — confident and calm, never agency boilerplate.
- **Don't** go **childish or cartoonish**: no manga halftones, kawaii faces, cartoon magnifiers, or comic props. The detective influence is mood (palette, framing), never costume.
- **Don't** use gradient text anywhere — it's hard to read. The wordmark and hero name are solid Bowtie Red; gradients are for button *backgrounds* and the photo ring only, never letters.
- **Don't** introduce a third accent color or a permanent gray drop shadow. Two signals, flat-until-touched.
- **Don't** let the blue eyebrow label harden into scaffolding on literally every block, and never add numbered `01 / 02` section markers — vary the cadence so it reads as voice, not AI grammar.
