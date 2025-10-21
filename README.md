# pm-portfolio-assets
🏛️ Shannon Callins — Interactive Portfolio

Vision: an immersive “walk into my office” experience. Visitors enter a warm, wood-paneled study. As they explore, framed certificates, a bookshelf of projects, and a desk with interactive items reveal my work and credentials.

Objectives

Memorable, professional first impression fit for project management roles.

3D/interactive vibe without sacrificing performance or accessibility.

Content driven from simple data files so updates don’t require code changes.

Tech Stack

Developer’s choice. Use whatever stack and libraries you prefer (Three.js or other).
I only care about the visual concept being realized.

Scene Flow
1) Landing — “Business Card”

Full-screen office view (dark wood, lamp glow, bookshelf hints).

Overlay text:

Name: Shannon Callins

Title: Project Manager • SOP Specialist

Calm motion (parallax or slow camera dolly).

CTA indicator: ornate button that says “Step Inside.”

2) Certificates Wall

Gallery of framed certificates/badges.

Hover → soft highlight; click → modal with issuer, date, description, link.

Camera can pan or slide in to show the wall.

3) Projects — Bookshelf Concept

Bookshelf:

Book spines = smaller projects (click spine → detail card with summary & links).

Framed case study = PassItOn widget (rich panel with images/write-up).

Blueprints/scrolls = spreadsheets & data workflows (click unrolls or zooms to panel with images and notes).

Possible shelf categories (Client, Internal, Labs) — dev’s choice.

4) Desk — About / Résumé / Contact

Name plate → About Me card (bio, strengths, industries).

Letter → résumé modal with download PDF button.

Business cards → LinkedIn, GitHub, Email.

Papers & pen sets can appear here (not in the opening scene).

Creative Direction & Requirements
Feel / Vibe

Old-world stability — think “Queen of England’s library”: centuries of books, tradition, quiet authority.

Emotion: stability, trust, professionalism; warm and inviting, never flashy.

Pacing: calm, deliberate camera moves.

Visual Guardrails

Palette: dark woods, deep blues/reds, brass or antique gold, warm lamp light.

Gold accents: antique brass / darkened gold preferred (adjust saturation/brightness to avoid shiny “new” gold).

Avoid: neon, ultra-modern/glossy UI, bright minimal white spaces, cyber/tech look.

Textures: wood grain, aged leather, linen/preserved parchment, brass accents.

Books: very old, leather-bound, preserved paper look (I’ll provide reference photos).

Scrolls/Blueprints: papyrus vibe — ancient but clear and readable.

Frames: antique/ornate; I’ll supply reference images.

Desk Scenes

Opening desk: clean — nameplate and lamp only. No papers or pens.

Closing desk: may include papers, pen sets, and a dark charcoal-grey laptop off to the side (screen hidden).

CTA / Navigation Indicators

Entrance prompt should fit the old-world style — e.g., an ornate plaque or frame-shaped button.

Color: darkened/antique gold or brass to match the office.

Preferred wording: “Step Inside.”

Should glow softly or highlight on hover to show interactivity without breaking immersion.

Résumé Behavior

Opens in a pop-up/modal viewer with a Download PDF button.

Background dims; Esc/close returns user to desk.

Interactions

Certificates: hover highlight; click → modal.

Bookshelf: books, framed case study, blueprints/scrolls as described above.

Include a gentle reduce motion toggle for users sensitive to animation.

Accessibility & Responsiveness

Mobile & tablet friendly (developer decides how to simplify for small screens).

Keyboard support (Tab, Enter/Esc).

Alt text and ARIA labels for all images/interactive elements.

Performance

Optimize textures and images (compressed but sharp).

Lazy-load heavy assets and case study media.

Maintain smooth feel at normal desktop frame rates.

Content Checklist (to be delivered by me)

 Final list of certificates + dates + links

 Case study copy for PassItOn (problem → approach → outcome)

 Blueprint items (spreadsheets) with blurbs + sanitized images

 Book-spine projects with summaries + links

 About blurb (80–120 words)

 Résumé PDF

 Profile links (LinkedIn, GitHub, Email)

 Visual references: bookshelf style, nameplate, frame samples

Milestones

Prototype base scene (office, lighting, camera).

Certificates wall with interactive modals.

Bookshelf projects (books, framed case study, blueprints).

Desk interactions (About, Résumé, Contact).

Content integration (final text & images).

Performance & accessibility review.

Mobile and fallback support.

Deployment.

Open Questions for Developer

Preferred asset format (textures/models)?

How mobile will be simplified?

Any size/texture limits I should know before I prep images?

Placeholders needed or wait for my content first?

---
## Decor & Placement Updates (Oct 2025)

Decor & Placement Updates (Oct 2025)

Theme: Inherited, heirloom study passed down through generations. Brass = intellect/exploration. Silver = heritage/lineage. Blue gemstone accents = insight/clarity.

Object Placement (single use per object)

Tea Set (pick one: pink or blue): Side table beside the chair in the certificates zone. Two cups, one “in use.”

Framed Motto (placeholder for now): Above the floor globe. Use parchment placeholder; I’ll supply the final texture later.

Motto text (final to come): “Improvise, Adapt, and Overcome.”

Ancestor Portrait (public domain): Small frame on bookshelf or a side niche; add tiny brass nameplate (e.g., “Founder, 1823”).

Silver Letter Tray: Back-right of desk. Polished silver, light tarnish in filigree.

Dome Desk Magnifier: Mid-right of desk, angled toward map blotter.

Blue Agate Geode: Back-left of desk or upper shelf corner—visible, not in work area.

Compass/Spyglass/Magnifier Set (if used): Front-right of desk or shelf vignette (avoid crowding blotter).

Left-Handed Desk (straight-wrist)

Main writing area: center-left of blotter.

Pen holder/glass globe: front-left.

Lamp on left to avoid hand shadow.

Keep center front clean for nameplate.

Assets, Formats & Pipeline

Source images: .jpg/.png preferred; .webp/.avif OK for references.

Runtime: Three.js with .blend source → export .glb.

Compression: OK for dev to convert to .ktx2 for GPU compression.

Textures: BaseColor, Roughness, Metallic, Normal, (optional) AO.

Scale: Real-world (desk ~1.5 m).

Instancing: Books, scrolls, frames.

Material targets

Mahogany wood: satin polish, micro-wear.

Aged brass: metallic 1, roughness ~0.3.

Polished silver: metallic 1, roughness ~0.45, cool AO in crevices.

Leather map blotter: dark frame + parchment center, visible stitching.

Porcelain (tea): subtle clear coat.

Gemstone (agate): thin clear coat; gentle sparkle/emissive specks.

Placeholders (Swap Later)

/textures/motto_placeholder.jpg → /textures/motto_final.jpg

Ancestor portrait: temp public-domain image → can be swapped with final at same path.

QR code: currently LinkedIn; will replace with portfolio QR later.

Frames & CTA button: may be reused across props for consistency.

Accessibility & Motion

Keyboard: Tab focus for hotspots; Enter/Esc modals.

“Reduce motion” toggle (softer camera tween, no bob).

Alt text for all interactives (certs, books, scrolls, desk items).

Content Hand-Off Checklist (decor phase)

 Tea set (pick one)

 Motto frame (placeholder)

 Ancestor portrait (public domain)

 Letter tray (silver)

 Dome magnifier

 Geode placement

 Desk layout (left-handed, straight-wrist)

 Frames/CTA reusable note

 QR = LinkedIn (temp)

Suggested follow-up commit messages

Add new office decor assets and placement notes

Update README: decor placement, placeholders, left-handed desk
