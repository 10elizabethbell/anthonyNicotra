---
name: Anthony Nicotra — Fencing & Home Contracting
description: A phone-first one-pager built out of fresh pressure-treated pine on an evergreen backyard, whose job is a pre-filled text for a free estimate.
colors:
  ground: "#1d3a31"
  ground-deep: "#152c25"
  ground-up: "#24463b"
  cream: "#f5ead6"
  cream-deep: "#ead9bb"
  pine: "#e6bf80"
  pine-hi: "#f0d09a"
  pine-deep: "#b98a4e"
  pine-dark: "#7a5530"
  ink: "#1c2a24"
  ink-soft: "#4a5a50"
  on-ground: "#f4ecdc"
  on-ground-soft: "#c9d6c6"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.6rem, 12.4vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.35rem, 6vw, 1.7rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.4
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.45
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    letterSpacing: "0.01em"
  wordmark:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "0.04em"
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
rounded:
  inset: "5px"
  plank: "10px"
  frame: "12px"
  control: "14px"
  pill: "999px"
  disc: "50%"
spacing:
  gutter: "20px"
  gutter-wide: "32px"
  stack-sm: "12px"
  stack-md: "14px"
  stack-lg: "22px"
  column-gap: "56px"
  container: "1180px"
  control-height: "58px"
  hit-min: "44px"
components:
  button-primary:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "{spacing.control-height}"
  button-primary-hover:
    backgroundColor: "{colors.pine-hi}"
    textColor: "{colors.ink}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.on-ground}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "{spacing.control-height}"
  button-secondary-on-cream:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    padding: "20px 4px"
    height: "64px"
  go-disc:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.pine}"
    rounded: "{rounded.disc}"
    size: "44px"
  tag:
    backgroundColor: "{colors.cream-deep}"
    textColor: "{colors.ink}"
    typography: "{typography.small}"
    rounded: "{rounded.pill}"
    padding: "5px 10px"
  plank:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.plank}"
    padding: "20px 20px 20px 70px"
  plank-number:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.pine}"
    rounded: "{rounded.disc}"
    size: "36px"
  photo-frame:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.frame}"
    padding: "12px"
    width: "340px"
  sticky-bar:
    backgroundColor: "{colors.ground-deep}"
    padding: "10px 12px"
---

# Design System: Anthony Nicotra — Fencing & Home Contracting

## Overview

**Creative North Star: "The New Fence in the Backyard"**

The page is built out of the thing the owner is proudest of: a freshly built horizontal fence of pressure-treated pine, standing on new posts against a deep evergreen yard, with sunlit sawdust hanging in the air. Every surface is either the yard (evergreen ground), sawn lumber (cream sections, pine planks and frames), or the hardware between them (ink discs, grain-line seams). Nothing on the page is a generic web surface; the job photo is mounted in a pine frame, the steps are planks, and the hero and closer each end in a living fence the visitor can push.

Density is low and the reading order is short: one heavy headline, one line of pitch, two thumb-sized buttons. The system is phone-first and contractor-to-neighbor in tone: chunky uppercase type, big tap targets, warm wood against cool green. Motion is physical, not decorative: boards bow, spring and settle; planks lean away from a finger; seams ripple like grain. All of it stops dead under reduced motion and leaves a complete static page.

The confirmed rejection is a black ground. The darkest thing on the page is evergreen.

**Key Characteristics:**
- Two grounds only: evergreen (`ground`) and sawn cream (`cream`), joined by animated three-line grain seams.
- Pine (`pine`) is both the material and the primary action color; ink text always sits on it.
- One system font stack, made characterful by weight 900, uppercase and tight tracking.
- Procedural pine textures (generated at runtime) skin the fence, the photo frame and the step planks.
- One shared spring (stiffness 38, damping 6.5) drives every physical motion.
- Phone base layout, one structural breakpoint at 760px, a sticky Text/Call bar on phones.

## Colors

Warm sawn pine against cool evergreen, with ink-green standing in for black.

