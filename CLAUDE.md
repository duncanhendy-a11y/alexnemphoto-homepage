# alexnemphoto.cz — CLAUDE.md

Plain HTML/CSS site deployed on Vercel. No build step.

**Repo:** https://github.com/duncanhendy-a11y/alexnemphoto-homepage
**Domain:** alexnemphoto.cz
**PRD:** Agency/clients/Alex-Nemecz/website-prd.md

## Structure
Each page = one HTML file + shared style.css
vercel.json has cleanUrls: true — /portfolio serves portfolio.html

## Pages
index.html → /
portfolio.html → /portfolio
sluzby.html → /sluzby
cenik.html → /cenik
idea-statica.html → /idea-statica
o-mne.html → /o-mne
kontakt.html → /kontakt

## Design tokens (CSS variables in style.css)
--bg: #0A0A0A | --surface: #141414 | --accent: #C8A96E | --text: #F5F5F5

## Before editing
- No wedding content on any B2B page
- Czech language throughout — correct diacritics: ě š č ř ž ý á í ú ů
- All internal links use clean URLs (no .html)
- Images go in /images/ — use next/image when migrating to Next.js

## TODOs (before go-live)
- Replace placeholder images with real Alex photos in /images/
- Add Alex's email + phone to kontakt.html and schema
- Replace REPLACE_WITH_FORMSPREE_ID in kontakt.html
- Add IDEA StatiCa quote to o-mne.html when confirmed
- Replace placeholder case study in idea-statica.html when permission confirmed
