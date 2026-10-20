---
name: Anthony Nicotra · Fencing & Home Contracting
description: A calm, phone-first one-pager in paper and navy bands with one pressure-treated-pine accent, whose job is a pre-filled text for a free estimate.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  ink: "#13243a"
  body: "#2a3a4c"
  soft: "#4a5868"
  navy: "#1f4166"
  deep: "#13243a"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d6e6"
  pine: "#e8b65a"
  pine-2: "#f0c878"
  pine-ink: "#7c5210"
  focus: "#1f4166"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(21px, 5.6vw, 24px)"
    fontWeight: 400
    lineHeight: 1.2
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
rounded:
  card: "24px"
  field: "10px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  band: "64px"
  band-wide: "96px"
  stack-sm: "12px"
  stack-md: "20px"
  stack-lg: "32px"
components:
  button-primary:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.pine-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  eyebrow:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  arrow-circle:
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "44px"
  arrow-circle-hover:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
  step-number:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Anthony Nicotra · Fencing & Home Contracting

## Overview

**Creative North Star: "The Squared-Up Yard"**

This is Ellie's house calm band style applied to a hands-on fence builder: a page that earns trust through calm order rather than spectacle. Full-width bands alternate between off-white paper, navy, and deep navy, so the page reads like a fence line of even, level boards. One warm colour runs through it, the gold of fresh pressure-treated pine taken from Anthony's own fence photo (he has no logo or brand colours). Display type is Cal Sans, round and friendly; body copy is the system stack, set loose at 16/1.7 for phones inside Facebook's in-app browser.

Density is low and the rhythm is generous: one idea per band, a single column on phones, two columns only where the content pairs naturally (photo and quote, heading and form, name and big phone number). The one real job photo sits as a 4:5 card in the light band; it is never a full-bleed hero, never stock, never filtered beyond a bottom scrim for its caption. Motion is limited and named: the hero H1 bounces in letter by letter, below-the-fold blocks fade up 12px once, and a floating text circle appears after the hero. All three are absent under reduced motion, and the bounce and fade-up are absent without JS.

The previous living-pine-fence world (evergreen ground, system 900 display, fence canvas) has been discarded entirely; nothing of it carries forward.

**Key Characteristics:**
- Paper, navy, and deep-navy bands; deep navy carries a faint 135deg line texture.
- One warm accent (pine gold), used as a fill on light and as fill or text on dark.
- Cal Sans display at weight 400 for every heading, button, and row label; system body at 16/1.7.
- Soft geometry: 24px cards, 10px fields, pill buttons, chips, and circles.
- The phone number is always one tap away: header top right, close band, floating circle.
- House calm-style features kept by Ellie's choice: eyebrow pills, H1 bounce-in, floating text circle, band texture.

## Colors

A cool paper-and-navy ground with a single warm gold borrowed from the wood of his fence.

### Primary
- **Pressure-Treated Pine** (pine): The one accent. On light surfaces it is a fill only: the primary button, the step numbers, the floating circle, the eyebrow dot, the arrow circle on hover, and text selection. Text on it is always Ink. On navy and deep navy it may also be text, in the accent phrase that closes a dark-band heading, the big phone icon, and link hovers.
- **Sunlit Pine** (pine-2): Hover state of the primary button only.
- **Stained Pine** (pine-ink): Pine when it must be text or an icon on light, such as the header phone icon and the header phone number on hover.

### Neutral
- **Cool Paper** (paper): Page ground, header, light bands, and the inside of fields and unselected chips.
- **Card White** (card): Form card and the Facebook row; the only surfaces lifted off paper.
- **Harbor Navy** (navy): Hero, services, and close bands.
- **Night Navy** (deep): How-it-works band and footer, always with the line texture.
- **Ink** (ink): Headings on light, text on pine, selected chips. Same value as Night Navy; it is named separately because its role is text.
- **Slate Body** (body): Running text on light.
- **Soft Slate** (soft): Secondary text on light (ledes, placeholders, captions, the wordmark tagline).
- **Mist** (on-dark): Headings and labels on navy and deep navy.
- **Soft Mist** (on-dark-soft): Running text on navy and deep navy.
- **Focus Navy** (focus): Focus ring on light, and the hover outline or border on form controls. Same value as Harbor Navy, kept separate so it is never confused with the pine fill.
- **Brick** (error): Field error text and error border.
- **Hairline** (`rgba(19,36,58,.12)` on light; `rgba(255,255,255,.12)` between service rows on navy): dividers only.

