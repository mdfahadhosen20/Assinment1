Design and code a "Hackathon Details" section for the DevConf 2026 landing page, to replace the "Something Missing?" placeholder.

CONTEXT — match the existing site:

- Tech stack: pure HTML5 + CSS3 only, no JS, no frameworks
- Existing color palette: background #f8fbff, text #0f172a, primary blue #2563eb, dark navy #0f172a (used for the highlighted Pro pricing card), card borders #e2e8f0, rounded corners (24-28px radius), soft box-shadows like the speaker/pricing cards
- Font: Inter / system-ui, same as rest of site
- Section pattern to follow: centered <h2> heading + optional subtitle paragraph (like "Meet the Speakers" and "Secure Your Spot"), then a content grid below, wrapped in a .container div

CONTENT — a "DevConf 2026 Hackathon" section that includes:

- Section heading: "Build Something in 24 Hours"
- A short subtitle sentence about the hackathon happening alongside the conference
- 3-4 info cards in a row (grid, responsive: 1 column mobile, row on desktop) covering things like:
  - Dates & duration (e.g. "24-hour build sprint, Day 2-3")
  - Prize pool (make up a realistic figure, e.g. "$25,000 in prizes")
  - Team size (e.g. "Teams of up to 4")
  - Theme or focus area (e.g. "Open track — AI tools, dev tooling, or your own idea")
- Each card: a small icon or label at top, a bold headline value, one short supporting line
- One CTA button below the cards, e.g. "Register Your Team", styled like the existing .button-primary class

STYLE REQUIREMENTS:

- Visually distinct from the pricing/speaker sections but clearly part of the same design system (same border-radius scale, same shadow style, same spacing rhythm — 80px section margin-bottom like the sections above it)
- Fully responsive using the same breakpoint pattern already in the site (480px, 768px, 1024px)
- Use a class naming convention consistent with the rest of the CSS (e.g. .hackathon-section, .hackathon-grid, .hackathon-card)
- No Lorem Ipsum — write real, specific-sounding copy

Output the HTML block (to replace the current <section class="ai-section"> placeholder) and the matching CSS to add to style.css.
