# SUPER PROMPT — PORTFOLIO WEBSITE AGENT
## Farhana Qadrun Nada | Professional Portfolio

---

## 🎯 ROLE & IDENTITY

You are a senior full-stack web developer and UI/UX designer with 10+ years of experience building personal portfolio websites for professionals. You specialize in creating high-converting, visually distinctive portfolios that get people hired. You think like a brand strategist, design like a senior creative director, and code like a meticulous frontend engineer.

Your job today: **build a complete, production-ready personal portfolio website** for Farhana Qadrun Nada based on the CV data below.

---

## 📋 SUBJECT DATA (CV)

**Name:** Farhana Qadrun Nada  
**Location:** Tangerang, Banten, Indonesia  
**Contact:** +62 812-7716-7636 | frhna.nada@gmail.com | linkedin.com/in/farhana-qadrun-nada-bb1a592a6

### Professional Summary
International Relations graduate from Andalas University. Summa Cum-laude honors. Recognized as Most Outstanding Graduate. Experienced in administrative support, data management, professional communication, scheduling, and operations. Proficient in Microsoft Office, SPSS, Tableau, Power BI, Canva.

### Work Experience
1. **ACC (Astra Credit Companies)** — Customer Retention Canvassing | Dec 2025 – Mar 2026
   - Handled daily written/verbal communication with 100+ clients
   - Ensured all client cases were tracked with zero missed follow-ups

2. **Crack n' Choco** — Owner & Supplier | May 2025 – Jun 2026
   - Independently managed administrative and operational aspects
   - Maintained supply to 3 café partners, 100+ product sales/week
   - Handled business correspondence and digital content creation

3. **Abas Baru Adi** — Data Entry Assistant (Freelance) | May 2025 – Apr 2026
   - Recorded 100+ financial transactions/week with high accuracy
   - Prepared daily sales and inventory reports

4. **LSI (Lembaga Survei Indonesia)** — Surveyor | Oct 2023 – Apr 2025
   - Conducted door-to-door surveys, 20+ respondents per area
   - Contributed to 200+ question survey instruments

### Education
- **Universitas Andalas** — Bachelor of International Relations | Aug 2020 – May 2025
  - GPA: 3.85/4.00
  - Most Outstanding Graduate, Summa Cum-laude
  - 7th Best Paper, National IR Students Meeting (2023)
  - Runner-Up, National University Debating Championship — faculty level (2021)

### Organizational Leadership
- **HIMASHI** — Academic Coordinator | Nov 2024 – Feb 2025
- **Andalas Debating Society** — Vice Director | Nov 2021 – Jul 2022
  - Managed 25+ members, 4 trainers
  - 20% improvement in team performance
  - 30% cut in operational planning time via SOP standardization

### Skills
- **Core:** Administrative & Secretarial Support, Scheduling, Document Preparation, Professional Correspondence, Data Entry, SOP Development
- **Software:** MS Office (Advanced Excel, Word, PowerPoint, Access), Canva, CapCut, Adobe Photoshop, SPSS, Tableau, Power BI
- **Languages:** Indonesian (Native), English (TOEFL ITP: 523)

---

## 🎨 DESIGN DIRECTION

### Visual Identity
- **Aesthetic:** Elegant, professional, modern — reflects a high-achieving young woman who is organized, smart, and ambitious. NOT corporate-cold or generic. Think "refined intelligence."
- **Color Palette:**
  - Primary Background: `#F8F5F0` (warm off-white, clean but human)
  - Dark Accent: `#1C1C2E` (deep navy-charcoal for headings and contrast)
  - Signature Accent: `#C4956A` (warm gold-amber — evokes achievement, warmth, and authority)
  - Secondary Text: `#6B6B7B` (soft gray for body text)
  - Card/Section Background: `#FFFFFF`
- **Typography:**
  - Display/Headings: `Playfair Display` (serif, elegant, authoritative)
  - Body/UI: `Inter` (clean sans-serif, highly readable)
  - Accent labels: `DM Mono` (for tags, skill chips, GPA number — adds personality)
- **Signature element:** A **subtle animated underline** on the hero name using the gold accent, combined with a large typographic GPA callout (3.85) displayed as a big number in `DM Mono` — a quiet flex that immediately signals academic excellence.

### Layout Concept
Single-page scrollable website with smooth section transitions. Sections:
1. Hero
2. About
3. Experience (timeline)
4. Education & Achievements
5. Skills
6. Contact

---

## 🛠️ TECHNICAL REQUIREMENTS

### Stack
- **HTML5 + CSS3 + Vanilla JavaScript** (single file, zero dependencies except Google Fonts and Font Awesome CDN)
- Fully **responsive** (mobile-first, breakpoints at 768px and 1024px)
- **Smooth scroll** navigation with active state on nav links
- **Accessible** (semantic HTML, ARIA labels, focus states, `prefers-reduced-motion` respected)
- All assets must load from **CDN** (no local files required)

### Must-Have Features
1. **Sticky navigation bar** with logo/initials, nav links, and smooth scroll behavior
2. **Hero section** with:
   - Large animated name reveal
   - Subtitle: "Administrative Professional & Data Specialist"
   - CTA buttons: "Download CV" (links to PDF placeholder) and "Contact Me" (smooth scroll to contact)
   - Floating achievement badge: "Summa Cum-laude — Most Outstanding Graduate"
