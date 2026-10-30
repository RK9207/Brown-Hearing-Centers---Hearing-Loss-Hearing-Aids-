# IMAGE_PROMPTS.md — Brown Hearing Centers | Hearing Aids | Victoria, TX

**Stage:** Step 4B — image strategy and prompts only (no images generated, no page changes)
**Prepared:** October 30, 2026
**Inputs read:** Project Brief, RESEARCH.md, KEYWORD_RESEARCH.md, PAGE_STRATEGY.md, CONTENT_DIRECTION.md, DESIGN_SYSTEM.md, Awaiting_Client.md, the Step 4A `index.html`, and the live-site screenshots supplied for inspiration.
**Governing theme:** local hearing-aid help in Victoria, TX; assessment first, then fitting and ongoing support; easier everyday conversation as a possibility, never a guarantee.

---

## 0. Placeholder audit (from the actual Step 4A code)

Five intentional placeholders exist in `index.html`. No other section carries an image, and none should: recognition, process, FAQ, reviews and the final call-to-action band are deliberately type-led (DESIGN_SYSTEM.md).

| ID | Section | Frame in the layout | Rendered size (approx.) | Source verdict | Recommended option |
|---|---|---|---|---|---|
| IMG-HERO-01 | Hero | 5:4, right column, 16px radius, cream background | ~554 × 443 px desktop; full width below the copy on mobile | AI lifestyle appropriate (licensed stock or the client's own licensed hero is equally valid) | Option 1 |
| IMG-PROVIDER-01 | Meet Nick Yendrey | 3:4 portrait, left column, 16px radius | ~379 × 505 px desktop; max 260 px wide on mobile | **REAL PROVIDER IMAGE PREFERRED** (required) | Real portrait; no AI option is a substitute |
| IMG-HERITAGE-01 | Family-owned aside | ~15:16 thumbnail, 12px radius, with a factual caption | ~120 × 128 px | **REAL ARCHIVAL IMAGE REQUIRED** | Real 1966 photo; Option 3 only if it is unavailable and the caption changes |
| IMG-PRODUCT-01 | Hearing options | 4:3, sticky left column, 16px radius | ~473 × 355 px desktop | **REAL MANUFACTURER IMAGE PREFERRED** (licensed Signia or Starkey asset) | Real render; fallback Option 3 |
| IMG-CLINIC-01 | Find our Victoria office | 4:3, under the address card, 16px radius | ~480 × 360 px desktop | **REAL CLINIC / GBP IMAGE PREFERRED** (required) | Real photo; no AI option is a substitute |

**Result:** 5 placeholders, 4 where real imagery is preferred, 1 where AI-generated imagery is appropriate.

---

## 1. Shared art direction (applies to every prompt)

**Visual language, drawn from the live site and the design system.** The client's site uses natural-light, real-life photography (adults with family, a woman playing guitar in headphones, a hearing test in progress, a warm clinic corner with orange chairs and a teal door). This page's direction is "warm editorial healthcare": cream and white surfaces, navy ink, one restrained peach accent. Images should sit comfortably on `#fdf4ed` and white without feeling clinical.

| Element | Direction |
|---|---|
| Palette mood | Navy `#051c3b` and clear blue `#12639a` in wardrobe or objects, warm cream `#fdf4ed`, peach `#f6c8a4` in highlights. No saturated or neon colors, no heavy teal/orange grade. |
| Light | Soft, directional natural window light, slightly warm. Gentle shadows, no flash look, no heavy HDR. |
| Photography feel | Documentary-leaning editorial, 35–85 mm full-frame look, shallow-to-moderate depth of field, fine film-like grain at most. |
| People | Adults only. Natural expressions, mid-moment rather than posed. Real skin texture and age (lines, pores), no beauty retouching. Casting should reflect a South Texas community without tokenizing; leave ethnicity unspecified in prompts and review results for natural variety. |
| Hearing aids | Rarely visible. AI tools often distort ears and small devices. Where a device appears, it must be unbranded, small, anatomically plausible and checked closely before use. |
| Hands and ears | Five natural fingers, correct proportions; ears covered by hair or turned away unless the shot is about a device. |
| Text and marks | No readable text, no logos, no signage lettering, no manufacturer marks, no watermarks. |
| Claims | No before-and-after implication, no depiction of a specific medical procedure, nothing implying a real patient, a real clinic or a guaranteed outcome. |

**Standing rule.** AI images may illustrate a feeling or a situation. They may not stand in for the Victoria office, Nick Yendrey, Brown's history or a specific product.

**Shared "avoid" list (repeated in condensed form inside each prompt so each prompt is paste-ready):** stock-photo gloss, exaggerated smiles, people looking at the camera, over-posed hands, plastic skin, clutter, extra fingers, distorted ears, hospital imagery, stethoscopes, white coats unless specified, embedded text, logos, watermarks, saturated colors.

**Generation guidance.** Generate at roughly 2× the largest rendered size and at least 1.5× the stated crop so the page can crop safely. Export as high-quality JPEG/WebP; review at 100% for hands, ears, teeth and eyes before approval.

---

## IMG-HERO-01 — Hero

### 1. Placeholder Purpose

The hero must show a *human possibility*: easier, more relaxed conversation. It is the emotional opener for the headline "Hearing aid help in Victoria, TX, for easier everyday conversations." The visitor should feel recognition and hope, not shame or alarm, and should read the scene as ordinary life rather than a clinic ad. It supports conversion by making the benefit tangible before the visitor reads a word of the process, and it leaves the service and city to the headline. It opens the page's story arc (possibility, then familiar difficulty, then local proof). It is illustrative only and must not suggest the people are Brown patients.

### 2. Recommended Source Type

**AI-generated lifestyle/editorial image appropriate** (or licensed stock, or the client's existing licensed hero from brownhearingcenters.com if they approve its reuse).

Why: the hero's job is emotional, not evidentiary. Authentic provider and clinic proof is handled lower on the page. A staged AI "consultation" would imply a real clinic interaction, so none of these options shows one.

### 3. Recommended Composition

- **Aspect ratio:** 5:4 landscape (generate at 2000 × 1600 or larger).
- **Subject position:** primary subject right of center (about 60–70% across), turned slightly toward the left so her gaze leads the eye back to the headline and buttons.
- **Safe area:** faces within the central 70% horizontally and the upper 65% vertically. Nothing essential in the outer 12%.
- **Negative space:** soft, calm background on the left third; no busy detail near the frame edge.
- **Lighting and mood:** warm natural window light, calm, content, unhurried.
- **Desktop crop:** full 5:4 inside a 16px-radius frame next to the copy.
- **Mobile crop:** same 5:4 below the buttons and rating badge; can tighten to roughly 1:1 centered on the faces without losing the story.
- **Constraints:** no text overlay is planned, no hearing aids required, nothing that reads as medical.

### 4. Option 1 — Lifestyle / Outcome: "Kitchen-table connection"

**Visual concept:** an unposed moment of easy connection between two adults at a sunlit table. It speaks directly to "easier everyday conversations" and to the page's welcome to family members.

**Full AI image-generation prompt:**

Authentic lifestyle photograph, 5:4 landscape, of two adults sharing an easy, warm conversation across a sunlit kitchen table in a modern but lived-in South Texas home. In the right-center of the frame, a woman in her late 60s with silver-brown, chin-length hair that loosely covers her ears, wearing a soft navy cardigan over a cream top, leans slightly forward with a genuine, mid-laugh expression and attentive eyes, her gaze turned toward her companion on the left. Her companion, an adult daughter in her early 40s in a muted blue linen shirt, sits left of center, shown in three-quarter back view and slightly out of focus, one hand gesturing naturally as she speaks. On the table: two plain ceramic mugs, a glass pitcher of water, a small bowl of lemons. Soft window light from the camera-left, warm color temperature, gentle shadows, cream and peach tones in the walls, a calm out-of-focus background with a hint of a garden window. Shot at eye level with an 50 mm lens at f/2.8, shallow depth of field, documentary editorial realism, natural skin texture with fine lines and pores, subtle film grain. Palette: navy, soft blue, warm cream, peach highlights. Keep the left third of the frame calm and uncluttered; faces within the central 70%. Avoid: looking at the camera, exaggerated smiles, stock-photo posing, visible hearing aids, distorted ears or hands, extra fingers, plastic skin, text, logos, watermarks, clutter, saturated colors.

### 5. Option 2 — Community / Local Life: "Morning on the patio"

**Visual concept:** a wider, social scene of four adults chatting outdoors, showing that better hearing is about taking part in community life, not only one-to-one talk. This option is more atmospheric and local.

**Full AI image-generation prompt:**

Candid documentary-style photograph, 5:4 landscape, of four adults aged roughly 55 to 75 chatting around a long wooden table on a shaded covered patio on a pleasant Saturday morning in a Gulf Coast Texas town, with a large live oak and soft green lawn behind them. In the right-center foreground a man in his early 70s with short white hair, wearing a pale blue linen shirt, leans in with a relaxed, engaged smile, listening to a friend speaking just outside the left of the frame. Two women and another man laugh quietly in the mid-ground, none looking at the camera. Coffee cups, a plate of pastries and a pitcher of iced tea on the table. Dappled late-morning light filtering through the live oak, warm and gentle, soft shadows. Shot at 35 mm, f/4, eye level, natural candid moment, moderate depth of field that keeps the main man sharp and the others softly readable. Palette: navy and soft-blue clothing, warm cream and peach tones, muted greens. Leave calm space along the left edge; main subject right of center; all faces inside the central 75%. Authentic skin texture, natural proportions, no retouched gloss. Avoid: posed group photo, looking at the camera, exaggerated laughter, visible hearing aids, distorted hands or ears, text, logos, signage, watermarks, neon or oversaturated color, cluttered background.

### 6. Option 3 — Premium Editorial / Conceptual: "Listening close-up"

**Visual concept:** a tight, quiet frame of attentive listening: a profile, soft focus, coffee cups in the foreground. It is the most distinctive and most restrained option and plays on the idea of being fully present in a conversation.

**Full AI image-generation prompt:**

Premium editorial photograph, 5:4 landscape, tight composition of a woman in her late 50s to early 60s in profile, positioned right of center, listening attentively with a soft, calm half-smile, her gaze directed to the left toward an out-of-focus companion whose shoulder and one gesturing hand blur into the left foreground. She wears a deep navy knit sweater, her silver-brown hair worn loosely over her ear. In the foreground, two ceramic cups of coffee are softly blurred on a pale wooden table. Background: a cream wall with a gentle band of blue window light, almost no detail. Soft, directional window light from the left, warm tone, delicate highlights on skin showing real texture. Shot on an 85 mm lens at f/1.8 for a very shallow depth of field, intimate, quiet, minimal, strong clear focal point on the eye and cheek, generous negative space in the upper-left. Palette: navy, soft blue, warm cream, a trace of peach. Authentic skin, fine lines, no beauty retouching. Avoid: looking at the camera, heavy vignette, glamour lighting, visible hearing aids, distorted ears or hands, text, logos, watermarks, saturated color, clutter.

### 7. Recommended Option

**Option 1.** It maps most directly to the headline ("everyday conversations") and to the copy's family-welcome line. It is warm and legible at 335 px mobile width, uses only two figures (lower AI-artifact risk than Option 2), and its calm left third keeps the copy as the first read. Option 3 is more distinctive but depends on fine detail that is harder to read on a phone. Option 2 is the richest scene but the busiest and the most exposed to hand and face errors.

### 8. Real-Image Note

AI imagery is appropriate here. If the client prefers a real photo, the licensed hero on brownhearingcenters.com (an older woman and a child in a whispered exchange) would give brand continuity. Confirm the license and that it suits the client's ads. Whatever is used must be treated as illustrative, not as a Brown patient.

---

## IMG-PROVIDER-01 — Meet Nick Yendrey

### 1. Placeholder Purpose

This image answers "who will help me?" and puts a real face next to the name Nick Yendrey, Hearing Instrument Specialist. It is the strongest local proof asset after the Google reviews. The visitor should feel they are meeting a specific, approachable person. It anchors the trust peak of the page (portrait, then reviews).

### 2. Recommended Source Type

**REAL PROVIDER IMAGE PREFERRED, and effectively required.**

A generated person placed beside "Meet Nick Yendrey" would be a fabricated provider identity, which is never acceptable. The three AI options below depict no face and no person who could be mistaken for Nick. They exist only as non-identifying fallbacks; if the real portrait is unusable, the better Step 5 decision is to remove the frame, not to fill it with AI.

### 3. Recommended Composition

- **Aspect ratio:** 3:4 portrait (request an original of at least 1200 × 1600 px; the website copy at 600 × 800 is below retina size for a ~379 px column).
- **Subject position (real portrait):** head and shoulders to mid-torso, eyes at about the upper third line, a little headroom, no tight face crop.
- **Lighting and mood:** soft natural window light, warm and approachable, neutral background in cream, soft blue or the Victoria office interior.
- **Desktop crop:** full 3:4 in the left column, about 379 × 505 px.
- **Mobile crop:** same 3:4, capped at 260 px wide; keep the face central.
- **Constraints:** no avatar-style crop, no heavy retouching, wardrobe that is neutral and professional; no other branch's interior behind him.

### 4. Option 1 — Provider / Patient Interaction: "Hands across the desk"

**Visual concept:** the explanation moment told through hands only: a specialist's and a patient's hands over a blank printed chart. It shows patient, personal attention without any identifiable person. Fallback only.

**Full AI image-generation prompt:**

Warm editorial photograph, 3:4 portrait, close shot of two pairs of hands over a light wooden desk: on the right an adult specialist's hand in a plain gray sleeve holding a pen and gently pointing at a blank printed chart with abstract soft-grey curves and no legible text, and on the left an older adult's hands, relaxed and attentive, resting near the paper. A small ceramic cup of tea at the edge of the frame. No faces, no heads, no torsos visible. Soft natural window light from the upper left, warm tone, gentle shadows, shallow depth of field with the pointing hand sharp and the background softly blurred. Shot at 50 mm, f/2.8, slightly elevated angle. Palette: cream, soft blue, navy, a trace of peach. Realistic skin texture and age, natural five-finger hands. The frame should read as a calm, patient explanation. Avoid: faces, identifiable people, white coats, stethoscopes, medical props, text, numbers, logos, watermarks, extra fingers, plastic skin, saturated color.

### 5. Option 2 — Environment / Detail: "Window light and a waiting chair"

**Visual concept:** a quiet, human-scale detail of a welcoming consultation corner. It is generic and is not the Victoria office, so it must never be captioned as such.

**Full AI image-generation prompt:**

Calm editorial interior photograph, 3:4 portrait, a corner of a bright, welcoming professional consultation space: a simple upholstered chair in muted navy fabric angled toward a small round side table holding a glass of water and a small plant, beside a tall window with sheer curtains letting in soft morning light. Pale cream wall, light wood floor, no wall art, no signage, no logos. Soft natural light from the right, warm, with gentle falloff, shallow depth of field, shot at 40 mm, f/3.5, straight-on slightly low angle. No people. Palette: navy, cream, soft blue, warm peach highlights. Minimal, uncluttered, serene. Avoid: people, medical equipment, hospital look, text, logos, brand marks, saturated colors, clutter, distortion of furniture or windows, watermarks.

### 6. Option 3 — Premium Editorial / Conceptual: "Conversation, abstracted"

**Visual concept:** a brand-colored editorial illustration of overlapping speech-like waves on cream. It is conceptual, non-photographic and makes no factual claim.

**Full AI image-generation prompt:**

Refined flat editorial illustration, 3:4 portrait, abstract overlapping rounded speech-wave shapes in layered navy (#051c3b), clear blue (#12639a) and soft peach (#f6c8a4) on a warm cream (#fdf4ed) background. Shapes echo gentle sound waves and conversation bubbles, arranged with generous empty space in the upper third, crisp edges with a very subtle paper-grain texture. Calm, modern and warm, with a clear focal cluster slightly left of center, no gradients beyond a faint tonal shift, no drop shadows. No people, no faces, no letters, no numbers, no logos, no watermarks. Avoid: clip-art style, cartoon figures, ears, medical symbols, neon colors, busy patterns, text of any kind.

### 7. Recommended Option

**None of the three options should replace the real portrait.** Use Nick's actual photo. If it cannot be used, the least-misleading fallback is Option 3 with the section heading unchanged only if it is not visually paired with a stand-in person; Step 5 should instead consider removing the frame. Option 1 is the next best (hands only) but still suggests an interaction that did not happen.

### 8. Real-Image Note

**REAL PROVIDER IMAGE PREFERRED.**

- **Ideal image:** a fresh portrait of Nick at the Victoria office, mid-torso, warm window light, soft smile, relaxed posture. If he is not in a uniform, a plain navy, blue or gray top works with the palette.
- **Source:** the client's portrait (RESEARCH.md section 9, `Nick-Yendrey-600x800.jpeg`, already attempted in the page) or a new shoot. Ask for the original large file.
- **Why it matters:** every named review praises Nick, and the page asks visitors to meet him. An authentic face is the visual proof of the "local, patient guidance" promise.
- **AI role:** fallback only, and only as a non-person visual.

---

## IMG-HERITAGE-01 — Family-owned aside (small thumbnail)

### 1. Placeholder Purpose

A small, credible detail that supports "Family owned since 1962. Brown Hearing Centers opened its first office in Victoria in 1962." The visitor should sense lasting roots, not read a long history. The image is small (about 120 px wide) and works as a quiet trust marker rather than a feature.

### 2. Recommended Source Type

**REAL ARCHIVAL IMAGE REQUIRED.**

The caption states a specific fact: "The founder's father painting an early office sign, c. 1966." An AI image cannot be that photograph, and generating a "vintage" look-alike would fabricate company history. The three AI options below drop the historical claim entirely and are fallback only, with a changed caption.

### 3. Recommended Composition

- **Aspect ratio:** about 15:16 (source is 960 × 1024).
- **Orientation:** near-square portrait.
- **Subject position:** keep the full sign and the painter's hands visible; do not crop to a sliver. At 120 px width, only a single clear subject survives.
- **Lighting and mood:** original archival tone, warm and slightly faded. Do not over-restore or recolor.
- **Desktop and mobile crop:** identical, about 120 × 128 px; on narrow screens the thumbnail sits above or beside the text.
- **Constraints:** keep the existing factual caption only with the real photo.

### 4. Option 1 — Craft / Handmade: "Brushwork"

**Visual concept:** abstract hand-painted brushwork suggesting the craft of an old shop sign, with no letters.

**Full AI image-generation prompt:**

Close-up editorial photograph, 15:16 portrait, a hand-held flat paintbrush with navy paint resting against the edge of a smooth cream-painted wooden panel, with two or three bold, clean, abstract brush strokes in navy and one in soft peach. No letters, numbers, or symbols anywhere. Soft natural side light, warm tone, shallow depth of field with the bristles sharp, gentle paint texture, slight vintage warmth but modern and clean. Palette: navy, cream, peach. Centered subject with simple empty margins. Avoid: legible lettering, logos, signage text, faces, over-aged or distressed effects, saturated color, watermarks.

### 5. Option 2 — Object / Texture: "Blank oval sign"

**Visual concept:** a weathered wooden shop sign blank, hinting at a small family business without naming it. It deliberately avoids copying Brown's logo.

**Full AI image-generation prompt:**

Editorial still-life photograph, 15:16 portrait, a plain, blank painted wooden shop-sign panel with a simple soft navy border and a cream center, leaning against a warm brick wall in gentle afternoon light. Completely blank: no lettering, no logo, no oval emblem, no symbols. Subtle natural wood grain and a tiny amount of honest wear, shallow depth of field, shot at 50 mm, f/4, slightly low angle. Palette: navy, cream, warm brick, soft peach highlight. Calm, minimal, timeless. Avoid: any text or numbers, logos, faces, heavy distress, grunge, saturated color, watermarks.

### 6. Option 3 — Premium Editorial / Conceptual: "Generations, hands only"

**Visual concept:** an older and a younger pair of hands resting together, a quiet metaphor for a family business passed down. No faces, so no one is implied to be a real family member.

**Full AI image-generation prompt:**

Intimate editorial photograph, 15:16 portrait, an older adult's hands with natural lines and a simple ring resting gently over a younger adult's hands on a pale wooden table, soft out-of-focus background of a warm cream wall. Soft side light from a window, warm tone, delicate shadows, shot at 85 mm, f/2.2, shallow depth of field, focus on the hands. Sleeves in muted navy and soft gray. No faces or heads in frame. Realistic skin, natural five-finger hands. Palette: navy, cream, warm peach. Avoid: faces, jewelry that looks like a logo, stylized or glossy retouching, text, logos, watermarks, extra fingers, saturated color.

### 7. Recommended Option

**Use the real 1966 photograph.** If it cannot be used, Option 3 is the most legible at 120 px and carries the "family" idea. Whichever fallback is chosen, replace the caption with something non-historical (for example, remove it) and keep the "Family owned since 1962" copy beside it, because the copy rests on the sources and the image would not.

### 8. Real-Image Note

**REAL ARCHIVAL IMAGE PREFERRED.**

- **Ideal image:** the captioned c. 1966 sign-painting photo from the About page (RESEARCH.md section 9, `PICTURE-1-960x1024.jpg`).
- **Source:** the client's website assets. Confirm they approve its reuse on a campaign page.
- **Why authenticity matters:** this is real archival evidence of the company's origins; its credibility is the whole point.
- **Do not identify** the uncaptioned vintage couple photo as Lee and Dorothy Brown without client confirmation (Awaiting_Client.md #12).
- **AI role:** fallback only, never a historical substitute.

---

## IMG-PRODUCT-01 — Hearing options

### 1. Placeholder Purpose

The hearing-options section explains selection, everyday features and hands-on help. This image makes the technology tangible in a restrained way. The visitor should feel that modern hearing aids are small, approachable and manageable, and that the page is about their daily life, not a device catalogue. It sits beside, not above, the three benefit themes and the payment callout, so it supports rather than competes with the service and outcome story.

### 2. Recommended Source Type

**REAL MANUFACTURER IMAGE PREFERRED** (licensed Signia or Starkey render or lifestyle asset), not a clinic image.

Why: Brown carries Signia and Starkey (S11). Real renders show accurate models, but they need a rights check and accurate model context, and the page must not imply current stock (DESIGN_SYSTEM.md). AI renderings of hearing aids are the most error-prone part of this whole set (shape, ear placement, controls), so the options below avoid showing a recognizable model.

### 3. Recommended Composition

- **Aspect ratio:** 4:3 landscape (generate at 1800 × 1350 or larger).
- **Subject position:** centered or slightly left, one clear focal point, generous calm space.
- **Lighting and mood:** soft, warm, clean; premium but approachable.
- **Desktop crop:** full 4:3 in the left column, about 473 × 355 px, sticky beside the benefit list.
- **Mobile crop:** full-width 4:3; keep the subject in the central 70%. Note for Step 5: at tablet widths this frame becomes very wide, so cap its width.
- **Constraints:** unbranded, no model names, no battery-hour or feature text, nothing implying a specific device is stocked in Victoria.

### 4. Option 1 — Lifestyle / Outcome: "Phone call with family"

**Visual concept:** hands holding a smartphone mid video call at a kitchen counter, illustrating "calls and streaming" and everyday use with no hearing aid shown.

**Full AI image-generation prompt:**

Authentic lifestyle photograph, 4:3 landscape, close-medium shot of an adult in their mid 60s holding a smartphone in both hands at a sunlit kitchen counter, the phone screen showing an out-of-focus, abstract video-call image with no legible UI or faces, a warm smile just visible at the edge of the frame at the upper right, hair loosely covering the ears. Navy cardigan sleeve, a cream mug beside a small plant. Soft natural window light from the left, warm tone, gentle shadows, shot at 50 mm, f/2.8, shallow depth of field with the phone and hands sharp. Palette: navy, cream, soft blue, a trace of peach. Calm, unhurried, believable. Avoid: visible hearing aids, readable text, logos, distorted hands or ears, extra fingers, glossy screens with fake apps, saturated color, watermarks.

### 5. Option 2 — Patient / Provider Interaction: "Charging lesson"

**Visual concept:** hands guiding hands as a small, generic, unbranded hearing aid is placed in a charging case, tied to "hands-on help learning your hearing aids." Higher artifact risk; inspect closely.

**Full AI image-generation prompt:**

Warm editorial close-up photograph, 4:3 landscape, a specialist's hand in a plain gray sleeve guiding an older adult's hand as a small, plain, unbranded receiver-in-canal style hearing aid in a pale neutral color is set into an open round charging case on a light wooden table. No faces, no heads. A simple blank tablet in the soft-focus background. Soft window light from the upper left, warm, shallow depth of field with the device and fingers sharp, shot at a 60 mm macro-style perspective, f/3.2. The device is generic, with natural proportions, no buttons or logos visible. Palette: cream, navy, soft blue, trace of peach. Avoid: brand names or logos, text, over-detailed or wrong device geometry, extra fingers, plastic skin, faces, saturated color, watermarks.

### 6. Option 3 — Premium Editorial / Conceptual: "Still life on linen"

**Visual concept:** a quiet, top-three-quarter still life of a generic pair of hearing aids and a charging case on warm linen. It is the cleanest, most premium option and the easiest to inspect for errors.

**Full AI image-generation prompt:**

Premium editorial product photograph, 4:3 landscape, a pair of small, plain, unbranded receiver-in-canal style hearing aids in a soft neutral color resting beside an open round charging case on a warm cream linen surface, a single small sprig of green foliage out of focus in the upper left corner. Elevated three-quarter angle, soft diffused window light from the left, warm tone, delicate shadows and a gentle peach reflection, shallow depth of field, shot at 90 mm, f/4. Clear single focal point, generous calm negative space on the right, minimal and clean. Palette: cream, navy accent in the case lining, soft blue, peach. Devices are generic and anatomically plausible, with no logos, no buttons with text, and no brand-specific shapes. Avoid: brand marks, text, numbers, clutter, glossy ad gradients, floating or duplicated parts, distorted geometry, saturated color, watermarks.

### 7. Recommended Option

**Prefer a real licensed Signia or Starkey asset.** If AI is used as a fallback, **Option 3**: it keeps attention on "options" without faking an interaction, and a still life is the easiest to check at 100% for device errors. If the devices render poorly, **Option 1** is the safest AI choice because it shows no device at all and still speaks to phone connectivity. Option 2 is the strongest story but the highest risk.

### 8. Real-Image Note

**REAL MANUFACTURER IMAGE PREFERRED.**

- **Ideal image:** a clean render or lifestyle asset from the manufacturer's official media kit showing a hearing aid in a style Brown carries, ideally with a charging case.
- **Source:** the Signia or Starkey dealer or marketing portal, or the assets already inventoried in RESEARCH.md (S14, S26). Confirm usage rights and how the page should label them.
- **Why it matters:** product accuracy. A wrong device shape would misrepresent what the visitor can buy.
- **AI role:** fallback only, labeled illustrative; never name a brand or model beside an AI-generated device.

---

## IMG-CLINIC-01 — Find our Victoria office

### 1. Placeholder Purpose

The location section answers "where would I go?" This image shows the real destination, so the visitor can recognize the building and feel comfortable arriving. It is the single most location-specific trust image on the page. The map and address do the logistics; the photo does the reassurance.

### 2. Recommended Source Type

**REAL CLINIC / GBP IMAGE PREFERRED, and effectively required.**

Any AI "clinic" would be a fictional office shown beside a real address, which is exactly what must never happen. The three options below deliberately avoid depicting a facility and are fallback only. If no real photo arrives, Step 5 should consider removing the frame; the map, address and Get Directions button already carry the section.

### 3. Recommended Composition

- **Aspect ratio:** 4:3 landscape (request at least 1600 × 1200).
- **Ideal shots:** (a) daylight exterior showing the Heritage Mark building and the entrance toward Suite 200, (b) the suite entrance inside the building, (c) the waiting room. Choose the one that helps a first-time visitor find the door.
- **Lighting and mood:** daylight, straight-on, uncluttered, welcoming.
- **Desktop crop:** full 4:3 under the address card, about 480 × 360 px.
- **Mobile crop:** full-width 4:3; keep the entrance or signage in the central 70%. Note for Step 5: at tablet widths this frame becomes very wide, so cap its width.
- **Constraints:** no other branch's interior, no people without permission, no staged patients.

### 4. Option 1 — Lifestyle / Outcome: "Bringing someone along"

**Visual concept:** two adults, a parent and an adult child, walking side by side toward a soft-focus glass entrance. It speaks to the visit and the family welcome rather than faking the building.

**Full AI image-generation prompt:**

Warm documentary-style photograph, 4:3 landscape, an older woman in her early 70s and her adult son in his mid 40s walking side by side along a clean paved path in afternoon sun toward a soft-focus glass-doored professional building entrance, seen mostly from behind and three-quarter angle, faces not clearly visible. She wears a light navy jacket, he wears a plain blue shirt, his hand lightly at her elbow. The building is deliberately generic and out of focus: no signage, no lettering, no logos, no distinctive architecture. Low warm sun from the left, soft shadows, shot at 50 mm, f/3.2, eye level, shallow depth of field. Palette: navy, soft blue, cream, peach light. Calm and reassuring. Avoid: recognizable building, signage text, logos, faces toward the camera, exaggerated posing, distorted hands or legs, saturated color, watermarks.

### 5. Option 2 — Environment / Detail: "Quiet waiting-area detail"

**Visual concept:** a generic waiting-area corner suggesting a calm, unhurried visit. It is explicitly not the Victoria office.

**Full AI image-generation prompt:**

Calm editorial interior photograph, 4:3 landscape, a corner of a small, bright professional waiting area: two armchairs in muted navy and soft gray fabric on either side of a low wooden side table with a glass of water and a small plant, beside a window with sheer curtains. Pale warm walls, light wood floor, no wall art, no signage, no reception sign, no logos. Soft morning light from the right, warm tone, gentle shadows, shot at 35 mm, f/4, slightly raised angle. No people. Palette: navy, cream, soft blue, peach. Minimal and uncluttered. Avoid: people, medical equipment, hospital look, text, logos, brand marks, distorted furniture, saturated color, watermarks.

### 6. Option 3 — Premium Editorial / Conceptual: "A sense of place"

**Visual concept:** a quiet South Texas landscape at golden hour with live oaks, evoking the region rather than the building. It is the most atmospheric and least informative option.

**Full AI image-generation prompt:**

Premium editorial landscape photograph, 4:3 landscape, a wide South Texas coastal-plain scene at late afternoon: a mature live oak with spreading branches on the left, a soft green field, a faint line of low trees on the horizon, warm golden light and a pale blue and peach sky. Natural, serene, uncluttered, with calm open space across the right half. No buildings, no roads with signs, no people, no vehicles. Shot at 35 mm, f/8, eye level, gentle atmospheric depth. Palette: soft blue, warm cream, peach, muted green with navy-toned shadows. Avoid: buildings, signage, text, logos, people, oversaturated sunset color, HDR look, watermarks.

### 7. Recommended Option

**Prefer a real photo of the Victoria office.** If AI is the only choice, **Option 1**: it supports "bring a family member" and the visit itself without pretending to show the facility, and it reads clearly on mobile. Options 2 and 3 are weaker because a generic room can be mistaken for the office, and a landscape does not answer "where do I go?"

### 8. Real-Image Note

**REAL CLINIC / GBP IMAGE PREFERRED.**

- **Ideal images:** a daylight exterior of the Heritage Mark building and entrance, the Suite 200 door or wayfinding inside, and the waiting room (Google reviews confirm a waiting room exists).
- **Source:** the Victoria Google Business Profile photos (the profile has photos; originals are not yet supplied) or a quick shoot by the office. This is Awaiting_Client.md item #4.
- **Caution on the live site's clinic photo:** the homepage "Schedule" card shows a warm office with orange chairs and a teal door. Do not use it for Victoria unless the client confirms it is the Victoria office.
- **Why it matters:** an authentic photo is the most location-specific trust cue on the page.
- **AI role:** fallback only, never as the clinic itself.

---

## Final strategy review

1. **Purpose.** Each image has a reason: hero (possibility), provider (who), heritage (roots), product (options made tangible), clinic (where). No section received an image just for decoration.
2. **Brand consistency.** All prompts use the navy, blue, cream and peach palette and the warm editorial look in DESIGN_SYSTEM.md.
3. **Search intent.** Visuals support the approved theme (local hearing-aid help and assessment first). None shows a diagnosis, a procedure or an audiologist environment.
4. **Outcomes.** Benefit is shown as everyday connection, never as a result of treatment; no before/after, no restored-hearing implication.
5. **Credibility.** AI is limited to the hero and to non-identifying fallbacks. Provider, history, product and clinic are explicitly real-first.
6. **Distinct options.** Every set differs in kind (for example, hero: pair, group, close-up; clinic: arrival, interior detail, landscape), not in minor styling.
7. **Layout.** Safe areas, gaze direction, negative space and desktop/mobile crops are tied to the real frames and sizes in `index.html`.
8. **Repetition.** Subject matter varies across the page (adults in conversation, a portrait, archival photo, a device, a place); the two still lifes (product and provider fallback) are different in kind.
9. **Misleading representation.** No generated person is paired with a real name, no generated room with a real address, and no generated history with a factual caption.

---

## Flags and recommendations for Step 5

1. **Missing authentic assets (priority):** (a) larger original of Nick's portrait, (b) Victoria exterior, entrance and waiting-room photos from GBP or the office, (c) client approval to reuse the 1966 archival photo, (d) licensed Signia or Starkey product images, (e) client sign-off on the hero image source.
2. **Portrait resolution.** The 600 × 800 website portrait will look soft on retina screens at ~379 px wide.
3. **Tablet frame size.** Below 960 px the product frame and the clinic frame stack to full width and become very large; consider a max-width in the rebuild.
4. **Heritage thumbnail.** At 120 px the archival photo carries little detail; consider whether the caption image earns its place, or a slightly larger size.
5. **Clinic frame.** If no real clinic photo is supplied, consider dropping the frame rather than using AI.
6. **AI-image policy.** Confirm the client's comfort with any AI-generated hero image; keep it non-evidentiary and free of visible hearing aids.
7. **Visual opportunities (recommendation only).** None needed. Recognition, process, FAQ, reviews and the final call-to-action band work better type-led, as the strategy documents already intend.
8. **Sync rule.** If a section is moved, removed, redesigned or given a different visual purpose in Step 5, update the matching entry here.
