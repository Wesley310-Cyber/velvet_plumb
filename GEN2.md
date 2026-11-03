# Gen 2 checklist

Gen 1 is the static page at https://velvetplumb1.netlify.app/ (tagged `v1`). Work on gen 2 on a branch, and let Netlify Deploy Previews show each change before it merges to `main`. A full redesign goes in its own repo and Netlify site (`velvetplumb2`).

## Function
- [ ] Working reserve form: Netlify Forms with a hidden static twin in `index.html`, a honeypot field, and a clear success state.
- [ ] Move the form copy from "demo" to the real flow only when real fulfillment exists.
- [ ] Add JSON-LD `Product` schema once real name, price and specs are final.

## Imagery
- [ ] Upscale the hero still (currently 1k) and re-render the hero loop (currently 720p, 5 seconds played forward and back).
- [ ] Reshoot or regenerate the six product and scene images so the same frame appears in every one (hinge and arcade glasses differ slightly).
- [ ] Add a lens-and-light variation or a second angle for the product section.

## Quality
- [ ] Lighthouse 95+ on Performance, Accessibility, Best Practices and SEO.
- [ ] Self-host the three fonts (Pinyon Script, Cormorant Garamond, Outfit) instead of loading them from Google Fonts.
- [ ] Contrast check on mint and plum pairings, visible focus states, keyboard pass through the nav and form.
- [ ] Test the hero video on real phones, including low-power mode and slow connections.

## Content
- [ ] Replace placeholder name, price, specs and craft copy with real details.
- [ ] Add real policies (shipping, returns, privacy) and contact details.
- [ ] Keep the "design demo / AI-generated imagery" notice until real photography replaces the illustrations.