### Named Rules
**The Pine Is Wood, Not Ink Rule.** Pine (#e8b65a) is 1.7:1 on paper, so it never sets text on light surfaces. On light it is a fill with Ink text on top (8.4:1); when gold has to be read on light, use Stained Pine (6.3:1).

**The Dark-Band Accent Rule.** The accent phrase at the end of a heading ("NJ & Philly.", "build.", "works.") appears on navy and deep-navy bands only. Headings on paper are entirely Ink.

**The One Warm Colour Rule.** Every other colour is a cool navy or neutral. A second warm hue, a gradient accent, or a tint of pine as a band ground breaks the system. (The Facebook glyph uses Facebook's own blue as a third-party mark, not a palette colour.)

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** System stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans at its single regular weight is round, upright, and friendly, a neighbour's voice rather than a hard sell; the system body keeps paragraphs native and fast inside in-app browsers. Cal Sans loads async from Google Fonts with `display=swap`.

### Hierarchy
- **Display** (400, clamp(42px, 12vw, 80px), 1.02, max 12ch): The hero H1 only, in white on the navy hero.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): Section H2s and the close band's name. Balanced wrapping.
- **Title** (400, clamp(21px, 5.6vw, 24px), 1.2): Display-face labels: service rows, the Facebook row, step titles (21px, 22px on desktop), the photo caption, and the work quote (clamp(19px, 5vw, 22px), 1.35).
- **Lead** (400, clamp(17px, 4.7vw, 20px), 1.5): The hero promise (max 32ch, 40ch on desktop) and section ledes (clamp(17px, 4.6vw, 19px), max 38ch).
- **Body** (400, 16px, 1.7): Running text and all inputs (16px so iOS never zooms). Small print is 15px (form note, quote attribution, errors).
- **Label** (500, 14px, 0.02em): The eyebrow pill only.
- **Button** (Cal Sans 400, 18px, 1): Buttons. Phone numbers also set in Cal Sans with tabular numerals: 17px header (20px desktop), clamp(30px, 9vw, 52px) in the close band.

### Named Rules
**The Single Weight Rule.** Cal Sans is only ever weight 400; hierarchy comes from size, not weight. Bold appears only in body text (the promise's name, at 600).

**The Numbers Stay Whole Rule.** Every phone number is `white-space: nowrap` with tabular numerals, so 267-207-8015 never breaks across lines.

## Layout

A single centred column (max 1160px) with a 20px gutter on phones and 40px from 760px. Bands are full width with 64px vertical padding, 96px from 760px; the hero is taller (64/72px, 96/112px on desktop). Inside a band, stacks step in a small set of gaps: 12px between buttons, 16-20px between heading parts, 24-32px between groups.

Breakpoints: 760px (wider gutter and bands, hero buttons side by side at min 240px, service rows in two columns with a 56px column gap) and 1024px (photo and quote side by side, form heading sticky beside the form card at 1:1.2, close band splits name and big number, steps in three columns). Small-phone tweaks at 399px and 379px shrink the header wordmark and phone number and finally drop the phone icon, so the header never wraps.

Band order is fixed by the house style: paper header, textured navy hero, paper work, navy services, textured deep-navy steps, paper form, navy close, textured deep-navy footer. No two adjacent bands share a ground.

### Named Rules
**The Alternating Boards Rule.** Bands alternate light and dark; the faint line texture lives only on the hero and deep-navy bands, at `repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`. It is a house feature, kept quiet enough to read as grain, not pattern.

## Elevation & Depth

Mostly flat. Bands are separated by colour, not shadow. Only three things lift: the work photo card, the Facebook row under it, and the floating text circle. Each uses a soft, low-opacity navy shadow with a negative spread so it reads as a gentle contact shadow rather than a frame. The form card sits on paper by tone alone (white on paper), with no shadow.

### Shadow Vocabulary
- **Photo lift** (`box-shadow: 0 18px 40px -18px rgba(19,36,58,.45)`): The 4:5 work photo card.
- **Row lift** (`box-shadow: 0 10px 28px -16px rgba(19,36,58,.35)`): The white Facebook row under the photo.
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): The floating text circle, which must separate from any band it passes over.

### Named Rules
**The Tone Before Shadow Rule.** New surfaces separate by ground colour first (white card on paper, paper field in white card). A shadow is added only to something that sits on top of content, like the photo or the floating circle; never a hard offset shadow.

## Shapes

Soft and round throughout. Cards and the photo are 24px; the Facebook row is a slightly tighter 20px; fields are 10px; buttons, chips, and the eyebrow are full pills; arrow buttons, step numbers, and the floating action are perfect circles. No borders on cards. Lines appear only as hairline dividers between service rows and as the 2px transparent border every button, field, and chip carries so hover and error borders don't shift layout.

## Components

### Buttons
Big, round, thumb-sized.
- **Shape:** Full pill (999px), 56px tall, 26px side padding, Cal Sans 18px, optional 20px inline SVG icon at a 10px gap.
- **Primary:** Pine fill, Ink text. Used for "Get a free estimate" and the form submit (full width in the form).
- **Ghost:** Transparent with a 2px Mist border at 70% and Mist text; dark bands only ("Text Anthony" in the hero).
- **Hover / Focus:** Hover only with a real pointer (`hover: hover`). Primary goes to Sunlit Pine; ghost goes to a solid white border and a 10% white wash; the form submit also gains the 3px Focus Navy outline. Press scales to 0.98. Focus is a 3px ring offset 3px, Focus Navy on light and pine on dark.

### Eyebrow pill (house choice)
A quiet label above the hero H1 and a few section headings ("Free estimates", "Any job, big or small", "Text me a photo"), never every heading. 14px/500 system text, 9px by 14px padding, pill, with a 7px pine dot. On light: Ink on a 6% ink wash; on dark: Mist on a 12% white wash. It is a `span`, not a heading and not a control: no arrow, no hover, no shadow, no full pine fill. Ellie chose these for the calm band style; Impeccable's craft floor flags eyebrows, and this is recorded as a deliberate house exception, not a general licence.

### Chips
- **Style:** Pill, 48px tall, 18px side padding (14px under 380px), paper ground, Ink 16px system text, 2px transparent border. They are visually styled radio labels for the job type.
- **State:** Selected turns solid Ink with white text. Hover and keyboard focus show the 3px Focus Navy outline offset 2px.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card white on paper (form); navy behind the photo while it loads.
- **Shadow Strategy:** See Elevation; the form has none, the photo and Facebook row have their own soft lift.
- **Border:** None.
- **Internal Padding:** clamp(20px, 5vw, 32px), 20px between fields.

### Inputs / Fields
- **Style:** Paper fill inside the white card, 2px transparent border, 10px radius, 52px minimum height (textarea 110px, vertical resize), 16px system text, navy caret. Labels are Cal Sans 17px Ink; "(optional)" is 14px Soft Slate.
- **Focus:** Border turns Focus Navy; no glow. Hover (pointer only) shows the same border.
- **Error:** Border and a 15px message turn Brick; the field is marked `aria-invalid` and focus moves to the first bad field. The error clears as soon as the visitor types.

### Navigation
- **Header:** Paper, 64px (76px desktop). Wordmark left (Cal Sans 21px, 24px desktop, over a 12px uppercase Soft Slate tagline); tap-to-call number top right in Cal Sans with a Stained Pine phone icon, turning Stained Pine on hover. No menu.
- **Footer:** Textured deep navy, Soft Mist text, Mist links at a 44px tap height that turn pine on hover; bottom padding clears the floating circle and the safe area.

### Work photo card (signature)
His own job photo at 4:5, 24px radius, max 520px, served from `fence.webp` (1080w) and `fence-640.webp` (640w) via srcset, lazy-loaded. A bottom 42% scrim of deep navy carries a white Cal Sans caption. Beside it (or above, on phones) his Facebook quote is set in Cal Sans as a pull quote with a small "From my Facebook post" attribution. Under the photo sits the Facebook row: a white 76px pill-cornered row with the Facebook glyph, a Cal Sans label, and an arrow circle.

### Service rows (signature)
Each service is a full-width link row on navy, 68px minimum, Cal Sans title, hairline-divided, two columns from 760px. Only the 44px arrow circle on the right changes: it fills pine with Ink arrow on hover or focus. The row itself never highlights, underlines, or shifts. Clicking a row pre-selects the matching job chip and pre-fills the note.

### Numbered steps
Three steps on textured deep navy, each a 48px pine circle numbered in Cal Sans 20px Ink, beside a Cal Sans Mist title and a Soft Mist line. One column on phones, three from 1024px.

### Quote form to SMS
The form composes a text message ("Hi Anthony, this is ...") and opens `sms:` with it. If no messages app opens within 900ms, a status block appears with an "Open in Messages" link, the number, and the composed message in a read-only textarea to copy. A Soft Slate note under the button tells the visitor to add a photo.

### Close band
Navy band with his name as the headline, a short "who" line, the area sentence (max 40ch), and the big tap-to-call number in Mist with a pine phone icon at 0.8em, turning pine on hover.

### Floating text circle (house choice)
A single 60px pine circle, Ink chat icon, bottom right inside the safe area, with Float lift. It slides up (`transform .35s cubic-bezier(.2,.8,.2,1)`) once the hero leaves view and slides away while the form is on screen; it is removed without IntersectionObserver or when `CONFIG.FLOAT` is false. Never a bottom bar.

### Motion
- **H1 bounce-in (house choice):** Each hero H1 letter enters from 50px right with opacity 0, over `1s cubic-bezier(.34,1.56,.64,1)`, 20ms apart. The heading waits hidden up to 700ms (`CONFIG.H1_FONT_WAIT`) for Cal Sans, measures each word's line in the plain heading, inserts breaks so the split letters wrap identically, and restores the plain markup when the last letter lands so kerning and selection return. JS only.
- **Fade-up:** Only blocks that start below the first screen rise 12px with opacity over 400ms ease-out, once. Everything is visible at rest.
- **Reduced motion / no JS:** No bounce, no fade-up, no float slide, no button transitions, no smooth scroll; the plain heading shows immediately.

## Do's and Don'ts

### Do:
- **Do** alternate paper, navy, and textured deep-navy bands, and keep the 135deg line texture at 3.5% white.
- **Do** keep pine as a fill on light with Ink text on it, and switch to Stained Pine (#7c5210) whenever gold must be read on light.
- **Do** put the accent phrase only at the end of a heading on a dark band.
- **Do** set every heading, button, row label, and phone number in Cal Sans 400, and body and inputs in the system stack at 16px.
- **Do** keep the phone number reachable in the header top right, the close band, and the floating circle, unbroken and tabular.
- **Do** keep tap targets at 44px or more (buttons 56px, chips 48px, fields 52px).
- **Do** scope hover to `(hover: hover)` and keep focus rings visible: 3px Focus Navy on light, pine on dark.
- **Do** make the arrow circle the only thing that changes on a link row's hover or focus.
- **Do** use only his own photos, at card size with their provenance recorded beside the file.
- **Do** gate every motion behind JS and reduced-motion, and wait for Cal Sans before splitting the H1.

### Don't:
- **Don't** set pine (#e8b65a) as text or a thin line on paper or white; it is 1.7:1.
- **Don't** add a second warm hue or use pine as a band ground.
- **Don't** put an eyebrow above every heading, give it hover, an arrow, a shadow, or a full pine fill, or mark it up as a heading.
- **Don't** use hard offset shadows or shadow the form card; separate by tone first.
- **Don't** turn the floating circle into a sticky bottom bar or show it over the form.
- **Don't** use stock work photos or run the work photo full-bleed as the hero.
- **Don't** bold Cal Sans or bring back a system 900 display face.
- **Don't** add new motion beyond the H1 bounce-in, the single 12px fade-up, and the float slide.