### Primary
- **Fresh Pressure-Treated Pine** (`pine`): the primary action fill (Text button), the base color under the procedural textures on the photo frame and step planks, the warm half of the hero headline, the `selection` highlight and the arrow/number glyph color inside ink discs.
- **Sunlit Pine** (`pine-hi`): hover state of the primary button, the focus ring (3px outline, 3px offset), and link color on evergreen (header call link, footer phone link).
- **Weathered Pine** (`pine-deep`): button borders on cream, the outer grain line of every seam.
- **Pine Heartwood** (`pine-dark`): the thin dark grain line in seams. Reserved for grain; never a fill.

### Neutral
- **Evergreen Yard** (`ground`): the page ground, hero, steps band and closer. The browser `theme-color`.
- **Deep Evergreen** (`ground-deep`): footer, sticky bar (at 94% opacity), the band behind the first seam.
- **Lifted Evergreen** (`ground-up`): top stop of the hero's vertical gradient into `ground`; the only gradient on a surface.
- **Sawn Cream** (`cream`): light sections (proof, services, area).
- **Sawdust Cream** (`cream-deep`): rule lines between service rows (2px) and the tag fill.
- **Ink Green** (`ink`): all text on cream and pine; the fill of the round number and arrow discs.
- **Moss Ink** (`ink-soft`): secondary text on cream (ledes, row descriptions, citation).
- **Evening Light** (`on-ground`): primary text on evergreen.
- **Sage** (`on-ground-soft`): secondary text on evergreen (pitch line, wordmark descriptor, footer).

### Named Rules
**The Evergreen Ground Rule.** No black ground, anywhere. Dark surfaces are `ground` or `ground-deep`; even the shadow behind the canvas fence boards is a deep green, not black.

**The Two Grounds Rule.** A section is either evergreen with `on-ground` text or cream with `ink` text. Never introduce a third surface color; transitions between the two happen only through a seam.

**The Ink-On-Pine Rule.** Anything filled with pine carries `ink` text, and anything filled with `ink` carries a pine glyph. Light text never sits on pine.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same stack

**Character:** The system stack is the owner's deliberate house style: it renders as the face the visitor's own phone uses, which reads as plain-spoken and local. Character comes from weight and case, not from a typeface: headings are black weight (900), uppercase, tracked tight (-0.02em) and set almost solid (0.95), like stenciled lumber stamps.

### Hierarchy
- **Display** (900, clamp(2.6rem, 12.4vw, 6rem), 0.95, uppercase): the hero headline and the closer's name. Hero headline breaks into one span per line, capped at 11ch.
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), 0.95, uppercase): section headings.
- **Title** (900, clamp(1.35rem, 6vw, 1.7rem) on service rows, 1.3rem on planks, 1 to 1.05, uppercase): row and step headings.
- **Lead** (400, clamp(17px, 4.6vw, 20px), 1.4): the hero pitch and closer line, in `on-ground-soft`, capped at 34ch.
- **Body** (400, 17px, 1.55): default text; ledes and area copy capped at 44 to 46ch.
- **Body small** (400, 16px, 1.45): row descriptions and plank text.
- **Label** (800, 17px, 0.01em): button text.
- **Wordmark** (900, 17px, 0.04em, uppercase): the owner's name in the top bar and footer; the descriptor under it is 13px in `on-ground-soft`.
- **Small** (700, 14px): tags and the photo caption.

The customer quote is a one-off step between lead and headline (600, clamp(19px, 5vw, 24px), 1.38) with curly quotation marks.

### Named Rules
**The One Family Rule.** One font stack for everything. Hierarchy is built with weight (900 / 800 / 700 / 600 / 400), case and size; never add a second family.

**The Uppercase Is For Headings Rule.** Uppercase is reserved for weight-900 headings and the wordmark. Body, buttons, tags and captions stay in sentence case.

## Layout

Single column on phones, built for one thumb. Content sits in a centered container (max 1180px) with a 20px gutter on phones and 32px from 760px up. Vertical rhythm is loose: sections pad 56 to 70px at the bottom on phones and up to 90px on desktop; stacks inside use 12px (button groups), 14px (plank list, area stack), 22 to 26px (headline to actions).

