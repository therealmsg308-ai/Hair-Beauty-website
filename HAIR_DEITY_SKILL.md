# Hair Deity Web Design Skill
## Complete Luxury Hair Brand Website Framework

This skill contains everything needed to build a luxury hair brand website from scratch — based on the Hair Deity flagship build. Use this as a template for any future hair brand website project.

---

## 🎯 WHEN TO USE THIS SKILL

Use this skill when:
- Building a luxury hair extension brand website
- Creating a hair stylist booking platform
- Setting up an AI hair concierge
- Building a hair e-commerce store with kit bundles
- Creating service showcase pages for hair installs

---

## 🎨 BRAND SYSTEM

### Color Palette (Deep Ocean Gold Theme)
```css
:root {
  --ocean-deep: #0a1628;      /* Primary background */
  --ocean-mid: #0d2137;       /* Secondary background */
  --ocean-teal: #0e3a4a;      /* Teal accent background */
  --teal-glow: #1a6b7a;       /* Teal glow */
  --gold: #c8a84b;            /* Primary gold */
  --gold-light: #e8c96a;      /* Light gold */
  --gold-bright: #f5d98a;     /* Bright gold */
  --gold-dim: #8a6e2a;        /* Dim gold */
  --cream: #f5f0e8;           /* Primary text */
  --text-light: #d4c5a0;      /* Secondary text */
  --teal-text: #6ecfdf;       /* Teal text accent */
  --success: #4caf7d;
  --error: #e05c5c;
  --warn: #e8a94b;
}
```

### Typography
```css
/* Import from Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700;900&family=Cinzel:wght@400;600;700&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap');

/* Usage */
font-family: 'Cinzel Decorative', serif;  /* Hero titles, logos */
font-family: 'Cinzel', serif;              /* Subheadings, labels, nav */
font-family: 'Cormorant Garamond', serif;  /* Body text, descriptions */
```

### Visual Style Rules
- Always dark backgrounds (deep navy/teal) — never white
- All headers in gold gradient
- Shimmer animations on cards
- Particle effects on hero
- Gold divider lines between sections
- Luxury magnetic box visuals for products
- Split-screen layouts for service sections

---

## 🏗️ SITE ARCHITECTURE

### Required Sections (in order)
1. **Announcement Banner** — scarcity offer + promo code
2. **Sticky Nav** — logo + links + CTA
3. **Hero** — full-screen with particles + goddess imagery
4. **Product Kits** — 3-tier kit system
5. **Texture Selector** — 2 textures max for new brand
6. **Promo Code** — limited use code
7. **Service Sections** — K-Tips, Brazilian Knots, Sew-In
8. **The Oracle** — AI concierge chat
9. **Delivery Section** — Deity Dash or equivalent
10. **Booking Section** — stylist card + service menu
11. **Loyalty Program** — Gold Coin wallet
12. **Wholesale Portal** — gated stylist area
13. **Footer** — policies + links

### Overlay Pages (open as fixed overlays)
- Kit Showcase Pages (one per kit)
- Service Showcase Pages (one per service)
- Booking Platform (full 4-step booking flow)
- Admin Dashboard (stylist management)
- Media Release Form (Muse program)

---

## 💰 PRICING FRAMEWORK

### Kit Pricing Formula
```
Cost of hair from vendor × 2.5 = minimum kit price
Add tools/accessories cost
Round to nearest $9 or $9.50
```

### Service Pricing Research
- Always research local market before pricing
- New stylist: price 20-30% below established stylists
- Never go below cost of materials + 2 hours labor
- Add maintenance services for recurring revenue

### Deposit Rules
- 50% deposit on all services
- 100% hair cost upfront if stylist provides hair
- Non-refundable consultation fees
- 48-hour cancellation policy

### NC Sales Tax
- Charlotte/Mecklenburg County: **8.25%** (as of July 2026)
- Tax applies to: hair products, kits, all-inclusive services
- May not apply to: labor-only services (consult CPA)

---

## 🔮 THE ORACLE AI FRAMEWORK

