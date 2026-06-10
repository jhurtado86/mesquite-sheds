CLAUDE.md — Frontend Website Rules
Always Do First

Invoke the frontend-design skill before writing any frontend code, every session, no exceptions.

Client Context — OptiGlass+
Business Identity

Business name: OptiGlass+ (always include the "+" — it's part of the brand)
Industry: Auto glass repair and replacement
Owner/lead technician: Luis (praised by name in customer reviews — he's a personal brand asset, feature him)
Physical address: 4515 N 10th St, McAllen, TX 78504 (real shop location — use in schema and contact info)
Phone (for site — A2P number): (956) 403-6132 / tel:+19564036132 — NOTE: not yet A2P-verified; do not treat as launch-ready until verified
Phone (personal — do NOT feature on site): (956) 403-8232
Email: mroptiglass@outlook.com
Location base: McAllen, Rio Grande Valley (RGV), Texas
Years in business: TBD (verify with Luis)

Service Area (in priority order — use this order everywhere)

McAllen (primary market + physical location)
Edinburg
Mission
Pharr
San Juan
Palm View

All cities are in the Rio Grande Valley, Texas. The site should feel locally rooted in the RGV.
Services (six core services — one dedicated page each)

Windshield Replacement — full windshield replacement
Windshield Chip & Crack Repair — chip and crack repair
Headlight Restoration — restoring cloudy/yellowed headlights
Mobile Auto Glass Service — technician comes to the customer's location
Window Replacement — side and rear auto glass
Rear Windshield Replacement — rear windshield replacement

NOTE: Mirror replacement is offered but listed on homepage/footer only, no dedicated page.
NOTE: Do NOT include ADAS recalibration anywhere on the site (per client decision).
Insurance (MAJOR selling point — feature prominently)

"Free with insurance" is a primary value proposition
Direct billing relationships with: Allstate, USAA, Geico, Nationwide, Progressive, Liberty Mutual, Farmers Insurance, Assurance
Customers care most about "do you work with my insurance?" — make this easy to find
Use "works directly with your insurance" language — do NOT claim Luis files the claim FOR the customer (not yet verified with Luis)
For chip repair specifically: most insurance carriers waive the deductible — this is a major conversion driver

Key Differentiators (from reviews and GMB About)

Lifetime warranty on work
Fair, transparent pricing — no hidden fees
Mobile service — comes to the customer
Quick response times / same-day service
Flawless installation — vehicles look brand new
Step-by-step explanation — Luis explains the repair process, educational and friendly
Safety focus — "keeping your loved ones safe on the road"
High-quality craftsmanship and materials

Brand Voice & Tone

Safety-focused and caring (family/loved-ones framing)
Community-oriented and locally proud (RGV roots)
Warm and approachable, but professional
Transparent and educational (explains the process)
Emphasizes the "coming back HOME" feeling — trust and relationship
Core qualities Luis names: Honesty, Attention to Detail, Dedication, Professionalism

Brand Tagline

Primary slogan: "A Safer Way To Cruise The Road"
Supporting line: "Keeping your loved ones safe and your peace of mind"
Brand name pairs with it as: OptiGlass+ — A Safer Way To Cruise The Road
Use sparingly in 2-3 high-visibility spots (hero eyebrow, footer sign-off, optionally woven once into the Luis/Why-Us section). Do not overuse.

Social Proof

71 five-star reviews on Google Business Profile
Display via embedded GHL review widget (live feed)
Make review volume a prominent trust signal throughout the site

Reference About Us copy (from GMB — for voice, not verbatim use)
"We at OptiGlass+ specialize in keeping your loved ones safe on the road by providing the highest standards in each and every job we do. Our main goal is to provide high quality craftsmanship, as well as materials to last the road ahead... always giving a fair price as well as a lifetime warranty. Honesty, Attention to Detail, Dedication and professionalism are some of the qualities we keep in mind... the same that will keep you coming back HOME."
Brand Colors

Established palette from the site: deep navy (~#06101C) as primary dark, with orange accent for CTAs and key highlights, clean whites for body backgrounds. Provisional pending Luis's logo — once a logo is provided, refine to match.

Assets Status

Logo: TBD (waiting on Luis — using a styled text wordmark "OptiGlass+" until provided)
Photos: Mix of stock/AI + future Luis-provided
Hero background image: brand_assets/Hero_background.jpg (in place)
CTA section background image: brand_assets/cta-background.jpg (sunset open road, moody — for final CTA sections across all pages with a dark overlay for text readability)

Site Architecture (planned)

Homepage
About Us
Contact / Thank You
6 service pages at /services/[service-name].html:

windshield-replacement.html (built)
windshield-chip-crack-repair.html (built)
headlight-restoration.html
mobile-auto-glass-service.html
window-replacement.html
rear-windshield-replacement.html


6 service area / city pages at /areas/[city].html (one per city above, in priority order)
City pages require 30-40% unique content each (anti-doorway-page rule)

Final CTA Section Pattern (apply on every page)

All pages use the same final CTA section just before the footer
Background: brand_assets/cta-background.jpg (sunset open road)
Dark overlay (semi-transparent navy/black, ~55-65% opacity) on top of image for white/orange text readability
Headline + supporting copy + dual CTAs (Call + Get a Free Quote)
Same treatment across all pages for brand consistency

Domain

Final choice: optiglassplus.com (preferred) — verify availability before purchasing
Backup: optiglassplusrgv.com
Do NOT purchase or hardcode as canonical until Luis approves the build (use as the canonical/OG base URL in code, but know it's not live yet)

Open Items / To Confirm With Luis

A2P number verification (in progress)
Years in business
Logo file (or approval for placeholder wordmark)
Real photos
Final brand colors
Final approval of the 6 services and 6 cities as listed
Whether Luis files the insurance claim FOR the customer, or only handles direct billing after customer files

Content Writing Methodology
For all page COPY/content, read and follow SEO-CONTENT-PROMPT.md (in the project root) as the PRIMARY writing methodology before writing any page content. Apply the COMPLETE methodology — not just the Words to Avoid list. This includes the writing mission, all optimization guidelines (for both Google Algorithm and AI Systems), the balanced writing approach, content structure, language guidelines, quality signals, and the Words to Avoid list. The Local SEO Requirements below govern TECHNICAL implementation (meta tags, schema, sitemap, file structure) and work in tandem. If there is ever a conflict on wording or content approach, SEO-CONTENT-PROMPT.md takes precedence.
Local SEO Requirements
Every page built for this site must follow these SEO standards. This is a local service business — local SEO is the primary lead driver.
Per-Page Metadata (every page needs all of these)

Unique <title> tag, under 60 characters, format: "[Page Topic] | OptiGlass+ Auto Glass in McAllen, TX"
Unique <meta name="description">, under 160 characters, includes a service, a city, and a call to action with the phone number
<meta name="keywords"> with relevant local terms (service + city combinations)
<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1">
<link rel="canonical"> pointing to that page's own URL
<html lang="en"> and proper viewport meta

Open Graph + Twitter Cards (every page)

og:title, og:description, og:url, og:type, og:image, og:locale, og:site_name
twitter:card (summary_large_image), twitter:title, twitter:description, twitter:image
og:image and twitter:image point to a social share image (1200x630) — flag if not yet created

Structured Data (JSON-LD)

Homepage: AutoRepair LocalBusiness schema (closest standard schema.org type for auto glass)
Include: name ("OptiGlass+"), full PostalAddress (4515 N 10th St, McAllen, TX 78504 — this is a real address, use it), telephone (A2P number once verified), email, priceRange, openingHoursSpecification, areaServed (all 6 cities), hasOfferCatalog (all 6 services)
Include aggregateRating reflecting the 71 five-star reviews if displaying them
Service pages: add Service schema referencing the parent business
City pages: reference areaServed for that specific city
Validate all schema at search.google.com/test/rich-results before launch

Visible On-Page SEO

Each page must have exactly ONE <h1> with the page's primary keyword
H2/H3 used for section hierarchy, no skipped levels
City names must appear in human-readable body text, not just metadata
Service + city combinations should appear naturally in copy (e.g., "windshield replacement in McAllen")
All images need descriptive alt text including service/location context where relevant

City Pages — Critical Anti-Duplicate Rule

Each city page MUST have 30-40% unique content minimum
Do NOT just swap the city name across otherwise-identical pages — Google penalizes this as doorway pages
Each city page should reference local landmarks, neighborhoods, highways, or area-specific details
Unique intro paragraph, unique "why [city] chooses OptiGlass+" angle per page

Technical SEO Files

sitemap.xml listing all indexable pages (homepage, about, all service pages, all city pages — exclude thank-you page)
robots.txt allowing crawl, disallowing thank-you page, pointing to sitemap
thank-you page must have <meta name="robots" content="noindex, nofollow">

Per-Page Title/Description Pattern

Homepage: "Windshield Replacement & Auto Glass Repair in McAllen, TX | OptiGlass+"
Service page: "[Service] in McAllen | OptiGlass+"
City page: "Auto Glass Repair in [City], TX | OptiGlass+"

Reference Images

NOTE: For THIS project we are building ORIGINAL pages from the Client Context, NOT matching a provided reference. The reference-matching rules below apply ONLY when a reference image is explicitly provided. Otherwise, design original, high-craft pages per the guardrails.
If a reference image is provided: match layout, spacing, typography, and color exactly. Swap in placeholder content (images via https://placehold.co/, generic copy). Do not improve or add to the design.
If no reference image: design from scratch with high craft (see guardrails below).
Screenshot your output, compare against reference, fix mismatches, re-screenshot. Do at least 2 comparison rounds. Stop only when no visible differences remain or user says so.

Local Server

Always serve on localhost — never screenshot a file:/// URL.
Start the dev server: node serve.mjs (serves the project root at http://localhost:3000)
serve.mjs lives in the project root. Start it in the background before taking any screenshots.
If the server is already running, do not start a second instance.

Screenshot Workflow

Puppeteer is installed at C:/Users/nateh/AppData/Local/Temp/puppeteer-test/. Chrome cache is at C:/Users/nateh/.cache/puppeteer/.
Always screenshot from localhost: node screenshot.mjs http://localhost:3000
Screenshots are saved automatically to ./temporary screenshots/screenshot-N.png (auto-incremented, never overwritten).
Optional label suffix: node screenshot.mjs http://localhost:3000 label → saves as screenshot-N-label.png
screenshot.mjs lives in the project root. Use it as-is.
After screenshotting, read the PNG from temporary screenshots/ with the Read tool — Claude can see and analyze the image directly.
When comparing, be specific: "heading is 32px but reference shows ~24px", "card gap is 16px but should be 24px"
Check: spacing/padding, font size/weight/line-height, colors (exact hex), alignment, border-radius, shadows, image sizing

Output Defaults

Single index.html file, all styles inline, unless user says otherwise
Tailwind CSS via CDN: <script src="https://cdn.tailwindcss.com"></script>
Placeholder images: https://placehold.co/WIDTHxHEIGHT
Mobile-first responsive

Brand Assets

Always check the brand_assets/ folder before designing. It may contain logos, color guides, style guides, or images.
If assets exist there, use them. Do not use placeholders where real assets are available.
If a logo is present, use it. If a color palette is defined, use those exact values — do not invent brand colors.

Anti-Generic Guardrails

Colors: Never use default Tailwind palette (indigo-500, blue-600, etc.). Pick a custom brand color and derive from it.
Shadows: Never use flat shadow-md. Use layered, color-tinted shadows with low opacity.
Typography: Never use the same font for headings and body. Pair a display/serif with a clean sans. Apply tight tracking (-0.03em) on large headings, generous line-height (1.7) on body.
Gradients: Layer multiple radial gradients. Add grain/texture via SVG noise filter for depth.
Animations: Only animate transform and opacity. Never transition-all. Use spring-style easing.
Interactive states: Every clickable element needs hover, focus-visible, and active states. No exceptions.
Images: Add a gradient overlay (bg-gradient-to-t from-black/60) and a color treatment layer with mix-blend-multiply.
Spacing: Use intentional, consistent spacing tokens — not random Tailwind steps.
Depth: Surfaces should have a layering system (base → elevated → floating), not all sit at the same z-plane.

Hard Rules

Do not add sections, features, or content not in the reference (when a reference is provided)
Do not "improve" a reference design — match it (when a reference is provided)
Do not stop after one screenshot pass
Do not use transition-all
Do not use default Tailwind blue/indigo as primary color