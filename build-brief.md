# Build Brief — Dental Wellness of Charlotte

## Task
Build a complete, production-quality single-file landing page and save it as index.html in the current directory.

Read C:/workspace/projects/website-building-agency/clients/jf-air-and-heat/index.html first.
Match that level of quality: full inline CSS, schema.org JSON-LD, Google Fonts, smooth scroll, mobile responsive.

## Business Data
- **Name:** Dental Wellness of Charlotte
- **Tagline:** Charlotte's Premium Dental Care
- **Phone:** (704) 317-7337
- **Address:** 9915 Sandy Rock Pl, Suite 200, Charlotte, NC 28277
- **Hours:** Mon-Thu 8:00 AM - 4:30 PM | Fri 8:00 AM - 1:30 PM | Sat-Sun Closed
- **Founded:** 2010
- **Owner/Doctor:** Dr. Sergei Shirman, DDS
- **Rating:** 5.0 stars (380+ reviews)
- **Schema type:** Dentist (schema.org)
- **Canonical URL:** https://dental-wellness-charlotte.vercel.app

## Services
1. General & Preventive Dentistry
2. Cosmetic Dentistry & Veneers
3. Dental Implants
4. Invisalign & Clear Aligners
5. Teeth Whitening
6. Emergency Dental Care

## Design System
- **Palette:**
  - Deep Teal: #0D4A52 (primary dark)
  - Teal-mid: #0E5A63
  - Teal-light: #10707C
  - Accent: #14B8A6 (bright teal accent)
  - Warm Cream: #FAF7F2 (section backgrounds)
  - Off-white: #F5F2EE
  - White: #FFFFFF
  - Gold: #D4A853 (secondary accent, star ratings)
  - Charcoal: #1C2B2D (text)
  - Gray-400: #94A3B8
  - Gray-200: #E2E8F0
- **Fonts:** Plus Jakarta Sans (all weights) + Cormorant Garamond Italic (dramatic display) from Google Fonts
- **Aesthetic:** Clinical boutique. Clean, premium, trustworthy. Cream backgrounds with teal accents. Sophisticated and calm.

## Page Sections (in order)
1. **Nav** — sticky, white bg, logo left ("Dental Wellness of Charlotte"), "Book Appointment" teal CTA button right
2. **Hero** — full viewport, cream bg left column text, deep teal right column decorative shape. Large headline in Plus Jakarta Sans Bold, italic Cormorant Garamond display accent line. Subtext about modern comfortable dentistry. Two CTAs: teal "Book Appointment" + outline "Call (704) 317-7337". Trust row: 5.0 stars, 380+ Reviews, 15 Years, Dr. Shirman DDS
3. **Services** — cream section, teal-outlined service cards grid (3 cols). Each: teal SVG icon, service name, 1-line description
4. **About Dr. Shirman** — two column: teal placeholder square (initials "SS") left, bio paragraph right. Patient-first philosophy, advanced training, modern techniques
5. **Why Choose Us** — deep teal bg, white text stat blocks: 5.0 Stars, 380+ Patients, 15+ Years, Latest Technology
6. **Trust Signals** — cream bg, icon badges: ADA Member, State Licensed, Insurance Accepted, Sedation Available, Same-Week Appointments, Flexible Hours
7. **CTA Banner** — deep teal bg, headline "Ready for a Smile You Love?", subtitle, light teal "Book Your Appointment" button, phone number
8. **Footer** — charcoal bg, practice name, address, hours, phone, copyright

## Technical Requirements
- Single file: all CSS inline in style tag, no external CSS files
- Google Fonts via link tag (Plus Jakarta Sans + Cormorant Garamond)
- Schema.org JSON-LD for Dentist type with address, phone, hours, geo coords (latitude: 35.0540, longitude: -80.8450), aggregateRating ratingValue 5.0 reviewCount 380
- Smooth scroll behavior
- Mobile responsive
- OG meta tags pointing to https://dental-wellness-charlotte.vercel.app
- All CTAs link to tel:7043177337
