# Status Legend

| Status | Meaning |
|---|---|
| 🟢 Complete | Ready to build |
| 🟡 Draft Needed | We need to write it |
| 🔵 Client Review | Waiting on Ashley |
| ⚪ Planned | Placeholder only — not ready to build yet |

---

# Global Components

## Header

Content Needed:
- Logo
- Primary navigation
- Request Consultation button

Status:
🟢 Complete

---

## Footer

Content Needed:
- Business name, tagline ("Certified Forensic Document Examiner"), and logo
- Credentials: SAFE Member, IADE Member, CQDE Certified
- Services (shortened labels, all linking to the Services page): Questioned Signatures, Handwriting Analysis, Anonymous Writing, Altered Documents, Expert Witness, Litigation Support
- Phone number(s) — TN, KY, OH
- Email address
- Office/location information
- Quick navigation links
- Copyright

Content Source:
07-client-content-inventory.md → Contact Information, Site Structure, Services List, Professional Organizations

Status:
🟢 Complete — built as a 3-column layout (Brand & Credentials / Services / Contact) with a centered nav row and copyright below; social media link excluded per Ashley's request (declined). Credentials and Services columns go beyond the footer scope originally planned in 03-site-architecture.md — worth confirming Ashley is happy with a services summary in the footer alongside the full Services page.

---

## Global Call-to-Action

Purpose:
Encourage visitors to request a consultation throughout the website.

Content Needed:
- CTA headline
- Supporting text
- Button text

Status:
🟡 Draft Needed

---

# Home

## Hero

Purpose:
Immediately communicate what Precision Handwriting Analysis does and who it serves.

Content Needed:
- Main headline
- Supporting text
- Call-to-action button
- Professional headshot or hero image

Status:
🟢 Complete — built as a full-viewport split hero (photo left, copy right); headline "When authenticity is challenged, clarity matters.", eyebrow "Forensic Document & Handwriting Examiner", service-focused blurb, a 4-item service list (Questioned Signatures, Handwriting Analysis, Altered Documents, Expert Witness Testimony), and the two standard CTAs. Uses ashley-headshot-01.jpg. Committed 2026-07-13.

## Professional Credentials

Purpose:
Establish trust within the first few seconds.

Content Needed:
- SAFE & IADE member
- CQDE certified
- Published author
- Since 2020
- Continuing education
- 400+ documented cases assisted

Content Source:
07-client-content-inventory.md → Potential Website Content (Trust Indicators)

Status:
🟢 Complete — built as a slim full-width slate-blue "proof band" directly below the Hero (not a card section), 6 items in a single row at `sm`+ (CQDE Certified, 400+ Cases, Published Research, SAFE Member, IADE Member, Court-Ready Work), each with a gold label + white subtext line and thin dividers between. Stacks to a single column on true mobile widths. Built 2026-07-13.

## Services Overview

Purpose:
Give visitors a quick overview of Ashley's core services and help them determine whether she can assist with their needs.

