# Local preview QA | owner self-check

Checked 2026-09-01. This is owner evidence only; it is not an independent visual acceptance.

## Browser evidence

- Local server returned 200 during the Chrome renders. Each local server was then stopped.
- Chrome headless screenshot for the current Hero simplification: `evidence/simplified-logo-hero-1440.png` at 1440×900.
- Both are real local renders. The macOS display-link warnings emitted by headless Chrome did not prevent screenshots from being produced; no app/runtime conclusion is inferred from that warning.

## Product and scope checks

- All seven visible image placements use a distinct local asset. No placeholder, TODO, internal governance text, pricing, invented review, fake form, payment, login, CMS or self-hosted booking exists in the rendered HTML.
- Client-visible internal-text scan: PASS. Scope: `local_preview/index.html`; prohibited internal phrases were not found. The required low-impact `Independent concept preview` label is visible.
- Fresha links are direct outbound links only. Static source paths resolve under the local preview root.
- Desktop first-view inspection: header, large full original-ratio RP-01 logo artwork, explicit dog-grooming location label, one primary CTA, type hierarchy and source image load. The Hero now uses a simplified content hierarchy and a low-opacity blurred instance of the same image only as its background treatment.
- Bottom 40% self-check: PASS. It adds a distinct portfolio gallery and verified Romiley location/opening-times plus the existing Fresha handoff, rather than repeating hero copy.
- BUSINESS-FIDELITY QA: PASS for the stated concept scope. Visible services, address, opening times, review total and booking destination are source-recorded.
- Content update: PASS. The visible page now also maps Krista, the recorded City & Guilds/one-to-one home-based source claim, de-shedding, listed service times/prices, public phone/email, weekend closure, instant confirmation, and a short dated public Fresha review.
- Image integrity correction: PASS for owner self-check. All visible images use natural dimensions and `object-fit: contain`; no visible image is cropped with CSS. The complete RP-01 logo artwork is the Hero image.
- Specified Hero update: PASS for owner self-check. The user-selected logo image is large on desktop and shown in its complete original ratio. Contact, confirmation and opening-times remain in the final booking section immediately before the footer.
- User-directed layout update: PASS for owner self-check. The former middle services block was removed. Its recorded content is now the right-side service panel in the final booking section, replacing the former closing dog image without changing the booking/contact facts.
- Rhythm rework: PASS for owner self-check. Vertical whitespace and oversized type were reduced across the introduction, portfolio, review, gallery and closing sections. The closing service card is now aligned with the booking information and uses the same visual system.
- Art-direction rework: PASS for owner self-check. The logo artwork's aqua, blush and warm accent colours now form the page system; Hero, proof, gallery and closing use distinct but coherent colour fields. Foreground customer assets remain original-ratio `contain` renders. The blurred logo instance is a background-only decorative treatment behind the intact Hero foreground image.
- Non-image polish: PASS for owner self-check. The page now uses a consistent micro-label, card-shadow, colour-shape, numbering and button-feedback language; no customer image, verified business fact, service item, contact detail or section order was changed in this pass.
- Footer overscroll correction: PASS for owner self-check. The document canvas now matches the Footer's dark surface and disables vertical overscroll, so scrolling past the visible closing section cannot expose a plain cream canvas.
- Motion polish: PASS for owner self-check. The selected calm/premium motion personality uses a 650ms decelerating Hero-copy entrance, a slow 8-second Logo float and two low-amplitude ambient colour-field drifts. Buttons have press feedback. `prefers-reduced-motion: reduce` disables all automatic motion and press transforms.

## Required remaining gate

`INDEPENDENT VISUAL ACCEPTANCE = AWAITING` because this Owner cannot independently accept its own work. Consequently `CLIENT-SHOWABLE DEMO = FAIL / NOT YET CONFIRMED` under the project rule, despite this local preview draft and self-check.

## Authorization boundaries

`CUSTOMER AUTHORIZATION: NOT VERIFIED`.

Not made: Cloudflare upload package, display/upload package, source-transfer package, deployment, public/unlisted URL, account login, outreach draft/send, customer contact or payment action.
