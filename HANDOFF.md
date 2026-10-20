# Anthony Nicotra — handoff at ~60%

**Live:** https://10elizabethbell.github.io/anthonyNicotra/ · **Repo:** https://github.com/10elizabethbell/anthonyNicotra · **Built:** 2026-10-08 from Muse brief (2026-10-08, thin brief) · **Revamped:** 2026-10-19 to the calm band style · **Call Sheet:** URL set (script reported UNCHANGED: it was already there)

## Revamp, 2026-10-19: what changed
He hasn't been contacted yet, so the whole site was rebuilt in the new house style (`calm-photo-style.md`), starting from DPG's `index.html`. The old living-fence world is in git history (`47ee476`, `c4a4f70`) if you ever want it back as an opt-in signature.
- **Look:** the green "evergreen backyard" ground with the canvas fence is gone. Now:
  - paper and navy bands, with a deep-navy band that has the faint line texture
  - pressure-treated-pine gold `#e8b65a` as the one accent, taken from his fence; it's a fill only, with `#7c5210` when it has to be text on light
  - Cal Sans headings over the system-stack body
  - pill buttons and 24px cards
- **Hero:** a plain textured navy band. Under the 2026-10-19 hero-photo rule I tried his fence photo behind the hero (a navy overlay at .8/.7, white text sampled at 6.8:1 on phones and 8.5:1 on desktop), then reverted it after Ellie's "only if it renders nicely in the hero's shape" condition:
  - **Phone, 390px: it looked good.** A portrait shot suits a tall phone hero.
  - **Desktop, 1440px: it failed.** The only source is a 1080×1350 portrait phone shot (the rest of the frame is wires, an AC unit and covered furniture). Filling the wide band meant blowing it up about 1.33×; making the boards fill it took about 1.9×, which is soft. That's the "tall photo blown up to fill a wide band" case.

  So the photo stays as the 4:5 work card further down. The tried version is in this session's notes, not in git.
  - Contents: eyebrow "Free estimates", the H1 **"Solid new fences in NJ & Philly."**, the promise, and two buttons ("Get a free estimate" goes to the form; "Text Anthony" opens a pre-filled `sms:`).
  - No Call button: the number sits only in the top-right corner.
- **Motion** (the audience is homeowners, not flagged 40+, so the full calm motion applies):
  - **H1 bounce-in, letter by letter.** It waits up to 700ms (`CONFIG.H1_FONT_WAIT`) for Cal Sans, so the split heading wraps exactly like the plain one; I verified 360/390/430/1440 in Chromium and WebKit.
  - **One 12px fade-up** for anything below the first screen.
  - **The 60px floating text circle.** It's hidden on the hero and over the form.
  - Under reduced motion or without JS, everything shows at once.
- **Structure:**
  - hero
  - "Built new, from the posts up." with his own post quoted word for word, the 4:5 job photo, and the "Click to see more of my work" Facebook row right under it
  - "What I build" service rows (each pre-selects the job in the form; only the arrow changes on hover)
  - How it works (3 steps)
  - the quote form
  - the close with the big phone number
  - the footer with Facebook
- **Removed from the old build:**
  - the "Demo one-pager — free sample." footer
  - the sticky Text + Call bottom bar
  - the Call buttons under the hero
  - the "Text your town" button
  - the canvas fence and the animated seams
