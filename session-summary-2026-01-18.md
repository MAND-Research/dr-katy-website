# Dr. Katy Website Session Summary
**Dates:** January 18-23, 2026

## What We Accomplished

### Strategy Decisions
- Chose **vibe-coded static site** approach over platforms (Framer, Squarespace)
- Will deploy on Netlify once ready
- Three sites planned: Dr. Katy (primary), Midcoast Health Collective, Craft of Care
- Approach: build section by section, getting feedback before moving on

### Design Direction
- **Primary inspiration:** The Brecon (luxury editorial, photography-focused, calm and clear)
- Evolved toward more minimal, editorial aesthetic
- **Color usage refined:**
  - Cream: dominant background (80-90% of page)
  - Olive: brand color, used for lists section background and qualities banner
  - Sage: buttons and hand-drawn underline accent
  - Burnt orange: links and eyebrow text (used sparingly but intentionally)
  - Golden: removed as section background (was creating visual busyness)
- **Fonts:** Cooper BT (serif headlines), Sofia Pro (sans-serif body)
- **Corner radius:** standardized to 10px throughout

### Completed Sections

**Hero Section**
- Eyebrow: "Integrative Women's Health" (plain olive text, no pill)
- Headline: "Care that starts with deep listening"
- Subheadline: "Naturopathic medicine and acupuncture for midlife — practical, grounded, and designed to fit your life."
- CTA: Learn More (burnt orange with arrow)
- Split layout: text left, image right

**Qualities Banner**
- Olive background with cream icons and text
- Three qualities: Integrative, Thorough, Personalized

**Philosophy Section**
- Cream background, single column, centered (max-width 700px)
- Headline: "Find Your Starting Point" (with hand-drawn sage underline on "Your")
- Copy centered below headline

**Lists Section**
- Background image: rocky beach with pines (midcoast-health-collective-4-101.jpg)
- No overlay (tested olive 85%, black 30%, landed on no overlay for cleaner look)
- Two cream cards (10px corners) with lists
- Left: "You're looking for..." (5 items)
- Right: "Together we can address..." (5 items)

**About Section**
- Cream background, no card wrapper
- Two-column: photo left, content right
- Burnt orange "About" eyebrow above headline
- "I'm Dr. Katy" headline, bio text, "Meet Dr. Katy" link with arrow

**Testimonial Section**
- Cream background
- Thin editorial lines above and below (constrained to 800px width)
- Burnt orange "Kind Words" eyebrow
- Centered quote in Cooper BT with arrow navigation

**CTA Section**
- Cream background with generous padding (8rem)
- Centered single-column layout
- Headline, subhead (constrained width), centered button below

**Full-Width Image**
- Between CTA and footer
- 50vh height, cover fit
- Image: fall landscape with ocean (midcoast-health-session-III-24.jpg)

**Footer**
- Cream background
- Left: Dr. Katy Morrison name + tagline
- Right: Two link columns (Navigate, Patients)
- Bottom: copyright + Instagram icon

**Mobile Menu**
- Hamburger button appears below 768px
- Full-screen cream overlay with Cooper BT navigation links
- Animated hamburger to X transition

### Design System Refinements
- **Buttons:** Understated solid style (sage background, olive text, fills to olive on hover)
- **Links:** Burnt orange with arrow, gap animation on hover
- **Hover states:** Consistently burnt orange throughout
- **Focus states:** Olive outline for accessibility
- **Eyebrows:** Small uppercase burnt orange text (used on About and Testimonial)

## Files
- `/Dr. Katy Website/index.html` — complete homepage
- `/Dr. Katy Website/elemental-health.html` — Elemental Health sales page
- `/Dr. Katy Website/elemental-care.html` — Elemental Care page (draft)
- `/Dr. Katy Website/about.html` — About page (complete)
- `/Dr. Katy Website/css/styles.css` — design system and styles
- `/Dr. Katy Website/homepage-copy.md` — copy document
- `/Dr. Katy Website/elemental-health-copy.md` — Elemental Health copy
- `/Dr. Katy Website/elemental-care-copy.md` — Elemental Care copy
- `/Dr. Katy Website/about-copy.md` — About page copy
- `/Dr. Katy Website/fonts/` — Cooper BT and Sofia Pro
- `/Dr. Katy Website/images/` — clinic photos, headshot, landscape images

