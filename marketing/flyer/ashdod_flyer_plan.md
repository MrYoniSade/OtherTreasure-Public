# Ashdod Flyer Distribution Plan — OtherTreasure

> Physical A4 flyer campaign targeting city quarters 8, 10, 13, 16, and הקריה in Ashdod.
> Goal: reach 5,800 installs from an addressable population of ~58,000 people aged 16–60 (10% conversion target).

---

## Target audience snapshot

| Factor | Value |
|--------|-------|
| Target quarters | 8, 10, 13, 16, הקריה (Ashdod) |
| Total residents in target area | ~99,500 |
| Residents aged 16–60 | ~58,000 |
| Target conversion (10%) | **5,800 users** |
| Initial print run | **500 flyers** |
| Print cost (actual) | **655 NIS** |

### Per-quarter breakdown

| רובע | תושבים | גילאי 16–60 | % of addressable |
|------|---------|-------------|------------------|
| 8 | 18,000 | 10,500 | 18% |
| 10 | 24,000 | 14,000 | 24% |
| 13 | 21,000 | 12,200 | 21% |
| 16 | 27,000 | 15,700 | 27% |
| הקריה | 9,500 | ~5,500 (est.) | 10% |
| **Total** | **99,500** | **~57,900** | 100% |

---

## Budget breakdown

| Item | Cost |
|------|------|
| 500 × A4 color flyers (print shop) | **655 NIS** |
| Tape / stapler for bulletin boards | ~5 NIS (likely already home) |
| QR code generation | ~~Free~~ ✅ Done |
| A4 flyer design | ✅ Done |
| **Total** | **~660 NIS** |

> **Note:** 500 color A4 flyers were quoted and confirmed at **655 NIS**. Cost per flyer ≈ 1.31 NIS. This is the committed budget for the initial print run.

---

## Low/zero-cost reach multipliers (beyond the 500 flyers)

Use these to extend reach without additional print or ad spend.

| Method | Estimated reach | Cost |
|--------|----------------|------|
| Post in Ashdod Facebook groups (see list below) | Thousands per group | Free |
| WhatsApp forwards to quarter-specific community groups | 20–100 per group | Free |
| Ask building managers (ועד בית) in target quarters to share in their group | 50–200 per building | Free |
| Pin flyer in each building's notice board (elevator + entrance) | Passive daily reach | Already in print budget (655 NIS) |
| Pin in local laundromats, grocery store notice boards | Passive daily reach | Free |
| Post in Nextdoor / אשדוד neighbours apps | Local early adopters | Free |
| Ask friends in the quarters to hand-distribute 5 flyers each | Multiplies effort | Free |

---

## Milestone 1 — Pre-launch preparation (before app is public)

> Aligns with: **M1 — Launch** in `mvp-feature-checklist.md`
> Dependency: app must be live on Google Play before any flyer goes out.

- [x] Design the A4 flyer (use existing `app_download_flyer_a4_print.html` as base or redesign in Canva).
  - Must include: QR code, Google Play badge, short tagline in Hebrew, 3 bullet points ("free", "map", "near you"), app screenshots or icon.
  - Keep text minimal — someone must understand the app in under 5 seconds while walking past.
- [x] Generate a QR code pointing to the Google Play listing (not the web fallback) — use a free tool, no paid shortlink needed.
  - Test the QR code with at least 3 different phones before printing.
- [ ] Print 500 copies (color A4) — confirmed cost **655 NIS**.
- [ ] Confirm the app is live on Google Play (Internal → Closed → Production) before any flyer goes out. **Do not distribute before the store link is real.**
- [ ] Prepare the Hebrew caption text for WhatsApp/Facebook posts to accompany digital shares (see template in `LAUNCH_MESSAGES.md`).

---

## Milestone 1 — Launch week distribution (day of store rollout)

> Aligns with: **T-0 Launch Day** in `mvp-feature-checklist.md`

> Flyers are allocated proportionally to the addressable 16–60 population per quarter.

- [ ] **Quarter 8** (~18% of addressable → **~90 flyers**):
  - [ ] Pin on building notice boards (elevators + entrances).
  - [ ] Leave at local grocery store / kiosk if permitted.
  - [ ] Pin in any community centre, laundromat, or high-traffic shop.
- [ ] **Quarter 10** (~24% → **~120 flyers**):
  - [ ] Same placement strategy as Quarter 8.
- [ ] **Quarter 13** (~21% → **~105 flyers**):
  - [ ] Same placement strategy.
- [ ] **Quarter 16** (~27% → **~135 flyers**):
  - [ ] Same placement strategy.
- [ ] **הקריה** (~10% → **~50 flyers**):
  - [ ] Same placement strategy.
- [ ] Post in Ashdod Facebook groups on the same day flyers go out (compound effect):
  - [ ] עיריית אשדוד - מנהלת י'-י"ג
  - [ ] מרכז קהילתי דיונה רבעים י'-י"ג
  - [ ] אשדוד העיר שלי
  - [ ] פורום תושבי אשדוד
  - [ ] Any quarter-specific neighbourhood groups for quarters 8, 10, 13, 16, הקריה.