- **New:**
  - favicon and iPhone icon: an "AN" monogram (there's no logo)
  - an `og.jpg` link preview (1200x630)
  - the photo at 1080 and 640 sizes with srcset
  - a Facebook link (none before)
  - the quote form with a fallback: if Messages doesn't open, it shows an "Open in Messages" link and the composed text to copy
- Weight: `index.html` is about 33KB, the phone photo 68KB (156KB on desktop), plus Cal Sans from Google Fonts, loaded without blocking.

## What's built
- **Contact:** phone 267-207-8015 (from his post).
  - Top-right `tel:`.
  - Hero "Text Anthony" and the floating circle use `sms:+12672078015?&body=Hi Anthony, I found your website. I'd like a free estimate for: `.
  - The form composes e.g. "Hi Anthony, this is Sam. I'd like a free estimate for: Fence. Town: …. I'll send a photo of the spot."
  - No email anywhere (none exists).
- **Form fields:**
  - job chips: Fence, Gate, Deck, Something else
  - name (required)
  - town (required)
  - optional notes
  - Errors are written as plain sentences.
- **Service rows:**
  - Fences, Gates & posts, Decks
  - Kitchens & baths, Tile & flooring, Masonry, Windows & doors
  - Something else
- **Facebook:** https://www.facebook.com/profile.php?id=100000287224382 (his personal profile, from the brief's profile id), under the photo and in the footer.

## Assumptions I made
- **"NJ & Philly" in the H1** (the calm style requires a place in the H1). The brief says to keep the area unknown. I read that as no towns or radius, and the page names none.
  - Evidence for NJ: his own hashtags #newjerseyhandyman, #njcontractor and #collingswoodnj, plus his posts in NJ contractor groups.
  - Evidence for Philly: #phillyhandyman, #philadelphiacontractor, and his 267 number.
  - The close hedges it: "Not sure I cover your town? Call or text and ask."
  - The finish reviewer judged it acceptable. **Confirm with him first.**
- **Services beyond fences and gates come only from his hashtags:**
  - decks
  - kitchens and baths
  - tile and flooring
  - masonry
  - windows and doors

  They're no longer labelled "tagged in his posts", as they were on the old build. #electrician and #plumbing are still left out (licensed trades).
- **First person ("I")** per the finishing rules. His posts say "give **us** a call", so he may have a crew; switch to "we" if so.
- **Name:** "Anthony Nicotra / Fencing & home contracting". There's no business name; the brief says don't invent one.
- **Promise line:** "New posts, new boards, and a yard you'll be glad to look at." is my wording, built from his post.
- **How it works:** step 2 "Send a photo" is Muse's photo-quote idea. Step 3 says "Based on your photo and what you tell me", which is inferred.
- **Accent colour:** inferred from the pine in his photo, since there's no brand.

## Placeholders and gaps
- No business name, logo, email, hours, reviews, prices, years in business or licence on the page.
- Only one photo (the same image cross-posted to three groups), cropped to remove its red text banner. No gate photo and no before/after.
- The Facebook profile was 403-restricted to Muse, so visitors may see little there. Check what a logged-out visitor sees; if it's empty, link one of his group posts instead.

## Questions for the owner
1. Do you work in both NJ and Philly? Which towns?
2. What do you call the business? Logo or truck lettering?
3. Just you, or a crew ("I" vs "we")?
4. Which services do you want leads for? Are decks, kitchens, tile, masonry and windows really yours?
5. More job photos, especially gates, decks and before/afters?
6. Licensed and insured (NJ HIC number)? Hours? Any customer reviews?

## Ideas not built (yours to pick)
- **Runner-up signature (opt-in):** the living pine fence from the old build (`47ee476`), as an opt-in hero: boards that bow and spring back under a finger. The reviewer suggested adding a gate to it.
- **Other worlds considered:**
  - golden-hour picket shadows over swaying grass
  - sawdust curling in workshop light
  - a chalk-line snap
  - a lumber stack
- **Desktop hero's right half is empty texture** (as on DPG). Options:
  - from 1024px up, move the fence card into the hero's right column (phone layout unchanged)
  - if he sends a wide (landscape) job photo, put it behind the hero under navy
  - a phone-only photo hero (the fence boards under a .8 navy veil looked good at 390px) is possible, but it splits the hero by device, so it's your call
- **The kit's accent arrow on the photo card isn't there,** because the card isn't a link. Making it link to Facebook would duplicate the Facebook row under it.
- A pine check mark on "Text this to Anthony" before Messages opens.
- A wood-grain fill on the step numbers (only if it reads as real wood).
- A before/after slider once he sends pairs.
- **Impeccable findings I kept because they're your calm-style choices:**
  - the eyebrow pills (the craft floor bans eyebrows outright)
  - the H1 bounce-in (`quieter` says no bounce easing)
  - the floating circle (distill wants one action)
  - the faint band texture (the detector's `repeating-stripes-gradient`, ignored for `index.html` in `.impeccable/config.json`; the reviewer notes it runs behind the H1 at 3.5% white)
  - the fade-up on every section (the craft floor dislikes one identical entrance)
- **Detector finding left standing:** `flat-type-hierarchy`. It counts the small 11–20px text steps; the display-to-body jump is clear.
- **Floating circle placement:** at 390px it can sit over the last visible service-row arrow. A tap there texts him instead of jumping to the form; both reach him.

## Not verified
- Real-device touch, and the real SMS handoff on iOS and Android, especially inside Facebook's in-app browser (uses the `?&body=` form).
- What his Facebook profile shows to a logged-out visitor.
- The H1 on a slow cellular load: if Cal Sans takes more than 700ms, the bounce runs in the fallback face and may re-wrap when it settles.
