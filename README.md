[README.md](https://github.com/user-attachments/files/26505382/README.md)
# 🌿 Mirava Hospitality — Website

A clean, responsive 3-page static website for **Mirava Hospitality**, a curated coastal stay management company operating in **Alibag & Murud**, Maharashtra. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step required.

---

## 📁 Project Structure

```
mirava-hospitality/
├── index.html          # Home page
├── properties.html     # Properties listing page
├── contact.html        # Booking inquiry / contact page
├── style.css           # Shared stylesheet (all 3 pages)
└── README.md           # This file
```

---

## 🖥️ Pages Overview

### 1. Home (`index.html`)
- Full-screen hero banner with tagline and call-to-action
- Quick search strip (property type, check-in, check-out, guests)
- Stats bar (properties, locations, guests, rating)
- "Why Choose Us" — 4 feature cards
- Featured properties section (3 cards)
- Guest testimonials (3 reviews)
- CTA banner with links to Properties and Contact pages

### 2. Properties (`properties.html`)
- Sticky filter bar — filter by **type** (Villa / Hotel / Cottage) and **location** (Alibag / Murud)
- 6 property cards with amenities, pricing, and ratings
- Each "Book Now" button deep-links to the contact form with the property pre-selected
- Animated card entrance on scroll
- Live count of filtered results

### 3. Contact / Booking (`contact.html`)
- Full booking inquiry form with fields:
  - Full Name, Mobile Number, Email Address
  - Check-In & Check-Out Dates
  - Number of Guests, Number of Rooms
  - Property Type selector (Villa / Hotel / Cottage)
  - Property dropdown (filtered by selected type)
  - Special Requests & How did you hear about us
- Contact sidebar with phone, email, location, and WhatsApp button
- Properties list sidebar for quick reference
- Success confirmation screen after form submission
- Form validation with visual error highlights

---

## 🚀 Deployment (GitHub + Vercel)

### Step 1 — Push to GitHub
```bash
# Initialize a new git repo inside this folder
git init
git add .
git commit -m "Initial commit — Mirava Hospitality website"

# Create a new repo on GitHub and push
git remote add origin https://github.com/YOUR_USERNAME/mirava-hospitality.git
git branch -M main
git push -u origin main
```

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **"Add New Project"** → **"Import Git Repository"**
3. Select your `mirava-hospitality` repo
4. Leave all settings as default (Vercel auto-detects static HTML)
5. Click **"Deploy"** — your site will be live in seconds!

### Step 3 — Custom Domain (Optional)
In your Vercel project dashboard → **Settings → Domains** → add your domain (e.g. `miravahospitality.com`)

---

## ✏️ Customisation Checklist

Before going live, update the following placeholder values:

| Location | What to Update |
|---|---|
| All 3 HTML files | Phone number: `+91 98XXX XXXXX` |
| All 3 HTML files | Email: `hello@miravahospitality.com` |
| `contact.html` | WhatsApp link: `https://wa.me/91XXXXXXXXXX` |
| `properties.html` | Add real property images (replace gradient backgrounds) |
| `properties.html` | Update property names, descriptions, pricing |
| `index.html` | Update testimonials with real guest reviews |
| `index.html` | Update stats (properties count, guests served, etc.) |

---

## 🎨 Design System

**Theme:** Tropical & Fresh — coastal Konkan vibes

| Token | Value | Use |
|---|---|---|
| `--primary` | `#1B4332` | Deep forest green — headings, buttons |
| `--primary-mid` | `#2D6A4F` | Primary interactive elements |
| `--accent` | `#52B788` | Highlights, tags, focus states |
| `--accent-pale` | `#D8F3DC` | Backgrounds, hover states |
| `--sand` | `#F7F4EB` | Section backgrounds |
| `--gold` | `#C9A84C` | Star ratings, accents |

**Fonts (Google Fonts):**
- `Playfair Display` — headings and brand name
- `Inter` — body text and UI elements

---

## 📞 Contact

**Mirava Hospitality**
Alibag, Raigad District, Maharashtra
📞 +91 98XXX XXXXX
📧 hello@miravahospitality.com

---

*Built for Mirava Hospitality — Curating the finest coastal stays on the Konkan coast* 🌊