### Elemental Health Copy (Jan 19)

**Tone & Accuracy Edits**
- Removed ~12 instances of "actually" throughout
- Reworked hero subheadline: "Four months of naturopathic care and acupuncture, focused on what matters most for you."
- Rewrote opening section to include both patient types (vague unexplained symptoms AND clear symptoms needing proper investigation)
- Sharpened program promise: "The goal isn't just feeling better. It's feeling better and knowing how to stay there."
- Changed "one or two things" to "one or two systems" (more accurate to her approach)

**Structure Changes**
- Trimmed three phases to 2-3 sentences each
- Added medication to Phase Two treatment list ("chosen together" for shared decision-making)
- Simplified What's Included: new headline "What's included over four months," changed "custom wellness plan" to "personalized care plan"
- Condensed How It Works section to single line at bottom of What's Included
- Simplified pricing: flat $2,500, "Payment plans available" (removed discount structure)

**FAQs**
- Merged draft FAQs with published website FAQs
- Edited all for clarity and consistent tone
- Added placeholder links to care guide articles (insurance, labs, new patient process, PCP, what I treat)

**Placeholder Links Added**
- About page (from My Approach section)
- Elemental Care page (from After Elemental Health section)
- Care guide articles throughout FAQs

## Elemental Health Page Build (Jan 19)

### Page Structure
Built complete sales page with the following sections:

**Hero (Offer Page Style)**
- Full-viewport image background (currently midcoast-health-session-II-57.jpg)
- Dark overlay (35% opacity)
- Centered cream card with:
  - Eyebrow: "Find your starting place"
  - Headline: "Elemental Health"
  - Subheadline: "Four months of naturopathic care and acupuncture..."
  - Button: "See what's included"
- This hero style differentiates offer pages from homepage

**Opening Section**
- Centered single column (650px max)
- Problem/philosophy copy
- Bold emphasis on key lines: "It's not.", "Either way, symptoms aren't random. They're information.", "That's what Elemental Health helps you figure out."
- Copy edit: changed "been told to" → "felt like you needed to"

