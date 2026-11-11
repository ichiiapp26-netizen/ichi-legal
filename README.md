# ichi-legal

Public legal pages for the Ichi app, served by GitHub Pages:

- Privacy Policy: https://ichiiapp26-netizen.github.io/ichi-legal/privacy/
- Terms of Use: https://ichiiapp26-netizen.github.io/ichi-legal/terms/

Plain HTML and CSS, no build step. Only `app/` has JavaScript, a short inline script that picks the store; nothing is tracked or loaded from elsewhere. Keep these URLs stable once the app is
submitted: the app and both store listings link to them, and changing one needs an app update.
When the policy changes, update its effective date (the same applies to the terms).

- `app/`: the page Ichi's "Share Ichi" links to. It says Ichi is coming soon until the store links are added to `STORES` at the top of the page; then it sends iPhones to the App Store and Android phones to Google Play, and shows both on a computer. Keep this URL stable: shared messages point to it.
