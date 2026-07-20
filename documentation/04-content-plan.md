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
🟢 Complete — built as a 3-column layout (Tennessee, Kentucky, Ohio) on `bg-brand-slate`, each with a short description, a clickable phone number, and for KY/OH a "Visit the [State] Page →" link to `/kentucky` / `/ohio` (will 404 until those pages exist). Built 2026-07-14.

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
🟢 Complete — built as `AboutHero.tsx`: full approved bio text (both paragraphs, verbatim), a 400+ Cases / 2026 CQDE Certified stat pair, and Ashley's headshot. Built and committed 2026-07-16.

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
🟢 Complete — built as the "Education" group within `ProfessionalCredentials.tsx`'s timeline (TTU B.S. Political Science 2013 incl. Dean's List honors and the Mark Gore internship; Gatton Academy 2009 incl. the WKU dual-enrollment/Mathematica detail). Positioned last in that section (after Continuing Education) per Ashley's request. Diploma images viewable via "View Credentials."

## Professional Experience

Content Needed:
- Forensic Document Investigations
- Since 2020
- Case experience

Content Source:
07-client-content-inventory.md → Professional Experience

Status:
🟢 Complete, with one deliberate deviation from this outline — case volume (400+ cases since 2020) and casework variety are covered in the Biography. **Forensic Document Investigations, Inc. and Dianne Peterson are intentionally NOT named anywhere on the site**, matching Ashley's own approved bio wording rather than this row's original content-needed list — see `07-client-content-inventory.md`'s note on avoiding conflict with her former employer. Confirmed decision, not an oversight.

## Professional Training

Content Needed:
- Dianne Peterson
- Interactive training

Content Source:
07-client-content-inventory.md → Professional Training

Status:
🟢 Complete, same Dianne Peterson omission as above — built as the "Certification & Training" group in `ProfessionalCredentials.tsx`'s timeline (CQDE Certification; Interactive Training Program described without naming instructors, per client request).

## Continuing Education

Content Needed:
- SAFE Conferences
- AFDE/NADE Symposium
- Wroclaw Symposium
- Monthly education

Content Source:
07-client-content-inventory.md → Continuing Education

Status:
🟢 Complete — appears twice: as a group within `ProfessionalCredentials.tsx`'s timeline (Wroclaw Symposium 2026, SAFE Conference 2025, AFDE/NADE Symposium 2024) and again as its own full `ContinuingEducation.tsx` section further down the page (photo background, full chronological list back to 2023, notes monthly SAFE/IADE coursework).

## Publications

Content Needed:
- Scientific Journal publication
- The Examiner publication

Content Source:
07-client-content-inventory.md → Publications

Status:
🟢 Complete, structure changed from the original plan — Ashley indicated she didn't want Publications as its own dedicated section. Both citations (2025 Scientific Journal of IADE; 2026 The Examiner) now live in `AdditionalBackground.tsx`, de-emphasized (no photo/thumbnail), alongside the 2023 seminars/workshops list and volunteer/leadership facts pulled in from elsewhere in `07-client-content-inventory.md`. Mention-only, no links, per Ashley's confirmed publications policy.

## Professional Organizations

Content Needed:
- SAFE (active member)
- IADE (active member)
- CQDE certification (IADE, 2026)

Content Source:
07-client-content-inventory.md → Professional Organizations

Status:
🟡 Content confirmed, but not built as its own section — after several placement attempts (standalone section, subsection of Credentials, under the Hero photo, inline with the Hero stats — full history in the `project-website-build` memory), the client's final call was to remove it entirely. SAFE/IADE active membership is now stated exactly once, in the Biography paragraph prose; CQDE is covered via the Certification & Training timeline group. No logos or dedicated callout anywhere on the site. Revisit only if asked.

## Call to Action

Purpose:
Invite visitors to request a consultation after learning about Ashley.

Content Needed:
- Consultation button
- Contact information

Status:
🟢 Complete — reuses the shared `ContactCta` component (`src/components/shared/ContactCta.tsx`), same one used on the homepage.

---

# Services

## Introduction

Purpose:
Explain what forensic document examination is and how Ashley can help.

Status:
🟢 Complete — built as the page hero (eyebrow, heading, intro paragraph, signature photo). Intro copy is drafted, not yet reviewed by Ashley. Built 2026-07-20.

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
🟢 Complete — built as a full-width divider-separated list (title + one-line description each), matching the homepage Services section's editorial style, no icons. Split around a slate breaker image after "Detection of Traced or Simulated Handwriting." Titles are Ashley's confirmed wording; one-line descriptions are drafted and still pending her review. Built 2026-07-20.

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
- Kentucky cities served — original confirmed list was Owensboro, Bowling Green, Louisville. Ashley's Jul 15 follow-up spreadsheet expanded this to 13 cities (Louisville, Lexington, Bowling Green, Owensboro, Covington, Richmond, Georgetown, Florence, Elizabethtown, Paducah, Frankfort, Hopkinsville, Somerset) — still need to decide how many of these make the actual page.
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
- City mentions: original confirmed list was Akron, Cleveland, Columbus. Ashley's Jul 15 follow-up (see 07-client-content-inventory.md → Site Structure) expanded this with an unprompted "Ohio's Largest Cities" population ranking (Columbus, Cleveland, Cincinnati, Toledo, Akron, Dayton, Parma, Canton, Lorain, Hamilton) — still need to decide how many of these make the actual page.
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
- What is a Forensic Document Examiner?
- What documents do I need to provide for examination?
- Who should engage your services?
- What equipment is used in your laboratory?
- Do you perform on-site examinations of documents?

Content Source:
07-client-content-inventory.md → FAQ — CONFIRMED

Status:
🟢 Complete — built as a client-side accordion (one question open at a time) below the page hero. Content is Ashley's own wording, sent directly rather than drafted. Built 2026-07-20.

---

# Contact

## Contact Form

Status:
🟢 Complete — built as a Next.js Server Action (`src/app/contact/actions.ts`) that sends via Resend to Ashley's existing inbox (`precisionhandwritinganalysis@gmail.com`), with reply-to set to the visitor's email. Uses Resend's shared `onboarding@resend.dev` sender for now since the production domain isn't connected/verified yet — once it is, swap the sender to a `precisionhandwritinganalysis.com` address so delivery isn't restricted to the Resend account owner's inbox. Requires a `RESEND_API_KEY` env var (documented in `.env.example`, set in Vercel project settings). Built 2026-07-20.

## Contact Information

Content Needed:
- Phone (TN, KY, OH)
- Email
- Office address

Content Source:
07-client-content-inventory.md → Contact Information

Status:
🟢 Complete — built as a column beside the form (phone numbers with labels, email, office address), sourced from `site-config.ts`. Built 2026-07-20.

## Consultation CTA

Status:
🟢 Complete — folded into the page hero copy above the form rather than a separate closing CTA section (the whole page already is the CTA target).
