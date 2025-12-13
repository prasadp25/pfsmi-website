# PFSMI Project Documentation

## Project Overview

**Project Name:** PROTECTHER Fire & Safety Management Institute (PFSMI) Website
**Type:** Static HTML Website
**Location:** `C:\Users\PC-05\Projects\pfsmi`

### Quick Start
```
# Open in browser directly:
file:///C:/Users/PC-05/Projects/pfsmi/index.html

# Or run local server:
npx serve -p 8080
# Then visit: http://localhost:8080
```

---

## About the Client

**PROTECTHER Fire & Safety Management Institute (PFSMI)** is a fire and safety education institute located in Pune, India.

### Contact Information
- **Address:** F 507, Mega Center, Magarpatta, Hadapsar, Pune, Maharashtra 411013
- **Phone:** +91 8830024093, +91 8888201419
- **Email:** info@protecther.com, admissions@protecther.com
- **Student Portal:** https://protecther.site/
- **WhatsApp:** +91 8830024093

### Social Media
- Facebook: https://www.facebook.com/profile.php?id=100093077889265
- Instagram: https://www.instagram.com/protectherfireandsafety/
- LinkedIn: https://www.linkedin.com/company/protectherpfsmi/
- YouTube: https://www.youtube.com/channel/UCH3buo5hAMoBqLk7xmQzV6A

### Leadership
- **Director:** Ms. Bhagyashri Bhidekar
- **Co-Director:** Mr. Mahesh Shelote

---

## Project Structure

```
pfsmi/
├── index.html          # Homepage
├── about.html          # About Us page
├── courses.html        # All courses listing
├── certifications.html # Certification programs (NEBOSH, IOSH, etc.)
├── admissions.html     # Admissions info & application form
├── placements.html     # Placement cell & recruiters
├── gallery.html        # Photo & video gallery
├── contact.html        # Contact form & info
├── css/
│   └── styles.css      # Main stylesheet (large file ~40k tokens)
├── js/
│   └── main.js         # Main JavaScript (sliders, animations, forms)
└── images/
    ├── PFASMI_logo.png # Institute logo
    ├── favicon.png     # Browser favicon
    └── New folder/     # Hero images
        ├── graduation.png
        ├── Fire drill.png
        ├── harness drill.png
        ├── drile.png
        └── First Aid Stretcher Drill.png
```

---

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styles in `css/styles.css`
- **Vanilla JavaScript** - `js/main.js`
- **Google Fonts:** Montserrat, Roboto
- **Font Awesome 6.4.0** - Icons (CDN)
- **External Images:** Unsplash (stock photos), Clearbit (company logos), RandomUser (testimonial avatars)

---

## Page Details

### 1. Homepage (index.html)
- Hero slider with 3 slides (auto-rotate every 5s)
- Stats bar (animated counters): 5000+ Graduates, 200+ Partners, 15+ Certifications, 95% Placement
- Accreditations section (NEBOSH, IOSH, ISO 9001:2015, NSDC)
- Featured courses grid
- Why Choose Us section
- Recruiters logo slider
- Testimonials slider
- Contact form

### 2. About (about.html)
- Institute story and background
- Vision & Mission cards
- Core Values section
- Leadership team profiles
- Services offered (Institute, E-Learning, Corporate Training)
- Affiliations (MSBTE, NCFSE Nagpur)
- Client logos

### 3. Courses (courses.html)
**Filter tabs** for course categories:

**Autonomous Courses (10 courses):**
- Diploma in Health, Safety and Environment
- Diploma in Fire and Safety Management
- Diploma in Industrial Safety Management
- Advance Diploma in Fire and Industrial Safety Engineering
- PG Diploma in Fire and Safety Management
- MBA in Fire & Safety Management
- Executive MBA in OHSE
- Executive MBA in Oil & Gas Management
- Executive MBA in Construction Safety Management
- Diploma in Disaster Management

**MSBTE Courses (8 courses):**
- Advance Diploma in Industrial Safety
- Advance Diploma in Industrial & Security Management
- Advance Diploma in Fire and Safety & Industrial Environment Engineering (FA)
- Diploma in Fire Service Engineering (FR)
- Advance Diploma in Project Management in Building Construction (PR)
- Advance Diploma in Energy Management & Audit (EW)
- Advanced Diploma in Environmental Engineering (EZ)
- Advance Diploma in Cyber Security Management (CB)

