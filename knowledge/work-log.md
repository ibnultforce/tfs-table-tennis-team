# Work log

Written automatically: one line per change Claude made to this site that was kept, oldest first. Claude reads this before every request so new work stays consistent with earlier work. Older lines move to knowledge/archive/. Standing decisions belong in knowledge/notes.md, not here.
- 2026-10-14 · assistant:add-file-to-site · assets/img/uploads/logo-mark.png · Adds your logo to the site's images.
- 2026-10-14 · assistant:update-logo-settings · site.config.json · Uses your logo as the site's logo mark and browser-tab icon, with the team name beside it.
- 2026-10-14 · page:edit · content/pages/home.md · This is a new, empty page. Write it from scratch. Homepage for a one-day table tennis tournament hosted by the TFD Table Tennis Team in Dhaka, Bangladesh, on N…
  - Set frontmatter description, metaTitle, metaDescription and focusKeyword, and replaced the placeholder hero with a full tournament hero.
  - Added a key facts strip with Date, City and Host cards, plus Venue, Entry fee and Prizes cards marked 'To be announced'.
  - Added a November 26 schedule timeline with Registration & check-in through Prize giving, each row showing 'Time TBA'.
  - Added About the event, How to register / contact (email and WhatsApp link) and FAQ sections, plus page-scoped styles in navy, blue and off-white.
- 2026-10-14 · assistant:update-menu-and-footer · content/data/navigation.json · Menu now links to the real homepage sections (Home, Schedule, Contact) instead of missing pages, and the footer links are fixed.
- 2026-10-14 · chrome:design · templates/partials/header.html · Restyle the header to match a bold, sporty tournament homepage: deep navy (#0d1b2c) background, off-white (#f5f7fb) text, bright blue (#6f9bff) accents and a p…
  - Swapped the theme/tone/layout data attributes for a fixed navy (#0d1b2c) header with off-white text and a blue gradient hairline, shrinking to h-14 on scroll.
  - Logo link now reads nav.appearance.header.logoOnDark (falling back to the brand mark); nav links and CTA are right-aligned.
  - Restyled nav links, dropdown panel (#13263c) and current-page states in navy/white/blue, and made the CTA a pill-shaped #6f9bff button with navy text.
  - Mobile menu: hamburger animates into an X, panel is full-width navy with taller tap targets; footer moved to the same navy/blue palette.
- 2026-10-14 · page:edit · content/pages/contact.md · This is a new, empty page. Write it from scratch. Contact page for the TFD Table Tennis Tournament, held November 26 in Dhaka, Bangladesh, hosted by the TFD Ta…
  - Rewrote frontmatter description and added metaTitle, metaDescription and focusKeyword fields for the contact page.
  - Replaced the placeholder hero with a navy "Get in touch" hero showing the "November 26 · Dhaka, Bangladesh" line, intro sentence, floating ball graphic and page styles.
  - Added two contact cards linking to mailto:ibnulashir.tforce@gmail.com and https://wa.me/8801556777043, each with icon and pill button.
  - Added a "Still to be announced" section with four dashed cards (Venue, Entry fee, Prizes, Match times) and a "Back to the schedule" button to /#schedule.
- 2026-10-14 · assistant:update-menu-and-footer · content/data/navigation.json · Points the Contact button and footer link to the new Contact page.