**Program Overview**
- Two-column layout: image left, text right
- No bordered box (tested bordered box, didn't keep)
- Button: "View program details"
- Tested editorial two-column split with vertical divider line (didn't work)

**My Approach**
- Two-column: photo left, content right
- Eyebrow: "My Approach"
- Headline: "Two lenses, one picture"
- Explains dual training (naturopathic + acupuncture)
- Arrow link to About page

**Three Phases**
- Olive background (the color moment)
- Vertical stacked layout with large decorative numbers (1, 2, 3 in cream at 30% opacity)
- Tested multiple layouts: three columns, stacked with small numbers, cards on olive, large numbers on sage, cards with numbers
- Final choice: olive background + vertical + large numbers

**What's Included**
- Bordered box with thin border
- Centered headline
- List format: **Bold item:** description (inline, no divider lines between items)
- Pricing tucked in: "$2,500 for four months" + "Payment plans available."
- Location note at bottom (italicized)

**After Elemental Health**
- Simple centered text section
- Links to Elemental Care
- Bold closing line about long-term health, not dependence

**FAQs**
- Accordion style (11 questions)
- +/− toggle, only one open at a time
- Hover turns burnt orange
- Links to future care guide articles:
  - /new-patients
  - /lab-testing
  - /insurance
  - /primary-care
  - /conditions

**Final CTA**
- Same style as homepage CTA
- Headline: "Let's figure out where to begin"
- Button: "Book a consultation"

**Full-Width Image**
- Between CTA and footer
- Currently using same image as homepage (needs different one)

**Footer**
- Same as homepage

### Design Decisions Made
- Offer page heroes use image background + centered card (differentiates from homepage split layout)
- Opening section uses bold for emphasis (not size differential)
- Program overview: two-column with image works better than bordered box
- Three phases: vertical layout handles uneven content lengths better than columns
- FAQs: accordion keeps page tighter
- Tested editorial newspaper-style two-column for opening+overview (didn't feel right)

### Images to Upload/Replace
- **Hero background:** needs its own image (not shared with homepage)
- **Program overview:** needs vertically oriented image
- **My Approach photo:** different photo of Dr. Katy
- **Full-width before footer:** different landscape from homepage

### Placeholder Links to Create
FAQ care guide articles:
- /new-patients (new patient process)
- /lab-testing (lab testing info)
- /insurance (insurance and billing)
- /primary-care (PCP relationship info)
- /conditions (what I treat)

Other:
- /elemental-care (from After Elemental Health section)
- /about (from My Approach section)

### Cohesion Review (End of Session)

**Problem identified:** Page felt less cohesive than homepage. Too many one-off layout treatments (9 different section styles). Each section felt like a standalone decision rather than part of a system.

**Specific issues:**
- Program Overview and My Approach were too similar (both two-column, image left) and appeared back-to-back
- Olive section felt isolated (only appears once, unlike homepage where it repeats)
- Bordered box on What's Included was orphaned (only bordered element)
- Lower half of page was text-heavy without visual punctuation

**Fix applied:** Merged Opening and Program Overview into one continuous text section. Removed the image from Program Overview. This reduces layout variations and creates better flow.

**Still to address:**
- May want to flip My Approach photo to the right (to differentiate from other two-column sections)
- Consider adding section headers within the combined opening for visual variation
- May need another visual break in the lower half of the page
- Bordered box on What's Included may need reconsidering

## Session Jan 19 (cont'd)

**Opening Section Headers Added**
- Added eyebrow-style headers to break the opening section into three parts: "The pattern" → "The shift" → "The work"
- Burnt orange, uppercase, Sofia Pro (matches eyebrow treatment elsewhere)
- Removed bold emphasis from body text in this section (headers do the work now)
- Tried two-column layout with labels in left column, reverted to stacked (didn't work)

**Quote Banner Added**
- New section between Opening and Three Phases
- Image background (midcoast-health-collective-4-5.jpg - rocky Maine shoreline with evergreens)
- Dark overlay (40% opacity), centered quote in Cooper BT
- Final quote: "Your symptoms aren't random. They're messengers." (from Dr. Katy's content)

**My Approach Section Reworked**
- Moved from before Three Phases to after (better flow: program details first, then "about me")
- Cut the dense cortisol/progesterone example paragraph
- Changed from two-column layout to compact centered layout with 120px circular headshot
- Uses midcoast-health-session-III-61.jpg (old homepage headshot)

**Homepage Headshot Updated**
- New headshot: midcoast-health-collective-4-50.jpg
- Old headshot moved to Elemental Health circular photo

**Three Phases Section**
- Narrowed phases-list from 800px to 700px max-width (matches other sections)

**What's Included Section - Major Rework**
- Dropped the bordered box
- Added sage background with cream card (echoes hero treatment)
- Added "Elemental Health" eyebrow (centered)
- Two-column grid for list items (4 rows x 2 columns)
- 8 items: Four months of care, Initial visit, Follow-up visits, Acupuncture, Lab panel, Care plan, Direct messaging, Supplement discount
- Added "Your Investment" label above price (olive, centered)
- Added "Book a consultation" button at bottom
- Removed location note (covered in FAQ)

**After Elemental Health Section**
- Added "What comes next" eyebrow
- Added thin editorial lines above and below content
- Removed bold from final paragraph (lines provide enough structure)

**FAQs Section - Major Rework**
- Changed from single accordion to two-column grid layout
- Left column: "About the Program" (5 questions)
- Right column: "Practical Details" (5 questions)
- Group headers in Cooper BT (1.25rem, olive)
- Removed "What do you treat?" to balance columns
- Reduced section padding from 6rem to 4rem
- Stacks to single column on mobile

**Testimonial Section Added**
- New section between FAQs and Final CTA
- Simple centered layout (650px max)
- Cooper BT quote, understated cite line
- Placeholder quote: "For the first time, I feel like someone actually listened to the whole picture. The changes we made were small but they worked because they were the right ones for me." — Sarah, Elemental Health patient
- Needs real testimonial

**Full-Width Image Updated**
- Changed to midcoast-health-session-II-47.jpg (lavender with bee)
- Alt text: "Lavender flowers in soft sunlight"

## Session Jan 20

### Elemental Care Page Built

**Copy Development**
- Reviewed existing Elemental Care drafts in Copywriting folder
- Original version had heavy wellness language ("body's wisdom," "seasonal touchstones," "sanctuary")
- REVISED version was much closer to website tone
- Created new `elemental-care-copy.md` using REVISED as base, edited for website tone
- Broadened opening to include all established patients (not just Elemental Health graduates)

**Page Structure**
- Hero: full-image background with centered cream card (same style as Elemental Health, placeholder image)
- Opening: brief centered intro (narrower than Elemental Health)
- "Why ongoing care": three-column benefits grid with icons (stethoscope, calendar with checkmark, arrow flow)
- What's Included: sage background with cream card, 6 items, $250/month pricing, "Sign up" button
- FAQs: single column accordion (consolidated from 10 to 5 questions)
- Testimonial: placeholder quote
- Final CTA + full-width image + footer

**Design Decisions**
- Benefits section: icons centered above each item, all content centered
- Removed "No weeks-long wait" sentence (felt off)
- Single Visits: removed as standalone section, folded into FAQ instead ("What if I just need an occasional visit?")
- FAQs consolidated: visit flexibility (combined 3), lab panel, renewal (combined 2), payment (combined 2), single visits

**Files Created/Updated**
- `elemental-care.html` — complete page
- `elemental-care-copy.md` — copy document
- `css/styles.css` — added .benefits, .benefit, .single-visits styles
- `.claude/CLAUDE.md` — added Pricing Reference section

**Pricing Reference Added to CLAUDE.md**
Tracks all pricing touchpoints for future updates:
- Elemental Health: $2,500
- Elemental Care: $250/month
- Additional visits: $250
- Single visits: $350

**Still needs on this page:**
- Hero image (currently using Elemental Health placeholder)
- Real testimonial

## Session Jan 20 (cont'd) - About Page

### Copy Development
- Drafted About page copy from scratch (no existing copy file)
- Reworked existing website About content to match editorial tone
- Removed marketing-speak opener ("Most of my patients come to me after years of feeling dismissed...")
- Kept PCOS/infertility mention light (three sentences, not a whole section)
- Condensed ethnobotany background to one sentence
- Added personal detail: "My husband runs the office; our son and dog keep us busy outside of it."
- Created `about-copy.md` with finalized copy

### Page Structure
Built complete About page with the following sections:

**Hero (Two-Column)**
- Large photo left (4:5 aspect ratio), intro text right
- H1: "About Dr. Katy"
- Two paragraphs: positioning + approach summary
- Currently using homepage headshot (needs different photo)

**My Approach**
- Centered layout, 700px max
- Eyebrow: "My Approach"
- Headline: "Two lenses, one picture"
- Four paragraphs explaining dual naturopathic + Chinese medicine training
- This is the expanded version of the compact treatment on Elemental Health

**Why This Work**
- Centered, editorial lines top/bottom (like After Elemental Health treatment)
- Eyebrow: "Why This Work"
- Brief personal section (PCOS/infertility shaped how I practice)

**Background & Credentials**
- Two-column: Background text (left), Credentials (right)
- Background includes ethnobotany, Maine native, family mention
- Credentials organized by institution with bullet points
- Three licenses: Naturopathic Doctor, Acupuncturist, Chinese Herbalist

**Full-Width Image**
- Using midcoast-health-collective-4-75.jpg

**Footer**
- Same as other pages

### Design Decisions
- No CTA section (About page is trust-building, not sales; nav CTA is always visible)
- Two-column hero differentiates from offer pages (which use card-over-image)
- "Why This Work" uses editorial lines for visual separation without adding color
- Credentials in simple list format (not overly designed)

### Files Created/Updated
- `about.html` — complete page
- `about-copy.md` — copy document
- `css/styles.css` — added .about-hero, .about-approach, .about-why, .about-background, .about-credentials styles

### Still needs on this page
- **Hero photo:** swap out for different image (currently using homepage headshot)
- **Professional associations:** add with logo files (user has logos somewhere)

## Still To Do (Master List)

### Pages to Build
- ~~About page~~ (complete, needs photo swap + professional associations)
- ~~Elemental Care page~~ (draft complete)
- ~~404 page~~ (complete)
- ~~Blog index~~ (complete)
- Discovery call page (booking + pricing info for all visit types)
- Current patients resources page (Fullscript, patient portal links, Elemental Care info, single visits pricing)
- Care guide hub page (articles grouped by topic)
- Care guide articles (new-patients, lab-testing, insurance, primary-care, conditions)

### Blog Work
- Review and edit 40 draft posts in `blog/drafts/`
- Create HTML files from drafts using template
- Add posts to posts.json
- Source/add images for blog posts

### Features to Add
- Email newsletter sign up
- Replace placeholder testimonials on homepage with real quotes
- Replace placeholder testimonial on Elemental Health with real quote
- Replace placeholder testimonial on Elemental Care with real quote

### Decisions to Make
- Keep or toss existing pages: guiding principles, naturopathic medicine, east asian medicine
- Add offerings grid/slider to homepage?
- Newsletter sign up pop up?

### Polish
- Responsive refinements for tablet/mobile
- Deployment to Netlify

## Style Notes
- No em dashes — use sentences or parentheses instead
- Avoid: "actually" (sounds comparative), vague wellness language
- Headlines should evoke feeling; who/what comes later on page
- Target visitor: exhausted, possibly dismissed by other providers, or overwhelmed by research
- Elemental Health copy: reworked from marketing-speak to match homepage tone (compelling, honest, clear). Removed dramatic copywriting techniques ("Here's the truth," excessive bold/italics). Kept "starting place" philosophy.

## Luxury Editorial Principles Applied
- Minimal color usage (cream dominant, olive as signature, burnt orange sparingly)
- Generous whitespace
- Consistent corner radius (10px)
- Understated buttons (sage, not bold olive)
- Thin editorial lines for structure
- Photography as visual punctuation

## Session Jan 21-22

### 404 Page Built
- Simple centered design
- Headline: "Page not found"
- Subtext with link back to homepage
- Full-height layout

### Blog Post Template Created
- `blog-post-template.html`
- Long-form article layout
- Smaller featured image (not full-width hero)
- Header, image, content area, author footer

### Blog Index Page Built
- `blog.html` — JSON-driven blog index
- 3-column card grid (responsive: 3 → 2 → 1 column)
- Category tags on each card
- Pagination at bottom

**Bug Fixed:** Pagination was appearing at top of page covering the menu bar
- Cause: Global `nav` CSS had `position: fixed; top: 0; z-index: 100;` which applied to `<nav class="blog-pagination">`
- Fix: Changed pagination from `<nav>` to `<div>`

### JSON + JavaScript Blog System
Built dynamic blog system for filtering across all posts (not just current page):

**Files Created:**
- `blog/posts.json` — central data file with posts array, categories array, config
- `blog/README.md` — documentation for maintaining the blog
- `.claude/commands/blog-post.md` — slash command for adding new posts

**Data Structure (posts.json):**
```json
{
  "posts": [
    {
      "slug": "post-url-slug",
      "title": "Post Title",
      "date": "YYYY-MM-DD",
      "category": "category-id",
      "categoryLabel": "Category Display Name",
      "excerpt": "Brief description",
      "image": "images/filename.jpg",
      "imageAlt": "Image description"
    }
  ],
  "categories": [
    { "id": "category-id", "label": "Category Display Name" }
  ],
  "config": {
    "postsPerPage": 9
  }
}
```

**Features:**
- Category filter buttons auto-generate from categories array
- Filtering works across ALL posts (not just current page)
- Pagination adjusts based on filtered results
- Posts auto-sort by date (newest first)

### Blog Post Migration
Extracted **40 blog posts** from existing website (drkatymorrison.com) into markdown files.

**Location:** `blog/drafts/*.md`

**Frontmatter Format:**
```yaml
---
title: "Post Title"
date: YYYY-MM-DD
category: category-slug
slug: post-url-slug
status: draft
---
```

**Categories Extracted:**
- natural-medicine (11 posts)
- stress (8 posts)
- digestion (12 posts)
- supplements (4 posts)

**Posts with Recipes:**
- Pumpkin Spice (tea recipe)
- Traditional Fermented Foods (sauerkraut recipe)
- Blueberries (cucumber-mint salad)
- Fall Harvest: Winter Squash (roasted squash)
- Bone Broth (broth recipe)
- Heirloom Carrots (salad recipe)

**Note:** User mentioned 42 posts total; extracted 40. Discrepancy may be from different URL patterns or approximate count.

### Files Created/Updated
- `404.html` — error page
- `blog.html` — JSON-driven blog index
- `blog-post-template.html` — template for individual posts
- `blog/posts.json` — blog post data
- `blog/README.md` — blog documentation
- `.claude/commands/blog-post.md` — command for adding posts
- `blog/drafts/*.md` — 40 markdown files with extracted blog posts
- `.claude/CLAUDE.md` — added Blog System documentation section

### Still To Do (Updated)

**Pages to Build:**
- ~~About page~~ (complete)
- ~~404 page~~ (complete)
- ~~Blog index~~ (complete)
- Discovery call page
- Current patients resources page
- Care guide hub + articles

**Blog Work Remaining:**
- Review and edit 40 draft posts in `blog/drafts/`
- Create HTML files from drafts
- Add to posts.json
- Add images to blog posts

**About Page Remaining:**
- ~~Swap hero photo~~ (done - midcoast-health-session-II-14.jpg)
- ~~Add professional associations with logos~~ (done)

## Session Jan 22 (cont'd) - About Page Finished + Meet Bill

### About Page Simplified
- Restructured from 4 sections to 3 simpler sections
- Removed eyebrows and section headers from bio (felt too broken up)
- Combined into flowing narrative: Hero (photo + intro), Bio (flowing paragraphs), Credentials

**Hero Changes:**
- New photo: midcoast-health-session-II-14.jpg (Dr. Katy in sage cardigan)

**Bio Section:**
- Reduced top padding (6rem → 2rem) for tighter connection to hero
- Increased max-width to 1000px (matches hero width)
- Added burnt orange link styling for inline links

**Credentials Section:**
- Made school names clickable (NUNM, St. Lawrence)
- Changed Licenses format: "State of Maine" as location line (like schools) rather than repeated in each item

**Professional Association Logos:**
- Created `images/logos/` folder
- Added logo row section at bottom of About page
- Three logos with links: AANP, MAND, NCCAOM
- Logos at 160px height (desktop), 120px (mobile)
- User removed white backgrounds manually

### Meet Bill Page Created
- New page at `/meet-bill`
- Bill is office manager (Katy's husband)
- Simple structure reusing About page styles (about-hero, about-bio)
- Headshot: midcoast-health-collective-4-43.jpg
- Placeholder content for now
- Linked from About page bio ("My husband Bill runs the office" is now a link)

### Files Created/Updated
- `about.html` — restructured, added logos, added link to Bill
- `meet-bill.html` — new placeholder page
- `css/styles.css` — added .about-logos styles, .about-bio-inner link styles
- `images/logos/aanp-logo.png` — transparent logo
- `images/logos/mand-logo.png` — transparent logo
- `images/logos/nccaom-logo.png` — transparent logo

### About Page: Complete
The About page is now finished with:
- Simplified structure
- New hero photo
- Professional association logos
- Link to Bill's page

## Session Jan 23

### Discovery Page Updated
- Added two-column layout: clinic exterior photo on left, content on right
- Image: midcoast-health-session-II-4.jpg (white colonial building with flowers)
- Image and text match height (align-items: stretch)
- Added Practice Better booking link
- Responsive: stacks on mobile with 4:5 aspect ratio image

### About Page Tweaked
- Removed full-width landscape image before footer
- Page now goes directly from professional logos to footer

### Image Usage Updated
**Now used:**
- midcoast-health-session-II-4.jpg (Discovery page)

**Still unused:**
- midcoast-health-collective-4-10.jpg (moss with red leaves)
- midcoast-health-collective-4-61.jpg (beach landscape)
- midcoast-health-session-III-12.jpg (Maine landscape with stone structure)
