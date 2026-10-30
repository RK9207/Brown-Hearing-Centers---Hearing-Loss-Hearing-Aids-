# Awaiting_Client.md — Brown Hearing Centers | Hearing Loss / Hearing Aids | Victoria, TX

**Prepared:** October 30, 2026
**Purpose:** Open questions that the website, Google Business Profile and public sources could not answer. Each item has a safe default so the build can continue without waiting; the default is replaced once the client answers.
**Evidence base:** RESEARCH.md (source codes in brackets refer to its §0 Source Key).

---

## A. Questions for the client

### Priority 1 — affects headline, trust or CTA copy

| # | Question | Why it matters | What we found | Safe default until answered |
|---|---|---|---|---|
| 1 | Can we advertise a **free hearing test / free hearing evaluation**, or only a free consultation / complimentary hearing screening? | Strongest offer lever for the hero and CTAs | Website says only "free consultation" and "complimentary hearing screening" (S1, S34). Brown-written third-party profiles and the Google cover graphic suggest a free test/check (T8, G2), but the wording is inconsistent | Use **"Free consultation"** / **"Complimentary hearing screening"** |
| 2 | Is **Matthew A. Toohey, BC-HIS** regularly scheduled at the Victoria office, and may we feature him? | Founder's grandson serving the city where the company started — strong heritage and credential hook | His bio lists the Victoria Office (S35), but all Victoria Google reviews name Nick only (G1) | Feature **Nick Yendrey** as the Victoria specialist; mention Matthew only as company leadership, if at all |
| 3 | Which **insurance plans** (if any) does the Victoria office accept? Should insurance appear on the page? | Common objection; possible FAQ | Website is silent: its "Billing & Insurance Information" section lists only CareCredit and Cherry (S33). Only third-party hints (T1, T9) | No insurance claims; lead with **CareCredit and Cherry financing** |
| 4 | Can you share **photos of the Victoria office** (exterior, waiting room, testing room) or the original Google Business Profile photos? | Real local imagery builds trust; none exists on the website | Victoria page has no images; GBP has photos we can't download (G2) | Use Nick's headshot, brand imagery and the archival heritage photos |

### Priority 2 — affects location, FAQ or supporting sections

| # | Question | Why it matters | What we found | Safe default until answered |
|---|---|---|---|---|
| 5 | Where exactly do patients go inside **Heritage Mark** (floor, suite signage, reception)? Is there **parking**, and is the suite accessible? | Directions and "what to expect" copy | Site: "Located Inside Heritage Mark, Inc." (S24); Google lists "#200" (G2). No parking/access info anywhere | "Located inside the Heritage Mark building, Suite 200" + Get Directions button |
| 6 | Please confirm the Victoria **hours**: Mon/Wed/Fri 9–12 & 1–4, closed Tue/Thu? Are **phones answered Mon–Fri from 8 am**? | Hours block and "call us" expectations | GBP shows Mon/Wed/Fri 9–12 & 1–4 (G2); older site data said Mon–Fri 9–5 (T4); GBP cover graphic hints phones open Mon–Fri 8 am | Show GBP hours, or omit hours and route visitors to call/book |
| 7 | Are **house calls** and **remote (telehealth) care** offered to Victoria-area patients? | Convenience/mobility objection; FAQ | Offered company-wide (S1, S2, S10); not confirmed for Victoria | Don't mention, or keep wording company-level |
| 8 | Which **nearby towns** does the Victoria office serve (e.g., Cuero, Edna, Goliad, Port Lavaca, Yoakum)? | Local relevance; possible "serving…" line | Testing centers exist in these towns (S23), but testing-center pages show no link to Victoria (S32) | No "serving [towns]" line |
| 9 | Is the **Victoria Chamber of Commerce** membership current, and may we show the logo? | Local trust badge | Active member listing at the Victoria address (T7, last updated Feb 2024); not on the Awards page | No Victoria Chamber badge |
| 10 | Are the **service plans** for hearing aids bought elsewhere (Bronze $299 / Silver $499 / Gold $599) current and offered in Victoria? | Possible offer for existing hearing aid wearers | Found on an unlinked site page whose office list omits Victoria (T3) | Don't mention plans or prices |

### Priority 3 — accuracy checks and nice-to-haves

| # | Question | Why it matters | What we found | Safe default until answered |
|---|---|---|---|---|
| 11 | For **tinnitus**, does Brown offer only hearing aids with tinnitus-masking features, or also tinnitus retraining / counseling? | Tinnitus FAQ accuracy | The tinnitus page lists several treatments generally, without saying Brown provides them all (S25) | Mention masking-capable hearing aids + evaluation only |
| 12 | Is the vintage couple photo (About page thumbnail) **Lee and Dorothy Brown**? May we use it? | Heritage section | Uncaptioned (G2); founders named in T1 | Use the captioned 1966 sign-painting photo (S2) instead |
| 13 | Any **trial period, return policy or warranty** terms we can state? | Purchase-risk objection | None published; demos available in-office per one review (G1); repair page mentions manufacturer warranties (S9) | No trial/return/warranty claims |
| 14 | Does Nick hold **board certification (BC-HIS)** or other credentials beyond his license? | Provider credential line | Bio lists BBA/MBA only (S4); Texas requires a TDLR license to fit hearing aids (T11) | "State-licensed Hearing Instrument Specialist" |
| 15 | Is the client comfortable with **"AI" wording** for Starkey/Signia technology? | Tech section tone (some Onspire clients avoid AI language) | Manufacturer pages use AI language heavily (S14, S26) | Neutral wording, e.g., "advanced, rechargeable, Bluetooth-connected hearing aids" |
| 16 | Preferred **company scale wording**: "Since 1962", number of offices, number of locations? | Trust copy consistency | Site and third parties conflict: 11 / 15 offices; "hundreds" / "over 300" / 124 listed locations; BBB start date 1963 (S1, S2, S22, S23, T6, T10) | "Family-owned since 1962" with no counts |

---

## B. Internal items (Onspire — not for the client)

| # | Item | Status / default |
|---|---|---|
| I-1 | Privacy Policy link for the footer | Brief has a placeholder. Candidate: https://brownhearingcenters.com/privacy-policy/ (HIPAA-referencing, S29); confirm whether a campaign-specific policy is needed for the GHL form |
| I-2 | Value of `{{location.name}}` for the footer copyright | Confirm that the GHL sub-account resolves it to "Brown Hearing Centers" (spelling: Centers, not Centres) |
| I-3 | Keywords, ad groups, ad copy, promoted offer | Not supplied; Step 2B (KEYWORD_RESEARCH.md) pending |
| I-4 | GHL form embed iframe ID | Supplied as `inline-…`; Onspire standard is the `formEmbed-` prefix to avoid the GHL autoscroll bug — apply at build |
| I-5 | Button style, border radius, logo for a white sticky header | Not verifiable from text; visual check of the live site needed |

---

## C. Resolved (for reference — no client action needed)

| Item | Resolution | Source |
|---|---|---|
| Campaign phone number | 409-207-8726 is the tracking number; use it exclusively on the page | User confirmed |
| Google rating / review count | 4.9 ★, 51 reviews; 8 verbatim reviews captured | G1 |
| Victoria hours | Mon/Wed/Fri 9–12 & 1–4 per Google (confirmation requested in #6) | G2 |
| Walk-in vs appointment | Appointment-based; site never mentions walk-ins | S2, S22, S34 |
| Office type | Staffed in-person office with a waiting room | G1 |
| BBB status | Accredited since 2002, A+ rating | T6 |