Content Needed:
- Short introduction
- A featured subset (3 of 8) as an editorial list, not a card grid — Questioned Signature Examination, Handwriting Comparison & Analysis, Examination of Altered Documents. Full 8 (Ashley's exact confirmed wording) live in `src/lib/services-data.tsx` and appear in full on the `/services` page and in the footer.
- "View All Services" button

Content Source:
07-client-content-inventory.md → Services List — CONFIRMED

Status:
🟢 Complete — built as a left-aligned editorial section on `bg-brand-cream` (slate-blue headings/icons/links, gold used only for small accents: eyebrow, heading rule, "Most Requested Services" label, hover states), with a faded slate-blue "A"-monogram watermark bleeding off the bottom-right corner. Client confirmed "let's be done with this section for now" (2026-07-13).

## Meet Ashley

Purpose:
Introduce Ashley on a personal level and build trust through her experience and background.

Content Needed:
- Professional headshot
- Short biography
- Years of experience
- Link to About page

Content Source:
07-client-content-inventory.md → Biography

Status:
🟢 Complete

## Why Choose Precision Handwriting Analysis

Purpose:
Highlight the experience, training, and qualifications that set Ashley apart.

Content Needed:
- Published research
- Specialized training
- Professional organizations
- Continuing education
- Experience with questioned document examinations

Status:
🟢 Complete

## Areas Served

Purpose:
Explain the geographic areas Ashley serves and direct visitors to the appropriate landing page.

Content Needed:
- Nationwide messaging (primary framing, per Ashley)
- Tennessee, Kentucky, Ohio highlighted specifically
- Links to KY and OH landing pages

Content Source:
07-client-content-inventory.md → Site Structure

Status:
🟡 Draft Needed

## Call to Action

Purpose:
Encourage visitors to request a consultation.

Content Needed:
- Contact button
- Brief invitation to reach out
- Phone and email

Status:
🟢 Complete

---

# About

## Biography

Purpose:
Share Ashley's professional story.

Content Needed:
- Full biography
- Professional headshots

Content Source:
07-client-content-inventory.md → Biography

Status:
🟢 Complete

## Education

Content Needed:
- Gatton Academy
- Tennessee Technological University
- Dean's List
- Internship
- Academic background

Content Source:
07-client-content-inventory.md → Education

Status:
🟢 Complete

## Professional Experience

Content Needed:
- Forensic Document Investigations
- Since 2020
- Case experience

Content Source:
07-client-content-inventory.md → Professional Experience

Status:
🟢 Complete

## Professional Training

Content Needed:
- Kathy Koppenhaver
- Debra Dunlap
- Dianne Peterson
- Interactive training

Content Source:
07-client-content-inventory.md → Professional Training

Status:
🟢 Complete

## Continuing Education

Content Needed:
- SAFE Conferences
- AFDE/NADE Symposium
- Wroclaw Symposium
- Monthly education

Content Source:
07-client-content-inventory.md → Continuing Education

Status:
🟢 Complete

## Publications

Content Needed:
- Scientific Journal publication
- The Examiner publication

Content Source:
07-client-content-inventory.md → Publications

Status:
🟢 Complete

## Professional Organizations

Content Needed:
- SAFE (active member)
- IADE (active member)
- CQDE certification (IADE, 2026)

Content Source:
07-client-content-inventory.md → Professional Organizations

Status:
🟢 Complete

## Call to Action

Purpose:
Invite visitors to request a consultation after learning about Ashley.

Content Needed:
- Consultation button
- Contact information

Status:
🟢 Complete

---

# Services

## Introduction

Purpose:
Explain what forensic document examination is and how Ashley can help.

Status:
🟡 Draft Needed

## Individual Services

Content Needed:
- Questioned Signature Examination
- Handwriting Comparison & Analysis
- Anonymous Writing Examination
- Detection of Traced or Simulated Handwriting
- Forensic Document Examination for Criminal Investigations
- Examination of Altered Documents
- Expert Witness Testimony & Court-Ready Opinion Reports
- Litigation Support & Attorney Consultation

Content Source:
07-client-content-inventory.md → Services List — CONFIRMED

Status:
🟢 Complete

## Examination Process

Purpose:
Help clients understand what to expect.

Content Needed:
- Initial consultation
- Document submission
- Examination
- Report preparation
- Expert testimony (if applicable)

Status:
🟡 Draft Needed

## Common Questions

Purpose:
Answer 2–3 of the most common service-related questions and direct visitors to the full FAQ page.

Content Needed:
- Brief introduction
- 2–3 featured questions
- "View All FAQs" link

Status:
🟡 Draft Needed

## Contact CTA

Status:
🟢 Complete

---

# Kentucky

Purpose:
Create a localized landing page for Kentucky visitors while improving local SEO and building trust with Kentucky attorneys, businesses, and individuals.

Content Needed:
- Kentucky-focused hero
- Kentucky cities served
- Kentucky native
- Kentucky Colonel recipient
- Services overview
- Contact information
- Call-to-action

Content Source:
07-client-content-inventory.md → Site Structure, Contact Information, Regional Background

Status:
🟢 Content Available (awaiting final copy)

---

# Ohio Landing Page

Unblocked — Ashley confirmed nationwide service with KY/OH landing pages as SEO-focused local pages, and provided the OH phone number.

Content Needed:
- Localized hero
- Ohio-focused copy
- City mentions: Akron, Cleveland, Columbus (examples given; confirm if more are wanted)
- Services
- Why choose Ashley
- FAQ
- Contact information (440-452-0592)

Content Source:
07-client-content-inventory.md → Site Structure, Contact Information

Status:
🟡 Draft Needed

---

# FAQ

Content Needed:
- What is forensic document examination?
- What types of documents can be examined?
- How long does the process take?
- How are documents submitted?
- Will I need to appear in court?
- Do you testify as an expert witness?

Status:
🟡 Draft Needed

---

# Contact

## Contact Form

Status:
🟢 Complete

## Contact Information

Content Needed:
- Phone (TN, KY, OH)
- Email
- Office address

Content Source:
07-client-content-inventory.md → Contact Information

Status:
🟢 Complete

## Consultation CTA

Status:
🟢 Complete
