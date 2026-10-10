# La Vista Developments — Dedicated Architectural Showcase Portfolio

An ultra-luxurious, modern, mobile-responsive landing page showcasing the premier development portfolio of **La Vista Developments (New Cairo & Capital Portfolio)**, operated by **properties-z.com**.

---

## 🏛️ Architectural Layout Evolution (Full-Width Dedicated Sections)

As requested, the portfolio is no longer a compressed grid or summary cards. 
**Each development is its own dedicated, full-width section** with:
- An individual architectural backdrop & high-resolution visual render
- Dedicated project narrative & architectural positioning
- Unit typologies & space specifications (SQM)
- Distinct financial console with starting price formatted in clean capital **'M'** (e.g., `31M EGP`, `9M EGP`)
- Payment schedules (up to 10 years installments, 0% & 5% down payments)
- Dedicated project-specific WhatsApp CTA button (`#25D366`) reading **`CONTACT US`** with prefilled inquiry message (`Hello, I would like to inquire about [Project Name]`).

---

## 🎨 Strict Zero Gold Policy & Calm Luxury Aesthetic

- **Strict Zero Gold Policy**: Absolutely no gold, bronze, brass, or yellow tones anywhere across the application.
- **Calm Luxury Color Palette**:
  - **Dominant**: Crisp pure white (`#FFFFFF`), clean alabaster (`#FAFBFD`), and stone/platinum grey (`#F8F9FA` / `#F1F3F5`).
  - **Accents**: Deep rich charcoal & slate (`#1A202C` / `#2D3748`).
  - **Cards & Consoles**: Translucent frosted white cards (`rgba(255, 255, 255, 0.92)`) with delicate 1px borders (`#E2E8F0`) and backdrop blur.
  - **Typography**: Tailored editorial Serif headlines (`Cinzel`) paired with modern Sans-serif (`Plus Jakarta Sans`).

---

## 📐 Global UI & Navigation Rules

1. **Flush Hero (Strictly NO Top Sticky Menu)**:
   - Starts directly at `top: 0` of the viewport with no top sticky/fixed white header bar or navigation strip.
2. **Official Branding & Global Sub-Branding**:
   - Official La Vista Developments XL Logo (`assets/images/lavista_logo.png`) with `By properties-z.com` styled in letter-spaced caps underneath in Hero and Footer.
3. **Price Formatting**:
   - Strictly capital **'M'** format across all 7 projects.
4. **Mobile Responsiveness**:
   - 100% mobile-first single column responsive flow with thumb-friendly controls (min 52px touch targets).
5. **WhatsApp Integration**:
   - **Floating Button**: Round green icon-only button (`#25D366`) linking directly to `+201033373331` (no text label).
   - **Inline Project CTAs**: Solid vibrant WhatsApp Green (`#25D366`) reading `CONTACT US` with dedicated prefilled inquiry texts.
6. **Backend Lead Routing & Zapier Webhook**:
   - Integrated with live Zapier Webhook: `https://hooks.zapier.com/hooks/catch/25429357/uclzmpn/`
   - Automatically passes:
     - `fullName`: Full submitted name
     - `phoneNumber`: International phone number with country dial code
     - `landingPageUrl`: Full URL of the landing page
     - `submissionDate`: ISO 8601 submission timestamp
   - Multi-recipient email routing fallback:
     - `Rahma@irtkaz.com`
     - `Mostafa.a.ashmawy@gmail.com`
     - `Mostafa.ashmawy@irtkaz.com`
   - Backed by persistent browser storage in `localStorage` under `lavista_inquiries`.
7. **Standalone Legal Routed Pages**:
   - `terms.html`: Standalone routed Terms & Conditions (100% white text on solid black background).
   - `privacy.html`: Standalone routed Privacy Policy (100% white text on solid black background).

---

## 📂 7 Dedicated Sections in Chronological Order

1. **Section 1: El-Patio Town Side** (`#el-patio-town-side`)
   - New Cairo | First Launch | Villas Only | Starting from 225 SQM | 31M EGP
2. **Section 2: El Patio Town** (`#el-patio-town`)
   - New Cairo | Delivery in 2 Years | Luxury Villas | 30M EGP | 5% DP, 7 Years
3. **Section 3: El Patio Oro** (`#el-patio-oro`)
   - New Cairo | Ready to Move Available | 10% Down Payment | 17.2M EGP | 7 Years
4. **Section 4: Patio Vida** (`#patio-vida`)
   - 5th Settlement | Luxury Apartments & Signature Duplexes | 11.5M EGP | 5% DP, 10 Years
5. **Section 5: Patio Riva** (`#patio-riva`)
   - 5th Settlement | Tranquil Lush Landscapes | 9M EGP (Portfolio Starting Point) | 5% DP, 8 Years
6. **Section 6: Patio Hills** (`#patio-hills`)
   - 5th Settlement | Exclusive Private Standalone Villas Only | 21M EGP | 5% DP, 8 Years
7. **Section 7: Patio Jade** (`#patio-jade`)
   - New Administrative Capital | Luxury Villas & Apartments | 19.8M EGP | 5% DP, 10 Years
