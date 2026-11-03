# Velvet Plum (gen 1)

A fictional one-product luxury sunglasses site and design demo. The product ("Aubade"), price, specifications and all copy are placeholders. Product and scene images are AI-generated illustrations.

## What is here
- `index.html` is a single static page with inline CSS and a small script. There is no build step.
- `img/` holds the web-optimized images and the silent hero loop (`hero-loop.mp4`).
- `netlify.toml` publishes the repo root and caches `/img/*`.

## Run it locally
Open `index.html` in a browser, or serve the folder: `python3 -m http.server 8000`.

## Design tokens
Plum `#64165D`, magenta-plum `#8A176E`, mint `#A7E8D7` / `#C6F0E4`, pearl `#F1EAF6`, gold hairlines `#C8A862`, background `#1b0618`.
Type: Pinyon Script (wordmark), Cormorant Garamond (headlines), Outfit (text).

## Hero motion
The loop fades in over the still after the opening animation, pauses when off-screen, and is removed for visitors who prefer reduced motion.

## Ideas for gen 2
- Working reserve form (Netlify Forms with a honeypot), meta and Open Graph images, JSON-LD.
- Upscale the hero still and loop (the hero is 1k; the loop is 720p).
- Real campaign photography and product shots that show the same frame in every image.
- Accessibility and Lighthouse pass (target 95+), self-hosted fonts.