**Breakpoints.** The phone layout is the base. One structural breakpoint at **760px** (min-width in CSS, the matching max-width 759px in script) switches: button groups from stacked grid to wrapped row; short button labels to wide labels that include the phone number; the header call link appears; proof becomes a two-column grid (text left, frame right, 300 to 400px); services become a 0.9fr / 1.1fr split with 56px gap; planks become three columns with the number moved above the text; the sticky bar is removed. A second, minor step at 1100px only lifts the photo frame higher over the fence.

**The fence as layout.** The hero is at least 100svh: wordmark, headline, pitch, buttons, then a fence zone that takes the remaining height (min 150px; 34vh on desktop). The first light section's photo frame overlaps upward into the fence (-118px phone, -430px desktop, -600px at 1100px+). The closer repeats the fence at the bottom (min 170px).

### Named Rules
**The Thumb First Rule.** The primary action is visible without scrolling on a phone, and once the hero buttons scroll away a fixed bottom bar (Text, Call) slides up; it hides again when the closer's buttons are on screen. Every tap target is at least 44px; buttons are 58px tall.

**The Same Fence Twice Rule.** The page opens and closes on the living fence. Copy sits above the fence, never on top of the boards.

## Elevation & Depth

Depth is physical: lumber sits on the yard, cast by a soft sun from above. Shadows are lifts, not outlines; each has zero horizontal offset, a downward y-offset, a large blur and a negative spread so it pools under the object. Shadows on cream are evergreen-tinted; on evergreen they are low-alpha dark. Seams and the hero gradient give the only tonal layering.

### Shadow Vocabulary
- **Button lift** (`0 8px 18px -10px rgba(8,20,16,.7)`): primary button at rest; deepens on hover to `0 12px 24px -12px rgba(8,20,16,.8)`.
- **Frame hang** (`0 26px 50px -22px rgba(21,44,37,.65), 0 6px 14px -6px rgba(21,44,37,.35)`): the photo frame hanging over the fence; the deepest shadow on the page.
- **Plank lift** (`0 18px 30px -18px rgba(0,0,0,.55)`): step planks on the evergreen band.
- **Bar cast** (`0 -10px 30px -12px rgba(0,0,0,.5)`): the sticky bar, cast upward.

### Named Rules
**The Lifted Not Offset Rule.** Shadows have zero x-offset and negative spread. No hard-edged or diagonally offset shadows, no borders standing in for elevation.

## Shapes

The form language is boards: rectangles with modest, worked corners. Controls round at 14px, the photo frame at 12px, planks at 10px, the photo inside its frame at 5px. Circles are reserved for hardware: the 36px plank number and the 44px arrow disc are both ink circles carrying pine glyphs. Tags are full pills. Lines are 2px (button borders, row rules). Leaning is part of the shape: the photo frame rests rotated (-1.6deg on phones, 2deg from 760px up) and planks and frame sway about ±0.35deg.

**Seams.** Every change between evergreen and cream happens through a 46px seam: three wavy grain lines (outer `pine-deep` 2px at 75%, middle `pine` 3.5px, inner `pine-dark` 1.6px at 60%) with the next section's color filled below the middle line. There are no straight horizontal section edges.

### Named Rules
**The Seam Rule.** Section boundaries are grain, never a straight edge or a divider line.

## Components

### Buttons
Chunky and tactile, sized for a thumb. Primary and secondary are one component that differ only in fill.
- **Shape:** rounded board (14px), 58px min height, 22px side padding, 2px border, 10px gap between the 22px stroke icon and label.
- **Primary (Text):** pine fill, ink label, pine border (weathered pine border on cream), button lift shadow. Always the `sms:` action with a pre-filled message.
- **Secondary (Call / Text your town):** transparent with a pine border; label is `on-ground` on evergreen, `ink` with a `pine-deep` border on cream.
- **Hover (hover-capable pointers only):** primary to `pine-hi` with a deeper lift; secondary gains a 12% pine wash. Transitions 0.18s on cubic-bezier(.2,.8,.2,1).
- **Press:** scales to 0.97.
- **Focus:** 3px `pine-hi` outline at 3px offset, 8px radius (global).
- **Labels:** phones get a short label (Text for a free estimate / Call Anthony); 760px+ swaps in the wide label with the number.

