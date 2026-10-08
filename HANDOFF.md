# Anthony Nicotra — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/anthonyNicotra · **Built:** 2026-10-08 from Muse brief (run 2026-10-08, thin brief)

## What's built
- One page, phone first: hero → his job (photo + his own post quote) → what he builds → how a free estimate works → where he works → name + buttons again → footer ("Demo one-pager — free sample.").
- **World: fresh pressure-treated pine on an evergreen backyard ground.** No logo or colors exist, so the palette comes from his own fence: pine (`--pine`) on deep green (`--ground`), cream "sawn pine" sections.
- **Signature element: the living fence** (`Fence` IIFE, constants in `CFG`). Horizontal boards with procedural grain and knots bow between their posts on three layered waves. A finger or mouse pushes boards away and they spring back with a wobble. A fast swipe across the boards knocks sawdust loose. Sunlit dust motes float above and get pushed around. A sun sheen glides across. It runs in the hero and again in the closer.
- Carried through the page: the seams between sections are three moving grain lines (the fill follows the middle one). The photo frame and the three step planks use the same procedural pine and lean away from the finger.
- His photo is framed in pine and leans on the hero fence. On phone it peeks up under the fence in the first screen; on desktop it's the right column.
- **Contact:** every "Text" button and service row is an `sms:+12672078015?&body=…` link with a pre-filled estimate request naming the job ("Job: New fence / Town: / I'll send a photo"). Call buttons use `tel:`. On phones a sticky Text + Call bar appears once the hero buttons scroll away and hides at the closer. On desktop the text button shows the number.
- Weight: about 140KB in one file (photo is about 100KB of that, loaded after the scripts).

## Assumptions I made
- **Name on the page = "Anthony Nicotra" + "Fencing & home contracting".** The brief says don't invent a business name. His personal name is what he posts under. Confirm at outreach.
- **Headline "Built new, from the posts up."** Built from his post ("All new posts and new gate installed"). Benefit framing, not a quote.
- **Services:** Fences and Gates & posts are verbatim from his post. The "Any job big or small" tags (decks, tile, flooring, kitchens, baths, masonry, windows & doors) come from his own hashtags only, and are labelled "Tagged in his posts". I left out **#electrician and #plumbing**: those are licensed trades in NJ/PA and claiming them unconfirmed is risky.
- **Area:** the page says he posts in New Jersey contractor groups and tags Philadelphia-area work (both facts from the brief). It names no towns. In place of a list there's a "Text your town" button with the message pre-filled ("Do you cover my town?").
- **How it works:** the steps are inferred from "call or text for free estimate" plus Muse's photo-quote idea. "Gets back to you" is a reasonable inference, not his words.
- Voice: third person ("Anthony…"), casual. His posts say "us"; switch to first person if he prefers.

## Placeholders and gaps
- Service area / town list (the page asks visitors to text their town instead).
- Business name, logo, hours, email, reviews, prices, years in business: none on the page.
- Only **one** photo exists (the same image cross-posted to all three groups). I cropped off its red text banner. No plates, faces or house numbers were visible. No gate photo, no before/after.

## Questions for the owner
1. What do you call the business? Logo or truck lettering?
2. Which towns do you cover (Collingswood? Philly neighborhoods)?
3. More job photos, especially gates, decks, and before/after pairs?
4. Which services do you actually want leads for? Do you do electrical/plumbing yourself (licensed)?
5. Licensed & insured (NJ HIC number)? That's worth showing if true.
6. Hours / best time to text? Any customer reviews we can quote?

## Review round (Impeccable finish reviewer, applied)
- Area copy corrected (the groups are NJ; Philly comes from hashtags). The "coming soon" marker became a real text button.
- Fence calmed: bow 1.4/1.8px, nearly one phase across boards, 4–5px bend columns (smoother edges), max push 14px. If it now feels too tame, raise `CFG.waveAmp` and the `b * .12` phase term.
- Step planks use knot-free pine, so knots no longer sit under text.
- Seams no longer leave straight color edges. The card lean pauses off screen and has a 60px reach on phones.
- Not done: on desktop ≥1100px the photo frame doesn't rise further into the hero's empty right half. The grid's `align-items:end` cancels the negative margin. Fix by positioning the frame inside the hero on desktop.
- Reviewer's ceiling notes for you: the fence still reads a little "ribbon" rather than milled lumber, and there's **no gate** in the fence even though the gate is half his showcase job. Adding a gate section to the canvas is a good next touch.

## Ideas not built (yours to pick)
- **Runner-up world:** backyard at golden hour, with long fence-picket shadows sliding across swaying grass, the grass parting under the finger.
- Other worlds considered: sawdust and shavings curling in workshop light; chalk-line snap / blueprint; a lumber-yard stack; a masonry grid that ripples.
- Before/after slider once he sends pairs (taste section 4).
- `book.html` short estimate form → composed text (name, town, job, photo reminder).
- Seams reacting to the pointer like the fence does.
- Photo gallery as a row of "boards" you swipe sideways.
- First-person copy variant ("Give us a call or text…"), which is his own phrasing.
- Self-hosted display face: Impeccable's craft floor bans system faces as display voice. I kept the system stack per Ellie's house style. Worth a look if you want more character.

## Not verified
- Real-device touch (tested with simulated touch and mouse sweeps in headless Chrome only).
- Real SMS handoff on iOS and Android, especially from inside Facebook's in-app browser (`?&body=` form used).
- Frame rate on old phones (phone: 4px bend columns × ~8 boards, 34 motes, dpr capped at 2).
- Headless full-page captures garble the photo at very tall heights. It renders fine at real phone heights; recheck on a device.
