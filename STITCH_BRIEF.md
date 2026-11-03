# Velvet Plum: Gen 1B Stitch brief

**Gen 1B** means exploring ideas on top of the live gen 1 site (https://velvetplumb1.netlify.app/, repo `velvet_plumb`, branch `main`). It is not a rebuild. Gen 2 (see `GEN2.md`) is the larger functional and imagery upgrade. Anything chosen in Gen 1B can be carried into gen 2.

## Rules
- Do not change `main` directly. Work on a branch named `gen-1b` and open an unmerged pull request. Netlify's Deploy Preview shows the result next to the live site.
- The site stays a static page: `index.html`, `img/`, `netlify.toml`. No build step unless asked.
- The brand is fictional and the site is a design demo. Product name, price, specs and copy are placeholders. Do not add invented reviews, awards, counts or credentials.
- Keep the demo notice in the footer and the "AI-generated illustrations" note.
- Keep `prefers-reduced-motion` behavior, visible focus states, and no horizontal scroll from 320 px to 2560 px.

## The design as it is now
**One product:** the "Aubade", an oversized cat-eye in solid plum acetate with a slim gold hinge and plum-to-blush gradient lenses. Sample price $480.

**Mood:** modern, feminine, luxurious. Dark and immersive. Plum dominates, mint is a rare highlight, gold appears only as hairlines.

**Palette**
| Role | Hex |
|---|---|
| Background (velvet black-plum) | `#1b0618` |
| Raised panel | `#2a0a27` |
| Brand plum | `#64165D` |
| Magenta-plum | `#8A176E` |
| Mint | `#A7E8D7` |
| Soft mint | `#C6F0E4` |
| Pearl (primary text) | `#F1EAF6` |
| Pearl dim (secondary text) | `#CDBED6` |
| Gold hairline | `#C8A862` |

**Type:** Pinyon Script (the "Velvet" in the wordmark), Cormorant Garamond (headlines, light and italic), Outfit (body and UI). Wordmark: script "Velvet" beside spaced serif "PLUM".

**Section order (top to bottom)**
1. Sticky header: wordmark, links (The frame, Craft, In the city), mint "Reserve" button.
2. Hero: "One frame. Cut in plum." with a short paragraph, "Reserve yours" button and sample price, over a full-width photo with a silent looping video.
3. Statement band on plum: "Modern. Feminine. Luxurious."
4. The frame: "Built around one shape." Product photo on marble beside a spec list.
5. Details: "Look closer." Hinge close-up and flat-lay with case, offset columns.
6. Craft: "Made slowly." Acetate, Gold, Lens in three columns with gold hairlines.
7. In the city: "Worn in the city." Three palette-styled scenes (arcade, rooftop, old town).
8. Reserve: "Reserve yours." Name, email, country, demo-only form on a plum panel.
9. Footer with demo notice. On phones a sticky Reserve bar sits at the bottom.

**Motion:** on load the hero photo settles in and the headline, paragraph and button rise in. After about 2.5 seconds a 5-second silent loop (played forward then in reverse) fades in over the still, pauses off-screen, and is removed for reduced-motion visitors.

**Images (all in `img/`):** `hero.webp` (16:9, 1k), `hero-loop.mp4`, `front.webp` (1:1), `hinge.webp` and `flatlay.webp` (4:5), `milan.webp`, `rooftop.webp`, `street.webp` (4:5 scenes), `og.jpg` (share card). Originals are kept outside the repo.

## Ideas to explore in Stitch
- Two or three alternative hero compositions: type over image (current), split layout, product centered with the headline below.
- A light "pearl and lavender" variant of the whole page, to compare against the dark one.
- A more editorial "In the city" section: one large image with two small, or a horizontal scroll.
- A fuller product section: three angles, a colorway selector, or a lens-detail callout.
- A calmer, more minimal Reserve section, and a mobile menu.
- Alternative wordmark lockups.

## Prompt to give Stitch
> Design a luxury landing page for "Velvet Plum", a fictional brand that sells exactly one product: an oversized cat-eye sunglass in solid deep plum acetate with a slim gold hinge. Mood: modern, feminine, luxurious, dark and immersive. Palette: deep velvet plum background (#1b0618) and panels (#2a0a27), brand plum #64165D, magenta-plum #8A176E, mint highlights #A7E8D7 and #C6F0E4 used sparingly, pearl-lavender text #F1EAF6, thin gold hairlines #C8A862. Type: a script wordmark ("Velvet") beside a spaced serif "PLUM", Cormorant Garamond headlines in a light weight, Outfit for small text. Sections: sticky header, full-width hero with the headline "One frame. Cut in plum." and a "Reserve yours" button, a one-line statement band, a product section with spec list, a close-up details gallery, three craft notes, a "worn in the city" strip of three portraits, and a short reserve form. Generous empty space, soft light, no clutter, mobile first. Show 3 distinct hero options first.

## Bringing ideas back
1. Export or screenshot what you like from Stitch.
2. On branch `gen-1b`, rebuild the chosen ideas in `index.html` (and `img/` if new images are needed), reusing the existing tokens.
3. Check the page at 390, 768 and 1440 px, and with reduced motion turned on.
4. Push the branch, open an unmerged pull request, and send the Deploy Preview link.
5. Do not merge until Wesley decides. `main` and the live site stay unchanged until then.
