# Hair Deity — Hair of a Goddess
**Website:** [hairdeity.com](https://hairdeity.com)

> Luxury hair extensions and divine installs by Eva Marie. Custom K-Tip Extensions, Brazilian Knots, Traditional Sew-Ins and Deity Kits. Delivered 24/7 via Deity Dash. Charlotte NC.

---

## 🔮 Project Overview

Hair Deity is a full luxury e-commerce and booking platform built as a single-file HTML application. The site includes:

- Full luxury e-commerce experience
- AI-powered Oracle concierge
- Complete booking platform with admin dashboard
- Stripe payment integration
- 3 Deity Kit product showcases
- 3 Service showcase pages (K-Tips, Brazilian Knots, Sew-In)
- Step-by-step technique diagrams
- Hair Deity Muse media permission system
- Gold Coin loyalty program
- Wholesale Sanctuary portal
- Deity Dash delivery section
- VAPI voice agent configuration

---

## 📁 Repository Structure

```
hairdeity-repo/
├── index.html              # Complete site — upload to IONOS public_html
├── README.md               # This file
├── docs/
│   ├── BRAND_GUIDE.md      # Colors, fonts, brand guidelines
│   ├── SERVICES.md         # Complete service menu and pricing
│   ├── STRIPE_CONFIG.md    # Stripe products and price IDs
│   └── LAUNCH_CHECKLIST.md # Go-live checklist
└── config/
    └── oracle-vapi.json    # VAPI AI agent configuration
```

---

## 🎨 Brand Guidelines

| Element | Value |
|---|---|
| Primary Background | `#0a1628` Deep Ocean Blue |
| Secondary Background | `#0d2137` |
| Teal Accent | `#0e3a4a` |
| Gold Primary | `#c8a84b` |
| Gold Light | `#e8c96a` |
| Gold Bright | `#f5d98a` |
| Gold Dim | `#8a6e2a` |
| Cream Text | `#f5f0e8` |
| Body Text | `#d4c5a0` |
| Headline Font | Cinzel Decorative |
| Subheading Font | Cinzel |
| Body Font | Cormorant Garamond |

---

## 💰 Service Pricing

| Service | Price | Deposit |
|---|---|---|
| K-Tips Full Head 14"–18" | $800 all inclusive | $400 |
| K-Tips Half Head 14"–18" | $500 all inclusive | $250 |
| K-Tips Maintenance | $175 | Full |
| K-Tips Removal | $125 | Full |
| Brazilian Knots | $400 | $200 |
| Traditional Sew-In | $175 | $75 |
| Wig Drop-Off Prep | $75 | Full |
| Wig Installation | $50 | At appt |
| Consultation | $50 | Full |

---

## 🛍️ Deity Kit Pricing

| Kit | Price |
|---|---|
| Acolyte Basic Kit | $199 |
| Goddess Premium Kit | $369 |
| Supreme Deity Kit | $579 |

---

## 💳 Stripe Configuration

**Mode:** Test (switch to live before launch)
**Publishable Key:** `pk_test_51UDWod...` (stored in index.html)

| Product | Price ID |
|---|---|
| K-Tips Full Head Deposit | `price_1UDo7FIQxJoiFgM3uHz3Wdrs` |
| K-Tips Half Head Deposit | `price_1UDo6hIQxJoiFgM32XrNNYTH` |
| Brazilian Knots Deposit | `price_1UDZKjIQxJoiFgM3PcMXhE1O` |
| Sew-In Deposit | `price_1UDe8YIQxJoiFgM337E8qZT5` |
| Acolyte Basic Kit | `price_1UDYIMIQxJoiFgM3DbHAVDY3` |
| Goddess Premium Kit | `price_1UDYRLIQxJoiFgM3VRvlebzY` |
| Supreme Deity Kit | `price_1UDYSTIQxJoiFgM3lDp6GcjL` |
| Consultation | `price_1UDeBwIQxJoiFgM33iIos3MB` |

---

## 🚀 Deployment

### IONOS Upload
1. Log into IONOS dashboard
2. Go to Hosting → File Manager
3. Open `public_html` folder
4. Upload `index.html`
5. Verify at hairdeity.com

### Switch to Live Payments
1. Get live keys from Stripe Dashboard → Developers → API Keys
2. Replace `pk_test_` with `pk_live_` in index.html
3. Replace all `price_` test IDs with live price IDs
4. Re-upload index.html

---

## 🔮 The Oracle — VAPI Configuration
See `config/oracle-vapi.json` for the complete VAPI voice agent setup.

**Still needed:**
- WhatsApp Business number for Eva Marie
- Anthropic API key for website Oracle AI
- VAPI account at vapi.ai

---

## 📅 Launch Checklist

- [x] Domain purchased — hairdeity.com
- [x] IONOS hosting purchased
- [x] Stripe account created (test mode)
- [x] All 17 Stripe products created
- [x] index.html built and ready
- [ ] Upload index.html to IONOS
- [ ] Switch Stripe to live mode
- [ ] Get WhatsApp Business number
- [ ] Set up VAPI voice Oracle
- [ ] Get Anthropic API key
- [ ] Create professional emails on IONOS
- [ ] Model call — first 3-5 real heads
- [ ] Launch Founding Goddess offer

---

## 📞 Business Information

**Brand:** Hair Deity LLC
**Stylist:** Eva Marie
**Location:** Charlotte, NC
**Hours:** Tuesday–Saturday, 9AM–6PM
**Website:** hairdeity.com
**Delivery:** Deity Dash — 24/7

---

© 2025 Hair Deity LLC. All rights reserved. Hair of a Goddess™
