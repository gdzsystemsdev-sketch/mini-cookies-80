# Project memory

## Product intent & audience

- **Mini Cookies**: adult content creator management agency website.
- Recruits ambitious, disciplined women for a fully-managed streaming + off-platform earning setup.
- Core value props: done-for-you systems, 24/7 sales/chat teams, multi-streaming across 5 platforms, up to 5 off-platform income sources, coaching, equipment, privacy/geo-blocking.
- Single flat offer: no tiers, no upfront fees, no lock-in contracts; revenue split model (50/50 streaming, 25/75 off-platform).
- Selective positioning: "fewer than 3% of applications accepted."

## Brand personality & voice

- Direct, confident, premium, selective.
- Framed as partnership, not service — "our success is tied to yours."
- Plain language with high-status cues ("sharks," "all in," "most who apply are not").
- Conversion-oriented: reassurance (free to start, leave anytime) paired with exclusivity.

## Visual design & UX direction

- Dark background, pink accent for highlights/key numbers/CTAs.
- Card-based sections with hover-lift effect; pink-highlighted cards vs neutral cards for comparison layouts.
- Consistent section rhythm reused across homepage, How It Works, About Us.
- Layout patterns: grid cards, two-column comparisons (good/bad, we-run/you-carry), checklist grids with pink dots, split highlight cards with large percentage numbers.
- Hero includes badge + headline with pink accent word + subheadline + multiple smooth-scroll CTA buttons.
- Anchored sections: `#our-team`, `#requirements`.
- Apply CTA links to application form/modal on homepage.
- Responsive: desktop and mobile nav menus; footer links across pages.

## Decisions, constraints & rationale

- Built with Vite + React.
- Multi-page site: Homepage, How It Works, About Us (`/about`), Earnings, Privacy Policy.
- About Us page consolidates agency model, inclusions, earnings split, team standards, and creator requirements on one long-scroll page.
- Reuses shared design system (colors, card styles, heading sizes, section rhythm) across all pages for cohesion.
- Final Apply button on About Us deep-links to homepage application form rather than duplicating it.

## Open questions & assumptions

- Earnings page content not yet detailed in context — may need separate build.
- Application form/modal implementation details on homepage not fully specified.
- Privacy Policy page content not yet provided.
- Assume single-language (English) site.