\# Design System — Brown Hearing Centers, Victoria

\#\# Status and design intent

Approved visual direction: \*\*warm editorial healthcare\*\*, serving Option A with early local proof. These are governing design recommendations derived from the supplied brand inputs, not claims that every component matches the live website's styling.

Read PAGE\_STRATEGY.md for section purpose/order and CONTENT\_DIRECTION.md for message/claim limits. The original \`Project Brief \- Brown Hearing Centres.md\` remains authoritative for supplied requirements and embeds. RESEARCH.md inventories source assets; no original clinic/review image files are present in the checkout at Step 3\.

Design for adults who need a readable, reassuring route through unfamiliar decisions. Use typography, authentic evidence, whitespace and a few deliberate emphasis moments. Avoid an institutional medical look, a device catalogue, repetitive cards and decorative animation.

\#\# Brand colors and functional usage

\| Token \| Value \| Role \|  
\| \--- \| \--- \| \--- \|  
\| Primary/action \| \#12639a \| Primary buttons, selected/focused accents, links where contrast passes \|  
\| Navy/ink \| \#051c3b \| Headings, body emphasis, footer/final CTA background \|  
\| Peach \| \#f6c8a4 \| Restrained accents, small process markers; never low-contrast text \|  
\| Cream \| \#fdf4ed \| Warm hero/supporting surfaces and visual relief \|  
\| White \| \#ffffff \| Main reading surfaces and primary-button text \|  
\| Body text \| \#26364a \| Proposed neutral for readable body copy \|  
\| Muted text \| \#526174 \| Proposed supporting text on white/light surfaces \|  
\| Border \| \#d6dfe5 \| Proposed structural separator; not sufficient alone for input/control boundaries \|  
\| Control border \| \#68788b \| Proposed visible boundary for custom controls on white/light surfaces \|

Supplied brand colors are fixed inputs; neutrals are design additions. Use blue with white text for primary actions; never peach for the main CTA. Navy text on cream/peach is preferred to pale text or low-opacity overlays.

Verify contrast in implementation: at least 4.5:1 for normal text, 3:1 for large text and required UI indicators. Star color must not be the sole communication of a rating. Use explicit numeric rating and text. Focus must remain visible on both dark and light backgrounds; use a dual light/dark ring when needed. Error/success states require text/icons, not color alone.

\#\# Typography

Headings: \*\*Lora\*\*, serif fallback such as Georgia. Body/interface: \*\*Open Sans\*\*, sans-serif fallback. Use only required weights, generally Lora 500/600 and Open Sans 400/600/700, subject to available font files. Confirm font licensing and load strategy; do not delay readable content behind external font loading.

\| Style \| Desktop target \| Mobile target \| Guidance \|  
\| \--- \| \--- \| \--- \| \--- \|  
\| H1 \| 48–56px \| 34–40px \| Line height 1.12–1.2; fluid sizing; avoid forced line breaks \|  
\| H2 \| 34–40px \| 28–32px \| Line height 1.2–1.3 \|  
\| H3 \| 22–26px \| 21–24px \| Clear hierarchy; may use Open Sans for compact utility labels \|  
\| Lead \| 20–22px \| 18–20px \| Line height approximately 1.5 \|  
\| Body \| 18px \| 17–18px \| Line height approximately 1.6; no tiny mobile body copy \|  
\| Supporting \| 16px \| 16px \| Keep important terms and trust information readable \|  
\| Buttons/nav \| 16–18px \| 16–18px \| Open Sans semibold \|

Use one H1, logical heading levels and sentence-case copy. Keep paragraphs approximately 55–70 characters wide. Do not place essential text inside images. Avoid tightly tracked all-caps paragraphs or extensive italics in testimonials.

\#\# Layout, grids and spacing

\- Main container: maximum 1,200px, centered. Narrow text/FAQ container: approximately 760px.  
\- Page gutters: 20px mobile, 24–32px tablet, 40px desktop. At 320px width, allow 16px where necessary to retain useful content space.  
\- Desktop: flexible 12-column grid; hero approximately 6/6, provider approximately 4/8, benefits approximately 5/7. Ratios serve content and may adjust after asset inspection.  
\- Breakpoint guidance: mobile below 768px; tablet 768–1023px; desktop 1024px and above. Let actual navigation/content fit determine the header-collapse point.  
\- Spacing scale: 4, 8, 12, 16, 24, 32, 48, 64, 80, 96px. Typical section padding 72–96px desktop, 48–64px mobile. Recognition is intentionally more compact.  
\- Heading-to-body spacing 16–24px; subsection gaps 32–48px; related controls 12–16px. Maintain proximity between a claim and its qualification.  
\- Single-column mobile reading order follows persuasion order, not arbitrary desktop placement. Avoid horizontal scrolling and fragile absolute positioning.  
\- Support 200% text resizing, narrow viewport reflow, keyboard use and comfortable touch interaction. Do not require hover to reveal essential content.

\#\# Components

\#\#\# Primary and secondary CTAs

Primary blue background, white semibold text, approximately 52–56px minimum height, 20–28px horizontal padding and 8px radius. Minimum touch target 44×44px, preferably at least 48px high. Keep text readable when it wraps.

Body label is Contact Us. Secondary phone action is a clearly labeled link/outlined control using the campaign number. On white/light surfaces use a verified-contrast darker blue hover; on navy surfaces a white/outlined secondary treatment may be used. Focus styles must be explicit. No scale/bounce effects, gradients or multiple equally dominant filled buttons in one cluster.

\#\#\# Sticky header and navigation

Desktop: white header, approximately 80–88px tall with a fine divider. Logo left, balanced in-page navigation, Schedule an Appointment phone treatment with visible 409-207-8726. Logo links to the company homepage as required; most other navigation remains within the landing page.

Mobile: logo plus Book Appointment trigger, with Explore This Page dropdown containing every in-page navigation link. Allow a second compact row rather than shrinking the logo or controls excessively. Menu toggle uses accessible expanded state and closes after selection. Offset anchors for sticky-header height. Include a skip link and visible focus.

Inspect header/footer logo SVGs before selecting versions. Do not recolor an unsuitable logo blindly or assume a light logo will work on white. Preserve aspect ratio and provide a descriptive accessible name.

\#\#\# Hero

Warm white/cream surface with navy type; strong service/location identifier, one main headline, short lead, action cluster and compact Google badge. Keep reading and action ahead of the main image on mobile. Avoid fixed viewport-height composition that clips content on short screens.

Desktop hero image target is approximately 4:3 or 5:4 with the subject framed away from the copy. Actual provider portrait may require a 3:4 frame instead. Prefer adjusting composition to the asset rather than cutting off a face or fabricating a consultation scene. No text over busy photography.

\#\#\# Recognition strip

Three concise situations with ample spacing and optional simple line icons; no raised card treatment required. Mobile uses a short vertical list. This section should be noticeably quieter and shorter than the hero and provider proof.

\#\#\# Provider and dedicated reviews

Nick's authentic 3:4 portrait anchors a provider introduction. Keep his name and actual role adjacent. Short heritage text supports credibility without a competing timeline.

The Google Reviews subsection must have a visible heading, numeric rating/count, attributed review cards and See all our Google reviews link. Use three default reviews on desktop and mobile; never exceed six desktop/three mobile. No automatic carousel. Read more expansion preserves full review text, exposes expanded state and remains keyboard accessible. Do not visually imply edited summaries are verbatim quotes.

Review cards are the principal card group on the page: white surface, subtle border, 12px radius, 24–32px padding and minimal/no shadow. Use ordinary Open Sans body styling. Avoid fabricated headshots, Google-certified marks or unattributed star clusters. Make source/attribution clear without copying browser chrome from screenshots.

\#\#\# Process

Four numbered stages connected by a restrained line on desktop; stack vertically on mobile. Each stage contains a short benefit-led label and a short explanation. Use semantic sequence markup. No excessive arrows, animated flow or requirement for photography. Labels should explain the path even without icons.

\#\#\# Benefits and payment callout

One purposeful product image or small approved group of product renders supports an editorial benefits list. Identify illustrative/model-specific imagery appropriately. Do not add a grid for every device style or a comparison table without verified useful distinctions.

Payment reassurance uses a contained cream/peach-accented callout with navy copy. Keep conditions adjacent and readable. Finance logos, if used, are secondary; do not introduce an outbound finance application as a competing action.

\#\#\# FAQ

Narrow text-led area, generous 20–24px row padding, understated dividers and clear expand/collapse icons. Use semantic buttons/details with accessible names and keyboard interaction. Do not communicate expanded state through the icon alone. Content must remain available to assistive technology. No imagery or sales button in every answer.

\#\#\# Appointment invitation and GHL form modal

Final appointment invitation is a navy emphasis band with white heading/body and a clearly visible primary CTA. It triggers the same modal used throughout the page; there is no duplicate inline form.

Modal heading: Request an Appointment, followed by brief truthful request context, then the supplied iframe. Suggested desktop outer width 680–760px, constrained to viewport width minus gutters; mobile uses nearly full available width. The brief's data-height 882 signals a tall form, not a reason to clip or shrink it. Provide an appropriately scrollable experience and test actual iframe sizing/scroll behavior.

Required behavior: visible accessible close control, Escape support, focus moved into the dialog, background interaction blocked, focus contained, and focus restored to the trigger. Cross-origin iframe focus boundaries require real browser testing; do not claim accessibility from the outer markup alone. Prevent background scrolling without losing scroll position. Ensure the mobile Call bar cannot overlap the dialog or submit area. Use appropriate dialog semantics.

Use the exact supplied iframe source, form ID, attributes and embed script from the project brief. Script loads once; iframe IDs are unique. RESEARCH.md flags a possible Onspire \`formEmbed-\` prefix adjustment to avoid autoscroll. Verify that requirement against the actual integration; if a change is technically necessary, update linked identifiers consistently and document/test it. Do not silently change the form contents or consent attributes based only on a presumed fix.

Provide a visible phone alternative if the form cannot load. Do not simulate a successful submission, fabricate a confirmation, or remove required consent to make a demo appear complete. Verify loaded fields, errors, consent and confirmation behavior in the appropriate testing workflow; do not submit real inquiries without authorization.

\#\#\# Location and map

Use the supplied Google Maps iframe with its place identity preserved, responsive width and a descriptive title. Desktop map may use approximately 16:10; mobile a useful 4:3 or minimum approximately 280px height. Avoid enormous map height before the final CTA. Lazy-load where appropriate.

Address and Heritage Mark context must be readable outside the iframe. Place Get Directions with a direction icon below the map as required. Address/directions are logistics; appointment action remains visually dominant. No unsupported parking, accessibility or walk-in claims.

\#\#\# Mobile sticky Call CTA

Blue bar with white phone icon and Call text, linking to tel:4092078726. Minimum comfortable touch height, plus device safe-area inset. Add equivalent page-bottom clearance; footer and lower controls must not be obscured. Hide or disable its background interaction while the form dialog is open. Test combined header, bottom bar, on-screen keyboard and iframe behavior on short mobile screens.

\#\#\# Footer

Navy or light surface consistent with the final invitation, modest typography that remains readable. Include Privacy Policy, Visit Our Website, relevant contact/location and current-year copyright. Use Brown Hearing Centers spelling. Validate the appropriate campaign privacy URL. If used in GHL, ensure \`{{location.name}}\` resolves correctly; otherwise use an explicit approved identity rather than displaying an unresolved token. No invented legal/privacy assurances.

\#\# Imagery and asset rules

Source inventory in RESEARCH.md §9 includes header/footer logos, Nick's portrait, company team image, archival sign image and generic service/product images. Availability in the inventory does not establish that assets have been downloaded, visually approved, licensed for reuse or optimized.

\- \*\*Authentic provider:\*\* Nick's portrait is the priority proof asset. Keep its 3:4 character where possible; avoid tight face crops.  
\- \*\*Authentic clinic/GBP:\*\* use confirmed Victoria exterior/interior imagery in the provider/location sections if supplied and suitable. Never use another branch's interior as Victoria.  
\- \*\*Lifestyle/outcome:\*\* one restrained image may establish conversation/connection in the hero. Depict adults naturally and respectfully. Do not imply the people are actual patients or that the image proves an outcome.  
\- \*\*Heritage:\*\* captioned 1966 sign-painting image is an optional small replacement for a text trust detail, not an additional large section. Do not identify the uncaptioned vintage couple without confirmation.  
\- \*\*Product:\*\* use verified manufacturer assets with suitable rights and accurate model context. No unsupported current-stock or compatibility implications.  
\- \*\*Reviews:\*\* rebuild transcribed text as attributed text components. Original screenshots are evidence, not display-ready artwork; browser UI and unrelated tabs must not appear.  
\- \*\*AI images:\*\* not needed for the planned page. Never fabricate staff, clinic facilities, patient testimonials or procedural evidence. Any later illustrative AI use requires a clear non-evidentiary purpose and must not be presented as authentic Brown photography.  
\- \*\*No imagery:\*\* recognition, process, payment explanation and FAQ generally communicate better through type/sequence and whitespace.

Typical page image budget: one hero human image, one provider portrait and one selective product visual, plus logo/map. Avoid repeating the same portrait in adjacent sections. If authentic assets are unavailable, simplify the layout rather than fill spaces with arbitrary images.

Use responsive sizes, modern formats where appropriate, explicit dimensions, purposeful crops and descriptive alt text. Decorative icons use empty/hidden semantics. Prioritize the hero image appropriately and lazy-load below-fold imagery. Do not invent scene descriptions in alt text that the image does not establish.

\#\# Visual storytelling system

\#\#\# Page-level arc

\*\*Human possibility → familiar difficulty → authentic local reassurance → clear path → useful options → quiet answers → a concrete local action.\*\*

\| Moment \| Intensity/density \| Layout and image role \| Transition \|  
\| \--- \| \--- \| \--- \| \--- \|  
\| Hero \| High emphasis, low copy density \| Spacious split; human image communicates an outcome possibility \| Open space gives way to a compact recognition band \|  
\| Recognition \| Quiet, compact \| Text-led situations; no image needed \| Visitor relevance leads naturally to who can help \|  
\| Nick and reviews \| Evidence peak, moderate density \| Authentic portrait then the main card group; optional small heritage detail \| Patient experience establishes credibility for the process \|  
\| Process \| Quiet explanatory moment \| Connected sequence, no image \| Clear steps make the device/support explanation easier to understand \|  
\| Practical options/payment \| Moderate emphasis/density \| Selective product image, editorial list, distinct payment note \| Benefits give way to remaining questions \|  
\| FAQ \| Quiet, selectively detailed \| Narrow text-led layout \| Resolution prepares the practical close \|  
\| Location/final invitation \| Specific logistics then strong action emphasis \| Map/address followed by navy invitation \| Exact location and request context make action concrete \|

\#\#\# Hierarchy and rhythm

Reserve strongest scale/contrast for the hero promise, local proof heading and closing action. Let the process stand out through structure and whitespace rather than another dark band. Product features should never visually outrank service/outcome or proof.

Use white and cream deliberately; not every section needs a new background. Navy is concentrated in text, persistent identity and the final invitation/footer. Peach is a small warmth cue, not a full-page wash. Limit strong shadows, excessive quotation marks, floating shapes, waves and ornamental dividers.

Border radius guidance: 8px buttons/controls, 12px review cards, 12–16px image frames/dialog where appropriate. Do not put every paragraph in a rounded box. Icons use one coherent line style, generally 20–24px, always secondary to labels. Animation is optional and restrained, approximately 120–200ms for ordinary state transitions. Respect reduced-motion preferences. No scroll-jacking, autoplay media or entrance animation that initially hides essential content.

\#\#\# Mobile storytelling

Keep service/location, benefit, proof cue and primary action near the opening; allow natural height rather than forcing a single-screen fit. Stack hero imagery after action. Preserve recognition → provider/reviews → process order. Show three purposeful reviews with expansion for long text, not a sideways-only experience. Stack process stages and benefit explanations without introducing a sequence of identical large cards.

Keep qualifiers with their claims, payment terms with payment mentions and reviewer attribution with reviews. Avoid cropping authentic images into meaningless slivers. Minimize simultaneous persistent UI; the header and bottom Call bar must leave enough usable reading/form space.

\#\# Implementation and review acceptance

No application stack is selected by this design document. The repository currently contains planning documents; do not infer a React application or install a framework merely to follow this brief. Prefer conventional, maintainable implementation compatible with the eventual delivery platform and the supplied GHL embeds; establish the Step 4 deliverable before coding.

Review desktop, tablet and narrow/short mobile layouts; keyboard navigation; 200% text sizing; reduced motion; contrast; form/modal focus and scrolling; sticky control clearance; map/directions; image crop/attribution; and all CTA destinations. A headline-only scan should explain the story and next action without relying on photography. Functional verification belongs to implementation, not the Step 3 document creation claim.

