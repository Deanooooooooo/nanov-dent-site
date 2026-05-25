# QA — Дентална клиника NANOV DENT

- Gate 1 source/fact audit: PASS — business name, category, address, phone, Facebook, Superdoc profile, Google Maps place link, doctor profile, reviews, and images documented in `image-map.md`. No invented prices, credentials, awards, or service claims.
- Gate 2 visual asset audit: PASS — real clinic/interior/doctor images from Oink and Superdoc inspected. Rejected black-bar crops, empty corridor, decorative-only images, and duplicates. Selected clinic rooms, reception, exterior sign, and doctor portrait.
- Gate 3 testimonial/review audit: PASS — written patient opinions used from Superdoc with displayed names and original Bulgarian text. No rating-only cards. Visible negative complaint was not used.
- Gate 4 copy audit: PASS — H1 clearly states business type + location + service; source-meta wording removed after QA; copy is client-facing and factual.
- Gate 5 links/schema audit: PASS — phone, Superdoc, Facebook, Google Maps, nav anchors, canonical, and Dentist schema present. Hours checked but full weekly table unavailable; not invented.
- Gate 6 image/layout audit: PASS — all images load; no duplicate image use; no letterboxing, ugly containers, or awkward crop in final screenshots.
- Gate 7 map/local SEO audit: PASS — bottom map/contact block directly above footer; embedded Google Maps iframe has explicit width/height, visibly loads, fills container; exactly one visible Google Maps navigation CTA in contact block.
- Gate 8 responsive visual QA: PASS — desktop/mobile screenshots inspected by strict image QA after fixes; no blockers for typography, copy, hero order, images, testimonials, map, footer icons, or CTA duplication.
- Gate 9 final live QA: pending deployment.

## Notes
- `[blocked: full working-hours table unavailable in accessible public sources]` — Google Maps limited view and Superdoc appointment page did not expose a reliable full weekly schedule.
- Final local screenshots: `artifacts/nanov-desktop-final.png`, `artifacts/nanov-mobile-final.png`.
