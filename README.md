# MetroMate Classifieds

**One Call. All Solutions.** A mobile-first Surat classifieds and local-services discovery prototype.

## Overview

MetroMate Classifieds lets visitors browse 30 priority service categories, search sample listings, filter by Surat area, view listing details, and open post-ad and enquiry forms. The page includes responsive layouts, featured/urgent listing labels, click-to-call, WhatsApp links, and a lightweight install-app information panel.

## Run locally

No build step is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

## Project files

- `index.html` — standalone HTML, CSS, and JavaScript front-end.

## Current prototype limitations

This repository contains a **front-end prototype**, not a production classifieds backend.

- Listings and categories are hard-coded sample data in the page.
- New ads are added only to the in-memory browser session; they are not saved to a database.
- Enquiry forms show a demo confirmation; they do not send or persist enquiries.
- Phone-number display and report actions are demo interactions.
- Sample advertisers, prices, verification labels, and listing details are placeholders and must not be treated as verified live businesses.
- There is no authentication, moderation console, payments, image upload, spam protection, or persistent storage yet.

Before a public production launch, connect a backend/database, implement phone verification and moderation, add privacy/terms pages, and validate all sample data and business claims.

## Suggested next phase

A production implementation could add persistent listings, user accounts, enquiry routing, moderation, paid placements, photo uploads, and searchable SEO landing pages. The original in-page developer notes outline a suggested Next.js, PostgreSQL, object-storage, Razorpay, and WhatsApp Cloud API direction.

## Contact

MetroMate · Surat, Gujarat  
Phone / WhatsApp: **+91 97274 13309**

---

Powered by **SNTL84**.
