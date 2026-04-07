# 🍊 LIQUID VITALITY — Project README

**Premium Cold-Pressed Juice Website**
Built by feontend • Full website with Sign In, Cart, Billing & Account

---

## 🚀 HOW TO RUN

1. Unzip the project folder
2. Drop your images into the `assets/` subfolders (see below)
3. Double-click `index.html` — opens in any browser. Done.

No server. No install. No npm. Just open and go.

---

## 📁 FOLDER STRUCTURE

```
liquid-vitality/
├── index.html                        ← Your entire website (open this)
└── assets/
    ├── logo/
    │   ├── logo-icon.png             ← LV orange square icon (500×500 PNG transparent)
    │   └── logo-full.png             ← Full "Liquid Vitality." wordmark
    ├── hero/
    │   ├── hero-bg.jpg               ← Hero background splash (1920×1080 JPG)
    │   └── hero-bottle.png           ← Floating bottle, transparent BG (800×1200 PNG)
    ├── frames/
    │   ├── orange/
    │   │   ├── frame1.jpg            ← Calm bottle (scroll animation frame 1)
    │   │   ├── frame2.jpg            ← Tilt / first splash
    │   │   ├── frame3.jpg            ← Mid explosion
    │   │   ├── frame4.jpg            ← Full chaos splash
    │   │   └── frame5.jpg            ← Settling / beautiful pour
    │   └── green/
    │       ├── green1.jpg            ← Green bottle (scroll animation frame 1)
    │       ├── green2.jpg            ← Kiwi explosion
    │       ├── green3.jpg            ← Green pour + leaves
    │       └── green4.jpg            ← Close-up detox
    ├── sections/
    │   ├── feature-split.jpg         ← Orange pour (left side split section, 1200×900)
    │   └── kiwi-banner.jpg           ← Full-width kiwi banner (1920×700)
    ├── products/
    │   ├── cherry.jpg                ← Wild Cherry product card (600×600)
    │   ├── blueberry.jpg             ← Vibrant Blueberry
    │   ├── strawberry.jpg            ← Pure Strawberry
    │   ├── green.jpg                 ← Green Refresh
    │   ├── orange.jpg                ← Sunrise Orange
    │   └── mango.jpg                 ← Mango Paradise
    ├── wellness/
    │   ├── vitamins.jpg              ← Wellness card 1 (700×500)
    │   ├── energy.jpg                ← Wellness card 2
    │   └── antioxidants.jpg          ← Wellness card 3
    └── avatars/
        ├── sarah.jpg                 ← Review avatar (200×200)
        ├── james.jpg                 ← Review avatar
        └── emily.jpg                 ← Review avatar
```

---

## ✅ PAGES & FEATURES

| Page | What's Inside |
|---|---|
| **Home** | Hero, scroll canvas animation, products carousel, kiwi banner, green canvas, wellness cards, testimonials, partners, footer |
| **Products** | Full grid of 12 juice products with Add to Cart |
| **Wellness** | 6 blog article cards |
| **Billing** | 3 subscription plans, payment form, delivery address, order summary |
| **Account** | Overview, Orders history, Subscription manager, Settings (edit name/email/password) |

### All Working Buttons
- ✅ Sign In (email + Google + Apple)
- ✅ Sign Up (with validation)
- ✅ Sign Out
- ✅ Add to Cart (any product)
- ✅ Cart sidebar (qty +/−, remove, total)
- ✅ Checkout → Billing flow
- ✅ Plan selector (Starter / Vitality / Elite)
- ✅ Complete subscription
- ✅ Account tabs (Overview / Orders / Subscription / Settings)
- ✅ Save settings / Change password
- ✅ Cancel subscription
- ✅ Canvas scroll animation (orange + green)
- ✅ Product carousel (drag + arrows)
- ✅ Scroll reveal animations on all sections

---

## 🎨 CREATING YOUR ASSETS IN CANVA

> See the full step-by-step guide in `asset-creation-guide.html`

### Quick Canva Workflow
1. Go to **canva.com** → Create design → Custom size
2. Use **Apps → Text to Image** and paste the prompts from the guide
3. Export as **JPG** (sections/products/wellness) or **PNG transparent** (logo/bottle)
4. Rename files exactly as shown above
5. Drop into the correct `assets/` subfolder

### Important Export Settings
| Asset Type | Format | Size | Transparent? |
|---|---|---|---|
| Logo icon | PNG | 500×500 | ✅ YES |
| Hero bottle | PNG | 800×1200 | ✅ YES |
| Hero background | JPG | 1920×1080 | No |
| Canvas frames | JPG | 1920×1080 | No |
| Kiwi banner | JPG | 1920×700 | No |
| Product cards | JPG | 600×600 | No |
| Wellness cards | JPG | 700×500 | No |
| Avatars | JPG | 200×200 | No |

---

## 🔄 IMAGE FALLBACK SYSTEM

If any local image is missing, the website **automatically loads from Unsplash** so nothing breaks. You'll see placeholder images from the internet until you add your own Canva assets.

---

## 🌐 DEPLOY TO THE INTERNET (Optional)

To put it online for free:

### Option A — Netlify (Easiest, 2 minutes)
1. Go to **netlify.com** → Sign up free
2. Drag and drop your entire `liquid-vitality/` folder onto the Netlify dashboard
3. You get a live URL instantly (e.g. `liquid-vitality-abc123.netlify.app`)

### Option B — GitHub Pages
1. Create a free GitHub account → New repository
2. Upload all files → Go to Settings → Pages → Deploy from main branch
3. Live at `yourusername.github.io/liquid-vitality`

---

## 🎨 DESIGN DETAILS

| Property | Value |
|---|---|
| Primary Font | Bebas Neue (headings) |
| Body Font | Outfit (Google Fonts) |
| Primary Color | #F47B20 (orange) |
| Dark Color | #1A0F08 |
| Cream | #FFF8F0 |
| Canvas Animation | HTML5 Canvas + JS scroll listener |
| Images | Local assets with Unsplash fallback |
| Auth | Client-side simulation (session only) |
| Cart | JavaScript in-memory state |

---

## ⚠️ NOTES

- Auth is **demo only** — no real backend. Refreshing the page resets login state.
- To add real auth, connect to **Firebase**, **Supabase**, or any backend.
- To add real payments, integrate **Stripe** or **PayPal**.
- The website is fully **mobile responsive**.