# Doodad demo

Static investor demo. No build step.

- `index.html`: A Day with Doodad (3D device + family app walkthrough)
- `flows.html`: data flows and senior speech training data

All libraries and fonts are inlined, so the pages work offline. Pages send `noindex` headers and robots.txt blocks crawlers.

- `og.png` (link preview card), `favicon.svg`, and `device.png` (the still shown when a phone has no WebGL; the chapters, captions and family app still run).
- The 3D stage renders only while it is on screen and the tab is visible, and uses a lower pixel ratio on touch screens.
- Price, 911 and speech-training wording match the product: $29 a month for the app and $49 with the handheld, Call 911 opens the phone dialer in the app (the handheld that dials is planned), and opt-in speech training is planned, not collected at launch.

Not search-indexed does not mean private: anyone with the link or the GitHub repo can read it. Keep the repo private and turn on Vercel Deployment Protection before sharing the link widely.

Deploy: import this repo in Vercel with the "Other" framework preset and no build command.
