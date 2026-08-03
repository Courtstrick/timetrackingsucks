# timetrackingsucks.com

A funny, anonymous landing page + community for everyone who hates filling out timesheets. A support group disguised as a website.

The long-term play: build an audience around a genuinely funny brand, then monetize via B2B time-tracking software (sponsorships, an honest "least-bad software" shortlist, and affiliate placements).

## Stack

Dead simple on purpose: a single self-contained `index.html` (inline CSS + vanilla JS, Google Fonts). No build step, no dependencies. Open the file, it works.

## Local preview

```bash
python3 -m http.server 8787
# then visit http://localhost:8787
```

## Design

Retro "pixel-desktop" genre (a wink at cfosecrets.io) rendered in an original palette — warm paper, ink, alarm red, highlighter amber, classic-gray windows — so it reads as a cousin, not a clone. Voice is a dry, anonymous corporate insider (Secret CFO style).

## Structure

- **Hero** — headline + live-typing fake timesheet window + error dialog
- **Ticker** — running "Misc — Other" hours counter
- **Manifesto** — the angry insider rant
- **The Six-Minute Lie** — stat cards
- **The Receipt** — itemized cost of one wasted Friday
- **The Shortlist** — *(monetization)* B2B software slots + a paid sponsor card
- **Join the community** — email capture (primary CTA)

## TODO before / after launch

- [ ] **Wire the email form** (`#joinForm` in `index.html`) to an email provider — Beehiiv, ConvertKit, Substack, or a community tool like Circle/Skool. Currently it just shows a success message client-side. Search for the `TODO:` comment in the `<script>`.
- [ ] Decide where **"Join the community"** points — newsletter vs. an actual community space (Circle, Discord, Slack).
- [ ] Fill the **Shortlist** cards with real, honest reviews once there's an audience; turn the sponsor card into a real "Advertise" page / mailto.
- [ ] Point the domain (`timetrackingsucks.com`) at the host.

## License

Content & code © 2026. All rights reserved (for now).