### Consultation Flow (Required Questions)
1. "What is your natural hair texture?" (4A/4B/4C/3C/Relaxed/Transitioning)
2. "Does your hair revert in heavy heat or moisture?" (YES/NO — most important question)
3. "Will you use a closure or leave out natural hair?"

### Texture Recommendation Logic
```
If reverts → Kinky Curly
If doesn't revert + leave out → Deep Wave with closure recommended
If doesn't revert + closure → Either works, Deep Wave preferred
```

### K-Tips Specific Questions
1. Hair density? (Fine/Medium/Thick)
2. Length goal?
3. Adding volume only or volume + length?
4. Chemical history? (relaxer/color/bleach)
5. Daily styling routine?

### K-Tips Photo Requirements (MANDATORY)
- Photo 1: Hair dry — full head
- Photo 2: Hair wet or with product (curl pattern)
- Photo 3: Scalp and hairline close-up

### Oracle Knowledge Bank Topics
- All service pricing and deposits
- Hair texture matching
- Strand/bundle count by density
- Booking policies (48hr cancellation)
- Delivery info (no local pickups)
- Loyalty program (Gold Coins)
- Wholesale requirements
- Escalation to stylist (WhatsApp)

---

## 📦 PRODUCT KIT SYSTEM

### 3-Tier Kit Structure
```
Tier 1 (Entry) — "The Beginning"
  - 2 bundles + basic tools
  - Price: ~$175-$250

Tier 2 (Mid) — "The Ascension" — MOST POPULAR
  - 3 bundles + professional tools
  - Price: ~$300-$400

Tier 3 (Premium) — "The Divinity"
  - 4 bundles + HD frontal + luxury add-ons
  - Price: ~$500-$600
```

### Kit Box Visual Requirements
For Gemini image generation:
- Matte black magnetic box
- Gold fleur-de-lis exterior pattern
- Gold "Hair Deity" script on front
- Black velvet/foam interior
- Kit info printed inside lid in gold text
- Dark marble surface
- Hollywood vanity mirror with bulbs background
- All items visibly arranged inside

---

## 💆 SERVICE SHOWCASE FRAMEWORK

### Each Service Page Must Include
1. Full-screen hero with real service image
2. Service description (what it is)
3. Why clients choose this service (5 feature cards)
4. Technique diagram (step by step SVG)
5. Hair pricing table (if applicable)
6. Texture selector
7. Step-by-step journey (5-6 steps)
8. Oracle mini-chat
9. Policy strip (4 items)
10. CTA bottom section

### Technique Diagram Style
- SVG format, 680px wide
- Background: #0a1628
- Border: rgba(200,168,75,0.2)
- Step boxes: rgba(14,58,74,0.5) with teal left border
- Key technique step: rgba(20,50,35,0.4) with gold border
- All text in Cinzel/Cormorant Garamond
- Gold arrows between steps
- Illustrations using SVG paths and shapes

---

## 📅 BOOKING PLATFORM FRAMEWORK

### 4-Step Booking Flow
1. **Service Selection** — with hair add-on calculator
2. **Date & Time** — calendar (closed Sun/Mon for beauty)
3. **Client Info** — name, email, phone, referral, notes
4. **Payment** — Stripe + PayPal, policy checkbox

### Calendar Rules
- Show only available days (close Sun/Mon by default)
- Long services (4-6hr): limit to 9AM or 1PM slots only
- Short services: show full day slots
- Add 30-min buffer between appointments

### Admin Dashboard Must Include
- Stats: appointments, pending, revenue, deposits
- Appointment list with status chips
- Confirm/Complete/Cancel actions
- Today's schedule sidebar
- Revenue breakdown by service
- Quick actions (reminders, booking link, block date)

---

## 💳 STRIPE INTEGRATION

### Setup Checklist
1. Create products for all services and kits
2. Get publishable key (pk_live_...)
3. Get price IDs for each product (price_...)
4. Load Stripe JS in <head> — MUST be first script
5. Initialize Stripe lazily on window.load event
6. Apply local tax rate automatically

### Payment Modal Requirements
- Card payment tab
- Apple Pay tab
- Google Pay tab
- Order summary with tax breakdown
- SSL security badge
- Receipt email field
- Test card: 4242 4242 4242 4242

