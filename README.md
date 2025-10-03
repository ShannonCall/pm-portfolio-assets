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
