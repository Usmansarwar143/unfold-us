# UnfoldUS Website

Complete website package for UnfoldUS, the SaaS services company founded by Usman Sarwar. This is the current client facing launch version, fully responsive with a small border radius.

## How to run
Open index.html in any browser. The page is fully self contained: styles, scripts, the favicon and the logo graphics are inlined in the single HTML file, so no server or build step is needed. An internet connection is used only to load the Google Fonts (Sora and Inter).

To publish it, upload index.html to any static host and point the domain at it.

## Contents
- index.html: the complete website (hero, services, process, about, project enquiry form, Privacy Policy, Terms of Service, footer)
- logos/: the four UnfoldUS logo images (primary light, app icon, dark horizontal, wordmark only) with their own README

## Notes
- Responsive: single column stacking on phones, mobile menu under 820px, tap targets of at least 48px, no horizontal scrolling
- Border radius: small only, 6px on buttons, fields and panels, 4px on the header logo tile
- Colours: Midnight Navy #0A1931, Emerald Green #0B8A5F, Pearl #F7F5F0 background
- Fonts: Sora for display text, Inter for body text, Space Grotesk as the Sora fallback
- The enquiry form is front end only. Connect it to an email service or form backend before launch so submissions are delivered.
- Privacy Policy and Terms of Service sections are included inside index.html, effective November 2026.