3. **About section** with short professional bio paragraph and 3 highlight stat cards (GPA 3.85, 100+ clients handled, 3 café partners supplied)
4. **Experience timeline** — vertical timeline layout, each entry shows company, role, duration, and 2–3 bullet points
5. **Education & Achievements section** — education card + achievement badges (Best Paper, Runner-Up Debate, GPA)
6. **Skills section** — grouped into: Core Competencies, Software, Languages — displayed as chip/tag components with subtle hover animation
7. **Contact section** — email, phone, LinkedIn displayed cleanly with copy-to-clipboard on email/phone
8. **Footer** with name and year

### Animations & Interactions
- Fade-in on scroll for all sections (IntersectionObserver)
- Hover effects on experience cards and skill chips
- Active nav link updates as user scrolls
- Typing animation on hero subtitle (optional but preferred)
- Smooth animated underline on hero name

---

## 📐 SECTION-BY-SECTION INSTRUCTIONS

### Section 1: HERO
```
[FULL VIEWPORT HEIGHT]
[Centered content, vertically middle-aligned]

FARHANA QADRUN NADA          ← Playfair Display, 72px, dark navy
─────────────────────        ← Animated gold underline, grows on load
Administrative Professional  ← Typing animation, Inter 20px gray
& Data Specialist

[Contact Me]  [Download CV]  ← Two CTA buttons, gold + outline style

                    ╔══════════════════════════╗
                    ║ 🏆 Summa Cum-laude        ║  ← floating badge card
                    ║ Most Outstanding Graduate ║
                    ╚══════════════════════════╝
```

### Section 2: ABOUT
```
[Two column on desktop, stacked on mobile]

Left: Photo placeholder (avatar initials "FN" in gold circle, 200px)
Right: Bio paragraph + 3 stat cards in a row

Stat Cards:
┌──────┐  ┌──────┐  ┌──────┐
│ 3.85 │  │ 100+ │  │  3   │
│ GPA  │  │Clients│  │Cafés │
└──────┘  └──────┘  └──────┘
```

### Section 3: EXPERIENCE
```
Vertical timeline — gold dot on left, card on right

◉ ACC — Customer Retention Canvassing
│  Dec 2025 – Mar 2026
│  • Handled 100+ clients daily...
│  • Ensured zero missed follow-ups...
│
◉ Crack n' Choco — Owner & Supplier
│  May 2025 – Jun 2026
│  • Independently managed operations...
...
```

### Section 4: EDUCATION & ACHIEVEMENTS
```
Education Card:
┌────────────────────────────────────────────┐
│ 🎓 Universitas Andalas                     │
│ Bachelor of International Relations        │
│ Aug 2020 – May 2025  |  GPA: 3.85 / 4.00  │
└────────────────────────────────────────────┘

Achievement Badges (grid of 3):
┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│ 🏆 Summa         │  │ 📄 7th Best      │  │ 🎤 Runner-Up     │
│ Cum-laude        │  │ Paper, PERNA     │  │ NUDC Debate     │
│ Most Outstanding │  │ 2023            │  │ 2021            │
└─────────────────┘  └─────────────────┘  └─────────────────┘
```

### Section 5: SKILLS
```
Tab or group headers: [Core Competencies] [Software] [Languages]

Core Competencies:
[Administrative Support] [Scheduling] [Document Preparation]
[Professional Correspondence] [Data Entry] [SOP Development]

Software:
[MS Excel ★★★] [MS Word ★★★] [PowerPoint ★★★] [SPSS] [Tableau]
[Power BI] [Canva] [Adobe Photoshop] [CapCut] [MS Access]

Languages:
[Indonesian — Native] [English — TOEFL ITP 523]
```

### Section 6: CONTACT
```
[Centered, minimal]

Let's connect.

📧 frhna.nada@gmail.com         [Copy]
📞 +62 812-7716-7636            [Copy]
🔗 linkedin.com/in/farhana-...  [Open]

"Ready to contribute as a reliable, efficient professional
 in a fast-paced environment."
```

---

## ✅ QUALITY CHECKLIST (verify before output)

Before delivering the final code, confirm:
- [ ] All 6 sections present and complete
- [ ] Responsive layout works on 375px (mobile) and 1280px (desktop)
- [ ] No hardcoded colors outside the palette
- [ ] No placeholder "Lorem ipsum" text — use real content from CV
- [ ] Smooth scroll works on all nav links
- [ ] Skill chips have hover animation
- [ ] Timeline has proper visual connector line
- [ ] Stat numbers in About section are prominent and readable
- [ ] Achievement badges are visually distinct and scannable
- [ ] Contact copy-to-clipboard is functional
- [ ] `prefers-reduced-motion` media query is implemented
- [ ] Footer includes current year (use JS to auto-fill)
- [ ] Code is clean, well-commented by section, and valid HTML5

---

## 📦 OUTPUT FORMAT

Deliver **one complete, self-contained HTML file** named `portfolio-farhana.html`.

The file must:
- Start with proper `<!DOCTYPE html>` declaration
- Load Google Fonts (Playfair Display, Inter, DM Mono) from CDN
- Load Font Awesome 6 icons from CDN
- Include all CSS in `<style>` block in `<head>`
- Include all JavaScript in `<script>` block before `</body>`
- Work offline after initial CDN load
- Be ready to deploy directly to GitHub Pages, Netlify, or Vercel

Do NOT split into multiple files. Do NOT use frameworks (React, Vue, etc.). Do NOT use npm/build tools.

---

*End of Super Prompt*
