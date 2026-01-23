# Dr. Katy Website Project

## Design System

### Color Palette
- **Olive:** #686A47 (headlines, accent backgrounds)
- **Burnt orange:** #AB5818 (links, eyebrows, hover states)
- **Cream:** #FDFAF5 (primary background, cards)
- **Near-black:** #272626 (body text)
- **Sage:** #D6DAC8 (buttons, section backgrounds)
- **Golden:** #BC8B41 (not currently used)
- **Muted teal:** #9CAFAA (not currently used)

### Fonts
- **Headlines:** Cooper BT (serif) - h1, h2, quotes
- **Body:** Sofia Pro (sans-serif) - paragraphs, nav, buttons, eyebrows

### Spacing & Layout
- **Section padding:** 6rem vertical (--section-padding)
- **Content padding:** 2rem horizontal (--content-padding)
- **Border radius:** 10px (--radius)
- **Max widths:**
  - Narrow content: 650px (opening, about compact)
  - Standard content: 700px (philosophy, FAQs, what's included)
  - Wide content: 900px (FAQ grid)
  - Two-column layouts: 1000px

### Component Patterns

**Eyebrows**
- Sofia Pro, 0.7rem, uppercase, letter-spacing 0.1em
- Burnt orange for section eyebrows
- Olive for secondary labels (e.g., "Your Investment")
- margin-bottom: 0.75rem before headline

**Buttons (.btn)**
- Sage background, olive text
- Hover: olive background, cream text
- Padding: 1rem 2rem
- Border-radius: 10px

**Arrow Links**
- Burnt orange with inline SVG arrow
- Gap animates on hover (0.75rem → 1rem)

**Editorial Lines**
- 1px solid rgba(39, 38, 38, 0.15)
- Used above/below content for subtle structure

**Cards**
- Cream background on colored section (sage)
- Padding: 2.5rem 3rem
- Border-radius: 10px

### Section Templates

**Quote Banner (.quote-banner)**
- Full-width image background
- Dark overlay (40% opacity)
- Centered quote in Cooper BT, cream text
- Height: 40vh, min-height: 300px

**Compact About (.approach-compact)**
- Centered layout, 650px max
- Circular headshot (120px)
- Eyebrow + headline + paragraphs + arrow link

**Two-Column Grid (lists, FAQs)**
- grid-template-columns: 1fr 1fr
- Gap: 2.5rem (FAQs), 1.25rem row / 2.5rem column (lists)
- Stacks to single column on mobile

**Testimonial Simple (.testimonial-simple)**
- Centered, 650px max
- Cooper BT quote, Sofia Pro cite
- Padding: 4rem

### Page Types

**Homepage**
- Split hero (text left, image right)
- Qualities banner (olive)
- Alternating cream/olive sections

**Sales/Offer Pages (Elemental Health)**
- Full-image hero with centered card
- Opening with eyebrow headers (The pattern → The shift → The work)
- Quote banner for visual break
- Olive section for key content (Three Phases)
- Sage card for pricing (What's Included)
- Two-column FAQ grid
- Testimonial before CTA

### Navigation
- Desktop: dropdown on hover for Services
- Mobile: full-screen overlay, flattened menu
- CTA button in nav: sage background

## Pricing Reference

**When updating prices, check ALL locations listed below.**

### Elemental Health: $2,500
- `elemental-health.html` — What's Included section
- `elemental-health-copy.md` — Investment section

### Elemental Care: $250/month (12-month commitment)
- `elemental-care.html` — What's Included section
- `elemental-care.html` — FAQ "How does payment work?"
- `elemental-care-copy.md` — Investment section
- (future) Current patients resources page

### Additional Visits (Elemental Care): $250
- `elemental-care.html` — What's Included note
- `elemental-care.html` — FAQ "How flexible are the visits?"
- `elemental-care-copy.md` — What's Included section

### Single Visits: $350
- `elemental-care.html` — FAQ "What if I just need an occasional visit?"
- `elemental-care-copy.md` — Single Visits section
- (future) Discovery call page
- (future) Current patients resources page

## Copy Style
- No em dashes (use sentences or parentheses)
- Avoid vague wellness language
- Headlines evoke feeling; who/what comes later on page
- Avoid "actually" (sounds comparative)
- Target visitor: exhausted, possibly dismissed by providers, or overwhelmed by health research

## Blog System

The blog uses JSON + JavaScript for filtering and pagination across all posts.

### Key Files
- `blog/posts.json` — All post metadata (title, date, category, excerpt, image, slug)
- `blog/README.md` — Full documentation
- `blog-post-template.html` — Template for individual posts
- `blog/[slug].html` — Individual post pages

### Adding Posts
Use `/blog-post` command to add new posts. It will:
1. Add entry to posts.json
2. Create the HTML file from template
3. Add category if new

### Manual Post Addition
1. Add entry to `posts.json` with: slug, title, date, category, categoryLabel, excerpt, image, imageAlt
2. Copy `blog-post-template.html` to `blog/[slug].html`
3. Update content in the new file

### Categories
Defined in posts.json `categories` array. Filter buttons auto-generate from this list.

### Configuration
- `postsPerPage` in posts.json config (default: 9)
- Posts auto-sort by date (newest first)

## Files
- `index.html` — Homepage
- `elemental-health.html` — Elemental Health sales page
- `elemental-care.html` — Elemental Care page
- `about.html` — About page
- `blog.html` — Blog index (JSON-driven)
- `blog/posts.json` — Blog post data
- `blog-post-template.html` — Template for blog posts
- `404.html` — Error page
- `css/styles.css` — All styles
- `session-summary-2026-01-18.md` — Session notes

## Pages to Build
- Discovery (booking page)
- Current patients resources page
- Care guide hub + articles: new-patients, lab-testing, insurance, primary-care, conditions

## Working Approach
- Build section by section, get feedback before moving on
- Don't build full pages and react (that didn't work well)