### Common Issues
- "Stripe is not defined" → Move CDN to <head>, initialize on window.load
- Payments not processing → Check price IDs match test/live mode

---

## 🎬 MUSE PROGRAM FRAMEWORK

### Media Permission Form Fields
- Full name, email, phone
- Instagram + TikTok handles
- Service booked
- Individual permission checkboxes (video, photos, Instagram, TikTok, website, ads)
- "Grant all" checkbox
- Restriction options (no face, no tag, no ads)
- Notes field
- Legal release statement
- Digital signature + date

### Muse Perks to Offer
- Professional content theirs to keep
- Featured on social media
- Tagged and credited
- Priority booking
- Loyalty coin bonus
- Discount on next service

---

## 🚀 LAUNCH SEQUENCE

### Phase 1 — Model Call
- Friends and family — free
- Social media models — hair cost only
- Goal: 3-5 real heads for portfolio

### Phase 2 — Founding Client Offer
- Full price — no discounts
- Added value: free consultation, muse package, priority booking
- Limited to 10 spots
- Require: media permission + Google review + social follow

### Phase 3 — Official Launch
- Site fully live
- All systems operational
- Social media active
- Reviews established

---

## 📱 SOCIAL MEDIA CONTENT STRATEGY

### TikTok/Instagram Content Types
1. Before/after transformations (highest performing)
2. Technique process videos (builds trust)
3. Product unboxing (kit content)
4. Oracle AI demo (unique differentiator)
5. Client testimonials
6. Educational content (K-Tips vs Sew-In etc.)

### Hashtag Strategy (Charlotte NC)
```
#CharlotteNChair #CharlotteHair #CLTHair
#KTipsCharlotte #KTipExtensions #BrazilianKnots
#HairDeity #HairOfAGoddess #LuxuryHair
#NaturalHair #4CHair #KinkyCurly #DeepWave
#HairExtensions #CharlotteNC
```

---

## 🔧 TECHNICAL NOTES

### File Size Management
- Embed images as base64 for standalone HTML
- Images add ~1-2MB each in base64
- Keep total file under 50MB for IONOS upload
- Consider external image hosting for production

### Common Browser Issues
- Stripe "not defined" → Initialize on window.load
- Anchor links not scrolling → Use JS scrollIntoView instead of href="#"
- Fixed overlays blocking content → Ensure display:none by default
- Font not loading → Add Google Fonts link in <head>

### IONOS Deployment
- File must be named exactly: index.html (lowercase)
- Upload to: public_html folder
- Domain connects automatically if purchased together
- SSL activates within minutes

---

## 📋 GEMINI IMAGE PROMPTS

### Service Images
Always start with:
"Generate an image for me. Create a brand new luxury beauty photography image from scratch."

Always end with:
"Background: Dark luxury salon, warm golden light, Hollywood vanity mirror with round bulbs, dark marble surface. Color palette: Black, gold, deep navy blue only. Style: Ultra realistic luxury beauty photography. No white backgrounds."

### Kit Box Images
"Matte black magnetic gift box. Gold fleur-de-lis pattern on exterior. Gold Hair Deity script. Black velvet interior. Kit info in gold text inside lid. Dark marble surface. Glamour vanity mirror with bulbs background. Black and gold only."

### Key Rules
- Never use ✦ or ★ symbols — Gemini prints them literally
- Specify exact price in text: "$579.00" not just the number
- Say "Generate an image" not "Create" or "Make"
- For consistency: reference previous images in the series

---

## ✅ QUALITY CHECKLIST

Before launch verify:
- [ ] All section IDs exist and nav links work
- [ ] Stripe test payments process successfully
- [ ] Oracle consultation flow completes
- [ ] Booking platform 4 steps work
- [ ] Kit showcase pages open correctly
- [ ] Service showcase pages open correctly
- [ ] Media release form submits
- [ ] Mobile responsive on iPhone
- [ ] All images display correctly
- [ ] Tax calculates at correct local rate
- [ ] Deposit amounts are correct throughout
- [ ] No console errors in browser

---

*Hair Deity Web Design Skill v1.0 — Built September 2026*
*Based on the Hair Deity flagship website build*