**MSBV Courses (7 courses):**
- Advance Diploma in Industrial Safety (MSBQ411217)
- Advance Diploma in Industrial Safety Management (MSBQ411218)
- Advance Diploma in Process Safety Management (MSBQ411220)
- Advance Diploma in Tunnel Safety (MSBQ411219)
- Diploma in Health Sanitary Inspector
- Diploma in Fire Technology and Safety Management
- Diploma in Fire and Industrial Safety Engineering (MSBQ411403)

**Certification Courses (3 courses):**
- Certificate in Health Sanitary Inspector
- Certificate Course Construction Supervisor
- Scaffolding Inspector

### 4. Certifications (certifications.html)
Featured certifications with detailed info:
- NEBOSH IGC (3 months)
- IOSH Managing Safely (4-5 days)
- Fire Safety Certification (1-2 months)
- First Aid & CPR Certification (2-3 days)

### 5. Admissions (admissions.html)
- Admission highlights (Open for 2024-25, Early bird discount)
- 5-step admission process
- Eligibility criteria for Diploma, PG Diploma, Certification
- Fee structure table
- Documents required checklist
- Application form

### 6. Placements (placements.html)
- Stats: 100% placement assistance, 200+ recruiters, 5000+ placed, 15+ sectors
- 5-step placement process
- Top recruiters grid (Tata, L&T, Adani, Reliance, JSW, etc.)
- Industry sectors (Construction, Manufacturing, Oil & Gas, etc.)
- Success stories/testimonials
- Placement registration form

### 7. Gallery (gallery.html)
- Photo gallery with filter (All, Campus, Training, Events, Graduation)
- Lightbox functionality for image viewing
- Video gallery section
- Uses Unsplash stock images as placeholders

### 8. Contact (contact.html)
- Contact info cards (Address, Phone, Email, Hours)
- Contact form with subject dropdown
- Embedded Google Maps
- Department contacts (Admissions, Placement, Corporate)
- FAQ accordion section

---

## JavaScript Features (main.js)

1. **Header scroll effect** - Adds `.scrolled` class on scroll > 100px
2. **Hero slider** - Auto-rotate every 5s, prev/next/dot controls
3. **Stats counter animation** - Animates numbers on scroll into view
4. **Testimonials slider** - Auto-rotate every 6s
5. **Mobile menu toggle** - Hamburger menu for responsive nav
6. **Back to top button** - Shows after 500px scroll
7. **Contact form validation** - Client-side email/required validation
8. **Scroll animations** - Fade-in cards on scroll (IntersectionObserver)
9. **Smooth scroll** - For anchor links

### Page-specific JavaScript:
- **courses.html** - Course category filter tabs
- **contact.html** - FAQ accordion
- **gallery.html** - Image filter, lightbox with keyboard navigation

---

## Common Components

### Header (all pages)
- Top bar with phone, email, social links, student portal link
- Logo linking to index.html
- Main navigation with dropdowns
- "Apply Now" CTA button
- Mobile hamburger menu

### Footer (all pages)
- Brand info and social links
- Quick Links, Our Courses, Resources, Contact Info columns
- Copyright and policy links

### Floating Elements
- WhatsApp chat button (bottom-right)
- Back to top button (bottom-right, shows on scroll)

---

## Styling Notes

- **Primary Color:** Blue (#1C549D based on gradients)
- **Secondary Color:** Orange/Gold (for accents)
- **Typography:** Montserrat (headings), Roboto (body)
- **Responsive:** Mobile-first with media queries
- **CSS file is large** (~40k tokens) - use line ranges when reading

---

## Forms (No Backend)

All forms use `e.preventDefault()` and show JavaScript alerts:
- Contact form (index.html, contact.html)
- Application form (admissions.html)
- Placement registration form (placements.html)

**Forms are NOT connected to a backend.** To make them functional, integrate with:
- Email service (EmailJS, Formspree)
- Backend API
- Google Forms/Sheets

---

## External Dependencies (CDN)

```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

---

## Known Issues / TODOs

1. **Placeholder images** - Gallery and some sections use Unsplash URLs; should be replaced with actual institute photos
2. **Forms non-functional** - Need backend integration
3. **Video gallery** - Play buttons are decorative; no actual video playback
4. **Company logos** - Using Clearbit API which may break; should host locally
5. **Student portal link** - Points to https://protecther.site/ (external)
6. **Privacy Policy / Terms** - Links are `#` placeholders

---

## Deployment

This is a static site. Can be deployed to:
- Any web hosting (shared hosting, VPS)
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

No build step required - just upload files.

---

## Maintenance Notes

- Update copyright year in footers annually
- Update batch year in admissions.html ("2024-25 Batch")
- Update testimonials with real student data
- Replace stock images with actual institute photos
- Add Google Analytics if needed