### Chips (tags)
- **Style:** `cream-deep` pill, ink 14px/700 text, 5px by 10px padding, 6px gap, wrapping.
- **State:** static scope hints only; not interactive.

### Service rows
Whole rows are the links. Each row is a title, a one-line description and an ink arrow disc on the right, separated by 2px `cream-deep` rules top and bottom. Min height 64px, 20px vertical padding. Hover tints the row with an 18% pine wash and slides the disc 4px right (0.25s, same easing). Tapping opens a pre-filled text for that job.

### Navigation
- **Top bar:** wordmark (name over a 13px descriptor) on the left; from 760px a `pine-hi` call link with icon on the right. No menu.
- **Sticky contact bar (phones):** fixed bottom, `ground-deep` at 94%, safe-area padding, primary Text button flexing to fill and a compact Call button. Slides in from below (translateY 110% to 0, 0.35s). Removed at 760px+.

### Photo frame (signature)
The owner's real job photo mounted in a procedural pine frame with knots: 12px padding, 12px corner, frame hang shadow, bold 14px caption in ink beneath. Max 340px on phones, 300 to 400px column on desktop. Rests at a slight lean and springs away from a nearby pointer.

### Plank (signature)
Each estimate step is a pine plank (knot-free procedural texture, so text sits cleanly), 10px corner, plank lift, ink text, with an ink number disc pinned top-left. Phones: number left, 70px text indent. 760px+: three across, number on top, 74px top padding. Planks lean and shift away from a nearby pointer.

### Living fence (signature)
A canvas fence fills the bottom of the hero and closer: horizontal procedural pine boards with shadow gaps, front posts with screw heads every 150px (phone) or 270px (desktop), a slow sun sheen gliding across, and floating sawdust motes. Boards bow between posts on three layered sine waves (ambient amplitude 1.4px phone / 1.8px desktop at 2.4 rad/s), are pushed by a finger or mouse within 80px / 120px and spring back (stiffness 38, damping 6.5, max 14px); fast swipes knock loose sawdust (capped 70 / 150 particles). Before the script runs, a striped pine-and-shadow gradient stands in. Full constants live in the sidecar.

### Motion system
One requestAnimationFrame loop serves every animated part; each part subscribes only while its section intersects the viewport. Under `prefers-reduced-motion: reduce`, all CSS transitions are removed, the fence and seams draw a single still frame, and plank/frame lean is disabled.

**The One Spring Rule.** Every physical response (fence boards, plank and frame lean) uses the same spring: stiffness 38, damping 6.5. New interactive elements inherit it so everything feels like the same wood.

**The Still Page Rule.** Motion is an enhancement over a complete static composition; nothing is revealed, hidden or sequenced by animation except the sticky bar.

## Do's and Don'ts

### Do:
- **Do** keep every dark surface evergreen (`ground`, `ground-deep`); the darkest canvas value is a deep green.
- **Do** put `ink` text on pine and pine glyphs on `ink` discs.
- **Do** make the pre-filled `sms:` text the primary (pine) button and `tel:` the secondary (outlined) button, in that order.
- **Do** join evergreen and cream sections only with the three-line grain seam (46px).
- **Do** build headings at weight 900, uppercase, -0.02em, line-height 0.95 in the system stack.
- **Do** keep tap targets at least 44px and primary buttons 58px tall.
- **Do** design the phone layout first; restructure only at 760px.
- **Do** drive any new physical motion with the shared spring (38 / 6.5) and the shared loop, gated by viewport visibility and fully disabled under reduced motion.
- **Do** frame real photography in procedural pine rather than placing it bare.

### Don't:
- **Don't** use black or near-black neutral grounds.
- **Don't** add a second typeface or a webfont; the system stack is the house display face.
- **Don't** introduce a third surface color or a straight-edged section divider.
- **Don't** put light text on pine or pine text on cream.
- **Don't** use hard-edged or horizontally offset shadows.
- **Don't** place copy over the fence boards.
- **Don't** set body, button or tag text in uppercase.
