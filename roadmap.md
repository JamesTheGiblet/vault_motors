# 🗺️ Vault Motors – Project Roadmap

This roadmap outlines the phased development plan for **Vault Motors**, a lean PWA-based car listing platform designed for speed, simplicity, and long-term flexibility.

---

## ⚙️ Phase 1 – MVP Launch (Public Demo)

✅ Basic car listing UI  
✅ Image-first design (carousel per listing)  
✅ Radial side menu with listing sections: Details, History, Performance, Contact  
✅ Responsive layout (mobile-first)  
✅ Public-facing JSON data (`listings.json`)  
✅ Direct contact via phone/WhatsApp/email  
✅ Installable PWA (manifest + service worker)  
✅ Hosted on GitHub Pages

> 🎯 Goal: Provide a fully browsable, offline-capable public demo. Zero login, zero server, maximum feel.

---

## 🔁 Phase 1.5 – Visual Polish & User Cues

⬜ Visual state for active filters  
⬜ “Contact trader” overlay CTA  
⬜ Install prompt animation (custom banner)  
⬜ Fallback image loader for missing thumbnails  
⬜ Animated radial menu microinteractions  
⬜ Feature badges overlay on listing images (“MOT Fresh”, “Featured”, etc.)

---

## 🔐 Phase 2 – Trader Tools (Optional Expansion)

⬜ Login system (Supabase or Firebase Auth)  
⬜ Submission portal for traders  
⬜ Trader listing dashboard  
⬜ Trader logo/icon on listings  
⬜ GDPR-safe storage of contact + car data  
⬜ Role-based publishing tools (optional moderation)

---

## 💰 Phase 2.5 – Monetization & Subscriptions

⬜ Pay-as-you-go Stripe form  
⬜ Listing credits with discount tiers  
⬜ Subscription tiers: Starter, Pro, Elite  
⬜ Featured listing and boost upgrades  
⬜ Loyalty discounts for consistent subscribers  
⬜ Admin panel to view listing/usage stats

---

## 📦 Phase 3 – Native App Conversion (Optional)

⬜ Capacitor-based wrapper (iOS + Android)  
⬜ App Store/Play Store submission  
⬜ App icon, splash screen, push notification integration  
⬜ In-app deep linking for direct listing URLs

---

## 📈 Phase 4 – SEO & Outreach Tools

⬜ Static OpenGraph tags per listing  
⬜ Dynamic meta-data generation  
⬜ Sitemap and robots.txt  
⬜ Submission page QR code for print flyers  
⬜ Trader public pages (profile, active listings)

---

## 🔄 Phase X – Ideas to Revisit or Park

- AI image caption generator  
- Location-aware filters  
- Admin moderation queue  
- Feedback tool on each listing  
- Share-to-social copy blocks

---

### 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Tailwind or CSS Grid), vanilla JS  
- **Hosting**: GitHub Pages (initial), Vercel/Netlify (optional later)  
- **Data**: JSON-based flat listing for MVP, Supabase/Sanity later  
- **Auth**: Firebase or Supabase (Phase 2+)  
- **Payments**: Stripe or LemonSqueezy  
- **App Wrapper**: Capacitor (Phase 3)

---

### ✍️ Maintained by [@James-The-Giblet](https://github.com/james-the-giblet)  
*Built with grit, vision, and a splash of gin.*
