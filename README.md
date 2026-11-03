# Morsy website

Published website: https://jsheonH.github.io/

This repository contains the built static website. GitHub Pages serves the main branch root. No API keys, signup data, or internal application notes are included.

The interactive showcase runs local rule-based modeling code; it does not call a live AI service. The waitlist is not connected and does not save submissions.

To update: build the website source with `npm ci`, `npm test`, `npm exec -- tsc --noEmit`, and `npm exec -- vite build --assetsDir . --base /`. Update the Open Graph and canonical URLs to the published domain, then replace the deployed static files. Preserve `.nojekyll`.