- [ ] Send the QR flyer image to 3–5 WhatsApp groups in the target area on launch day.
- [ ] Ask 3–5 friends who live in the target quarters to share the WhatsApp message and hand out a few physical flyers.

---

## Milestone 1 — Post-distribution tracking (week 1–2 after launch)

> Aligns with: **Track first 14 days post-public launch** in `mvp-feature-checklist.md`

- [ ] Check Google Play Console install stats daily for the first 14 days; note any spikes that correlate with distribution days.
- [ ] Record how many flyers were placed per quarter and at what locations (simple notes on phone).
- [ ] Note which Facebook group posts got the most engagement (likes, comments, shares).
- [ ] At day 14: count total installs and estimate install-per-flyer ratio to inform the next print run.

---

## Milestone 2 — Expand distribution (50 → 100 users target)

> Aligns with: **M2 — Early traction** in `mvp-feature-checklist.md`
> Trigger: once 50+ installs confirmed from M1 flyer wave.

- [ ] Evaluate M1 results: which quarter and placement type drove the most installs?
- [ ] Prioritize top-performing quarter for a second flyer wave (print 200–300 more; at ~1.31 NIS/flyer the incremental cost is ~260–390 NIS).
- [ ] Update the flyer design to include a real testimonial or stat: "50 items given away in Ashdod already!" — adds social proof.
- [ ] Add iOS App Store QR code alongside Google Play if iOS is live by M2.
- [ ] Expand to adjacent quarters (e.g., quarter 11 or 14) if early quarters are saturated.
- [ ] Reach out to ועד בית (building committee representatives) in the top-performing quarter — offer to supply a stack of 20 flyers per building for self-distribution.
- [ ] Pin flyers in any youth centres, libraries, or community clubs in the target quarters.
- [ ] Post a "50 users!" milestone update in the same Facebook groups with a real item-shared story.

---

## Milestone 3 — Community seeding (100 → 1,000 users)

> Aligns with: **M3 — Growth** in `mvp-feature-checklist.md`
> At this stage, the flyer becomes a supporting channel, not the primary driver.

- [ ] If a Facebook / Instagram paid boost is used, geo-target the same 5 areas exactly (quarters 8, 10, 13, 16, הקריה) with a ≤50 NIS boost — the audience overlap with flyer viewers compounds the effect.
- [ ] Print a larger second batch (500–1,000 flyers) if organic growth from M1/M2 flyers validated the channel — by M3 the cost-per-install from print should be measurable.
- [ ] Expand flyer distribution to schools, high schools, and universities in or near the target quarters.
- [ ] Approach local municipal social services or community workers to include the flyer in their materials.
- [ ] If the app has reached 200+ users in Ashdod, update flyer to show the live stat ("200+ Ashdod users") to trigger social proof at scale.

---

## Flyer design checklist (applies to all milestones)

- [x] App name and logo prominent (top 30% of flyer).
- [x] Single clear headline in Hebrew: e.g., "חפצים בחינם ממש ליד הבית" ("Free stuff right next to home").
- [x] 3 short bullet points: post, find on map, take for free.
- [x] QR code: large enough to scan from 50 cm (~4×4 cm minimum).
- [ ] Google Play badge (and App Store badge if iOS is live).
- [x] No clutter — white space is your friend on a notice board.
- [ ] Test print: verify QR scans correctly from the printed page before doing the full run.

---

## Conversion funnel estimate

| Stage | Count | Assumption |
|-------|-------|------------|
| Flyers distributed | 500 | Initial print run (655 NIS) |
| Flyers seen (×10 passive views per placement) | 5,000 | Estimate: each notice board placement seen by ~10 people |
| QR scans / Play Store visits (5% of viewers) | 250 | Typical CTR for physical QR |
| Installs (50% of store visits) | 125 | Typical store conversion |
| Active users after 7 days (50% of installs) | 62 | Standard day-7 retention |
| **Cost per active user** | **~10.5 NIS** | 655 NIS ÷ 62 users |
| **Total from 500 flyers** | **~62 active users** | Conservative baseline |

To reach 5,800 users: combine flyers with Facebook group posts, WhatsApp forwards, and word-of-mouth from early users — physical flyers seed the area, digital multipliers drive the volume. The addressable pool of ~58,000 residents aged 16–60 across 5 areas makes a 10% conversion realistically achievable over multiple campaign waves.

---

## Related files

- [app_download_flyer_a4_print.html](app_download_flyer_a4_print.html) — current printable flyer template
- [LAUNCH_MESSAGES.md](LAUNCH_MESSAGES.md) — WhatsApp / Facebook caption templates
- [MILESTONE_CONTENT_PLAN.md](MILESTONE_CONTENT_PLAN.md) — full content strategy per milestone
- [mvp-feature-checklist.md](../mvp/mvp-feature-checklist.md) — canonical feature and launch checklist
