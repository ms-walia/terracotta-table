# TT — The Terracotta Table (demo website)

A demo ordering website for The Terracotta Table (TT), a bakery, café and kitchen in Hall Bazaar Road, Amritsar. Built by Mehtab Singh Ahluwalia as a pitch.

One HTML file, no build step. Open `index.html` in a browser, or turn on **Settings → Pages** (branch `main`, root) to host it.

## What it does
- Menu with **Add** buttons and a takeaway cart: pick today or another day and a pickup time
- **Cake pre-order builder**: flavour, size (½, 1 or 2 kg), egg or eggless, message and pickup date, with a live cake preview
- Party and group order form
- Live open/closed badge using Amritsar time
- Device checks (`is-phone` / `is-laptop` on `<html>`) so the same design adjusts for phones and laptops

## Demo status
- Prices show `₹ —` until TT shares its menu prices
- Orders and forms are not sent anywhere yet; the plan is to send them to TT on WhatsApp
- Photos are linked from TT's public listings on EazyDiner and Yappe.in, plus Unsplash placeholders. Use TT's own photos, with their permission, before going live

Based on the free burger restaurant template by 8B (MIT). See `LICENSE` and `CREDITS.md`.
